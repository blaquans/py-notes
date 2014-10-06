py-notes
========

## IDE

* [iPython Notebook](http://nbviewer.ipython.org/)

      ipython notebook


## Importing Data

    fname = "out.csv"
    file = open(fname, "wb")
    writer = csv.writer(file)
    writer.writerow( ('Prix', 'Désignation') )
    writer.writerow( (9.80, 'Tarte aux pommes') )
    writer.writerow( ('13.40', 'Galette des rois') )
    writer.writerow( (2.45, 'Beignet') )
    file.close()


## Data Visualisation

* [Tutorial pour apprendre Bokeh](http://nbviewer.ipython.org/gist/fonnesbeck/ad091b81bffda28fd657)




