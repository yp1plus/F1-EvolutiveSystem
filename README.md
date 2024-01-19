# F1-EvolutiveSystem
Nesse projeto, é feito um sistema simples com três parâmetros (velocidade, eficiência e força) para um carro, o qual deve andar num circuito reto com alguns obstáculos no meio do caminho que fazem com que o carro perca velocidade. Se o carro chegar a uma velocidade zero, é o equivalente ao carro morrer o motor e ele não consegue mais continuar e perde a partida. 

Usamos um sistema evolutivo para descobrir as melhores combinações de parâmetros para chegar primeiro no fim do circuito considerando limites pré-determinados. Não necessariamente o carro tunado no máximo em todos os parâmetros é o melhor, porque a força do carro faz perder velocidade, por exemplo.

Como, no circuito, os obstáculos são gerados randomicamente, é preciso testar o carro em vários circuitos. 

## Resultados

Com 20 gerações, 100 indíviduos na população e 100 circuitos, percebe-se que em 2 gerações já encontramos o resultado ótimo.

<img width="731" alt="image" src="https://github.com/yp1plus/F1-EvolutiveSystem/assets/48031838/1516ccd2-945e-4314-8041-e16117990d4c">


Com 200 gerações, 10 indivíduos na população e 100 circuitos, percebe-se que levamos mais gerações para chegar ao resultado ótimo.

<img width="738" alt="Captura de Tela 2024-01-19 às 15 48 28" src="https://github.com/yp1plus/F1-EvolutiveSystem/assets/48031838/0e0ede01-3ac2-4be8-8eb6-07f19c885d73">

Os resultados podem variar com a execução, porque o conjunto de circuitos é randômico. 

Vídeo de Apresentação: https://drive.google.com/file/d/1ZzIccqcGBTUMeTjmkhHXoeHz1awDxHLg/view?usp=drive_link
