# SEMCON Seismic Use-case Mashup

The graphical user interface for `sc-sparql` that is connected to `sc-seismic` is available in the following [link](https://rebrand.ly/sc-seismic-sparql)

![1560929653274](images/1560929653274.png)

On the left side you will see [sc-seismic-sparql](http://pebbie.org/mashup/widget/sc_seismic_sparql) widget where you can change the source `sc-seismic` API URL amd the duration parameter to the API. 
You can use the text box, slider, or specify the start date using the date picker (*note: the duration is limited to 365 days*). 

If you scroll down the widget you will see the SPARQL query editor with a default query (*left-hand side*) and the query result in JSON format (*right-hand side*).

![1560929863305](images/1560929863305.png)

You can specify the SPARQL query that you want to execute here and re-run the widget (click on play/triangle button) to get the updated result. 