# I.A RL Model Playning Games

- ## Using Python 3.11 for Cartpole I.A

    - ### CartPole I.A PPO MlpPolicy Model

        - ### Environment Requeriments

            - #### Stable BaseLines3 
                    pip install stable-baselines3

            - #### Gynasium
                    pip install gym
 
        - ### Setting Variables

            - #### num_cpu 
                    Your CPU threads amount (Be careful with high values, they can frezzing your PC)

            - #### total_timesteps
                    Amount of times to run (High values can take many hours)

            - #### local
                    Directory PATH to write the trained model
---

- ## Using Python 3.6 for Super Mario Bros I.A

    - ### Super Mario Bros I.A PPO CnnPolicy Model

        - ### Environment Requeriments

            - #### Stable BaseLines3 
                    pip install stable-baselines3

            - #### Gym SuperMarioBros 
                    pip install gym-super-mario-bros

            - #### TensorBoard 
                    pip install tensorboard

            - #### OpenCV 
                    pip install opencv-python

            - #### NesPY 
                    pip install nes-py

        - ### Setting Variables

            - #### VecFrameStack (venv: VecEnv, n_stack: int, channels_order: str) 
                    Example Usage:
                        env = VecFrameStack(env, 32, channels_order='last')

                Choose how many stacks you want. (Be careful, this function will use up your RAM). In my case I put 32

            - #### total_timesteps
                    Amount of times to run (High values can take many hours)

            - #### check_freq
                    Frequency at which a model will be saved



