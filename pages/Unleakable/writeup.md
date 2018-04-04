# Everybody gets a paper

Wait... What?

Everyone gets a question paper. Of their own.

How about making every question paper unique? This would make *leaks* akin to leaking sample papers, because every question paper would be unique. 

## So... every paper is random?

No. Unique is different from random. Every paper is *procedurally generated* using an extensive dataset of question types, a schema for the paper, and a random number. Simply put, each paper is of the same difficulty and is generated such that no question in a particular paper is harder than one in another set.

Let's explain procedural generation. 

So imagine we have (or rather, CBSE has) datasets of question types. It isn't quite a simple database of question-answer pairs, but is tailored such that the questions are generated at the same difficulty. 

There's the schema—this is also called the 'marking scheme' and is published every year—and refers to the number of questions that will be present from each topic.

And we have a random number, unique for every paper. This one's called the *seed*. This is similar to how games (like Minecraft!), application fuzzers, and a lot of other software function.

An algorithm generates the question paper and answer key using the dataset, schema, and seed. The algorithm generates the same output given the same seed.

And now, we have a unique question paper with its own answer key.

## So how does this work IRL?

Simple. Instead of directly sourcing questions from subject experts, we get them to help create a dataset of question types.

The question papers are printed and distributed just like they are now, except that leaks are no longer a concern. They have a seed printed on them, instead of a set number. The seed could just be a 5-6 letter alphanumeric key, as that provides enough combinations.

Now, sometime before the exam, the head office could let regional offices access their API and download a suitable range of question papers. Or just run the algorithm on their end after downloading the dataset. 

Leaking doesn't exist as a concept when every question paper is unique, making this **unleakable**.
