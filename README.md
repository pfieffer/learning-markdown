No local repo was made during this. For learning purpose only
# Learning Markdown 
>This is a quoted text. Spaces are important in **Markdown**

**Bold Text**
***Italic plus bold text***
*Italic Only Text*

Remember the spaces
* Bullet
  * Sub Bullet
  
## Checkboxes:
[x] Checkbox 1 
- [ ] Checkbox 2 
- [x] Checkbox 3 

## Table:

Zone|District|Municipality
-|-|-|
Narayani|Chitwan|Ratnanagar
### Java Code:
``` Java
     protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        btnMakeObjectRequest = (Button) findViewById(R.id.btnObjRequest);
        btnMakeArrayRequest = (Button) findViewById(R.id.btnArrayRequest);
        txtResponse = (TextView) findViewById(R.id.txtResponse);

        pDialog = new ProgressDialog(this);
        pDialog.setMessage("Please Wait....");
        pDialog.setCancelable(false);

        btnMakeObjectRequest.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                //making json object request
                makeJsonObjectRequest(); //function definition below
            }
        });
        
        btnMakeArrayRequest.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                //maing json array Request
                makeJsonArrayRequest(); //function definition below
            }
        });
    }
```


# Image Using Markdown Syntax
![Ed Sheeran Divide](https://www.radioliberatutti.it/images/extra/musica/Ed_Sheeran_Galway_Girl-cover.jpg)

*Can also use html code to display image*

  
# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag



The <a href> here is different than the `<a href>` here.

# Auto Syntax Highlighting (four spaces)
    int x=0;
    bool y==true;
    if(y){
        x+=2;
        System.out.println("The value of x is "+x);
        }





## Horizontal Rule
---
Use  Hyphens(3 or more)


## Markdown Image on Table
Oneplus 3T|Matebook X|Apple Macbook
-|-|-|
![caption](http://www.cellulare-magazine.it/wp-content/uploads/2016/11/OnePlus-3t-1.jpg)|![alt text](https://static2.teknoblog.com/wp-content/uploads/2017/05/huawei-matebook-x-230517-1.jpg)|![alt text](http://d.ibtimes.co.uk/en/full/1562290/new-apple-macbook-pro.png)

Important link : http://dillinger.io/
