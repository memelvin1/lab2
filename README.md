# lab2
Unit Testing
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using AwesomeCalculator;
using NUnit.Framework;

namespace ClassLibrary1
{
    [TestFixture]
    public class Calctest
    {
        [Test]
        public void GetMultiplication_Input4point4and2point0_Returns8point8()
        {
            double number1 = 4.4;
            double number2 = 2.0;
            double expectedResult = number1 * number2;
            Calc testCalc = new Calc(number1, number2);
            double actualResult = testCalc.GetMultiplication();
            Assert.AreEqual(expectedResult, actualResult);
        }
