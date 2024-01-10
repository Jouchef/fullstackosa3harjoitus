#Projektin aloitus

1. ```npm init```
2. Lisää scripti: ```"start": "node index.js",```
3. käynnistä ohjelma ```npm start```



#Nodemon
Käynnistää serverin uudestaan jos sen alaisuudessa oleva tiedosto muuttuu

1. Asenna kehityksen aikaiseksi: ```npm install --save-dev nodemon```
2. Lisää Scripti: ```"dev": "nodemon index.js",```
3. Käynnistä sovellus käyttäen: ```npm run dev``` jos haluat käyttää nodemonia

#Express

Asenna Express ```npm install express```

#REST Client -Plugin
1. Asenna REST client VSC:ssä
2. Luo juureen "requests" kansio
3. luo kuvaava .rest -päätteinen tiedosto
4. Tiedoston sisään ensin pyynnön tyyppi (delete, get, ...) ja sitten osoite
esim. ```GET http://localhost:3001/api/notes/1```

esim. 2 
```
POST http://localhost:3001/api/notes/
Content-Type: application/json

{
    "title": "Updated title",
    "content": "Updated content"
}
```

#Same origin policy
Jotta voi käyttää eri localhostin porteissa olevia asioita yhteen, niin:

1. Asennetaan backendiin cors
```npm install cors```

#Frontin tuotantoversio
Viten avulla tehdyistä sovelluksista saadaan tehtyä tuotantoversio komennolla ```npm run build```.
