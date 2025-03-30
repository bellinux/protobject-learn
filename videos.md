---
title: Videos
nav_order: 2
---

# Videos to learn Protobject



{% raw %}

 <div class="playlist-container">
        <a href="https://example.com/" target="_blank">
            <img src="https://img.youtube.com/vi/SaZ4_BbYDUQ/maxresdefault.jpg" alt="Playlist Cover" class="playlist-image">
        </a>
        <div class="playlist-text">
            <h2><a href="https://example.com/" target="_blank">Titolo della Playlist</a></h2>
            <p>Breve descrizione della playlist con alcuni dettagli interessanti per incuriosire l'utente.</p>
        </div>
    </div>
    <style>
        .playlist-container {
            display: flex;
            align-items: center;
            border: 0px solid #ccc;
            border-radius: 15px;
            padding: 32px;
            background: #eee;
        }
        .playlist-image {
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            margin-right: 32px;
            border: 2px solid #111;
        }
        .playlist-text {
            flex: 1;
        }
        .playlist-text h2 a {
            text-decoration: none;
            color: inherit;
        }
        @media (max-width: 600px) {
            .playlist-container {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            .playlist-image {
                margin-right: 0;
                margin-bottom: 16px;
            }
        }
    </style>
{% endraw %}
