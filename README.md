# histo_jal
Histological tissue recognition project with Keras VGG16

The identification of tissues from histological sections by a machine is not something which is a pressing requirement. Infact, today's human pathologists are so adept at it that they don't need assistance from a machine in any way.

However, the real reason I took up this project was to invetigate our own visual systems, i.e. workings of the occipital cortex. Everyday objects (like a book, pen, animals, fruits ) - which both humans and machines are good at recognising - are not suited for this purpose. We grow up looking at them, and by the time we are five, these objects become second nature to us. We do not __think__ and analyse them anymore.

Histologic images, on the other hand, are completely new to the non-pathologist human. Try going through the dataset yourself (remove the labels first) and see if __you__ are good enough as the ML model (histo_3.model). The model has made a few errors, which have been reported in our preprint https://www.medrxiv.org/content/10.1101/2021.07.20.21260573v1. Consider the following images. Without any labels, would you consider them the same class?


The 'kidney' class is particularly troublesome for the machine. It seems to confuse 'glomeruli' (Yes, Bowman's corpuscles, from your biology book) with alveolar spaces, and what not. Strangely, many rookie pathologists have suffered once or twice from this problem, but never after. We seem to develop an intrinsic 'sixth sense' of what is a glomerulus.

'I see therefore I am' -- (someone)


