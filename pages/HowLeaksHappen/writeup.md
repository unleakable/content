# How did the leak happen?

That's not what you came here to read anyway—a better question would be: How *can* a leak happen?

To elaborate: Given the system of generation of these question papers, the logistics involved in distribution, human and machine vulnerabilities, and the avenues for corruption, in what way could a leak occur?

## So, to the point.

There appear to be the three major faults with the system:

* F1: **Systemic size**
* F2: **Points of failure**
* F3: **Low fault tolerance**

### Systemic size
CBSE is tasked with an ambitious project. Their job is conduct massive examinations across the country for the world's largest youth population, every year. The amount of money that can be spent per examinee is greatly limited, making technology based solutions impractical.

The CBSE is dealing with Amazon level logistics here, except it can't access Amazon level technology. 

Changing things from the top is hard. Planned economies aren't very effective for this reason. The organization seems unable to react to events on the ground without a dozen letters being dispatched from its head office in Delhi.

An organization like the CBSE deals with effects called [the diseconomies of scale](https://en.wikipedia.org/wiki/Diseconomies_of_scale). While a school or college can respond to a leak event within an hour, and reschedule the exam the very next day, the insane logistics involved in a system like the CBSE make this impossible.


### Multiple points of failure

If you made the claim that there was a conspiracy that involved the same number of people that as there are in the CBSE's distribution network, you'd be laughed at. But how exactly are these two different? Both involve a large number of people keeping a valued secret from the public.

It appears as if the system presupposes the reliability of all these nodes. The organization seemed particularly confident about this, because it recently abolished a zone based system (where papers were prepared for specific zones), which could have *limited* the effects of failure to a smaller region (though still uncomfortably large).

### Low fault tolerance

A single malevolent actor could do damage the equivalent of a wrecking ball, tearing through this fragile system. 

Low resolution pictures of the question paper taken half an hour before the exam by any one person connected in some way to the logistics of the question paper can be catastrophic, and one doesn't need to be an expert on memetics to know that this will eventually reach millions of people.

Even if it doesn't reach anybody before the exam ends, the revelation of this leak could still be catastrophic. It would ruin the credibility of the exam, and raise the usual demands for a retest.

This isn't theoretical knowledge from a systems design course. It's a literal description of the events of March 2018. Any giant system of importance with so many points of failure and such low fault tolerance **will fail**—the only question is *when*.

---

**Sources:**
- The practice of setting multiple set of questions for different zones: [1](http://www.business-standard.com/article/pti-stories/alternate-set-of-ques-papers-could-have-checked-leaks-ex-cbse-officials-118033000826_1.html), [2](https://www.indiatoday.in/pti-feed/story/alternate-set-of-ques-papers-could-have-checked-leaks-ex-cbse-officials-1201503-2018-03-30)