Getting Started:
-----------------------------------------------------------------------------------------------------------------------------------------
Issue trackers monitor the progress of software development “issues”, such as bug fixes and discussions about features. Typically, developers
subscribe to issues they are interested in through the tracker, and are informed of changes and new developments via automated email. In
practice, however, this approach does not scale well, as developers may receive large volumes of messages that they must sort through using
their mail client; over time, it becomes increasingly challenging for them to maintain awareness of the issues that are relevant to their
activities and tasks. To address this problem, DASH tool can be used, it presents personalized views of issues; developers indicate issues of
interest and DASH presents customized views of their progress and informs them of changes as they occur.

License
-----------------------------------------------------------------------------------------------------------------------------------------
DASHboards can be redistributed with both the source code and the executable of the tool. However, authors have stated to include information about the original authors with the code/executable you distribute.

Contents on Desktop
-----------------------------------------------------------------------------------------------------------------------------------------
1. Installation.txt - Contains instructions on installing Dash from scratch.
2. DASHboards Video - Video demonstration on how to get started with Dash in this VM.
3. License - This file contains license information pertaining to all softwares that are used in this VM.

Steps to use Dash
-----------------------------------------------------------------------------------------------------------------------------------------
1. In settings.json file located at "/var/www/html/cgi-bin/" provide link to elastic cluster with Bugzilla data in it. Author has provided us with the settings.json file that is present along with this VM.
2. Open any browser, and go to "http://localhost".
3. DASH webpage opens asking for username and period during which a bug was raised. 
4. Upon entering valid details, it shows the issues, patches & reviews pertaining to that user.
