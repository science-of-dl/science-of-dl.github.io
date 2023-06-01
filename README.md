# _Sudo Science_: Empirical Approaches for Understanding How Deep Learning Works

Despite the widespread proliferation of neural networks, the mechanisms
through which they operate so successfully are not well understood.
While there is a strong community that seeks to understand training and
generalization, this work is largely performed by developing
*fundamental mathematical theories*. These theories often rely on strong
assumptions and simplified setups that admit tractable mathematical
analysis, but have the unintended consequence of also paring away
complexities of deep learning pipelines that may be responsible for
their success. Furthermore, these theories focus largely on classifiers,
and have not yet addressed the remarkable performance of modern
generative models. At the same time, there is a large community studying
*applied science* — engineering new algorithms, tuning hyper-parameters,
and achieving new benchmark numbers.

Meanwhile, the deep learning community has had trouble creating a home
for fundamental science, i.e, empirical studies that seek to understand
the phenomena that underlie neural network behaviors, and test the
veracity of mathematical theories, using the scientific method without
resorting to highly simplified toy models. Fundamental empirical studies
risk rejection by the deeply mathematical fundamental ML community
because they do not contain proofs, often leading to toy theorems
appearing in papers to satisfy reviewers, and simultaneously fail to
appeal to the applied science community because they do not advance
conventional engineering benchmarks. Nonetheless, this approach has been
indispensable for understanding deep learning and has given rise to
important topics such as the lottery ticket hypothesis , deep double
descent , and the sharp-flat hypothesis for generalization . In short,
despite its fundamental importance, fundamental science lacks strong
representation in the deep learning community because it does not fit
into the conventional categories of theory, methods, or applications.

**The goal of this workshop is to be a home for fundamental studies that
use empirical science to examine the inner workings of the full-fledged
neural network systems that are used in practice, particularly with
respect to understanding generalization**. This focus will be reflected
through contributed talks, invited talks, a poster session, and a panel
discussion comprising both theorists and empirical ML researchers who
will discuss the roles of each approach in developing an understanding
of deep learning. We wish to differentiate this workshop from other
important but distinct efforts on interpretable and safe machine
learning, which tend to be focused on interpreting what influences the
predictions of a trained model, rather than understanding how neural
networks provide good generalization. We believe a focused approach is
required to make this topic recognized as a distinct and vital research
effort.

Topics of focus will include **(1)** What phenomena have recently been
demonstrated in empirical studies, but for which we do not yet have a
theoretical understanding? **(2)** Do rigorous theories stand up to the
test of sudo science, or do they fail to describe the behaviors, inputs,
and training loops required for deep learning in practice? **(3)** What
standards should be applied to fundamental experimental work in deep
learning, and what is the role of reproducibility? **(4)** How can
recent empirical work inform us in designing better models and
algorithms?

 If you have any questions, please reach out to us at this email (<scienceofdl@gmail.com>).

## Tentative Workshop Schedule (times CDT)


| Time    	| Speaker/ Activity   	     | 
|---------	|-----------	     |
| 9:00am-9:30am 	| Informal Coffee Social    | 
| 9:30am-10:05am    | Invited Talk 1 (Ludwig Schmidt) and Q&A | 
|10:05am-10:40am |  Invited Talk 2 (Yasaman Bahri) and Q&A |
| 10:40am-11:15am | Invited Talk 3 (Zahra Kadkhodaie) and Q&A |
| 11:15pm-12:00pm | Contributed Talks Session 1 | 
| 12:00pm-1:30pm | Lunch Break |
| 1:30pm-2:05pm | Invited Talk 4 (Behnam Neyshabur) and Q&A |
|2:05pm-3:30pm | Contributed Talks Session 2 |
| 3:00pm-3:45pm | Panel Discussion | 
|3:45pm-5:30pm |  Poster Session |
| 5:30pm-6:30pm |  Science Meets Theory Speed Dating with Snacks |
| 6:30pm - | Dinner at Legacy Kitchen's Craft Tavern | 


*Panel members - Preetum Nakkiran, Surbhi Goel, Zachary Lipton

----


## Invited Speakers


**[Yasaman Bahri](),** _Research Scientist at Google DeepMind_.
>Yasaman is a theoretical and computational scientist working at the intersection of machine learning and physical science. In one direction, she has worked on building foundations for deep learning and investigated core machine learning problems. In the other, she is interested in connections with and applications of machine learning to specific domains of physical science.


**[Ludwig Schmidt](),** _Assistant Professor at University of Washington, Research Scientist at Allen Institute for AI, Member of LAION_.
>Ludwig’s research interests revolve around the foundations of machine learning, often with a focus on datasets, evaluation, reliable generalization, and large models. He is the recipient of a Google Ph.D. Fellowship, a Microsoft Simons Fellowship, a Best Paper Award from the International Conference on Machine Learning (ICML), and a Sprowls Dissertation Award from MIT.


**[Zahra Kadkhodaie](),** _PhD student at NYU, Guest Researcher at the Center for Computational Neuroscience_.
>Zahra’s research focuses on understanding and improving deep neural networks by analyzing and imposing mathematical symmetries on the architecture.  She is currently a PhD student advised by Prof.  Eero Simoncelli.

**[Behnam Neyshabur]()** _Senior Staff Research Scientist at Google DeepMind_.
>Behnam is a senior staff research scientist at Google DeepMind. Before that, he was a postdoctoral researcher at New York University and a member of Theoretical Machine Learning program at Institute for Advanced Study (IAS) in Princeton. Behnam’s interests include the science of deep learning and (out-of-distribution) generalization, where he has studied the role of implicit bias as well as compression-based notions of generalization.




## Panelists

**[Zachary Lipton](),** _Assistant Professor at CMU, Chief Scientific Advisor to Abridge_.
>Zachary’s research spans core ML methods and theory, their applications in healthcare and natural language processing, and critical concerns, both about the mode of inquiry itself, and the impact of the technology it produces on social systems.

**[Preetum Nakkiran](),** _Research Scientist at Apple_.
>Preetum’s research builds conceptual tools for understanding learning systems, including deep learning--- using both theory and experiment. His past works include Deep Double Descent, the Deep Bootstrap Framework, and Distributional Generalization.

**[Surbhi Goel](),** _Magerman Term Assistant Professor of Computer and Information Science at University of Pennsylvania_.
>Surbhi’s research interests lie at the intersection of theoretical computer science and machine learning, with a focus on developing theoretical foundations for modern machine learning paradigms, especially deep learning.





## Organizers

**Micah Goldblum,** _New York University, Main Coordinator_.
> Micah Goldblum is a postdoctoral researcher at the Center for Data Science at NYU.  His research focus lies at the intersection of machine learning and optimization with the aim of creating practical systems that are secure, efficient, and reliable on real-world problems and understanding how such systems work. His current work focuses on understanding the mechanisms of data augmentation, transfer learning, and compressibility-based notions of generalization.  Micah was the chair of the organizing committee for the NeurIPS 2020 Workshop on Dataset Curation and Security.

**Tom Goldstein,** _University of Maryland, College Park_.
>Tom Goldstein is the Perotto Associate Professor of Computer Science at the University of Maryland.  His research lies at the intersection of machine learning and optimization, and targets applications in computer vision and signal processing. Before joining the faculty at Maryland, Tom completed his PhD in Mathematics at UCLA, and was a research scientist at Rice University and Stanford University. Professor Goldstein has been the recipient of several awards, including SIAM’s DiPrima Prize, a DARPA Young Faculty Award, a JP Morgan Faculty award, and a Sloan Fellowship.

**Andrew Gordon Wilson**, _New York University_.
>Andrew is an Associate Professor in the Courant Institute of Mathematical Sciences and Center for Data Science at New York University. His work is focused on developing a prescriptive understanding of model construction and generalization, often working with probabilistic and Bayesian methods involving deep neural networks and Gaussian processes. He has organized over 10 highly successful workshops across NeurIPS and ICML, including a major NeurIPS 2017 symposium on interpretable machine learning. Andrew also co-organized the NeurIPS 2021 competition for approximate inference in Bayesian deep learning, has been the EXPO Chair for ICML 2020, 2021, and is the Tutorial Chair for NeurIPS 2022.

**Sanae Lotfi,** _New York University_.
> Sanae is a PhD student at the Center for Data Science at NYU and a DeepMind fellow, working with Professor Andrew Gordon Wilson. She is currently interested in understanding and quantifying the generalization of deep learning models. Her latest work focuses on understanding the failure modes of Bayesian deep learning under distribution shift and the limits of the marginal likelihood in predicting generalization. Before joining NYU, Sanae obtained a master’s degree in applied mathematics from Polytechnique Montreal where she focused on designing stochastic first and second order algorithms with compelling theoretical and empirical properties for machine learning. Sanae co-organized the NeurIPS 2021 Approximate Inference in Bayesian Deep Learning competition. 

**Gowthami Somepalli,** _University of Maryland, College Park_.
> Gowthami is a Ph.D. student in the Department of Computer Science at the University of Maryland, College Park. Her research is mainly focused on building both theoretical and empirical tools to understand deep learning models, especially for various Computer Vision tasks. Before starting her Ph.D., she worked in industry in various product and engineering roles and received her bachelors from IIT Madras. She is also the recipient of 2021 Kulkarni Fellowship.

**Jonas Geiping,** _University of Maryland, College Park_.
> Jonas is a postdoctoral researcher at the University of Maryland, College Park. His research is centered on the intersection of current deep learning and mathematical optimization. As such, recent work has included understanding the impact of optimization on fundamental phenomena behind generalization and other topics in empirical investigation of deep learning phenomena. Jonas was awarded a PhD by the University of Siegen in 2021. He has previously co-organized the workshop  “Imaging and Vision from Theory to Applications”.

**Aniruddha Saha,** _University of Maryland, College Park_.
>Aniruddha is a postdoctoral researcher at the University of Maryland.  Aniruddha’s current research focuses on memorization in neural networks and on language modeling.  During his PhD, he worked as a Machine Learning Research Intern at Bosch Center for AI, an Applied Scientist Intern at Amazon Rekognition, and a Machine Learning Intern at Matroid. Prior to this, he was part of the DRAM Group of Samsung Semiconductor India Research.
