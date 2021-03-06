# Baselines incl. RUDDER

Uses RUDDER on PPO to solve environments with delayed rewards.

Our code is based on the [OpenAI Baselines](https://github.com/openai/baselines) package, in which we included our implementation of RUDDER for PPO for ATARI games with delayed rewards.
Additionally, the [Tensorflow Layer Library (TeLL)](https://github.com/bioinf-jku/tensorflow-layer-library) package (v1.0) is required for RUDDER.

RUDDER for PPO2 and more documentation is located in the folder [baselines/ppo2_rudder](baselines/ppo2_rudder).

Modified/new files:
- baselines/common/atari_wrappers.py
- baselines/common/distributions.py
- baselines/common/vec_env/vec_frame_stack.py
- baselines/ppo2_rudder/
- logger.py
- README.md
