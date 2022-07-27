
# Covid-Tracker

A React.Js Website which shows the Covid stats of all the Countries in the World both in the form of numbers as well as graphical Representation.


## Demo

For demo visit the link
https://covidtracker15052000.herokuapp.com


## Deployment

To deploy this project run

```bash
  npm start
```


## Screenshots


![Screenshot 2022-07-27 at 6 23 38 PM](https://user-images.githubusercontent.com/64361223/181254800-8d6cb1c8-0f10-4893-890f-246de154ad18.png)
![Screenshot 2022-07-27 at 6 24 13 PM](https://user-images.githubusercontent.com/64361223/181254820-78297ead-876f-4bab-af4c-978096012e48.png)
![Screenshot 2022-07-27 at 6 24 03 PM](https://user-images.githubusercontent.com/64361223/181254839-da60bf62-21af-4ca5-99af-d8fe033fdc42.png)


## Contributing

Contributions are always welcome!



## Authors

- [@ritikjain](https://github.com/ritikjain77)


## API Reference

#### Get all items

```http
  GET /https://covid19.mathdro.id/api/countries
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /https://covid19.mathdro.id/countries/${country_id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |



