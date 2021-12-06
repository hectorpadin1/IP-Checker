# IP-Checker

O exercicio trata do deseño dun circuito lóxico capaz de validar os campos da cabeceira HTTP (excepto TOS e fragmentación que terán todos os bits a 0). O circuito recibirá una cabeceira xa descomposta en campos e comprobará se é válida ou non, no caso de que non o fose, o circuito diríanos que campo(s) recibiu de maneira incorrecta (ex: que a IP de destino non é a IP do dispositivo, Version IP non váida, ...etc). Só debe de recoñecer o Protocolo TCP/IP, se se usa outro protocolo dirá que o datagrama non é válido.

Campos da cabeceira HTTP.
∙ Formato Big Endian.
∙ Protocolo TCP/IP versión IPv4.
∙ No campo de tipo de servicio (TOS) poñeránse todos os bits de DS a 0, igual que nos de control de conxestión.
∙ Lonxitude total.
∙ Identificación do datagrama.
∙ Os campos de fragmentación estarán a 0.
∙ Time To Live (TTL) do datagrama.
∙ Sólo utilizaráse o protocolo TCP (0x06).
∙ Checksum.
∙ Direcciones IP (32 bits cada unha).
