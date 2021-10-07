# OffendES

1. Paper: OffendES: A New Corpus in Spanish for Offensive Language Research (RANLP 2021)

2. Authors: 

	- Flor Miriam Plaza-del-Arco: 		  fmplaza[at]ujaen.es
	- Arturo Montejo-Raéz: 			      amontejo[at]ujaen.es
	- L. Alfonso Ureña López: 			    laurena[at]ujaen.es
	- María-Teresa Martín-Valdivia: 		maite[at]ujaen.es

3. Description: 

	A recently created dataset based on comments over different social media platforms (YouTube, Instagram and Twitter) have been collected, tracking post comments on well-known young Spanish influencers. More than 50,000 comments have been manually annotated over Amazon Mechanical Turk, making this corpus the largest and more varied Spanish dataset for offensive language analysis. The corpus have been carefully created and comments are classified into four different categories, providing more fine-grained classes considering the type and target of offenses:

		- Offensive, target is a person (OFP)
		- Offensive, target is a group of people or collective (OFG)
		- Non-offensive, but with expletive language (NOE)
		- Non-offensive (NO)
		- No label (None). When no consensus among annotators is reached.

	The corpus is split into two different sets: one labeled by three annotators (3-Ann subset) and another labeled by 		ten annotators (10-Ann). Both sets are useful for multiclass classification analysis and the latter for multioutput 		regression analysis (multiclass with confidence values).

	- Number of instances in the 3-Ann subset:  44,951 
	- Number of instances in the 10-Ann subset: 13,706

4. Number of attributes (including target labels): 

	- 3-Ann subset:   9
	- 10-Ann subset: 16

5. Attribute information:

	- commment_id 		      (identifier of each conversation message)
	- media		              (data source of the message with three possible values: Instagram, Twitter and Youtube)
	- influencer: 		      (influencer to whom the message is associated)
	- influencer_gender:    (gender of the influencer with two possible values: man, woman)
	- comment:		          (the text of the message)
	- ann1 - ann10:	        (the target provided by each annotator with four possible values: 0FP, OFG, NOE, NO, None). Note than the 3-ann subset contains 3 annotators and the 10-ann subset contains 10 annotators. 
	- label: 		            (final target attribute of the message with four possible values: 0FP, OFG, NOE, NO, None)



