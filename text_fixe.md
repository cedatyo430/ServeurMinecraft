monitor = peripheral.wrap("directional")  --direction ou se eitue votre monitor par rapport au computeur
monitor.clear()  --premet a ce que le monitor se vide avavt d'eentrer de nouveaux crararactères
monitor.setCursorPos(1,1)  --Ou commence le texte
monitor.setTextScale(5)  --Taille du texte sachant que 5 est la plus grosse police
monitor.write("Je suis un programme")  --écrit sur le monitor ce qu'il y a entre ("")
