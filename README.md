# 1st_unit_test
year=2017
number1=200

def returnTwenty():
	return 20



 #Tests
 import unittest
 #here unittest is a library->python package

 class TestStringMethods(unittest.TestCase):
 #TestStringMethods is a special kind of object
 #unittest,TestCase is also object

     def test_year(self):
         self.assertEqual(year, 2010)
    #assertEqual

def test_gt_2019(self):
 		self.assertTrue(year > 2019)

 unittest.main()
 output: FAILED
