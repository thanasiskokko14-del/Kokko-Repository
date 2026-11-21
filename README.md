# Kokkonas-Repository
> dat=mtcars
> d=dist(scale(dat))
> hc=hclust(d, method = "ward.D2")
> plot(hc)
> cutree(hc, k=3)
>   Mazda RX4       Mazda RX4 Wag          Datsun 710      Hornet 4 Drive 
                  1                   1                   2                   2 
  Hornet Sportabout             Valiant          Duster 360           Merc 240D 
                  3                   2                   3                   2 
           Merc 230            Merc 280           Merc 280C          Merc 450SE 
                  2                   2                   2                   3 
         Merc 450SL         Merc 450SLC  Cadillac Fleetwood Lincoln Continental 
                  3                   3                   3                   3 
  Chrysler Imperial            Fiat 128         Honda Civic      Toyota Corolla 
                  3                   2                   2                   2 
      Toyota Corona    Dodge Challenger         AMC Javelin          Camaro Z28 
                  2                   3                   3                   3 
   Pontiac Firebird           Fiat X1-9       Porsche 914-2        Lotus Europa 
                  3                   2                   2                   2 
     Ford Pantera L        Ferrari Dino       Maserati Bora          Volvo 142E 
                  1                   1                   1                   2 
> cutree(hc, k=4)
          Mazda RX4       Mazda RX4 Wag          Datsun 710      Hornet 4 Drive 
                  1                   1                   2                   3 
  Hornet Sportabout             Valiant          Duster 360           Merc 240D 
                  4                   3                   4                   3 
           Merc 230            Merc 280           Merc 280C          Merc 450SE 
                  3                   3                   3                   4 
         Merc 450SL         Merc 450SLC  Cadillac Fleetwood Lincoln Continental 
                  4                   4                   4                   4 
  Chrysler Imperial            Fiat 128         Honda Civic      Toyota Corolla 
                  4                   2                   2                   2 
      Toyota Corona    Dodge Challenger         AMC Javelin          Camaro Z28 
                  3                   4                   4                   4 
   Pontiac Firebird           Fiat X1-9       Porsche 914-2        Lotus Europa 
                  4                   2                   2                   2 
     Ford Pantera L        Ferrari Dino       Maserati Bora          Volvo 142E 
                  1                   1                   1                   2 
> 
