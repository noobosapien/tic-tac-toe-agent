
# Tic-tac-toe game implementation with AI Agents

#### Stack:
* Autogen py
* pygame

#### Procedure:
* An UserProxyAgent is created pointing to a working directory.
* LLM config is imported from a JSON object.
* An Assistant Agent is created who is the engineer of the project, that engineer will write Python code.
* A critic is created to test and give feedback for the code written by the Python engineer. It gives a score out of 10 for every iteration.
* A group chat is created between the Python Engineer and the Critic.
* A GroupChatManager will manage the iterations of the group.
* The output of the group is saved in a cache to reduce the LLM costs.
