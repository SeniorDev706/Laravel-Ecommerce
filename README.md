# Get discount on Digital Ocean
Sign-up with [Digital Ocean and get $10 discount](https://m.do.co/c/bce94237de96)!

# Laravel FREE E-Commerce Software

Features Provided
- Products
- Cart
- Checkout
- Categories
- Customers
- Orders
- Payment
- Couriers
- Employees

# Simplified DOCKER setup
### In your teminal, issue these commands

- RUN `docker-compose up -d --build`
- If your runtime is apple silicon, use `docker-compose -f docker-compose-m1.yml up -d --build` command
- RUN `docker exec -it app bash`
- Inside the container, run `composer install && chmod -R 777 storage/ bootstrap/cache/`
- Inside the container, run `php artisan migrate --seed`
- While inside the container, compile the assets with `npm i && npm run dev`
- While inside the container, link the images `php artisan storage:link`
- OPEN [http://localhost:8000](http://localhost:8000)


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FLaracommerce%2Flaracom.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FLaracommerce%2Flaracom?ref=badge_large)
