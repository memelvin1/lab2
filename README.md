# lab2
Unit Testing
[Test]
        public void GetSubtraction_Input8point4and2point0_Returns6point4()
        {
            double number1 = 8.4;
            double number2 = 2.0;
            double expectedResult = number1 - number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetSubtraction();
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetSubtraction_Input4point4and1point1_Returns8point4()
        {
            double number1 = 9.5;
            double number2 = 1.1;
            double expectedResult = number1 - number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetSubtraction();
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input6point0and2point0_Returns4point0()
        {
            double number1 = 6.2;
            double number2 = 2.2;
            double expectedResult = number1 - number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetSubtraction();
            Assert.AreEqual(expectedResult, actualResult);
        }
    }
}
