# Course projects

Below ideas for course projects. If you have a question on any of them, feel
free to create a new GitHub issue or add your question to an existing one.

Deadline: TBD

Hand in your code and a short report on your work.

## Discover the Higgs boson

Can you discover the Higgs boson? This project uses the Higgs Boson data set from one of the most popular Kaggle competitions ever. The obvious task to solve with this data set is to build a classifier that can select Higgs events. You can also attempt to using various dimensionality reduction techniques to create visualisations or create a regression task that aims to estimate the mass of the Higgs boson in each event. This is a tabular data set (no images).

You can find the data and a description of the features at: <http://opendata.cern.ch/record/328?ln=en>

Note: that this task uses "approximate median significance" as the evaluation metric, which is closer to what the real measure used at CERN is than simply accuracy.

## MAGIC gamma ray identification

The MAGIC telescope is based on one of the Canary islands and aims to observe air showers. The obvious task is to construct a classifier that correctly separates hadron observations from gamma ray observations. You can also attempt to using various dimensionality reduction techniques to create visualisations or separate the data. This is a tabular data set (no images).

You can find the data and a description of the features at: <http://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope>

Note: For this task the performance at different values of the false positive rate is used.

Wikipedia on MAGIC: <https://en.wikipedia.org/wiki/MAGIC_(telescope>) MAGIC homepage: <https://wwwmagic.mpp.mpg.de/>

## Merced land use classification

Can you predict what is on a satellite image? This is a well known multi class image classification problem. There are a total of 21 different classes with only 100 images each. The obvious task is to construct a classifier that correctly labels each image. You can also attempt to use various dimensionality reduction techniques to create visualisations or separate the data.

You can find the data and a description at: <http://vision.ucmerced.edu/datasets/landuse.html>

Note: You can create "more" data by rotating, mirroring, stretching, and cropping the original images. This goes under the name of data augmentation.

## (DIY) To map or not to map?

This project is similar to the Merced land use project but you can create your own data set! Several NGOs operate in very, very remote areas of the world for which no maps exist. They spend a lot of effort creating these maps <https://www.hotosm.org/>. One challenge they face is that remote areas mostly contain emptiness. It would be helpful if there was a tool that could sort satellite images by how likely they are to contain something that needs mapping (a road, house, etc) vs an 'empty' image with no boundaries between different land types.

By combining satellite images from the Bing search engine and OpenStreetMap you can construct a data set from which to learn whether an image contains something worth mapping or not. The challenge is finding an area of the world that has good OpenStreetMap coverage to construct that training data, but is not too different from the region on which the classifier will be applied.

You can extend this task by learning to predict what needs mapping, turning this into a multi class classification problem.

Note: Ask me for some pointers for code to download satellite tiles from Bing

## (DIY) (DIY) Your own OpenStreetMap project

OpenStreetMap (OSM) contains a very large amount of data about the world. Think of your own project based on either the OSM database alone or a combination of OSM and satellite images.

Note: This is a double DIY project as you need to find your own data and think of a task. Note: This means you have a lot of freedom (interesting projects!) but also means you could set yourself an impossible task. If you want to work on this please let me know and submit a proposal before you start (via GitHub).

## Bank

This is a classic machine-learning data set. The task is to predict based on customer attributes whether or not they will agree to buy a product from the bank. This is a classification task. You can also attempt to use various dimensionality reduction techniques to create visualisations or separate the data. This is a tabular data set (no images).

You can find the data and a description of the variables here: <http://archive.ics.uci.edu/ml/datasets/Bank+Marketing>

Note: Use the full data set in the file bank-additional-full.csv

## Adult

This is a classic machine-learning data set. The task is to predict from census data whether or not a person earns more than $50000\. This is a classification task. You can also attempt to use various dimensionality reduction techniques to create visualisations or separate the data. This is a tabular data set (no images).

You can find the data and a description of the variables here: <http://archive.ics.uci.edu/ml/datasets/Adult>

## Diabetes

The task is to predict whether or not a patient will be re-admitted to hospital or not within 30 days. This is a classification task. Interesting questions include: which factors contribute to re-admission, can you visualise the data in interesting ways. This is a tabular data set (no images).

You can find the data and links to descriptions here: <https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008> Original research that generated this data: <https://www.hindawi.com/journals/bmri/2014/781670/>

## (DIY) (DIY) Swiss open data

There are many open datasets available for cities in Switzerland. For example: Zurich Velo Counters: <https://data.stadt-zuerich.ch/dataset/verkehrszaehlungen-werte-fussgaenger-velo> SBB actual times: <https://opentransportdata.swiss/en/dataset/istdaten>

Can you find interesting patterns in the Zurich bike data and construct a machine-learning task on it?

Can you create a algorithm that can predict how late a SBB train will be? Or maybe whether it is likely to arrive on time or not.

Note: These data sets can be very large, are real world and you need to create your own project from them. This means you have a lot of freedom (interesting projects!) but also means you could set yourself an impossible task. If you want to work on this please let me know and submit a proposal before you start (via GitHub). This is a tabular data set (no images).

## (DIY) (DIY) (DIY) Create or find your own data, with your own problem

Create your own project with your own data, and problem statement.

This means you have a lot of freedom (interesting projects!) but also means you could set yourself an impossible task. If you want to work on this please let me know and submit a proposal before you start (via GitHub).
