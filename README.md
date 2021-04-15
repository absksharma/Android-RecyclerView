# Android-RecyclerView
Dynamic list with the help of RecyclerView :
# RecyclerView Concept 
 - View Holder - This will hold the view and helps in Recycling.
 
 - Adapter - This will adapt out dat aso that it can be displayed in the list.




### When you define your adapter, you need to override three key methods:

### onCreateViewHolder(): 
RecyclerView calls this method whenever it needs to create a new ViewHolder. The method creates and initializes the ViewHolder and its associated View, but does not fill in the view's contents—the ViewHolder has not yet been bound to specific data.

### onBindViewHolder(): 
RecyclerView calls this method to associate a ViewHolder with data. The method fetches the appropriate data and uses the data to fill in the view holder's layout. For example, if the RecyclerView dislays a list of names, the method might find the appropriate name in the list and fill in the view holder's TextView widget.

### getItemCount(): 
RecyclerView calls this method to get the size of the data set. For example, in an address book app, this might be the total number of addresses. RecyclerView uses this to determine when there are no more items that can be displayed.
