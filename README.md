# Applied Geospatial Data Science with Python		

<a href="https://www.packtpub.com/product/learn-azure-synapse-data-explorer/9781803233956?utm_source=github&utm_medium=repository&utm_campaign=9781803233956"><img src="https://static.packt-cdn.com/products/9781803233956/cover/smaller" alt="Applied Geospatial Data Science with Python" height="256px" align="right"></a>

This is the code repository for [Applied Geospatial Data Science with Python](https://www.packtpub.com/product/learn-azure-synapse-data-explorer/9781803233956?utm_source=github&utm_medium=repository&utm_campaign=9781803233956), published by Packt.

**Leverage geospatial data analysis and modeling to find unique solutions to environmental problems**

## What is this book about?
Data scientists, when presented with a myriad of data, can often lose sight of how to present geospatial analyses in a meaningful way so that it makes sense to everyone. Using Python to visualize data helps stakeholders in less technical roles to understand the problem and seek solutions. The goal of this book is to help data scientists and GIS professionals learn and implement geospatial data science workflows using Python.

This book covers the following exciting features: 
* Understand the fundamentals needed to work with geospatial data
* Transition from tabular to geo-enabled data in your workflows
* Develop an introductory portfolio of spatial data science work using Python
* Gain hands-on skills with case studies relevant to different industries
* Discover best practices focusing on geospatial data to bring a positive change in your environment
* Explore solving use cases, such as traveling salesperson and vehicle routing problems

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/B09NC5XJ6D) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
world_ae = world.to_crs("ESRI:54032")
graticules_ae = grat.to_crs("ESRI:54032")
```


**Following is what you need for this book:**
This book is for you if you are a data scientist seeking to incorporate geospatial thinking into your workflows or a GIS professional seeking to incorporate data science methods into yours. You’ll need to have a foundational knowledge of Python for data analysis and/or data science.	

With the following software and hardware list you can run all code files present in the book.

### Software and Hardware List

As readers of this book, we assume that you come from a background in either data science or GIS.
We also expect that you have some foundational knowledge of working with Python.
Software/hardware covered in the book Operating system requirements
 Windows, macOS, or Linux
 Windows, macOS, or Linux
Additionally, you will need to set up keys to several APIs, from which you will access data throughout
the book.
API Setup link
OpenMapQuest https://developer.mapquest.com/user/login/
sign-up
Google Maps https://developers.google.com/maps
US Census Bureau https://api.census.gov/data/key_signup.html

| Software required                      | OS required                        |
| ------------------------------------   | -----------------------------------|
| Anaconda Distribution                  | Windows, Mac OS X, and Linux (Any) |                                                            
| Python 3.10.6                          | Windows, Mac OS X, and Linux (Any) |

Additionally, you will need to set up keys to several APIs, from which you will access data throughout
the book.

| API              | Setup link                                        |
| OpenMapQuest     | https://developer.mapquest.com/user/login/sign-up |
| Google Maps      | https://developers.google.com/maps                |
| US Census Bureau | https://api.census.gov/data/key_signup.html       |

The quality of the hardware can impact the runtime for some analyses, as is the case for most data
science activities. As such, we recommend hardware similar or better to the specified hardware outlined
to prevent any potential issues:
• NVIDIA GeForce GTX 1050
• 16 GB RAM

We recommend that you use Anaconda as your Python environment and package manager. To begin
installing the Anaconda Distribution, you’ll want to visit the Anaconda Distribution installation website
at https://docs.anaconda.com/anaconda/install/. The Python version we are using
throughout this book is 3.10.6, as this is one of the latest versions of Python available at the time of
publication. Leveraging this version will ensure that all packages are compatible. To make the setup
of your virtual environment as streamlined as possible, we’ve exported our environment.yml
file and uploaded it to the GitHub repository at https://github.com/PacktPublishing/Applied-Geospatial-Data-Science-with-Python.

To set up the virtual environment called GeospatialPython, launch Anaconda prompt and execute the following command:
```
conda env create -file environment.yml
```

You’ll need to substitute environment.yml for the full path of the downloaded file.

After the environment is installed, you can activate it by executing the following command:

```
conda activate GeospatialPython
```

Throughout the book, you’ll see the following code:
```
data_path = r'YOUR FILE PATH'
```

Anytime you see this, you’ll need to substitute ‘YOUR FILE PATH’ with the file path of the data folder
which can be downloaded from the GitHub repo. The data stored in the GitHub repo can be found
in the Releases section or by visiting: https://github.com/PacktPublishing/Applied-Geospatial-DataScience-with-Python/releases. There are three parts to the data:

Data.pt1.zip
LCMS_CONUS_v2021-7_Land_Cover_Annual_2021.zip
S2B_MSIL2A_20220504T161829_N0400_R040_T17TNF_20220504T210702.SAFE.zip
You’ll need to extract the contents of these zip folders and store the contents in a single folder. You’ll
then point to this folder any time you see ‘YOUR FILE PATH’ referenced in the Jupyter notebooks.Preface xvii

Similarly, you will also see the following code from time to time:
```
out_path = r"YOUR FILE PATH"
```
You’ll need to substitute YOUR FILE PATH in this code reference with the directory to which you’d like the output to be saved.

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://packt.link/AN9bG).

### Related products <Other books you may enjoy>
* Learning Geospatial Analysis with Python - Third Edition [[Packt]](https://www.packtpub.com/product/azure-synapse-analytics-cookbook/9781803231501) [[Amazon]](https://www.amazon.com/dp/1803231505)

* Applied Machine Learning Explainability Techniques [[Packt]](https://www.packtpub.com/product/limitless-analytics-with-azure-synapse/9781800205659) [[Amazon]](https://www.amazon.com/dp/1800205651)

## Get to Know the Author
**David S. Jordan**
has made a career out of applying spatial thinking to tough problem spaces in the
domains of real estate planning, disaster response, social equity, and climate change. He currently
leads distribution and geospatial data science at JPMorgan Chase & Co. In addition to leading and
building out geospatial data science teams, David is a patented inventor of new geospatial analytics
processes, a winner of a Special Achievement in GIS (SAG) Award from Esri, and a conference
speaker on topics including banking deserts and how great businesses leverage GIS.
