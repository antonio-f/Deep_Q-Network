# Deep_Q-Network
Deep Q-Network example from Udacity's Deep Reinforcement Learning Nanodegree.

It may be necessary to install some basic python dev tools and some compiling tools. Moreover, install *swig* and try *pip3 install box2d box2d-kengz* or try to install *pybox2d*.
If you use Anaconda on Windows *64bit* and cannot build or install pybox2d (or box2d-py), you can edit the file \Lib\distutils\distutils.cfg in the Anaconda folder *removing* the lines

[build]

compiler=mingw32.

