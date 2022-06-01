
Na aba configuração de impressão, no item Outro adicione um G-code substitutions:  

No item ACHAR coloque: (?:G1)\s(?:E-\d*.?\d+)\s(?:F?\d.?\d+)       
No item SUBSTITUIR POR coloque: ;$0  

Pronto o Bug da troca de cor estará resolvido!  


Obs: Não esquecer de habilitar o checkbox "Expressão Regular"
