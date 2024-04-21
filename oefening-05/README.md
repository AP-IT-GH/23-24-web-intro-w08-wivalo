# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel. : c0bf7eba73e64547b7ba663c988fdb00
4. Voer het verzoek uit en bekijk de respons.

GET https://newsapi.org/v2/top-headlines?country=be&apiKey=c0bf7eba73e64547b7ba663c988fdb00

{
    "status": "ok",
    "totalResults": 33,
    "articles": [
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "franceinfo",
            "title": "Guerre en Ukraine : cinq questions sur le vote attendu du Congrès américain sur l'aide à Kiev - franceinfo",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMijgFodHRwczovL3d3dy5mcmFuY2V0dmluZm8uZnIvbW9uZGUvdXNhL2d1ZXJyZS1lbi11a3JhaW5lLWNpbnEtcXVlc3Rpb25zLXN1ci1sZS12b3RlLWF0dGVuZHUtZHUtY29uZ3Jlcy1hbWVyaWNhaW4tc3VyLWwtYWlkZS1hLWtpZXZfNjQ5NzkwNi5odG1s0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:02:50Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "L'Équipe",
            "title": "Nos favoris pour Liège-Bastogne-Liège : quels coureurs pour arbitrer le duel Pogacar-Van der Poel ? - L'Équipe",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMimQFodHRwczovL3d3dy5sZXF1aXBlLmZyL0N5Y2xpc21lLXN1ci1yb3V0ZS9BcnRpY2xlL05vcy1mYXZvcmlzLXBvdXItbGllZ2UtYmFzdG9nbmUtbGllZ2UtcXVlbHMtY291cmV1cnMtcG91ci1hcmJpdHJlci1sZS1kdWVsLXBvZ2FjYXItdmFuLWRlci1wb2VsLzE0NjIyNzjSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:00:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "7sur7",
            "title": "L'Ukraine lance une vaste attaque de drones en Russie: deux morts, un dépôt pétrolier touché - 7sur7",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMifmh0dHBzOi8vd3d3LjdzdXI3LmJlL21vbmRlL2x1a3JhaW5lLWxhbmNlLXVuZS12YXN0ZS1hdHRhcXVlLWRlLWRyb25lcy1lbi1ydXNzaWUtZGV1eC1tb3J0cy11bi1kZXBvdC1wZXRyb2xpZXItdG91Y2hlfmE2MTg3NjU2L9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T11:04:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "RTL info",
            "title": "\"C'est juste inouï\": les Disques d'Or du Télévie récoltent 300.000 euros - RTL info",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMihQFodHRwczovL3d3dy5ydGwuYmUvYWN0dS9tYWdhemluZS90ZWxldmllL2Nlc3QtanVzdGUtaW5vdWktbGVzLWRpc3F1ZXMtZG9yLWR1LXRlbGV2aWUtcmVjb2x0ZW50LTMwMDAwMC1ldXJvcy8yMDI0LTA0LTIwL2FydGljbGUvNjYwNjM00gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T11:02:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Walfoot.be",
            "title": "Presque une grande première au Standard pour le déplacement à Westerlo ? Voici la composition probable des Rouches - Walfoot.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMimAFodHRwczovL3d3dy53YWxmb290LmJlL25ld3MvMjAyNC0wNC0yMC9wcmVzcXVlLXVuZS1ncmFuZGUtcHJlbWllcmUtYXUtc3RhbmRhcmQtcG91ci1sZS1kZXBsYWNlbWVudC1hLXdlc3RlcmxvLS12b2ljaS1sYS1jb21wb3NpdGlvbi1wcm9iYWJsZS1kZXMtcm91Y2hlc9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T11:00:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Developpez.com",
            "title": "Vos ondes cérébrales seraient à vendre : pour la première fois, une loi du Colorado étend le droit à la vie privée aux données neuronales, de plus en plus convoitées par les entreprises technologiques - Developpez.com",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi7gFodHRwczovL2Ryb2l0LmRldmVsb3BwZXouY29tL2FjdHUvMzU2NzEyL1Zvcy1vbmRlcy1jZXJlYnJhbGVzLXNlcmFpZW50LWEtdmVuZHJlLXBvdXItbGEtcHJlbWllcmUtZm9pcy11bmUtbG9pLWR1LUNvbG9yYWRvLWV0ZW5kLWxlLWRyb2l0LWEtbGEtdmllLXByaXZlZS1hdXgtZG9ubmVlcy1uZXVyb25hbGVzLWRlLXBsdXMtZW4tcGx1cy1jb252b2l0ZWVzLXBhci1sZXMtZW50cmVwcmlzZXMtdGVjaG5vbG9naXF1ZXMv0gHyAWh0dHBzOi8vZHJvaXQuZGV2ZWxvcHBlei5jb20vYWN0dS8zNTY3MTIvVm9zLW9uZGVzLWNlcmVicmFsZXMtc2VyYWllbnQtYS12ZW5kcmUtcG91ci1sYS1wcmVtaWVyZS1mb2lzLXVuZS1sb2ktZHUtQ29sb3JhZG8tZXRlbmQtbGUtZHJvaXQtYS1sYS12aWUtcHJpdmVlLWF1eC1kb25uZWVzLW5ldXJvbmFsZXMtZGUtcGx1cy1lbi1wbHVzLWNvbnZvaXRlZXMtcGFyLWxlcy1lbnRyZXByaXNlcy10ZWNobm9sb2dpcXVlcy8_YW1w?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T10:55:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "RTL info",
            "title": "Les chaussures du petit Emile retrouvées près des ossements: ce détail intrigue les enquêteurs - RTL info",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMilgFodHRwczovL3d3dy5ydGwuYmUvYWN0dS9iZWxnaXF1ZS9mYWl0cy1kaXZlcnMvbGVzLWNoYXVzc3VyZXMtZHUtcGV0aXQtZW1pbGUtcmV0cm91dmVlcy1wcmVzLWRlcy1vc3NlbWVudHMtY2UtZGV0YWlsLWludHJpZ3VlLzIwMjQtMDQtMjAvYXJ0aWNsZS82NjA2MjLSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T10:27:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lalibre.be",
            "title": "\"L'hypothèse d'une victoire absolue de Poutine devient vraisemblable. Les troupes russes pourraient être à Kiev... - lalibre.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi4QFodHRwczovL3d3dy5sYWxpYnJlLmJlL2ludGVybmF0aW9uYWwvZXVyb3BlL2d1ZXJyZS11a3JhaW5lLXJ1c3NpZS8yMDI0LzA0LzIwL2xoeXBvdGhlc2UtZHVuZS12aWN0b2lyZS1hYnNvbHVlLWRlLXBvdXRpbmUtZGV2aWVudC12cmFpc2VtYmxhYmxlLWxlcy10cm91cGVzLXJ1c3Nlcy1wb3VycmFpZW50LWV0cmUtYS1raWV2LWVuLXNlcHRlbWJyZS1LSkhJVEdIWU5OSDNOSFk1QlFNTUdCNUJaTS_SAfABaHR0cHM6Ly93d3cubGFsaWJyZS5iZS9pbnRlcm5hdGlvbmFsL2V1cm9wZS9ndWVycmUtdWtyYWluZS1ydXNzaWUvMjAyNC8wNC8yMC9saHlwb3RoZXNlLWR1bmUtdmljdG9pcmUtYWJzb2x1ZS1kZS1wb3V0aW5lLWRldmllbnQtdnJhaXNlbWJsYWJsZS1sZXMtdHJvdXBlcy1ydXNzZXMtcG91cnJhaWVudC1ldHJlLWEta2lldi1lbi1zZXB0ZW1icmUtS0pISVRHSFlOTkgzTkhZNUJRTU1HQjVCWk0vP291dHB1dFR5cGU9YW1w?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T09:45:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Autohebdo",
            "title": "Rallye de Croatie - Le résumé du samedi matin - Autohebdo",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMikwFodHRwczovL3d3dy5hdXRvaGViZG8uZnIvYWN0dWFsaXRlcy9yYWxseWUvd3JjL3RoaWVycnktbmV1dmlsbGUtZW4tdGV0ZS1kZS1qdXN0ZXNzZS1kZXZhbnQtZWxmeW4tZXZhbnMtZXQtc2ViYXN0aWVuLW9naWVyLWF1LXJhbGx5ZS1kZS1jcm9hdGllLmh0bWzSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T09:43:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Sudinfo.be",
            "title": "« C'est du délire » : les internautes scandalisés par l'élimination de ce couple aux portes de la finale de « Danse avec les stars » - Sudinfo.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMif2h0dHBzOi8vd3d3LnN1ZGluZm8uYmUvaWQ4MjU5MzIvYXJ0aWNsZS8yMDI0LTA0LTIwL2Nlc3QtZHUtZGVsaXJlLWxlcy1pbnRlcm5hdXRlcy1zY2FuZGFsaXNlcy1wYXItbGVsaW1pbmF0aW9uLWRlLWNlLWNvdXBsZS1hdXjSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T08:57:03Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "DH Les Sports +",
            "title": "Début des actions syndicales chez Bpost: pas de courrier ni de journaux distribués ce lundi - DH Les Sports +",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMipAFodHRwczovL3d3dy5kaG5ldC5iZS9hY3R1L2JlbGdpcXVlLzIwMjQvMDQvMjAvZGVidXQtZGVzLWFjdGlvbnMtc3luZGljYWxlcy1jaGV6LWJwb3N0LXBhcy1kZS1jb3Vycmllci1uaS1kZS1qb3VybmF1eC1kaXN0cmlidWVzLWNlLWx1bmRpLVM1R0M3VUpVVkJHSVJNUEEzWFhSNEQ3VzdZL9IBswFodHRwczovL3d3dy5kaG5ldC5iZS9hY3R1L2JlbGdpcXVlLzIwMjQvMDQvMjAvZGVidXQtZGVzLWFjdGlvbnMtc3luZGljYWxlcy1jaGV6LWJwb3N0LXBhcy1kZS1jb3Vycmllci1uaS1kZS1qb3VybmF1eC1kaXN0cmlidWVzLWNlLWx1bmRpLVM1R0M3VUpVVkJHSVJNUEEzWFhSNEQ3VzdZLz9vdXRwdXRUeXBlPWFtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T08:37:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Le Soir",
            "title": "-2 degrés en Belgique, retrouvez les prévisions météo par région - Le Soir",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMibmh0dHBzOi8vd3d3Lmxlc29pci5iZS81ODIzODYvYXJ0aWNsZS8yMDI0LTA0LTIwLzItZGVncmVzLWVuLWJlbGdpcXVlLXJldHJvdXZlei1sZXMtcHJldmlzaW9ucy1tZXRlby1wYXItcmVnaW9u0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T08:36:02Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Nextgen-Auto.com",
            "title": "Verstappen signe la pole en Chine, déception pour Ferrari - Nextgen-Auto.com",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMidWh0dHBzOi8vbW90b3JzcG9ydC5uZXh0Z2VuLWF1dG8uY29tL2ZyL2Zvcm11bGUtMS92ZXJzdGFwcGVuLXNpZ25lLWxhLXBvbGUtZW4tY2hpbmUtZGVjZXB0aW9uLXBvdXItZmVycmFyaSwxOTAyODguaHRtbNIBbmh0dHBzOi8vYW1wLm5leHRnZW4tYXV0by5jb20vZnIvZm9ybXVsZS0xL3ZlcnN0YXBwZW4tc2lnbmUtbGEtcG9sZS1lbi1jaGluZS1kZWNlcHRpb24tcG91ci1mZXJyYXJpLDE5MDI4OC5odG1s?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T08:14:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lavenir.net",
            "title": "Examens et dépistages : et s’il n’était pas toujours bon de prévenir plutôt que guérir ? - lavenir.net",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMimwFodHRwczovL3d3dy5sYXZlbmlyLm5ldC9saWZlc3R5bGUvMjAyNC8wNC8yMC9leGFtZW5zLWV0LWRlcGlzdGFnZXMtZXQtc2lsLW5ldGFpdC1wYXMtdG91am91cnMtYm9uLWRlLXByZXZlbmlyLXBsdXRvdC1xdWUtZ3VlcmlyLU0yTVVKR1lTU1ZEUVRCREFPVE1KQUdMUkZFL9IBqgFodHRwczovL3d3dy5sYXZlbmlyLm5ldC9saWZlc3R5bGUvMjAyNC8wNC8yMC9leGFtZW5zLWV0LWRlcGlzdGFnZXMtZXQtc2lsLW5ldGFpdC1wYXMtdG91am91cnMtYm9uLWRlLXByZXZlbmlyLXBsdXRvdC1xdWUtZ3VlcmlyLU0yTVVKR1lTU1ZEUVRCREFPVE1KQUdMUkZFLz9vdXRwdXRUeXBlPWFtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T07:00:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Le Soir",
            "title": "L'homme qui s'est immolé devant le tribunal où comparait Donald Trump est décédé - Le Soir",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMifmh0dHBzOi8vd3d3Lmxlc29pci5iZS81ODIzNzYvYXJ0aWNsZS8yMDI0LTA0LTIwL2xob21tZS1xdWktc2VzdC1pbW1vbGUtZGV2YW50LWxlLXRyaWJ1bmFsLW91LWNvbXBhcmFpdC1kb25hbGQtdHJ1bXAtZXN0LWRlY2VkZdIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T06:51:17Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "20 Minutes",
            "title": "Taylor Swift ou l'art de faire de la tristesse un carton planétaire - 20 Minutes",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMib2h0dHBzOi8vd3d3LjIwbWludXRlcy5mci9hcnRzLXN0YXJzL2N1bHR1cmUvNDA4NzM1Ni0yMDI0MDQyMC10YXlsb3Itc3dpZnQtYXJ0LWZhaXJlLXRyaXN0ZXNzZS1jYXJ0b24tcGxhbmV0YWlyZdIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T06:32:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "DH Les Sports +",
            "title": "Attentat à Bruxelles: un magistrat avait commis \"une erreur grossière et inacceptable\", pas de sanction disciplinaire... - DH Les Sports +",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMitwFodHRwczovL3d3dy5kaG5ldC5iZS9hY3R1L2JlbGdpcXVlLzIwMjQvMDQvMjAvYXR0ZW50YXQtYS1icnV4ZWxsZXMtdW4tbWFnaXN0cmF0LWF2YWl0LWNvbW1pcy1lcnJldXItZ3Jvc3NpZXJlLWV0LWluYWNjZXB0YWJsZS1wYXMtZGUtc2FuY3Rpb24tZGlzY2lwbGluYWlyZS1GS0hSQllXTTRCQkJIQzdQUUtDUUZPTk1OSS_SAcYBaHR0cHM6Ly93d3cuZGhuZXQuYmUvYWN0dS9iZWxnaXF1ZS8yMDI0LzA0LzIwL2F0dGVudGF0LWEtYnJ1eGVsbGVzLXVuLW1hZ2lzdHJhdC1hdmFpdC1jb21taXMtZXJyZXVyLWdyb3NzaWVyZS1ldC1pbmFjY2VwdGFibGUtcGFzLWRlLXNhbmN0aW9uLWRpc2NpcGxpbmFpcmUtRktIUkJZV000QkJCSEM3UFFLQ1FGT05NTkkvP291dHB1dFR5cGU9YW1w?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T05:41:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lalibre.be",
            "title": "François De Smet: \"Paul Magnette a montré que le choix du PTB était en fait un vote utile: c’est irresponsable... - lalibre.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi1AFodHRwczovL3d3dy5sYWxpYnJlLmJlL2JlbGdpcXVlL2VsZWN0aW9ucy1iZWxnZXMvMjAyNC8wNC8yMC9mcmFuY29pcy1kZS1zbWV0LXBhdWwtbWFnbmV0dGUtYS1tb250cmUtcXVlLWxlLWNob2l4LWR1LXB0Yi1ldGFpdC1lbi1mYWl0LXVuLXZvdGUtdXRpbGUtY2VzdC1pcnJlc3BvbnNhYmxlLWV0LWNhdGFzdHJvcGhpcXVlLUFNSlBZS1NNTlpCTFRISEFCWjZHTTdCMlNVL9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T05:12:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Sudinfo.be",
            "title": "Le tant attendu «halving» a eu lieu cette nuit, les créations de bitcoins vont ralentir - Sudinfo.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMifGh0dHBzOi8vd3d3LnN1ZGluZm8uYmUvaWQ4MjU4NzMvYXJ0aWNsZS8yMDI0LTA0LTIwL2xlLXRhbnQtYXR0ZW5kdS1oYWx2aW5nLWV1LWxpZXUtY2V0dGUtbnVpdC1sZXMtY3JlYXRpb25zLWRlLWJpdGNvaW5zLXZvbnTSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T04:48:24Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "RTL info",
            "title": "Les tests de Mathieu : le pionnier de la caméra de surveillance sans fil baisse ses prix, quelles sont les concessions des nouvelles Arlo? - RTL info",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMikAFodHRwczovL3d3dy5ydGwuYmUvYWN0dS9tYWdhemluZS9oaS10ZWNoL2xlcy10ZXN0cy1kZS1tYXRoaWV1LWxlLXBpb25uaWVyLWRlLWxhLWNhbWVyYS1kZS1zdXJ2ZWlsbGFuY2Utc2Fucy1maWwtYmFpc3NlLzIwMjQtMDQtMjAvYXJ0aWNsZS82NjAzOTLSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T04:36:00Z",
            "content": null
        }
    ]
}