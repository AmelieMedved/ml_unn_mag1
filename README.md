# Описание задачи

Набор данных 
[30000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs)

Набор данных состоит из 32833 экземпляров с 23 признаками.   

Поставлена задача классификации песен по 6 классам (жанры плейлистов).  

Описание признаков:  
- track_id - индентификатор песни (int)  
- track_name - название песни (str)  
- track_artist - исполнитель песни (str)  
- track_popularity - популярность песни  (0-100) (выше - популярнее) (int)  
- track_album_id - идентификатор альбома песни (int)  
- track_album_name - название альбома песни (str)  
- track_album_release_date - дата выхода альбома (str)
- playlist_name - название плейлиста (str)
- playlist_id - идентификатор плейлиста (int)
- playlist_genre - жанр плейлиста (str)
- playlist_subgenre - поджанр плейлиста (str)
- danceability (float) - насколько трек подходит для танцев (0.0 - 1.0) (выше - танцевальнее)
- energy (float) - энергичность трека (скорость, громкость, шум) (0.0 - 1.0) (выше - энергичнее)
- key (int) - музыкальный термин
- loudness (int) - средняя громкость трека в дБ  
- mode (int) - модальность (мажорная/минорная)
- spiechiness - наличие в треке слов (0.0 - 1.0) (выше - больше слов) (float)
- acousticness - мера уверенности в том, что трек является акустическим (0.0 - 1.0) (выше - увереннее) (float)
- instrumentalness - содержит ли трек вокал (0.0 - 1.0) (выше - инструментальнее (менее вокальный)) (float)
- liveness - наличие аудитории в записи (0.0 - 1.0) (выше - вероятнее) (float)
- valence - позитивность песни (0.0 - 1.0) (выше - позитивнее) (float)
- tempo - темп трека в ударах в минуту (BPM) (float)
- duration_ms - продолжительность песни (int)

# Ссылка на google disk с письменными заданиями: 

[ml_unn_mag1](https://drive.google.com/drive/folders/1wmKK0zwU4kixCfapu6YeAZKkTbGgJgFT?usp=drive_link)