# Yosenabe Project


To submit your solution, please modify the file [yosenabe.lp](asp/yosenabe.lp) of the directory [asp](asp) with your encoding.

Every time you push a new commit, your solution will be tested automatically.
The timeout per instance is `180` seconds, and
the actual command call for the test is:
* ``python3.8 asp/test.py -e asp/yosenabe.lp -i asp/instances -s asp/solutions -t 180``

For help, type `python3.8 asp/test.py --help`.

After a few minutes you will be able to see the result of the test in the **Actions** tab.
You can get more information about the result of the test by clicking successively on:
1. The specific test.
2. "Autograding".
3. "Run education/autograding@v1".

Then scroll down until around line 150.
For each instance, you will see if the test is a:
* "success" (correct answer),
* "failure" (wrong answer),
* "timeout" (no solution found before the time runs out), or
* "error" (clingo error).
