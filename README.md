# Deep Learning Lessons

Quick reference list by [@heri](http://twitter.com/heri) - Feel free to fork or do a PR

# EXCEL

* image
* videos
* translation
* seq2seq
* GAN - e.g. style a picture into a Rembrandt
* NLP with attention (current research undertaken)
* possible to re-use models and add or combine with other models. See recent Google Brain paper

# FAIL

* NLP. Tbc
* Deep Layers can diverge. Activation function with 0 means and 1 variance such as SeLU can help though.
* Handling constraints. Not possible to find constraints-based solutions unlike linear programming
* Does not handle well unknown entities. Consider video where another person is outside the frame
* Audit or Test Deep Learning networks. You can't do unit test, functional, integration testing and make sure it follows business rules or laws.
* Structure is hidden and cannot be described to other practitionners or non-DNN practitionners
* Can learn bias from data. No data from Africa or under-represented groups. See also word2vec bias
* Needs massive dataset to generalize. Needs advanced computing rigs to train ($)
* Still needs optimization (client<->server or special optimized chip) to run inference on devices
