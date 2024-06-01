# Contextual bandits
Current repository stores the notebooks that were created during the completion of the course project for the third year of DSBA program in HSE. The comparison of different bandits is done with CTR simulations.

Author: Gorelskii Roman

Project Supervisor: Samsonov Sergey

Theme: Contextual bandits

The implementation of recommender systems’ algorithms remains to be one of the most crucial parts for many companies. It allows them to make the user experience to be more personalised. Finding a solution which adapts to the dynamic change in the pools of content and the scale of web services expansion is what modern developers are trying to implement. This research is aimed at the exploration and evaluation of the contextual bandit approach. It allows to reduce the computational complexity with the possibility to test the performance on the traffic recorded previously.

## Files

- **Contextual_bandits_Project.ipynb** contains realisation and comparison of epsilon-greedy, LinUCB, Thompson Sampling for Contextual Bandits and Neural Thompson Sampling with the MovieLens dataset through [Polara](https://github.com/evfro/polara/tree/master) framework. All the needed references are given in the file. It is optimised for the use in Jupyter Notebook. All the needed requirements can be found in requirements.txt.

- **Neural_Thompson_Sampling.ipynb** contains realisation and simulation of Neural Thompson Sampling. It is optimised for the use in Google Colab with GPU. That is why it is done in a separate file.

- **users.csv** - context about users which cannot be downloaded with Polara.

- **pickles** - saved simulations with "pickle" library. Excludes file for Neural Thompson Sampling. Look at pickles.zip.

- **pickles.zip** - all the saved simulations with "pickle" library.