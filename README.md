# Baires en miniatura

Buenos Aires en un planeta de bolsillo: una maqueta 3D interactiva de la Ciudad con 25 lugares, las líneas del Subte, el Río de la Plata y el Riachuelo.

**Verla en línea:** https://jedbweb-ai.github.io/baires-en-miniatura/

## Qué tiene

- 25 lugares modelados a mano en código, cada uno con ficha: foto, año, descripción, tres datos, un consejo y cómo llegar.
- Recorrido guiado, modo noche (se prenden las ventanas, el Obelisco y el faro del Barolo; la Floralis cierra sus pétalos) y capa del Subte (líneas A a H).
- Colectivos, taxis, gente caminando, veleros, un portacontenedores y el ferry al Uruguay.
- Español, inglés y portugués. Funciona en computadora y en celular.

## Cómo está hecha

Un solo archivo `index.html` con [Three.js](https://threejs.org/) 0.160 cargado desde jsDelivr; no necesita compilación. La ciudad real se proyecta sobre una esfera centrada en el Obelisco y las distancias se comprimen para que entren el centro, La Boca y Núñez en la misma cara. Las ubicaciones son aproximadas: los lugares se corren un poco para no pisarse.

Para verla en tu computadora, serví la carpeta con cualquier servidor estático (por ejemplo `npx serve`) y abrí la dirección que muestra.

## Créditos

Fotos de Wikimedia Commons, enlazadas desde su servidor:

| Lugar | Archivo | Autor | Licencia |
|---|---|---|---|
| Obelisco | [Obelisco de Buenos Aires at sunset.jpg](https://commons.wikimedia.org/wiki/File:Obelisco_de_Buenos_Aires_at_sunset.jpg) | Dpalma01 | CC BY-SA 4.0 |
| Teatro Colón | [Fachada del Teatro Colón en Buenos Aires, Argentina.jpg](https://commons.wikimedia.org/wiki/File:Fachada_del_Teatro_Col%C3%B3n_en_Buenos_Aires%2C_Argentina.jpg) | EEJCC | CC0 |
| Congreso de la Nación | [Congreso Nacional Buenos Aires.jpg](https://commons.wikimedia.org/wiki/File:Congreso_Nacional_Buenos_Aires.jpg) | Jacobo Tarrío | CC BY 2.0 |
| Casa Rosada | [Casa Rosada, Buenos Aires, Argentina.jpg](https://commons.wikimedia.org/wiki/File:Casa_Rosada%2C_Buenos_Aires%2C_Argentina.jpg) | Diego Delso | CC BY-SA 3.0 |
| Puente de la Mujer | [Buenos Aires Puente de la Mujer 1030985.jpg](https://commons.wikimedia.org/wiki/File:Buenos_Aires_Puente_de_la_Mujer_1030985.jpg) | Ermell | CC BY-SA 4.0 |
| La Bombonera | [La Bombonera 2.jpg](https://commons.wikimedia.org/wiki/File:La_Bombonera_2.jpg) | Matibro | CC BY-SA 4.0 |
| Caminito | [Buenos Aires - La Boca - Caminito - 200807i.jpg](https://commons.wikimedia.org/wiki/File:Buenos_Aires_-_La_Boca_-_Caminito_-_200807i.jpg) | Luis Argerich | CC BY 2.0 |
| Cementerio de la Recoleta | [Cementerio de la Recoleta.jpg](https://commons.wikimedia.org/wiki/File:Cementerio_de_la_Recoleta.jpg) | Sking | CC BY-SA 3.0 |
| Floralis Genérica | [Floralis Genérica (27547134408).jpg](https://commons.wikimedia.org/wiki/File:Floralis_Gen%C3%A9rica_(27547134408).jpg) | Deensel | CC BY 2.0 |
| Planetario Galileo Galilei | [Planetario Galileo Galilei-capturemind.jpg](https://commons.wikimedia.org/wiki/File:Planetario_Galileo_Galilei-capturemind.jpg) | Mariano Gilioli | CC BY-SA 4.0 |
| Cabildo | [Cabildo de Buenos Aires 2023.jpg](https://commons.wikimedia.org/wiki/File:Cabildo_de_Buenos_Aires_2023.jpg) | Fernando | CC BY-SA 4.0 |
| Catedral Metropolitana | [Catedral Metropolitana - Buenos Aires.jpg](https://commons.wikimedia.org/wiki/File:Catedral_Metropolitana_-_Buenos_Aires.jpg) | The Cosmonaut | CC BY-SA 2.5 ca |
| Palacio Barolo | [Palacio Barolo visto de frente.jpg](https://commons.wikimedia.org/wiki/File:Palacio_Barolo_visto_de_frente.jpg) | EEJCC | CC0 |
| Café Tortoni | [Café Tortoni 01.jpg](https://commons.wikimedia.org/wiki/File:Caf%C3%A9_Tortoni_01.jpg) | Bernard Gagnon | CC BY-SA 4.0 |
| Galerías Pacífico | [Buenos Aires - Galerías Pacífico.jpg](https://commons.wikimedia.org/wiki/File:Buenos_Aires_-_Galer%C3%ADas_Pac%C3%ADfico.jpg) | Rodrigo Galindez | CC BY 2.0 |
| Edificio Kavanagh | [Kavanagh building.jpg](https://commons.wikimedia.org/wiki/File:Kavanagh_building.jpg) | Marcos Prack | CC BY 2.0 |
| Torre Monumental | [HotelSheratonyTorreMonumentalBsAs-jul2016 (edit by C messier).jpg](https://commons.wikimedia.org/wiki/File:HotelSheratonyTorreMonumentalBsAs-jul2016_(edit_by_C_messier).jpg) | ezarate, edited by C messier | CC BY-SA 4.0 |
| Mercado de San Telmo | [Mercado de San Telmo 2025 02.jpg](https://commons.wikimedia.org/wiki/File:Mercado_de_San_Telmo_2025_02.jpg) | ProtoplasmaKid | CC BY-SA 4.0 |
| Usina del Arte | [Usina del Arte en La Noche de los Museos 2022.jpg](https://commons.wikimedia.org/wiki/File:Usina_del_Arte_en_La_Noche_de_los_Museos_2022.jpg) | Mauro Alfieri | CC BY-SA 2.5 |
| Palacio de Aguas Corrientes | [Palacio de Aguas Corrientes, Buenos Aires - 08.jpg](https://commons.wikimedia.org/wiki/File:Palacio_de_Aguas_Corrientes%2C_Buenos_Aires_-_08.jpg) | Sergio Moises Panei Pitrau | CC BY 4.0 |
| Biblioteca Nacional | [Biblioteca Nacional "Mariano Moreno".jpg](https://commons.wikimedia.org/wiki/File:Biblioteca_Nacional_%22Mariano_Moreno%22.jpg) | Gaboto2018 | CC BY-SA 4.0 |
| Facultad de Derecho | [Facultad de Derecho UBA (2014).jpg](https://commons.wikimedia.org/wiki/File:Facultad_de_Derecho_UBA_(2014).jpg) | Lars Curfs (Grashoofd) | CC BY-SA 3.0 nl |
| MALBA | [MALBA, Buenos Aires, Argentina.jpg](https://commons.wikimedia.org/wiki/File:MALBA%2C_Buenos_Aires%2C_Argentina.jpg) | OneEuropeanHeart | CC BY 3.0 |
| Jardín Japonés | [Buenos Aires - Jardín Japonés - 200806a.jpg](https://commons.wikimedia.org/wiki/File:Buenos_Aires_-_Jard%C3%ADn_Japon%C3%A9s_-_200806a.jpg) | Luis Argerich | CC BY 2.0 |
| Estadio Monumental | [Estadio Monumental (River Plate), Buenos Aires ARG.jpg](https://commons.wikimedia.org/wiki/File:Estadio_Monumental_(River_Plate)%2C_Buenos_Aires_ARG.jpg) | Stefano Vigorelli | CC BY-SA 4.0 |
