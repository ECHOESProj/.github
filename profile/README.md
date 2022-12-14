# The ECHOES Project Software

[ECHOES (Effect of climate change on bird habitats around the Irish Sea)](https://echoesproj.eu/)
seeks to address how climate change will impact coastal bird habitats of the Irish Sea,
and what effect this could have on our society, economy, and shared ecosystems.

The project is funded through [an Irish Welsh Programme](https://irelandwales.eu),
which promotes co-operation in the areas of innovation, climate change and sustainable development.
It is part-funded by the 2014-2020 European Regional Development Fund,
through the Welsh Government.

The code in these repositories was developed for the ECHOES project.

The ECHOES web application was developed to visualize the results of analysis
(such as predicted probability maps of the birds) and bird tracking data.
It also provides Earth Observation (EO) data, habitat maps and other data,
which can be used to gain a holistic understanding of the birds and their habitats.
It also enables to land mangers to understand how their land is changing over time.

There are two components: the *EO Service* and the *web component*.
The EO Service code has been released here,
and the web-component code will follow at a later date.

## The EO Service

[Compass Informatics](https://compass.ie) developed the ECHOES EO Processing Service,
to automate the processing of Copernicus data for the web component,
and provide an integrated environment for developing algorithms.

Read [the EO Service documentation](https://docs.compass.ie/EarthObservationDocs/)
(also the [eo-docs](https://github.com/ECHOESProj/eo-docs) repo) for an overview and usage instructions.

The EO Service comprises the following repositories:

* [eo-docs](https://github.com/ECHOESProj/eo-docs)
* [eo-playbooks](https://github.com/ECHOESProj/eo-playbooks)
* [eo-custom-scripts](https://github.com/ECHOESProj/eo-custom-scripts)
* [eo-io](https://github.com/ECHOESProj/eo-io)
* [eoian](https://github.com/ECHOESProj/eoian)
* [eo-processors](https://github.com/ECHOESProj/eo-processors)
* [eo-tracking-matchup](https://github.com/ECHOESProj/eo-tracking-matchup)
* [eo-stack](https://github.com/ECHOESProj/eo-stack)
* [websockets-server](https://github.com/ECHOESProj/websockets-server)
* [eo-notebooks](https://github.com/ECHOESProj/eo-notebooks)
