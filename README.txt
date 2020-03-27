# first-repository
ffirst repository is empty
second two
import unittest
from time import sleep
from mskzkt.base.base01 import MyBase
from mskzkt.page.loginpage import LoginPage
from mskzkt.page.studypage import StudyPage
from selenium.webdriver.support.ui import Select
from mskzkt.page.ondemandpage import OndemandPage
from mskzkt.page.parentpage import ParentPage
from selenium.webdriver.common.by import By


class StudentTestCase(MyBase):

    def test_student(self):
