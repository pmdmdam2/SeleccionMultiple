# SeleccionMultiple

Es un ejemplo de ListView con selección múltiple. Se utiliza un adaptador de tipo ArrayAdapter basado en un modelo datos implementado sobre una array de String. El layout de cada elemento de lista se obtiene de los recursos de Android, es android.R.layout.simple_list_item_multiple_choice. Este layout está formado CheckedTextView.

Cada elemento del ListView es seleccionable, los elementos seleccionados se muestran en TextView en la parte inferior de la interfaz. Observad el método de evento onItemClick que se obtiene a partir de la implementación, a nivel de clase, de la interfaz de evento ListView.OnItemClickListener.

El aspecto del diseño de la interfaz es el siguiente:

![Diseño de la interfaz](https://raw.githubusercontent.com/pmdmdam2/SeleccionMultiple/master/app/src/main/assets/lista_multiple.png)

El aspecto de la aplicación en ejecución es el siguiente:

![Aplicación en ejecución](https://raw.githubusercontent.com/pmdmdam2/SeleccionMultiple/master/app/src/main/assets/prueba_lista_multiple.png)
