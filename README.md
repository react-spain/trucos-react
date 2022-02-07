# Trucos React

# Funciones Flecha
```
const verificarSesion = (sesion) => {
  if(sesion === true){
       return JSX;
  } else {
    return <h1>No has iniciado</h1>
  }
 }
 ```
 
 # Condicionales
```
 const JSX = <>
              { sesion === true 
              ? <>
                  <h1 className='demo' style={{color: color}}>Hola {nombre}!</h1> 
                  <p>Hola texto</p>
                  { pais && <p>Tu eres de : {pais}</p>}
              </>
              : <p> no has iniciado </p> } 
            </>;
 ```
