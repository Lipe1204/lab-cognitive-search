# lab-cognitive-search
lab de IA de pesquisa cognitiva
Nesse lab experenciei o serviço de IA de pesquisa cognitiva do azure, assim como o passo a passo para criar esse serviço, criando o serviço de pesquisa do azure primeiro nas opções que tem disponiveis, depois uma conta de armazenamento para colocar os arquivos que assim vão servi para o enriquecimento da IA e testei o mecanismo de pesquisa que me deu esse resultado como exemplo: "{
  "@odata.context": "https://iadepesquisa.search.windows.net/indexes('azureblob-index1')/$metadata#docs(*)",
  "@odata.count": 9,
  "value": [
    {
      "@search.score": 1,
      "content": "\n\n\nReview: Fourth Coffee has super options for food on the go. There is a big variety of boxed lunches that can be ordered in bulk as conference meals or purchased individually. My Mondays are always busy, and I like being able to get my meals to-go with them. I usually call ahead instead of trying to order online. The only issue is they run out of the most popular menu items quickly, so be sure to call ahead! \nDate: October 8, 2018  \nLocation: Seattle, Washington\nimage1.png\n\nimage2.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctMy5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "\nReview: What I really like about this location is that there are also art classes offered for children! My family loves to come to Fourth Coffee on weekends for the live music and paint events! Some of the best events my kids have been to are at Fourth Coffee on a rainy Saturday. Hopefully they will bring back the Melodies & Collage Memories event, that was a great time for our whole family. \nDate: October 14, 2018\nLocation: Seattle, Washington  \nimage1.png\n\nimage2.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctNi5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "Review: I heard that Fourth Coffee had the best seasonal donuts, so I ordered a dozen for my team for an event. Everyone loved them, I’ll definitely order again! \nDate: October 25, 2018\nLocation: Seattle, Washington \n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctOS5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "\n\nReview: I love the coffee drinks here, but my favorite part is the local art they sell. There are many kinds of paintings and watercolors they showcase each week. I love checking out the new prints that they have and buying cards for friends. Also did I mention that the wi-fi is excellent? \nDate: September 3, 2018\nLocation: Seattle, Washington  \nimage1.png\n\nimage2.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctMS5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "\nReview: I often make Fourth Coffee my meeting spot for my client meetings weekday mornings. I own a small business and the folks who work at Fourth Coffee are always very friendly. It leaves a good impression on my clients. There are also plenty of drink selections, good wi-fi, and seating. Some of my favorite coffees are the lavender honey latte and, in the winter, the apple-chai latte. There are delicious baked goods offered as well. \nDate: October 21, 2018\nLocation: Chicago, Illinois \n\nimage1.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctNS5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "\n\nReview: The coffee tastings every Wednesday afternoon are so fun. Each month there is a new drink theme. You do need to book a spot in advance to attend. It is very worth it! I also love their local music. Fourth Coffee brings in rising artists every weekend. I like to head over there mid-afternoon on weekdays when it’s not too busy and get a slice of pie or their seasonal baked goods.  \nDate: August 13, 2018\nLocation: Chicago, Illinois  \n\nimage1.png\n\nimage2.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctNC5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "\n\n\nReview: My favorite part about going to Fourth Coffee is the atmosphere. I love the warm lights and plants. It’s a great place to go get a cup of coffee while working on your next business idea or with friends at school. It’s also right next to the University hub, which makes it so easy to access for students. It just gets so busy on the weekends! I wish it was not so crowded. Since they started offering amazing breakfast sandwiches, I wouldn’t try to go get a coffee Saturday morning.  \nDate: September 1, 2018\nLocation: Los Angeles, California \nimage1.png\n\nimage2.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctMi5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "\n\nReview: The great thing about this Fourth Coffee location is that there’s an event space for talks. I went to one the other day that focused on giving students a place to present their latest research. The event room is also perfect for larger groups or clubs to meet up. Just be aware that weekends it can get really crowded, which I don’t like. \nDate: October 11, 2018\nLocation: Los Angeles, California\t\nimage1.png\n\nimage2.png\n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctNy5kb2N40"
    },
    {
      "@search.score": 1,
      "content": "Review: Today I was truly disappointed with how long I had to wait for the pastries I ordered ahead of time. When I got my box, some of the pastries seemed stale. Terrible experience!  \nDate: October 23, 2018\nLocation: Chicago, Illinois \n\n",
      "metadata_storage_path": "aHR0cHM6Ly9hcm1hemVuYW1lbnRvaWFwZXNxdWlzYS5ibG9iLmNvcmUud2luZG93cy5uZXQvY29mZmVlcmV2aWV3cy9yZXZpZXctOC5kb2N40"
    }"
    Durante o lab, percebi que o AI Search é ótimo para lidar com grandes volumes de dados e que a integração com o Azure facilita muito, mas exige atenção na configuração inicial. Também notei que dá para adaptar os skillsets para quase qualquer necessidade, o que abre muitas possibilidades. Acho que as aplicações que mais se beneficiam são análise de feedback de clientes, como o caso das avaliações de café, onde dá para identificar rápido o que as pessoas gostam ou não, e busca em e-commerce, para combinar descrições, avaliações e imagens numa experiência fluida. No fim, aprendi a mexer com skillsets e indexadores, gerenciar recursos no Azure e criar consultas úteis, e vi como o AI Search pode ser uma solução poderosa para transformar dados em algo prático e valioso.
