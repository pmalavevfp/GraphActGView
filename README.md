# GraphActGView

Es repositorio donde se probará la impmentacion de graficas en una actividad concreta 
de una aplicación creada en Android Studio, utilizando la la librerias de GraphView 

  "Para utilizar GraphView en tu proyecto de Android Studio, primero debes asegurarte de tener
  agregada la dependencia del módulo en el archivo build.gradle del módulo app de tu proyecto.
  Para ello, agrega la siguiente línea en el archivo build.gradle:
  implementation 'com.jjoe64:graphview:4.2.2'
  Luego, debes añadir la vista del gráfico en tu layout XML. Por ejemplo, para añadir un gráfico de
  líneas, puedes usar el siguiente código:
    <com.jjoe64.graphview.GraphView
    android:id="@+id/graph"
    android:layout_width="match_parent"
    android:layout_height="match_parent" />
  Para configurar el gráfico y mostrarlo en tu actividad o fragmento, primero debes obtener una
  referencia a la vista del gráfico en tu código Java. Por ejemplo:
  GraphView graph = (GraphView) findViewById(R.id.graph);
  Luego, puedes configurar el gráfico y agregar datos a él. Por ejemplo, para agregar un conjunto de
  datos y mostrar un gráfico de líneas con ellos, puedes usar el siguiente código:
    List<DataPoint> points = new ArrayList<>();
    points.add(new DataPoint(0, 1));
    points.add(new DataPoint(1, 5));
    points.add(new DataPoint(2, 3));
    LineGraphSeries<DataPoint> series = new LineGraphSeries<>(points.toArray(new
    DataPoint[points.size()]));
    graph.addSeries(series);

  Más información:
     https://www.geeksforgeeks.org/line-graph-view-in-android-with-example/""
Para más iformcion se puede ver:

    https://github.com/jjoe64/GraphView/wiki/Documentation
