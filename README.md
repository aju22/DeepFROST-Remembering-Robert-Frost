# DeepFROST:Remembering-Robert-Frost

If there was one thing that we humans are collectively proud of that will put some of the best supercomputers and machines to shame, it is Art. Art has no rules, no patterns, no algorithms. It is a pure construct of creativity and randomness arising from the depths of a less understood human consciousness.

However, with the onset of Recurrent Neural Networks and further advancements in Natural Language Processing, it is looking quite a struggle for humans. As machines take advantage of the power of LSTMs and GRUs almost to mimic their minds and to put up a fight with some of the best of them like Sir Robert Frost when it comes to creating beautiful poetry.

This project experiments with LSTMs and Pre-Trained Word2Vec trained on a relatively small-sized dataset comprising of poems written by Robert Frost to generate poetry.

## Model Perfomance

* Considering the data size and the number of epochs the model was trained upon, the results are quite good. 

* Here are some samples that were generated.

```
let the night and mist
i was coming from
that everyone for bricks
that doesn t exist
some say i read that need forth
to set the end
it isn t drag barrier where judgement
under the cold burden of treading upon death glass
shatter it inward on the cellar though with the cellar against us
in front of all it now
```


```
only to tumble like a stricken bird
with his old barkless stray his aren t you seen thinking
the minute they were crooking will recognize
i wonder where the saddest city went
except it seemed the voices were glad
wishing in warren
we struck a road one less
i d done it lying or twitch
he won t tell the place
ascending to descend to here and victories of it
```

```
there is as if the way so all once and then three
so gave up to the rain wide on consideration
rather than tip on her lap ain t outspread
i saw her heart your see the place
i took the a glimpse through curtain laces
feared the whir from kiting graciously
from stumps still bleeding their life away
i paused and rested on the unswept floors
that only nothing had a bad man and gets up or something kiting to yield
and miles to go to lave my sake here
```

## Drawbacks

* Certain scentences definitely seem broken and crude, and there are only a few rhyming lines.

* Although there is a poetry-like aspect to the text generation, the model fails to create a poem that sticks to a particular context. A poem about rain, will suddenly have following lines that does not relate to rain in anyway.

## Improvements to be made

* Larger training times on a scaled version of dataset.
* Hyperparameter tuning.
* Modified networks with larger hidden layers or more complex structure.
* Allowing user to give an initial context.

## References

* [Poetry Generation with LSTMs](https://datawow.io/blogs/poetry-generation-with-lstm)
* [Generation of poems with a recurrent neural network](https://medium.com/@DenisKrivitski/generation-of-poems-with-a-recurrent-neural-network-128a5f62b483)
