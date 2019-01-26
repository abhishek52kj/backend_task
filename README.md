# Backend Task

### Dataset Content

You are provided with the Music Label Dataset on Kaggle. Description of the dataset is mentioned below.

#### ARTISTS
- id: artist's unique identifier
- real_name: artist's real name
- art_name: the career name the artist has chosen for him/herself
- role: the artist's main role (singer, guitarist, dancer, drummer... )
- year_of_birth: the artist's year of birth
- email: the artist's email. It's not necessarily unique as it can be also a common email
- country: where the artist comes from
- city: the city in which the artist lives. It can be in a different country from what stated above
- zip_code: the postal zip code

#### ALBUMS
- id: the album identifier
- artist_id: the artist identifier
- album_title: the title of the album
- genre: the genre of the album. An artist can release albums of different genres
- year_of_pub: the year the album was published
- num_of_tracks: how many tracks there are in the album (a small number can mean longer tracks)
- num_of_sales: how many sales the album has made in the first month after the release
- rolling_stone_critic: how magazine Rolling Stone has rated the album
- mtv_critic: how MTV has rated the album
- music_maniac_critic: how review site Music Maniac has rated the album

### Task

You are required to build REST APIs using Node.js and Express

#### Mandatory Features

- Users should be able to search on the basis of Album Title and Artist Name.
- Sorting (ex: Ratings) and filtering (ex: Genre) capabilities in the result.
