### Insight
---
Recently, I watched a tutorial video on building a multi-agent system using the Langchain library. In the video, two agents dynamically switched roles as key workers within the system, depending on cues detected in the user's input. The logic presented in the tutorial closely resembled a strategy recently introduced by Kakao, where one character responsible for emotional responses, while another handles logical tasks. <br>
There are various UX strategies for implementing multi-agent systems. One approach is to present the system as a single unified assistant, while actually running multiple agents behind the scenes.  Another approach is to design it like a group chat, where the user interacts with several agents, each with a distinct personality or role. <br>
Additionally, incoporating a dynamic reinforcement learning experience -where users can "teach" or provide feedback to individual agents- opens up further possibilies for user engagement and personalization.


---

최근 봤던 Langchain을 통해서 대화를 하는 중간에 Agent들이 옮겨다니면서 각 Agent들이 수행해야할 역할을 수행할 수 있도록 구현하는 튜토리얼을 봤는데 카카오에서 최근 발표한 '카나나'처럼 감성을 담당하는 Agent, 논리적 업무를 처리하는 Agent가 나뉘어서 사람과는 둘이면서 하나처럼 대화를 나누고 과업을 수행하는 형태로의 경험을 만들수도 있을 것이고 아예 그룹대화를 나누듯 하는 경험을 나눌 수도 있을 것 같다.
<br>
Reinforce Learning을 추가로 생각해보면 최근 읽은 논문에서 사람에게 각각의 Agent가 자신을 어떻게 지도해줘야 하는지 어떤 식으로 알려줘서 더 강화학습의 효율을 높일 수 있을지도 커뮤니케이션 경험의 한 과제가 될 수 있겠다.