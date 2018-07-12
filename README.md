# 3D-geoinformation--1-Research-
A basic procedural modelling engine for generating buildings and other features in CityGML
Ready to use datasets
If you are interested only in the datasets, without the need to run the code, please visit my webpage to download a prepared collection of datasets: Emanuz.geek

Introduction
semantically structured 3D city models in multiple LODs are not available. This project presents an effort to bridge this gap, by developing a basic procedural modelling engine which generates random CityGML buildings to test software and carry out various experiments. This experimental software prototype was developed as a part of my PhD research.

The engine is composed of two modules. The first one is procedural: it randomly generates buildings and their elements according to a set of rules and constraints. The buildings are realised through parameters which are stored in an XML form. The second part of the engine reads this data and constructs CityGML data in multiple LODs.

What Random3Dcity is not
Random3Dcity is not intended to compete with ESRI's CityEngine and similar tools, which are focused on taking real-world data and augmenting them for various purposes such as urban planning. This tool is far from that: it simply provides synthetic CityGML data in multiple levels of detail.


