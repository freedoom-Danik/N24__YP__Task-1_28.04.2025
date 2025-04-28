# N24__YP__Task-1_28.04.2025
содиржимое теста да он не публекуется 
using System;
using Microsoft.VisualStudio.TestTools.UnitTesting;
using N24__YP__Task_1_28._04._2025;

namespace TestProject2
{
    [TestClass]
    public class UnitTest1
    {
        [TestMethod]
        public void TestMin()
        {
            int min;
            min = Program.Min(3, 4, 5);
            Assert.AreEqual(3, min);
        }
    }
}
