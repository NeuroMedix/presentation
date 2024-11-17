Script :

Imagine Dr. Sarah Bennett, a research scientist at a small pharmaceutical startup specializing in Alzheimer’s treatments. Sarah wakes up each morning with a heavy weight on her shoulders, knowing that every passing day represents not just the loss of time but also the loss of hope for patients and families waiting for effective treatment options. Alzheimer’s is a relentless disease, robbing people of their memories, their identities, and their loved ones. Every three seconds, someone in the world develops dementia, and Alzheimer’s is its leading cause. In Canada alone, 750,000 people are living with this disease, making it the seventh leading cause of death.

Sarah’s journey, like that of many scientists, is one of uphill battles. Developing a new drug in her small lab is not just expensive; it’s painstakingly slow. Each candidate molecule she tests comes with a potential decade-long journey, and the odds of success are dismal, with only 1 in 5,000 compounds making it to the market. With global drug development costs now exceeding $1.5 billion per approved drug, Sarah needs a breakthrough—something that could transform her work and accelerate the path from lab to life-saving treatment.

This is where NeuroMedix steps in.

Our platform, NeuroMedix, is designed to help scientists like Sarah, empowering them to discover new drug candidates with unprecedented speed. We’re revolutionizing drug discovery for neurodegenerative diseases, and our first focus is Alzheimer’s. NeuroMedix utilizes the NP-VAE (Natural Product-oriented Variational Autoencoder), a powerful model trained on 30,000 compounds from DrugBank and other unique datasets teeming with complex, biologically-active molecules. Traditional models struggle to handle these intricacies, but ours thrives on them, thanks to advanced training methods that compress molecular structures into latent vectors packed with functional and structural details.

Here’s what this means for Sarah. In the past, she would spend months—or even years—testing a few potential candidates, not knowing if she was on the right track. Now, she can enter the name of any FDA-approved Alzheimer’s drug into our system. NeuroMedix then generates three new, carefully engineered drug candidates that are ready to be tested and synthesized. Each comes with crucial metrics: the SA Score tells her how easy the drug would be to synthesize, and the QED gives a snapshot of its drug-likeness. Our model also measures structural similarity using Tanimoto scores, and in our trials, we achieved an extraordinary 94.44% accuracy in preserving 3D structural integrity.

But what makes NeuroMedix truly innovative is that we haven’t just copied an existing model—we’ve pushed boundaries to make it work for Alzheimer’s drug discovery. The model encodes molecules from SMILES representations into chemical fingerprints that account for structural and functional nuances. It’s like giving Sarah a crystal ball, one that predicts viable molecules rather than relying on costly trial and error. The innovation lies not just in the model itself but in how we refined and adapted it for this specific use case.

However, creating this breakthrough wasn’t without its challenges. Given our limited computational resources during this hackathon, we could only train on structural data. Training on additional features like logP, SA score, and QED, which are essential for full drug viability, requires significant computational power. Yet, we have laid the groundwork, demonstrating that NeuroMedix can be expanded to a more feature-rich model when resources allow.

Despite these constraints, we’ve achieved something remarkable: we’ve shown how NeuroMedix could accelerate drug discovery for diseases like Alzheimer’s, making it more efficient and cost-effective. And beyond Alzheimer’s, the possibilities are endless. The system is built to scale, adaptable for other neurodegenerative diseases, or even entirely different therapeutic areas.

Sarah is no longer in a race against time, but rather on the front lines of a revolution. With NeuroMedix, the future of drug discovery is no longer a slow crawl but a leap forward, a breakthrough that brings hope and healing within reach. Our model, our technology, and our vision have the potential to transform not just one lab, but the entire field of medicinal chemistry, fueling the next generation of life-saving therapies.


### Slide 1: Introduction to Dr. Sarah Bennett
- Meet Dr. Sarah Bennett: A research scientist at a small pharmaceutical startup.
- Focus: Alzheimer’s treatments.
- Each day brings immense pressure: Every passing moment means more patients waiting for a breakthrough.

---

### Slide 2: The Urgency of Alzheimer’s
- Alzheimer’s is relentless, stripping memories, identities, and loved ones away.
- Every 3 seconds: Someone in the world develops dementia.
- Alzheimer’s is the leading cause of dementia.
- In Canada: 750,000 people live with this disease, making it the 7th leading cause of death.

---

### Slide 3: The Drug Development Struggle
- Sarah’s journey mirrors that of many scientists: slow and costly.
- Developing a new drug: Often a decade-long process.
- Success rates are dismal: Only 1 in 5,000 compounds make it to market.
- Global costs: Exceed $1.5 billion per approved drug.

---

### Slide 4: Enter NeuroMedix
- NeuroMedix: A game-changing platform designed to empower scientists like Sarah.
- Our mission: Revolutionize drug discovery for neurodegenerative diseases.
- First focus: Alzheimer’s.
- Core technology: NP-VAE model trained on 30,000 DrugBank compounds and unique, biologically-active datasets.

---

### Slide 5: How NeuroMedix Works
- Traditional models struggle; ours excels with complex compounds.
- Our NP-VAE model: Compresses molecules into latent vectors with rich structural and functional details.
- Example for Sarah: 
  - She inputs an FDA-approved Alzheimer’s drug.
  - NeuroMedix generates three new drug candidates.
- Metrics provided: SA Score (ease of synthesis) and QED (drug-likeness).

---

### Slide 6: Model Accuracy and Metrics
- Structural similarity measured using Tanimoto scores.
- Achieved 94.44% accuracy in preserving 3D structural integrity.
- NeuroMedix gives Sarah confidence, speeding up the drug discovery process.

---

### Slide 7: Pushing Boundaries with Innovation
- NeuroMedix: Not a mere copy of existing models.
- We refined and adapted the model specifically for Alzheimer’s drug discovery.
- Encodes molecules from SMILES into nuanced chemical fingerprints.
- A crystal ball for drug discovery, reducing costly trial and error.

---

### Slide 8: Challenges and Limitations
- Limited resources during the hackathon: Trained on structural data only.
- Full drug viability requires additional features like logP, SA score, and QED.
- Future potential: Expand to a feature-rich model with more computational power.

---

### Slide 9: Remarkable Achievements
- Despite constraints: NeuroMedix accelerates Alzheimer’s drug discovery.
- Efficiency and cost-effectiveness demonstrated.
- Built to scale: Adaptable for other neurodegenerative diseases or therapeutic areas.

---

### Slide 10: The Future with NeuroMedix
- Sarah is no longer racing against time but leading a revolution.
- NeuroMedix transforms drug discovery: A leap forward, not a slow crawl.
- Vision: Transform medicinal chemistry and fuel life-saving therapies for the next generation.
