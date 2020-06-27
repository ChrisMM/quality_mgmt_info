Part of [Quality](/README.md)

## :books: Guidance for Agile QA

1. Test early, test often


2. Apply Agile QA


3. Embed QA on Scrum teams


4. Work very closely with Engineers and Developers (on test cases, check with them before sending tickets back, IM (Slack?) is your friend)


5. Have a clear easy to use template for bugs (Title, Expected, Actual, Steps to reproduce, Severity)


6. Have a quality plan in mind that includes a testing strategy


7. Get tagged in merge requests / PR’s so QA can know when there is a new feature test, when to
update to feature tests, etc


8. Look at needs acceptance / QA lane first thing in the morning and whenever you
have time


9. Maintain/ update build verification scripts as much as you can


10. Automate testing

_And optional: ​Bi Weekly check in / 1:1 individually with Engineers on what is going well, what could be better_

![Testing Pyramid](https://blog.qatestlab.com/wp-content/uploads/2016/01/shirly-ronen-harel_automated-agile-testing-strategy1377960802889.jpg)

![Testing Quadrants](https://lisacrispin.com/wp-content/uploads/2011/11/Agile-Testing-Quadrants.png)

- Looking at the pyramid, Development / Engineering are responsible for Unit tests/component tests and some API level tests.
- QA Test Engineers / SDETs are responsible for API tests and GUI testings and Evan is the test manager / lead for manual tests.
- Looking at the quadrant, Development / Engineering are responsible for lower left quadrant.
- QA Test Engineers / SDETs are responsible for upper left quadrant.
- QA Testers manually testing are responsible for upper right quadrant.
- The lower right quadrant is fulfilled by different testms depending on the work.

Note:
- Development / Engineering can design their development to support UI / GUI tests because those sort of tests need "hook" to connect to in the UI experience.
- Often times a request / requirement / story / ticket will use DoD/AC to include criteria to support this so the Engineer is responsible to ensure that UIs are ready for automated testing. (This dependes highly on how it goes and if that would make sense or not.)
