# RecyclerView ItemClickListener
 Classe de auxilio em cliques do recyclerview

#Exemplo

```
recyclerView.addOnItemTouchListener(new RecyclerItemClickListener(getBaseContext(), recyclerView, new RecyclerItemClickListener.OnItemClickListener() {
    @Override
    public void onItemClick(View view, int position) {
        //CLIQUE NORMAL
    }

    @Override
    public void onLongItemClick(View view, int position) {
        //CLIQUE LONGO
    }

    @Override
    public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
    }
}));
```