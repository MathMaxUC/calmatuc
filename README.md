## MathMax Universidad Central
### Calculadora de Funciones

*Autores*: _Karen Pulido, Nicolle Murcia, Mateo Ruíz, Miguel Camargo, Jorge Pastran y Carlos Trujillo_

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/0wwaN3yGvxE/0.jpg)](https://www.youtube.com/watch?v=0wwaN3yGvxE)

Esta es una calculadora de funciones que le permitirá realizar operaciones de Mátematicas Básicas, Cálculo, Álgebra Linea,  Estadística y Cálculo Vectorial.

- Funciones
  Ingrese las funciones e formato Sympy
  Por ejemplo para ingresar
  ${𝑥^2}$
  escriba x**2.
  Chequee el botón de graficar si desea que aparezca la gráfica de la función
- Matrices
  Escriba las matrices en formato Sympy, por ejemplo la matriz de 2x3
  [[1,2,3],[4,5,6]].
- Puntos y Vectores
  Los puntos y vectores deben ser escritos como tuplas
  Por ejemplo el punto (2,3) o el vector (5,7).
  Estadística
  Ingrese las listas de datos numÃ©ricos separadas por coma
  Por ejemplo lista1 = 1,2,3,4,5.

Documentación API
<h2 class="groupheader">Documentación de las funciones</h2>
<a class="anchor" id="a0b41ab02d5d540c5e51b4b56e5d4cba0"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.ALOperacion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>operacion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>ALOperacion Función que recibe la operación a realizar Autor: Carlos Alberto Trujillo operación: Cadena con la operación a realizar. </p>

</div>
</div>
<a class="anchor" id="a6a8c14237769cad72071e3b1a3942177"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.CalcularRaices </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>CalcularRaices Función que recibe función expresada en Sympy y calcula las raices de la función. </p>
<p>Autor: Nicolle Murcia funcion: Función en formato Sympy </p>

</div>
</div>
<a class="anchor" id="a1666f25d1b3e0d6988d94477f631ed83"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.CalculoOperacion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>operacion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>CalculoOperacion Función que recibe la operación a realizar Autor: Carlos Alberto Trujillo operación: Cadena con la operación a realizar. </p>

</div>
</div>
<a class="anchor" id="ad4f791d7ab73ce183cf34f0569c44306"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.CVOperacion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>operacion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>CVOperacion Función que recibe la operación a realizar Autor: Carlos Alberto Trujillo operación: Cadena con la operación a realizar. </p>

</div>
</div>
<a class="anchor" id="a23f47999ae9876257265c54acad5212b"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.dep_or_ind </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>matriz</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<a class="anchor" id="adb32babd89ff5aeac5a796c3b4bcdfca"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.Derivar </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>orden</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>Derivar Función que recibe función expresada en Sympy y calcula su derivada en el orden establecido. </p>
<p>Autor: Miguel Ángel Camargo funcion: Función en formato Sympy orden: Número entero mayor a 0 que expresa el orden de la derivada. </p>

</div>
</div>
<a class="anchor" id="ad4480cdf330c407eaf4fbd1525284205"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.factorial </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>n</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>factorial Función que calcula el factoria de un número dado Autor: Miguel Ángel Camargo n: Valor para calcular el factorial </p>

</div>
</div>
<a class="anchor" id="a2e206358fb0a487d8ebd26a3ecb834df"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.GraficarFuncion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funciones</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>GraficarFuncion Función que recibe función expresada en Sympy y la grafica. </p>
<p>Autor: Karen Natalia Pulido funciones: Lista de funciones a graficar en formato Sympy style: Estilos de Grid </p>

</div>
</div>
<a class="anchor" id="ad19d1cc61df8e0d195effe8ef8285b57"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.GraficarTaylor </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>f</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>x0</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>n</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>Salto</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>x_lims</em> = <code>[-5</code>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>y_lims</em> = <code>[-5</code>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>npoints</em> = <code>800</code>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>GraficarTaylor Función que sirve para graficar la serie de Taylor de una función. </p>
<p>Autor: Miguel Ángel Camargo f: Función en formato Sympy x0: Punto inicial n: Número de Iteraciones Salto: Salto </p>

</div>
</div>
<a class="anchor" id="a88cc73139367e3d67538dc75141ebd7b"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.graficarVectores </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>lista</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<a class="anchor" id="a87915fd3833ae140f262e300cc0adaab"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.Integrar </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>a</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>b</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>Integrar Función que recibe función expresada en Sympy y calcula su integral con respecto a la variable establecida. </p>
<p>Autor: Mateo Ruíz Mendoza funcion: Función en formato Sympy variable: Variable con respecto a la cual se integra </p>

</div>
</div>
<a class="anchor" id="a6e387ae3f1c69a0bd0d08e1f37fd34ed"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractCalcularRaices </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractCalcularRaices Función que maneja el interact para la operación integrar. </p>
<p>Autor: Carlos Alberto Trujillo funcion: Función en formato Sympy graficar: True o False para graficar estilo: Lista de estilos disponibles para la gráfica </p>

</div>
</div>
<a class="anchor" id="ae80fa23c9aeb7ed6fbc79aef91935bd6"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractCoordPol </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>r</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractCoordPol Función que maneja el interact para graficar funciones en coordenadas polares. </p>
<p>Autor: Mateo Ruíz Mendoza r: Función en términos de t y r </p>

</div>
</div>
<a class="anchor" id="af1e933c64ade0db72a8248bbbe4072b9"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractCruzAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractCruzAL Función que maneja el interact para la operación producto cruz. </p>
<p>Autor: Miguel Ángel Camargo mat1: Expresión en formato Sympy de la matriz 1 mat2: Expresión en formato Sympy de la matriz 2 </p>

</div>
</div>
<a class="anchor" id="a2b82398d1efc3ad87d7586ae1b0f1b10"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractDerivarCalculo </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>orden</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractDerivarCalculo Función que maneja el interact para la operación derivar. </p>
<p>Autor: Carlos Alberto Trujillo funcion: Función en formato Sympy graficar: True o False para graficar orden: Valor entero de 1 a 10 con el orden de la derivada a calcular. estilo: Lista de estilos disponibles para la gráfica graficar: True o False para graficar orden: orden sobre el que se calcula la derivada estilo: Lista de estilos disponibles para la gráfica </p>

</div>
</div>
<a class="anchor" id="a171ea4fcdeeaf189415ac37d92ddfeed"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractDerivParc </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>df</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractDerivParc Función que maneja el interact para calcular las derivadas parciales de una función. </p>
<p>Autor: Miguel Ángel Camargo funcion: Funcion en terminos de x y y df: Operación a realizar </p>

</div>
</div>
<a class="anchor" id="ad2541116fa958b0368054eb59d03bd77"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractDeterminanteAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractDeterminanteAL Función que maneja el interact para la operación determinante. </p>
<p>Autor: Miguel Ángel Camargo mat: Expresión en formato Sympy de la Matriz </p>

</div>
</div>
<a class="anchor" id="a71fe23ed325d5ddcd3df9add346d4db7"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractDiagDisp </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>lista1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>lista2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractDiagDisp Función que maneja el interact para graficar el diagrama de dispersión. </p>
<p>Autor: Jorge Ali Pastran lista1: Lista de datos a graficar lista2: Lista de datos a graficar </p>

</div>
</div>
<a class="anchor" id="a0947f84e91b2ac7ec4b1eda61dcc1b34"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractDosPuntos </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>p1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>p2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractDosPuntos Función que maneja el interact para hallar la ecuación de la recta a partir de dos puntos. </p>
<p>Autor: Carlos Alberto Trujillo p1: Punto1 p2: Punto2 graficar: True o False para graficar estilo: Lista de estilos para la gráfica </p>

</div>
</div>
<a class="anchor" id="a779fb16e0c77ce847d6c6d0f17d8bb7e"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractEvalExp </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>valor</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractEvalExp Función que maneja el interact para evaluar una expresión Autor: Carlos Alberto Trujillo funcion: Función en formato Sympy variable: Variable a reemplazar valor: Valor a reemplazar. </p>

</div>
</div>
<a class="anchor" id="a914a4e3a70179a50e93ad93d61e411a0"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractExpan </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractExpan Función que maneja el interact para expandir un binomio. </p>
<p>Autor: Nicolle Murcia funcion: Función en formato Sympy </p>

</div>
</div>
<a class="anchor" id="a88594eb5626ee42abd4c9c00cb9fef7d"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractFactorial </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>n</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractFactorial Función que maneja el interact para hallar el factorial de un número. </p>
<p>Autor: Miguel Ángel Camargo n: Número entero al que se le calcula el factorial </p>

</div>
</div>
<a class="anchor" id="a8e11e6e6b38070727b74f8cc46d86c7f"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractGrafica3D </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractGrafica3D Función que maneja el interact para hallar la grafica 3D Autor: Karen Natalia Pulido funcion: Función en términos de x y y. </p>

</div>
</div>
<a class="anchor" id="ad00b14da340f3480766bfb0ba7fe2a69"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractIneq </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractIneq Función que maneja el interact para graficar inecuaciones Autor: Carlos Alberto Trujillo funcion: inecuacion en terminos de x graficar: True o False para graficar la función. </p>
<p>estilo: Llista de estilos para la gráfica. </p>

</div>
</div>
<a class="anchor" id="a39986e99aec3e22397a08e23d0de3198"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractInt2Def </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>inferior</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>superior</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>inferior_2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>superior_2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractInt2Def Función que maneja el interact para resolver integrales dobles definidas. </p>
<p>Autor: Mateo Ruíz Mendoza r: Función en términos de x y y variable1: variable 1 x variable2: variable 2 y inferior: limite inferior superior: limite superior inferior_2: limite inferior interna superior_2: limite superior interna </p>

</div>
</div>
<a class="anchor" id="ac6ff153301390a1334e10e9e3a21a940"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractInt2Ind </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractInt2Def Función que maneja el interact para resolver integrales dobles definidas. </p>
<p>Autor: Mateo Ruíz Mendoza r: Función en términos de x y y variable1: variable 1 x variable2: variable 2 y </p>

</div>
</div>
<a class="anchor" id="a47e3122e8b802048227bb8dce3a0427f"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractInt3Def </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>inferior</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>superior</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>inferior_2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>superior_2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_3</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>inferior_3</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>superior_3</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractInt3Def Función que maneja el interact para resolver integrales triples definidas. </p>
<p>Autor: Mateo Ruíz Mendoza r: Función en términos de x y y variable1: variable 1 x variable2: variable 2 y inferior: limite inferior superior: limite superior inferior_2: limite inferior interna superior_2: limite superior interna inferior_3: limite inferior interna superior_3: limite superior interna </p>

</div>
</div>
<a class="anchor" id="a407c1b4a3c09ed9594775045d05af51b"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractInt3Ind </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_2</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable_3</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractInt3Ind Función que maneja el interact para resolver integrales triples indefinidass. </p>
<p>Autor: Mateo Ruíz Mendoza r: Función en términos de x, y, z variable_1: variable 1 x variable_2: variable 2 y variable_3: variable 3 z </p>

</div>
</div>
<a class="anchor" id="ad635393de0df1bc8a1019cb4fc018355"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractIntegrarCalculo </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>limites</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractIntegrarCalculo Función que maneja el interact para la operación integrar. </p>
<p>Autor: Carlos Alberto Trujillo funcion: Función en formato Sympy graficar: True o False para graficar variable: x o y según se quiera integrar limites: Tupla que representa el valor inicial y final cuando la integral es definida. estilo: Lista de estilos disponibles para la gráfica </p>

</div>
</div>
<a class="anchor" id="ac088e16e814635c730cdbf9c99d29eb2"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractInversaAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractInversaAL Función que maneja el interact para la operación inversa. </p>
<p>Autor: Miguel Ángel Camargo mat: Expresión en formato Sympy de la matriz </p>

</div>
</div>
<a class="anchor" id="ac73d81fb0b2cc8bd3c6f72541ddb3282"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractLagrange </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>f</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>ecu</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<a class="anchor" id="a60c1c68ec8aded935389dc65026048c4"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractLims </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>variable</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>tiende</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractLims Función que maneja el interact para la operación límites. </p>
<p>Autor: Karen Natalia Pulido funcion: Función en formato Sympy variable: Variable sobre la cual se calcula el límite tiende: Valor al que tiende el límite </p>

</div>
</div>
<a class="anchor" id="a0f5626c3a39ef69511ada4d9f0d6627c"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractMaxMin </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractMaxMin Función que maneja el interact para la operación máximos y mínimos. </p>
<p>Autor: Karen Natalia Pulido Modificada: Carlos Alberto Trujillo funcion: Función en formato Sympy graficar: True o False para graficar estilo: Lista de estilos disponibles para la gráfica </p>

</div>
</div>
<a class="anchor" id="a47d36b700c8438f71360933936ad7127"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractMCD </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>num1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>num2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractMCD Función que maneja el interact para calcular el máximo común divisor. </p>
<p>Autor: Nicolle Murcia num1: Número 1 num2: Número 2 </p>

</div>
</div>
<a class="anchor" id="ad670cfcc702df973805b3449960a81aa"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.Interactmcm </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>num1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>num2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>Interactmcm Función que maneja el interact para calcular el mínimo común múltiplo. </p>
<p>Autor: Nicolle Murcia num1: Número 1 num2: Número 2 </p>

</div>
</div>
<a class="anchor" id="adb812a527785258f9581401963e902c3"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractMEAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>escalar</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractMEAL Función que maneja el interact para la operación multiplicar por un escalar. </p>
<p>Autor: Mateo Ruíz Mendoza mat: Expresión en formato Sympy de la matriz escalar: Valor escalar </p>

</div>
</div>
<a class="anchor" id="a878f90936db28d05c23cb26a19290f1d"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractMediana </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>lista1</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractMediana Función que maneja el interact para calcular la mediana. </p>
<p>Autor: Jorge Ali Pastran lista1: Lista de datos </p>

</div>
</div>
<a class="anchor" id="ac94baa694ca0d7531c3cd522db07c311"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractModa </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>lista1</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractModa Función que maneja el interact para calcular la moda. </p>
<p>Autor: Jorge Ali Pastran lista1: Lista de datos </p>

</div>
</div>
<a class="anchor" id="a4dbb92739e911c306e1ac4d9fb9f67b7"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractMultAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractMultAL Función que maneja el interact para la operación multiplicar Autor: Mateo Ruíz Mendoza mat1: Expresión en formato sympy de la matriz 1 mat2: Expresión en formato sympy de la matriz 2. </p>

</div>
</div>
<a class="anchor" id="ac9f2f320dd9daf6bf019aceee70165ce"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractPromedio </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>lista1</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractPromedio Función que maneja el interact para calcular el promedio. </p>
<p>Autor: Jorge Ali Pastran lista1: Lista de datos </p>

</div>
</div>
<a class="anchor" id="a03f383ed1465c21c5ad281b81ecd5d81"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractPtoPendiente </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>m</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>b</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>graficar</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>estilo</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractPtoPendiente Función que maneja el interact para la punto pendiente Autor: Miguel Ángel Camargo m: Pendiente b: Punto de Corte en Y graficar: True o False para graficar estilo: Lista de estilos para la gráfica. </p>

</div>
</div>
<a class="anchor" id="a884e8e058cced661d4afe8290e03fe58"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractRGJ </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat1</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractRGJ Función que maneja el interact para la reducción Gauss-Jordan Autor: Karen Natalia Pulido mat1: Expresión en formato Sympy de la matriz. </p>

</div>
</div>
<a class="anchor" id="a89420d17305d85e1ab68e53925636260"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractSumaAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat1</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat2</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractSumaAL Función que maneja el interact para la operación suma Autor: Karen Natalia Pulido mat1: Expresión en formato Sympy de la matriz1 mat2: Expresión en formato Sympy de la matriz2. </p>

</div>
</div>
<a class="anchor" id="a3c23006031e8fcb13c5e0a6ddb32a373"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractTaylor </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>funcion</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>x0</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>n</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>Salto</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractTaylor Función que maneja el interact para la Serie de Taylor Autor: Miguel Ángel Camargo funcion: Función en formato Sympy x0: Punto inicial n: Número de iteraciones Salto: Salto. </p>

</div>
</div>
<a class="anchor" id="a7c5751f233fb3200d1f70bb70427625a"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractTranspAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat1</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractTranspAL Función que maneja el interact para la operación transpuesta Autor: Miguel Angel Carvajal mat1: Expresión en formato Sympy de la matriz. </p>

</div>
</div>
<a class="anchor" id="a0440c3842ac2dbf9e9fc05d4608524b7"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.InteractVectAL </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>mat1</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>InteractVectAL Función que grafica vectores en 2D Autor: Karen Natalia Pulido mat1: Lista de vectores en texto. </p>

</div>
</div>
<a class="anchor" id="ab8c1c2c9c0b231f33d1073a4a6abe013"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.Latex2Sympy </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>text_in_latex</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>Latex2Sympy Función que recibe una expresión en LaTex y la devuelve en formato Sympy. </p>
<p>Autor: Carlos Alberto Trujillo text_in_latex: Cadena en formato LaTex </p>

</div>
</div>
<a class="anchor" id="a9796bb3f23f55ed20fe743d5d68d2852"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.ListaParesOrdenados </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>vector_raw_text</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>ListaParesOrdenados Funcion que convierte una cadena de texto en formato "(a,b),(c,d),...(x,y)" a una lista de pares ordenados Autor: Karen Natalia Pulido lista: texto con lista de pares ordenados. </p>

</div>
</div>
<a class="anchor" id="a1f5d96c6c4b9ca380895eb1d6e0308ec"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.MBOperacion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>operacion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>MBOperacion Función que recibe la operación a realizar Autor: Carlos Alberto Trujillo operación: Cadena con la operación a realizar. </p>

</div>
</div>
<a class="anchor" id="ad5d7cf4664e106dac09a2127270b316f"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.PresentarInterfaz </td>
          <td>(</td>
          <td class="paramname"></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>PresentarInterfaz Función que construye la interfaz de usuario y la presenta Autor: Carlos Alberto Trujillo. </p>

</div>
</div>
<a class="anchor" id="ac5fd67e3b9f6846d402e6bfeba7dcd45"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.reduccion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>matriz</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<a class="anchor" id="ab0709682c918fe68d9d04b21b22af35f"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.StatsOperacion </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>operacion</em></td><td>)</td>
          <td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>StatsOperacion Función que recibe la operación a realizar Autor: Carlos Alberto Trujillo operación: Cadena con la operación a realizar. </p>

</div>
</div>
<a class="anchor" id="a823babf1e55b4c6047187d5aa1b382ba"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">def calmatuc.calmatuc.taylor </td>
          <td>(</td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>function</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>x0</em>, </td>
        </tr>
        <tr>
          <td class="paramkey"></td>
          <td></td>
          <td class="paramtype">&#160;</td>
          <td class="paramname"><em>n</em>&#160;</td>
        </tr>
        <tr>
          <td></td>
          <td>)</td>
          <td></td><td></td>
        </tr>
      </table>
</div><div class="memdoc">

<p>taylor Función que recibe función expresada en Sympy y calcula la serie de Taylor. </p>
<p>Autor: Miguel Ángel Camargo funcion: Función en formato Sympy x0: Punto inicial n: Número iteraciones </p>

</div>
</div>
<h2 class="groupheader">Documentación de las variables</h2>
<a class="anchor" id="a14dbfc2d186e71f9ffaa262b60351cfd"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">calmatuc.calmatuc.__DEBUG__ = False</td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<a class="anchor" id="ad096d0c808649f3f2c84bf6326cdc695"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">tuple calmatuc.calmatuc.data = pkgutil.get_data(__name__, &quot;instructions.html&quot;)</td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<a class="anchor" id="a4673eddf36e12b6211db242a08e74387"></a>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">tuple calmatuc.calmatuc.instructions_html = None</td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">tuple calmatuc.calmatuc.tab_dict = dict(enumerate(<a class="el" href="namespacecalmatuc_1_1calmatuc.html#a71a6e5d6a86183b893ae123cbee4a864">tab_names</a>))</td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">list calmatuc.calmatuc.tab_names = ['Instrucciones', 'Mat Básicas', 'Cálculo', 'Algebra Lineal', 'Estadística', 'Cálculo Vectorial']</td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">tuple calmatuc.calmatuc.x = spp.Symbol('x')</td>
        </tr>
      </table>
</div><div class="memdoc">

</div>
</div>
<div class="memitem">
<div class="memproto">
      <table class="memname">
        <tr>
          <td class="memname">tuple calmatuc.calmatuc.y = spp.Symbol('y')</td>
        </tr>
      </table>
</div><div class="memdoc">
