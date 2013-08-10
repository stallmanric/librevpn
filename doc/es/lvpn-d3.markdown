% LVPN-D3(1) Manual de LibreVPN | lvpn
% Nicolás Reynolds <fauno@endefensadelsl.org>
% 2013

# NOMBRE

Exportar los enlaces y nodos a un gráfico de fuerza con d3.js.


# SINOPSIS

lvpn d3 > data.json


# DESCRIPCION

Extrae los nodos y enlaces conocidos del log de tincd y los imprime en
JSON para D3.

El daemon tincd debe iniciarse con *--logfile*.
