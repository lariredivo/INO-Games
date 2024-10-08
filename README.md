# INO-Games
## QA Test

### **General Questions**
**1. What is the primary purpose of Quality Assurance (QA)?**

The primary purpose of QA is to ensure that the software meets the specified requirements and standards (reliable, efficient, and high-quality). It works on the basis that if a good process is followed correctly, then it will generate a good product. QA applies to both the development and testing processes, and is the responsibility of everyone on a project.

**2. What is the difference between a test case and a test plan?**

Test case is a set of conditions that determine if the feature is working as intended. It is written as a documentation that specifies the exact steps, inputs, execution conditions and expected results for a particular test. 

On the other hand, a test plan is a high-level document that outlines the overall strategy, objectives, resources, schedule, and scope of the testing efforts. It describes how the testing will be conducted and includes details like the testing objectives, test criteria, resource planning, and risk management.

To summarize the difference: a test case is a specific instance of testing that falls under the broader strategy outlined in the test plan.

**3. What does the term 'regression testing' refer to?**

Regression testing refers to the process that confirms that no adverse consequences have been caused by a change, including a fix that has already been confirmed. These adverse consequences could affect the same component where the change was made, other components in the same system, or even other connected systems. It is important to say that regression testing may not be restricted to the test object itself but can also be related to the environment. 

**4. How would you create a template to describe bugs on a software that is being constantly
released?**

- ID: Unique identifier for each test case.
- Title: A brief summary of the bug.
- Description: Detailed description of the issue.
- Steps to reproduce the bug: Detailed, step-by-step instructions to replicate the bug.
- Test date: Set of input values, conditions, and variables used to execute a test case.
- Expected result: What the software should do.
- Actual result: What the software actually did.
- Severity: The impact level of the bug (e.g., critical, major, minor).
- Priority: The urgency for fixing the bug (e.g., high, medium, low).
- Responsible: Individual assigned to execute the test case.
- Date: When the test case was executed.
- Version of the software: Specific build or release of the software that was tested
- Environment: Information about the hardware, software, and network configurations where the bug was found.
- Attachments: Screenshots, logs, or any other relevant files.

[You can see an example of a template here](https://docs.google.com/spreadsheets/d/1LyH2q7MyDGEcR8amnAudTkTc0HQ-npO06ZKMozPK2pE/edit?usp=sharing)

**5. What is the importance of test automation in QA? What would you explore in terms of
automation for games being developed in a short period of time?**

Test automation is crucial for improving the efficiency, effectiveness, and coverage of software testing. It enables faster execution of repetitive test cases, helps in maintaining consistency, reduces human error, and allows for more frequent regression testing. For games developed in a short period of time, automation can be explored in the following areas:
- Smoke Testing: To ensure basic functionalities work after each build.
- Regression Testing: To quickly identify defects introduced by recent changes.
- Performance Testing: To check for any performance issues.
- Unit Testing: To validate individual components.
  
**6. Describe the main stages of the Software Testing Life Cycle (STLC).**

The Software Testing Life Cycle (STLC) ensures a systematic and structured approach to testing, resulting in high-quality software that meets user expectations. It has seven stages:
1) Requirement analysis: Understand project requirements and define testing objectives to establish a framework for testing.
2) Test planning: Create a detailed test plan outlining the approach, objectives, scope, schedule, and resource allocation, while assessing risks and mitigation strategies.
3) Test design: Develop comprehensive test cases and scenarios based on requirements to ensure full test coverage.
4) Test environment: Set up the testing environment, including hardware, software, and test data, to closely mimic the production environment.
5) Test execution: Run tests according to the plan, document outcomes, and identify any defects or issues.
6) Defect tracking: Log and track defects, prioritize them, and collaborate with the development team to resolve them.
7) Test reporting: Generate reports detailing testing progress, coverage, defect metrics, and overall software quality to inform stakeholders and assess readiness for release.

**7. How would you handle a situation where a bug you reported is marked as 'not
reproducible' by the development team?**

When a bug is marked as 'not reproducible' by the development team, I would take the following steps:
First, I would review the bug report to ensure the steps to reproduce and I would also check if the environment details and other information are clear and complete. Then, I would try to reproduce the issue in different environments or with different configurations. The next step that I would take is to talk about the issue with the development team to understand any potential differences in environments or steps. After this, I would provide additional evidence like more detailed logs, screenshots, videos, or any other relevant information. The last step would be to modify the bug report with any new findings or details that can help in reproducing the issue.

### **Hands-On Test**
The report is divided into two: bug report and test report. Test videos with supporting evidence are organized in a folder on Google Drive.

[Link for the report](https://docs.google.com/spreadsheets/d/1LyH2q7MyDGEcR8amnAudTkTc0HQ-npO06ZKMozPK2pE/edit?usp=sharing)

[Link for the test videos](https://drive.google.com/drive/folders/1mRocsfo7QbiHbrq2sf7dBpQuF4MMXuEy?usp=sharing)

**1. Game chosen:** [Bling Bling Penguin](https://slotcatalog.com/en/slots/Bling-Bling-Penguin)

**2. Testing the game:** 
- Functional testing:  identifier as FUNCT-XXXX for example
- Usability testing: identifier as USAB-XXXX for example
- Bug report: identifier as BUG-XXXX for example
- Performance testing: ​​stress testing is a critical aspect of performance evaluation for gambling games played in a browser environment. This testing is designed to assess how well the game performs under extreme conditions, specifically when subjected to high levels of user traffic and simultaneous interactions. This involves simulating a large number of concurrent users, such as thousands of players, to observe how the game’s servers, application, and browser handle the pressure. I wasn't able to perform this kind of test

**3. Suggestions for improvement:**
I would like to suggest the inclusion of a tutorial at the beginning of the game, which would explain the main buttons and gameplay mechanics. This would help new players get to know the game quickly and improve their overall experience. Additionally, incorporating themed events, such as those related to Easter, the Olympics, Christmas, and other holidays or celebrations could greatly enhance the game’s appeal and keep players engaged throughout the year.

**4.General Overview**
- Why did I choose this game?

I selected this game because it stands out with its quirky penguin and rap soundtrack, which add a fun and distinctive touch. Besides, the animation of the spinning wheel is particularly captivating compared to other games I've played. The combination of these features creates a more immersive and stimulating gaming experience.

- What are the ups and downs?

**Ups:**

- Engaging audio and visuals: The lively soundtrack and impressive animations enhance the overall excitement and immersion.
- Interactive features: The game offers interactive elements that keep players involved and entertained.
- User-friendly interface: The interface is intuitive and easy to navigate, making the game accessible for both new and experienced players.
- Bonus Wheel: The chance to win cash prizes, free spins, or one of five fixed jackpots through the wheel is a notable feature that can lead to substantial rewards.
- Free Spins Round: Can be retriggered and includes a gamble feature for those seeking extra spins, though it comes with the risk of losing the feature.
- Bonus buy feature: Available for non-UK players, allowing direct access to the bonus features for a set cost.

**Downs:**

- Repetitive Gameplay: The core mechanics may become repetitive over time, which could reduce long-term engagement.
- High Volatility: The game may have high volatility, leading to periods of low rewards, which might be frustrating for some players.
- Limited Customization: There might be limited options for personalizing the gameplay experience, which could be a drawback for players seeking more control.
- Sensory Overload: Despite the engaging audio and visual effects, the rapid and very colorful visual stimuli can cause discomfort or nausea for some players. It may be beneficial to include a warning for individuals with sensory sensitivities. Additionally, implementing options for less bright colors and accessibility features for color blindness could enhance the game's inclusivity.


- What would you consider a factor that would make you play again?

The possibility of hitting one of the five fixed jackpots, especially the Epic Jackpot worth up to 10,000x your stake, would definitely encourage me to play again. Also a key factor is the introduction of new and diverse features or updates. This could include additional bonus rounds or new game modes that refresh the gameplay experience. 

- Was this an engaging experience?

Yes, the game provided a highly engaging experience. The lively soundtrack and dynamic animations created a stimulating and immersive environment that kept me interested throughout my play session. Overall, the game’s engaging aspects were prominent, though there is room for improvement in terms of accessibility and customization to enhance the experience for a broader audience.




