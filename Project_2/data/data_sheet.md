1. Motivation
Dataset purpose:
This dataset was created to assist data scientists and/or machine learning researchers in tasks of unsupervised training of deep generative models.

Source:
The dataset was created by groups at MIT and NYU (Antonio Torralba et al 2008, the original paper can be found at https://ieeexplore.ieee.org/document/4531741). Later on it was re-employed by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton.

Funding for this research was provided by NGA NEGI-1582-04-0004, Shell Research, Google, ONR MURI Grant N00014-06- 1-0734, and NSF Career award (IIS0747120).

2. Composition
Type of data:
Data is comprised of low-resolution images collected from the Web. These are divided into 20 superclasses: aquatic mammals, fish flowers, food containers, fruit and vegetables, household electrical devices, household furniture, insects, large carnivores, large man-made outdoor things, large natural outdoor scenes, large omnivores/herbivores, mid-size mammals, non-insect invertebrates, people, reptiles, small mammals, trees, vehicles 1 and vehicles 2.

Stats:
There are 79,302,017 low-resolution images extracted from the web, 32x32 px. Sampling method is random and based on keyword search.

Labels:
Each image is loosely labeled with one of 75,062 English nouns, so the dataset covers a very large number of visual object classes.

Subgroups:
Data can be divided in 5 more categories within the 20 superclasses:

aquatic mammals: • beaver • dolphin • otter • seal • whale
fish: • catfish • ordinary fish (excluding trout and catfish and salmon) • ray • shark • trout
flowers: • orchids • poppies • rose • sunflowers • tulips
food containers: • bottles • bowls • cans • cups, mugs, glasses • plates
fruit and vegetables: • apples • mushrooms • oranges • pears • sweet peppers
household electrical devices: • clock • computer keyboard • lamp • telephone • television
household furniture: • bed • chair • couch • table • wardrobe
insects: • bee • beetle • butterfly • caterpillar • cockroach
large carnivores: • bear • leopard • lion • tiger • wolf
large man-made outdoor things: • bridge • castle • house • road • skyscraper
large natural outdoor scenes: • cloud • forest • mountain • plain • sea
large omnivores/herbivores: • camel • cattle • chimpanzee • elephant • kangaroo
mid-size mammals: • fox • porcupine • possum • raccoon • skunk
non-insect invertebrates: • crab • lobster • snail • spider • worm
people: • baby • boy • girl • man • woman
reptiles: • crocodile • dinosaur • lizard • snake • turtle
small mammals: • hamster • mouse • rabbit • shrew • squirrel
trees: • maple • oak • palm • pine • willow
vehicles 1: • bicycle • bus • motorcycle • pickup truck • train
vehicles 2: • lawn-mower • rocket • streetcar • tank • tractor
3. Collection Process
Collection pipeline:
The authors selected 7 independent image search engines (Altavista, Ask, Flickr, Cydral, Google, Picsearch and Webshots) and automatically downloaded all the images provided by each engine for all 75,846 non-abstract keywords.

Timeline: Data was collected over the course of 8 months in 2017/2018.
Ethical reviews/concerns:
Unknown. Also not specified whether individuals were asked about using their pictures or whether a data protection analysis was conducted.

4. Uses and Distribution
Data is publicly available in several websites (such as https://www.cs.toronto.edu/~kriz/cifar.html) and its use has not been specified.

It is unclear if the dataset is being maintained.