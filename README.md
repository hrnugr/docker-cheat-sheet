### DOCKER KOMUTLARI
1. Versiyon Sorgulama
    ```
    docker --version
    ```
2. Build Etme
   ```
   docker build . 
   ```
3. Image Sorgulama
   ```
   docker images 
   ```
4. Build sırasında tag verme
   ```
   docker build -t tag_name .
   ```
5. Image çalıştırmak
   ```
   docker run -it image_name
   ```
6. DockerHub'dan image indirmek
   ```
   docker pull postgres
   ```
7. Image silmek
    ```
   docker image rm image_id
    ```
8. Çalışan bir image silmek
    ```
   docker rmi -f image_id
    ```
   `f = force demek`
9. Kullanılmayan image silmek
   ```
   docker image prune -a
   ```
10. Docker Hub Login olmak için
     ```
    docker login
     ```
11. Docker Hub image push etmek
    ```
    docker push image_name:tag_name
    ```
12. Containerları listeleme
    ```
    docker container ls
    ```
13. container ayağa kaldırma
    ```
    docker run -p dıs_port:ic_port container_name
    ```
14. Container çalıştırma 
   ```    
   docker container start container_id
   ```
15. Container kapatma 
    ```
    docker container stop container_id
    ```
16. Container durdurma
    ```
    docker container pause continer_id
    ```
17. Durdurulmuş container devam ettirme
    ```
    docker container unpause container_id
    ```
18. Container Detayına ulaşma
    ```
    docker container inspect container_id
    ```
19. Durdurulmuş bütün containerları silme
    ```
    docker container prune
    ```
20. Container kapatma 
    ```
    docker container kill container_id
    ```
21. Container loguna ulaşma
    ```
    docker container logs container_id
    ```
22. Containerın satır sayısına göre sondan log bilgisini alma
    ```
    docker container logs --tail row_number container_id
    ```