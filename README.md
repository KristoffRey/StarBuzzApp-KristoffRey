# My version of the "Starbuzz App"
This application demonstrates the hierarchy of views using a switch case and the Intent with a sample code below:

```
public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
                switch (position) {
                    case 0:
                        Intent goToDrinks= new Intent(TopLevelActivity.this, Drinks.class);
                        startActivity(goToDrinks);
                        break;
                    case 1:
                        Intent goToFood = new Intent(TopLevelActivity.this, Food.class);
                        startActivity(goToFood);
                        break;
                    case 2:
                        Intent goToStores = new Intent(TopLevelActivity.this, Stores.class);
                        startActivity(goToStores);
                        break;
                }
            }
```

Intent allows one activity to move to another with the option to add values which will be passed on to the next activity

##Problem
Do design an application with a menu having 3 elements with each element having their own "submenu" with three more elements and finally displaying the details of the inner three elements.

##Disclaimer
This application is not an official app of Starbucks nor does it aim to be of any commercial value.

##Screenshots
![alt tag](https://github.com/KristoffRey/StarBuzzApp-KristoffRey/blob/master/Screenshot_2015-10-02-20-02-47.png)
![alt tag](https://github.com/KristoffRey/StarBuzzApp-KristoffRey/blob/master/Screenshot_2015-10-02-20-02-49.png)
![alt tag](https://github.com/KristoffRey/StarBuzzApp-KristoffRey/blob/master/Screenshot_2015-10-02-20-02-53.png)
![alt tag](https://github.com/KristoffRey/StarBuzzApp-KristoffRey/blob/master/Screenshot_2015-10-02-20-02-57.png)
![alt tag](https://github.com/KristoffRey/StarBuzzApp-KristoffRey/blob/master/Screenshot_2015-10-02-20-03-01.png)
