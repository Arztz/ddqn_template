# ddqn_template
# train model
python agent.py {name} --train



# replay
python agent.py {name} 




# thing need to change

What thing you need to run.  you need state  and action

    env = gymnasium.make(self.env_id, render_mode='human' if render else None, **self.env_make_params)
    

    num_states = env.observation_space.shape[0]
    num_actions = env.action_space.n