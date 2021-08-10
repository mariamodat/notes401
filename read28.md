# Create dynamic lists with RecyclerView   
## waht is recyclerView ?
it provides a fixed size window so that we can load a large data.

 ## Key Classes 
 it's a multiple classes that are used to build a dynamic list. 

 * RecyclerView is the ViewGroup that contains the views.notice that it's a view itself so we can add it to the layout.

 * View holder object : each element in the list. once it's created will be binded to the RecyclerView (RecyclerView.ViewHolder.) using RecyclerView.Adapter

 *  layout manager to arrange the individual elements in the list.

 ## Implementing the RecyclerView 
  
  * we should add the RecyclerView AndroidX library to gradle.build 

  * create a model class to be as a data source.
  * add RecyclerView to activity to display items. 

  * create a layout XML to view the item.

  ![img](https://sites.google.com/site/iotmobilemodule/_/rsrc/1479195592949/3-material-design/3-2-recycler-view/1.jpg)
