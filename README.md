# Deep_Q-Network
Deep Q-Network example from Udacity's Deep Reinforcement Learning Nanodegree.

It may be necessary to install some basic python dev tools and some compiling tools. In particular, if you use Windows you will need Visual Studio Build Tools (the C++ package will suffice). Moreover, install *swig* and install *pybox2d*.
If you use Anaconda on *64bit* Windows and cannot build or install pybox2d (or box2d-py), you can edit the file \Lib\distutils\distutils.cfg in the Anaconda folder *removing* the lines

[build]

compiler=mingw32.

