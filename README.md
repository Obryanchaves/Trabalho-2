# Trabalho-2
**estimativa de máxima verossimilhança**
 Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 

 $L (\theta) = log (K_{n}(\eta)) - \frac{1}{2} log (|\Sigma|) - 1/(2\eta) (1 + n\eta) log(1 + c(\eta) \delta),$

 
 **com** $log (K_{n} (\eta)) = \frac{\eta}{2} log (\frac{c(\eta)}{\pi}) + log \Gamma (\frac{1+\eta\eta}{2\eta}) - log \Gamma (\frac{1}{2\eta}) , \delta = \boldsymbol {Y}$
