# lab2
Unit Testing
 [Test]
        public void GetDivision_Input8point4and2point0_Returns4point2()
        {
            double number1 = 8.4;
            double number2 = 2.0;
            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetDivision();
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetDivision_Input4point4and1point1_Returns4point0()
        {
            double number1 = 4.4;
            double number2 = 1.1;
            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetDivision();
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input6point0and2point0_Returns3point0()
        {
            double number1 = 6.0;
            double number2 = 2.0;
            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetDivision();
            Assert.AreEqual(expectedResult, actualResult);
        }
