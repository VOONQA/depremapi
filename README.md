### Deprem API Container Kurulumu

1. Önce projeyi klonlayın ve depremapi klasörüne gidin: git clone https://github.com/kullaniciadin/depremapi.git

2. Docker ile container'ı başlatın: docker-compose up -d --build


## API Endpointleri

- http://localhost:3000/api/earthquakes (Kandilli'den son depremler)
- http://localhost:3000/api/earthquakes/latest?limit=40 (son 40 deprem)
- http://localhost:3000/api/earthquakes/magnitude (Büyüklüğü 4'ün üzerindeki depremler)   
