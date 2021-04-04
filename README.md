# SEB_dg

Test plan and automated test scripts for seb Calculator of leasing:
https://www.seb.lt/skaiciuokles/lizingo-skaiciuokle   (Lit)
https://www.seb.lt/eng/private/calculator-leasing      (En).
To run Test suite:
1. Select vykdyti1.jar;
2. Right-click the mouse and select "Open with";
3. Selelct "Java(TM)Platform SE binary";
Note: The last test case in the suite is semi-automatic, i. e. payment shedule printing should be performed manually (or cancelled manually presseing "Cancel" button). 

Test Suite consists of 3 test cases:
1. Validation of data entered (some test cases for the validation of values entered in the calculator’s fields (for negative and positive testing)) ;
2. Test cases for comparison of values calculated by “Calculator of leasing” with expected ones; 
3. "SMOKE" test for Payment shedule (test cases for display of data after “Payment schedule” button was pressed (including schedule printing) – semi automated case (schedule printing is tested manually));
Note1: see comments in the test scripts fore more detailed description;
Note2: at the end of 3. test case manual testing of payment schedule printing is required (press Print or just press ESC).
Note3. Test report is atached (file test_report.png).

