# Actividad1Calculadora

Aclaratoria :  ya que se esta usando el respaldo de Github como copia de seguridad de de los repositorios , es ideal programar que se actualice automaticamente , no obstante estaria mal , ir actualizando cada que realices un cambio importante.

Para sincronizar solo deberemos ir al control de codigo fuento , seleccionar el signo mas (* ) para que guarde los cambios , luego la palomita o chulo , una vez echo esto , dejamos un comentario para ir identificando que cambio y avances hemos realizado , y para finalizar en los tre spuntos , sinclonizar y push, con esto se sincronizan todos los cambios aplicados  al repositorio.


1. Se emplea GitHub con el animo de guardar y documentar el proceso.

2. Primer paso es crear por medio de la terminal con el comando " mkdir " Una carpeta la cual se llamo calculadora .

3. Una vez creada se selecciona por medio de terminal con el comando " cd " y nombre de la carpeta , en este caso Calculadora.

4. Por medio de terminal aplicamos el comando " dotnet new MVC " , este comando se usa en visual estudio code para crear todo el proyecto y que quede bien estructurado , si deseas validar que este vien , puedes aplicar dotnote run , y para que se actualice en linea el servidor dotnote watch run ".

5. Una vez creado todo , aplicamos " dotnote build " ,  para construir el proyecto.

6. Nos dirigimos a la carpeta controllers y creamos un nuevo archivo que sera la calculadora el cual llamare " Calculadora Censa " , pasare el codigo del home controller al nuevo archivo.

7. Aplicamos el siguiente codigo :

"// using System;
using System.Collections.Generic;
using System.Diagnostics;
using System.Linq;
using System.Threading.Tasks;
using Microsoft.AspNetCore.Mvc;
using Microsoft.Extensions.Logging;
using Calculadora.Models;

namespace Calculadora.Controllers
{
    public class CalculadoraController : Controller
    {
        private readonly ILogger<HomeController> _logger;

        public CalculadoraController(ILogger<HomeController> logger)
        {
            _logger = logger;
        }

        public IActionResult Index()
        {
            return View();
        }
    }
}

8. CReamos en la carpeta modelos un nuevo archivo con los metodos get y set

namespace Actividad1CAlculadora.Models
{
    public class CalculadoraViewModel
    {
        public string RequestId { get; set; } */ Metodo get y set es para la calculadora */

        
    }
}


9. 




