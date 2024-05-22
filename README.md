# This is a page of movies using **supabase** like database in the cloud.

## Requirements
- Have a count in [supabase](https://supabase.com/).
- You must insert this code in sql of supabase.
```
create table Movies (
  title text,
  year int8,
  director text,
  actors json,
  review text,
  img text,
  trailer text
);

create table Users (
  username text,
  password text
);
```

- You need insert in the folder `./data` a file with the name `keys.js`. Here you put the next code:
```
export const keys = {
  SUPABASE_KEY: "<YOUR KEY>",
  SUPABASE_URL_MOVIES: "<YOUR URL MOVIES>",
  SUPABASE_URL_USERS: "<YOUR URL USERS>"
}
```

- Your keys must to be `service_rol(secret)`.

> [!NOTE]
> Send your pull request for help me.