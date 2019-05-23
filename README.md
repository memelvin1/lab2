# lab2
Unit Testing
 [Test]
        public void GetAdditionn_Input8point4and2point0_Returns10point4()
        {
            double number1 = 8.4;
            double number2 = 2.0;
            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetAddition();
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetAddition_Input4point4and1point1_Returns5point5()
        {
            double number1 = 4.4;
            double number2 = 1.1;
            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetAddition();
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetAddition_Input6point0and2point0_Returns8point0()
        {
            double number1 = 6.0;
            double number2 = 2.0;
            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetAddition();
            Assert.AreEqual(expectedResult, actualResult);
        }
