# Theme 1: Video Games and their Developers
video_game_developers = {
 "Halo": "343 Industries",
 "The Legend of Zelda": "Nintendo",
 "God of War": "Santa Monica Studio",
 "Minecraft": "Mojang",
 "Portal": "Valve",
}
# Theme 2: Top Songs and their Performing Artists
top_songs_artists = {
 "Bohemian Rhapsody": "Queen",
 "Hey Jude": "The Beatles",
 "Thriller": "Michael Jackson",
 "Like a Rolling Stone": "Bob Dylan",
 "Smells Like Teen Spirit": "Nirvana",
 "Hotel California": "Eagles",
 "Stairway to Heaven": "Led Zeppelin",
 "Imagine": "John Lennon",
 "What's Going On": "Marvin Gaye",
 "Let It Be": "The Beatles",
}
# Output for Video Games and their Developers
print("The video game The Legend of Zelda was developed by " + video_game_developers["The Legend of
Zelda"])
print("The current games in this dictionary are " + str(list(video_game_developers.keys())))
print("The current developers in this dictionary are " + str(list(video_game_developers.values())))
# Output for Top Songs and their Performing Artists
print("The song Bohemian Rhapsody was performed by " + top_songs_artists["Bohemian Rhapsody"])
print("The current songs in this dictionary are " + str(list(top_songs_artists.keys())))
print("The current artists in this dictionary are " + str(list(top_songs_artists.values())))
# Converting Video Games and their Developers dictionary into a list of tuples
video_game_developers_list = list(video_game_developers.items())
# Output remains identical, but using a list of tuples as the data type
for game, developer in video_game_developers_list:
 print(f"The video game {game} was developed by {developer}")
print("The current games in this list are " + str([game for game, _ in video_game_developers_list]))
print("The current developers in this list are " + str([developer for _, developer in
video_game_developers_list]))
