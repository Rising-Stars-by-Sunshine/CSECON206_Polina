# 📌 MILESTONE 2
## QUESTION 1
### Analyze your experience with oTree, identifying pain points in behavioral game theory research. Review related literature and class discussions to understand experimental economics' goals. Propose a software solution that outperforms oTree in at least three aspects, enhancing strategic interaction studies. Highlight why these advancements are crucial.

Albeit not having extensive experience working with oTree, having just discovered the platform through our class activities, I believe that the oTree can be particularly useful for small-scale behavioral game theory research or tests of low-to-medium complexity to be conducted on a group of people. It has a relatively easy-to-understand pipeline and a sufficient body of guidelines on project development, for instance, the one provided by Professor Zhang in collaboration with DKU students back in 2021 (Zhang et al. 2021). I will refer to my example of attempting to design a Prisoner’s Dilemma game involving more stakeholders (since this experience can be useful for understanding more complex structures and algorithms at play), but the program only allowed me to work with two players and limited choice of the influence factors to some decisions (which, I want to point out, may have been due to my limited experience with the program, which I will need to breach in the future) (Figure 1). Therefore, I want to acknowledge that some potential areas for improvement of the interactive features of the platform may include wider customization for the provided problem sets, introducing new potential behavioral game theory problems (for instance, cake-cutting, which can be a useful point of analysis applicable to different fields, particularly economics), and (potentially) collaborate with the already present leaders on the market to provide more opportunities for visualization of the outcomes and the user’s interface. These three areas of advancement hold particular value to us and the researchers within the field because of more opportunities presented as a result of the implementation of these developments into the existing program. It is worth acknowledging that the software for oTree remains free and available for use, which can pose an obstacle for the developers to incorporate advanced changes into the existing software. However, having learned how many present companies on the technology market are interested in supporting the development of smaller companies/developers even with a limited financial gain during the conference with company representatives last Friday provides us hope that in the future the oTree software will see more developments integrated, or a different software developer will breach the gap.

![image](https://github.com/Rising-Stars-by-Sunshine/CSECON206_Polina/assets/148934457/aebaa8bc-b874-4a17-9bb9-61750d5ca11c)
Figure 1. oTree game experience. A personal screenshot of the student.

## QUESTION 2
### Delve into the limitations of current multi-agent reinforcement learning (MARL) frameworks, focusing on environment constraints and agent algorithm customizations. Choose a classic game (e.g., Prisoner's Dilemma, Battle of the Sexes, or the Trust Game) to illustrate these limitations. Describe the development process of a MARL agent for your selected game, detailing the definition of states, actions, and rewards grounded in fundamental behavioral assumptions. Your analysis should provide insights into overcoming MARL's current limitations, fostering advancements in the field.

Multi-agent reinforcement learning (MARL) is undoubtedly a tool of high utility when analyzing behavioral game theory largely due to its opportunity to grasp comprehensive dynamics between the group members and assess different social metrics. I had a personal experience witnessing one of the MARL algorithms unfold within the GoBigger game I played in my childhood - only under the name Agar.io (Zhang 2022) (Figure 2). The rules of the game are simple - the players consume particles and other players (smaller than yourself) to grow in size; the final goal of the game is to grow the biggest in size and occupy the whole playing area.

While this framework has seen significant advancements in the last couple of years, the framework still has some limitations. For analysis purposes, we will turn to the Prisonner’s Dilemma, previously discussed when referring to the first question, to allow us to look into potential development areas of this game in the MARL context. Some of the limitations of this dilemma within the scope of MARL include but are not limited to a constraining environment, which fails to account for larger dynamics, stemming outside of the direct outcomes of the decision (taking into account sentence longevity, financial payout, while potentially disregarding the shift between the two prisoners dynamics (which, fair to say, is hard to account for even in the psychology field)). Then, MARL may not possess the capability at the moment to adapt to more complex problems or increased participant dimensions, which limits its potential at the current stage — but also gives ground for further improvements. In an attempt to address these limitations, we will need to account for the development process of a MARL agent within the Prisoner’s Dilemma. Initially, we must take into account the actions of the agent that are relevant to different situations/environments (cooperating or defecting), the previous actions of the opponent, and any other environmental variables that may be relevant. Next, we need to understand the options available to each person, which are either to cooperate or defect. Additionally, we need to consider the rewards or punishments that are given based on the outcomes. To improve the development process and execution, we can explore the implementation of reinforcement learning algorithms such as meta-learning approaches. These can help to address scalability issues and other constraints in social dynamics after the choices have been made. One additional field for improvement would be the development of more sophisticated environment models that would have the capability to capture the complex dynamics and social interactions pertaining to the nature of the game. Due to the complexity of implementing state-of-the-art technologies in collaboration with behavioral game theory, addressing the limitations with new algorithms may take some time.

![image](https://github.com/Rising-Stars-by-Sunshine/CSECON206_Polina/assets/148934457/ee9d1b21-3746-40e2-aef3-554e38736dd7)
Figure 2. GoBigger game experience. A personal screenshot of the student.

## QUESTION 3
### Critically engage with existing research in the field of federated learning, using the specific paper presented by the guest speaker as a primary example. Students will assess the paper's research questions, methodologies, and application scenarios and propose new research ideas addressing the identified limitations or gaps.

As we have comprehensively covered the paper during the brilliant discussion by Professor Bing Luo on Friday, I decided to apply this skill to a different paper (Figure 3).

### The future of digital health with federated learning by Rieke, N., Hancox, J., Li, W. et al.

![image](https://github.com/Rising-Stars-by-Sunshine/CSECON206_Polina/assets/148934457/0e009f15-bb0c-4452-b5b7-3de554b4ce4d)
Figure 3. The future of digital health with federated learning by Rieke, N., Hancox, J., Li, W. et al. Chart created with gracious help from Whimsical.

### Summary of the Paper
The paper investigates how federated learning (FL) could offer a way forward for the future of digital health, emphasizing some of the obstacles and factors that must be tackled.

### Core Research Questions
What are the benefits and impacts of FL for medical applications? What are the key considerations and challenges of implementing FL for digital health?

### Methodologies
Overview of AI/ML/DL in Healthcare
Assessing Challenges with Data

### Application Scenarios
Digital Medicine, Medical Institutions adopting the knowledge gained as a result

### Critique of the Research Question
While I believe that the current research questions provide a useful general insight into the potential of the application of FL in medicine, it could also look into the societal perception, the current views the public and researchers hold on this topic, and how the potential implementation can help improve quality of medical services.

### Critique of the Methodology
This paper does not directly tackle the codes and FL itself but instead provides a general overview, which is also good. However, having this paper also address potential technical difficulties (for instance, the FL algorithms particularly applicable to the medical field) with examples of FL applied to certain medical field-related questions may provide more insights into the paper.

### Critique of the Application Scenario
As mentioned, an overview paper gives a great insight into why FL implementation in the medical field may not be as easy as it may sound, and provides sufficient reasoning for it, so I believe that the application scenario is quite on point.

### Beyond Computer Science and Economics
The study will become more positive towards application, disregarding the issues of privacy preservation and technology availability. I had a conversation with my friend who has impeccable digital skills and is majoring in Global Health. Her insights led me to believe that the introduction of participants with specific outlooks on federated learning may significantly alter the findings to become more positive and welcoming of FL, but may also stress the potential difficulties of FL in medicine.

## Bibliography

Rieke, N., Hancox, J., Li, W. et al. The future of digital health with federated learning. npj Digit. Med. 3, 119 (2020). https://doi.org/10.1038/s41746-020-00323-1

Zhang, L. (Sunshine), Tian, X. (Michelle), Zhuang, Z., Zhang, L. (Sunshine), Tian, X. (Michelle), Wu, T. (Henry), Li, J., Wang, C. (Claire), Zhuang, Z. (2022). oTree Instructions for Behavioral Experiments. In Autumn 2021. https://doi.org/10.21428/aa21bfc0.841ff112

Zhang M., Zhang S., Yang Z., Chen L., Zheng J., Yang C., Li C., Zhou H., Niu Y., & Liu Y. (2023). GoBigger: A Scalable Platform for Cooperative-Competitive Multi-Agent Interactive Simulation. In The Eleventh International Conference on Learning Representations. https://openreview.net/forum?id=NnOZT_CR26Z


