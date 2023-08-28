# background-subtraction
Background subtraction (BS) is a common and widely used technique for generating a foreground mask (namely, a binary image containing the pixels belonging to moving objects in the scene) by using static cameras.
As the name suggests, BS calculates the foreground mask performing a subtraction between the current frame and a background model, containing the static part of the scene or, more in general, everything that can be considered as background given the characteristics of the observed scene.

Background modeling consists of two main steps:

Background Initialization;
Background Update.
In the first step, an initial model of the background is computed, while in the second step that model is updated in order to adapt to possible changes in the scene.This method is implemented in the video below




https://github.com/bakhshiintel/background-subtraction/assets/98385786/a49fa1c6-b7fa-4c3b-8b99-a3aafe41b192


