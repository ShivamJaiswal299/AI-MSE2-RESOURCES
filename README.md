# AI-MSE2-RESOURCES
mse2 resources , temporary


Complete the code below. Replace only the `pass` inside update_agent. Return ONLY the lines that replace `pass`. Do not repeat the def line or the docstring. No explanation.

def update_agent(self, state, action, reward, next_state, done):
    """
    TASK 2: Implement the Tabular Q-Learning Update Rule.

    Requirements:
    - If done is True: target = reward
    - Otherwise:
        target = reward + self.gamma * max(Q(next_state, all_actions))
    - Update:
        Q(state, action) = Q(state, action)
                           + self.alpha * (target - Q(state, action))

    The function is attached to QLearningAgent below so that the
    notebook retains exactly seven cells.
    """
    ### >>> YOUR CODE HERE <<< ###
    pass
    ### ========================== ###

QLearningAgent.update_agent = update_agent
