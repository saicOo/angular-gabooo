![Screenshot 2021-10-15 045433](https://user-images.githubusercontent.com/83503164/137424781-0a5c1942-2580-4c99-b7ea-0a3b522fa539.png)

# [e-commerce store](https://saicoo.github.io/angular-gabooo/)
- single page application
- HTML
- CSS
- javaScript/TypeScript
- Bootstrap
- Angular
## Getting started
Install Json Server

```
npm i -g json-server
```
Creat a `db.json` file with some data
```json
{
  "collection": [
    {
      "id": 1,
      "image": [
        "https://images.hugoboss.com/is/image/boss/hbeu50450711_410_350?$large$=&fit=crop,1&align=1,1&wid=270&qlt=80",
        "https://images.hugoboss.com/is/image/boss/hbeu50450711_410_100?$large$=&fit=crop,1&align=1,1&extendN=0.05,0.05,0.05,0.05&wid=462&qlt=80",
        "https://images.hugoboss.com/is/image/boss/hbeu50450711_410_360?$large$=&fit=crop,1&align=1,1&wid=462&qlt=80"
      ],
      "title": "Cotton Contrast-Stripes",
      "description": "Cotton Contrast-Stripes Chest Pocket Regular-Fit Shirt for Men Cotton Contrast-Stripes Chest Pocket Regular-Fit Shirt",
      "price": 900,
      "gender": "male",
      "size": "xl",
      "category": "winter",
      "popular": "new"
    },
    {
      "id": 2,
      "image": [
        "https://www.dressinn.com/f/13834/138346353/pieces-cilla-high-neck-sweater.jpg",
        "https://www.dressinn.com/f/13809/138095241_3/pieces-bibi-sweater.jpg",
        "https://www.dressinn.com/f/13834/138346353_4/pieces-cilla-high-neck-sweater.jpg"
      ],
      "title": "Bibi Sweater Misty Rose",
      "description": "Bibi Sweater Misty Rose Bibi Sweater Misty Rose Bibi Sweater Misty Rose Bibi Sweater Misty Rose Bibi Sweater Misty Rose",
      "price": 1200,
      "gender": "fmale",
      "size": "xxl",
      "category": "spring",
      "popular": "bestsellers"
    },
    {
      "id": 3,
      "image": [
        "https://z.nooncdn.com/products/tr:n-t_400/v1603275401/N36739610V_1.jpg",
         "https://z.nooncdn.com/products/tr:n-t_400/v1603275401/N36739610V_2.jpg"
         "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQxDyrZno3MY3QTl7BoVuCHJe-nQJF5dG3-F0ZwSDX4YKaxSa3-amGENW9PmpDqroWbzpw&usqp=CAU"
      ],
      "title": "France 2020 Stadium Home And Away Shorts White",
      "description": "France 2020 Stadium Home And Away Shorts White France 2020 Stadium Home And Away Shorts White France 2020 Stadium Home And Away Shorts",
      "price": 700,
      "gender": "male",
      "size": "xl",
      "category": "summer",
      "popular": "on sale"
    }
  ]
}
```
Start JSON Server
```
json-server --watch db.json
```
