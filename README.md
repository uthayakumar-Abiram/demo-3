**q1**
```
movies> db.moviedetails.insertMany([ {MovieTitle: "Jurassic Park ",Genre: "Adventure",Director: "Steven Spielberg ",ReleaseYear:1993},{MovieTitle: "Forrest Gump",Genre: "Drama ",Director: "Robert Zemeckies",ReleaseYear: 1994 },{MovieTitle: "Titanic",Genre: "Romance",Director: "James Cameron",ReleaseYear: 1997},{MovieTitle: "The Dark Knight",Genre: "Action",Director: "Christopher Nolan",ReleaseYear: 2008 },{MovieTitle:"Avatar",Genre:"Science Fiction",Director:"James Cameron",ReleaseYear:2009} ]);
{

```


```
  acknowledged: true,
  insertedIds: {
    '0': ObjectId("654c85deed69f9da93d348a0"),
    '1': ObjectId("654c85deed69f9da93d348a1"),
    '2': ObjectId("654c85deed69f9da93d348a2"),
    '3': ObjectId("654c85deed69f9da93d348a3"),
    '4': ObjectId("654c85deed69f9da93d348a4")
  }
}


**q2**
```
db.collection_name.find()
```
```
[
  {
    _id: ObjectId("654c9bed52148b1df7a6a8bd"),
    MovieTitle: 'Jurassic Park ',
    Genre: 'Adventure',
    Director: 'Steven Spielberg ',
    ReleaseYear: 1993
  },
  {
    _id: ObjectId("654c9bed52148b1df7a6a8be"),
    MovieTitle: 'Forrest Gump',
    Genre: 'Drama ',
    Director: 'Robert Zemeckies',
    ReleaseYear: 1994
  },
  {
    _id: ObjectId("654c9bed52148b1df7a6a8bf"),
    MovieTitle: 'Titanic',
    Genre: 'Romance',
    Director: 'James Cameron',
    ReleaseYear: 1997
  },
  {
    _id: ObjectId("654c9bed52148b1df7a6a8c0"),
    MovieTitle: 'The Dark Knight',
    Genre: 'Action',
    Director: 'Christopher Nolan',
    ReleaseYear: 2008
  },
  {
    _id: ObjectId("654c9bed52148b1df7a6a8c1"),
    MovieTitle: 'Avatar',
    Genre: 'Science Fiction',
    Director: 'James Cameron',
    ReleaseYear: 2009
  }
]
```

```
