To procedurally generate question papers, we would need:

- A **dataset of question types**
    - Question types can be represented as **layered graphs**.
    - The question types can be engineered to produce questions of the **same difficulty** and ideally, take the **same time to solve**.
- A **schema**: It directs the layout of the question paper.
- A **seed**: a unique number for every question paper.
    - It will be printed on the question paper, and examinees write it down on the answer booklets. 
    - Additionally, a barcode/QR code sticker can also be used to speed things up.
- An **algorithm**: it procedurally generates question papers from the dataset and schema given a seed.
    - The procedural generation algorithm is **deterministic**; it generates the exact same question paper, given the same seed.
    - The same algorithm is used to generate the **answer keys** at evaluation time (using the seed number on the answer sheet).