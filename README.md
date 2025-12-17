# PA-brain-project

This repository hosts the results of the project "**The Brain-Wide Morphology of Objective Measurements of Physical Activity: A Population_Based Study of 4,409 Adolescents**"
Vertex-wise results can be interactively explored using the application hosted [here (https://0197f497-6aef-f372-1f0c-5d0ea91db8ef.share.connect.posit.cloud/)].

Interactive application for visualizing whole-brain surface vertex-wise statistical maps is a fork of the [**`verywise`wizard** app here (https://github.com/SereDef/verywise-wizard.git)].
<img src="www/vwwizard_logo.png" width="400"/>

### Running the application locally 
The 3D brain surface reconstructions (especially the high-resolution ones) may be faster to generate on your local machine. 
To run the application locally (on a UNIX system with Python 3.9 installed), run the following lines into your terminal:
```
git clone https://github.com/SereDef/verywise-wizard

cd verywise-wizard
pip install -r requirements.txt

shiny run --launch-browser app.py
```

## Funders  
<img src="www/funders.png" height="100" alt="Funders"/>

The Posit Connect Cloud app was supported by the *FLAG-ERA* grant [**Infant2Adult**](https://www.infant2adult.com/home) and by The Netherlands Organization for Health Research and Development (ZonMw, grant number 16080606). 


