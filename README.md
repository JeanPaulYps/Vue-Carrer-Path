# Vue carrer path 

# Obligatorio

- Git

# Basico

<details>
<summary>HTML</summary> 
    <details>
        <summary>Etiquetas y estuctura de documento </summary>
        <ul>
          <li> Etiquetas de texto </li>
          <li> Etiquetas de lista </li>
          <li> Etiquetas de imagen </li>
          <li> Etiquetas para tablas </li>
          <li> Enlaces </li>
          <li> Formularios </li>
          <li> Etiquetas contenedoras </li>
        </ul>
    </details>

  <li> HTML semantico </li>
</details>

<details>
    <summary>CSS</summary>
    <ul>
        <li>Selectores</li>
        <li>Unidades de medida</li>
        <li>Colores</li>
        <li>Propiedades de texto</li>
        <li>Pseudoclases y pseudoelementos</li>
        <li>Modelo de caja</li>
        <li>Position</li>
            <ul>
                <li>Relative</li>
                <li>Absolute</li>
            </ul>
        <li>Display</li>
    </ul>
</details>

<details>
    <summary> JS </summary>
        <li>Métodos de arreglos</li>        
        <details>
            <summary>ES6</summary>
                <li>Destructuring</li>
                <li>Spread operator</li>
                <li>String literals</li>
                <li>Parametros por defecto</li>
                <li>Arrow functions</li>
                <li>Promesas</li>
                <li>Modulos</li>
        </details>
        <li>Event bubbling</li>
        <li>Hoisting</li>
        <li>Scopes</li>
        <details>
        <summary>Errores</summary>
            <li>Try/catch</li>
            <li>Instanciar un error</li>
        </details>
</details>



# Intermedio

<details>
    <summary>CSS</summary>
        <li>Modelo de cascada</li>
        <li>Flexbox</li>
        <li>Grid</li>
        <li>Responsive design</li>
</details>



<details>
    <summary> JavaScript</summary>
        <li>Asincronismo</li>
        <li>`this`</li>
        <li>Strict mode</li>
        <details>
            <summary>Peticiones HTTP</summary>
            <li>`fetch`</li>
            <li>Axios</li>
            <li>Metodos HTTP</li>
        </details>
</details>


<details>
    <summary>Manejador de paquetes</summary>
    <li> yarn </li>
    <li> npm </li>
</details>

<details>
    <summary>Conceptos de librerías</summary>
    <li> Virtual DOM </li>
    <li> ¿Qué es el estado? </li>
    <details>
        <summary>Ciclo de vida componentes</summary>
            <li> `createApp` </li>
            <li> `beforeCreate` </li>
            <li> `created` </li>
            <li> `compile template` </li>
            <li> `beforeMount` </li>
            <li> `mounted` </li>
            <li> `beforeUpdate` </li>
            <li> `updated` </li>
            <li> `beforeUnmont` </li>
            <li> `unmonted` </li>
    </details>
    <details>
        <summary>Inicializar una aplicación</summary>
            <li> `vue.createApp()` </li>
            <li> `app.mount()` </li>
    </details>
    <details>
        <summary>Lenguaje de template</summary>
            <li> Operador de interpolación `{{ }}` </li>
            <li> `v-once()` </li>
    </details>
    <details>
        <summary>Directivas de vue</summary>
            <li> Directiva </li>
            <li> Nombre </li>
            <li> Modificador </li>
            <li> Valor </li>
             ```jsx
            v-on:click.stop="doThis"
            //directiva:nombre.modificador="valor"
            ```
    </details>
    <details>
        <summary>Usar JS dentro de HTML</summary>
        <li> `vbind` o el atajo `:` </li>
    </details>
    <details>
        <summary>Escuchar eventos</summary>
        <li> `on` o el atajo `@` </li>
    </details>
    <details>
        <summary>Ciclos y condicionales en componentes</summary>
        <li> `v-if` `v-else` </li>
        <li> `v-for` </li>
    </details>
    <details>
        <summary>Formularios controlados</summary>
        <details>
            <summary>`v-model`</summary>
                <li> Numeros </li>
                <li> Dropdowns </li>
                <li> Checkoboxes & Radio Buttons </li>
                <li> Con componentes </li>
        </details>
    </details>
    <details>
        <summary>Crear componentes con options API</summary>
            <li> `methods()` </li>
            <li> `data()` </li>
            <li> `computed()` </li>
            <li> `watchers()` </li>
    </details>
    <details>
        <summary>Estilos dinamicos</summary>
            <li>`:style`</li>
    </details>
    <details>
        <summary>Vue-CLI</summary>
            <li> Archivos `.vue` </li>
            <li> Comandos Vue </li>
    </details>
    <details>
        <summary>Comunicar componentes padres-hijos</summary>
        <li> `props: [ ]` </li>
        <details>
            <summary>Validacion de props</summary>
                <li> `type` `required` `default` `validator()` </li>
        </details>
        <details>
            <summary>Eventos personalizados en componentes</summary>
                <li> `this.$emit()` </li>
                <li> `emits: [ ]` </li>
                <li> El padre reacciona ante el evento transmitido por los componentes hijos </li>
        </details>
        <details>
            <summary>Pasar props a componentes que esten por debajo de los hijos</summary>
                <li> `provide()` para componentes padre </li>
                <li> `inject()`  para componentes hijo </li>
        </details>
        <details>
            <summary>Acceder al contenido envuelto dentro de un componente</summary>
            <li> `<slot>` </li>
            <li> `<v-slot>` para slots con nombre </li>
            <details>
                <summary>Scoped slots</summary>
                <li> `v-slot="propName"` </li>
            </details>
        </details>
    </details>
    <details>
        <summary>Renderizar componentes en otra etiqueta fuera del flujo normal</summary>
        <li> `<telport>` </li>
        <details>
            <summary>Alcances de los componentes</summary>
            <details>
                <summary>Alcance global</summary>
                 <li> `app.component()` </li>
            </details>
            <details>
                <summary>Alcance local</summary>
                 <li> `components: { }` </li>
            </details>
        </details>
    </details>
    <li> Composición de componentes </li>
    <li> Mejores prácticas composición de componentes </li>
    <li> Componentes presentacionales y no presentacionales </li>
    <details>
	    <summary>Enrutar una aplicación</summary>
         <details>
        	<summary>Vue-router</summary>
            <li> Crear el router `createRouter()` </li>
            <li> Registrar rutas `routes: [ ]` </li>
            <li> Crear enlaces `<router-link>` </li>
            <details>
                <summary>Agregar parametros `/ruta/:parametro/`</summary>
                <li> Acceder a los parametros `this.$route.params.parametro` </li>
            </details>
            <details>
                <summary>Navegación con código</summary>
                    <li> `$router.push()` </li>
                    <li> `$router.forward()` </li>
                    <li> `$router.back()` </li>
            </details>
            <details>
            	<summary>Navigation guards</summary>
                    <li> `beforeEach` </li>
                    <li> `beforeEnter` </li>
                    <li> `beforeRouteEnter` </li>
                    <li> `beforeRouterLeave` </li>
                    <li> `afterEach` </li>
            </details>
        </details>
    </details>
    <details>
	    <summary>Manejador de estado</summary>
         <details>
            <summary>VueX</summary>
            <li> Inicializar manejador de estado `createStore()` </li>
            <li> Guardar datos `state()` </li>
            <li> Acceder a los datos `getters` </li>
            <details>
                <summary>Cambiar los datos `mutations`</summary>
                <li> Payload </li>
                <li> Para ejecutar cambios en los datos `commit()` </li>
            </details>
            <li> Ejecutar código asincrono `actions` </li>
            <li> `mapActions()` `mapGetters()` para acceder a las acciones y datos guardados </li>
            <details>
        	    <summary>Encapsular con modulos `modules`</summary>
                <li> Leer los datos desde modulos </li>
            </details>
        </details>
        <li> Cuando usar un manejador de estado y cuando no </li>
    </details>
    <details>
        <summary>Re-utilizar lógica</summary>
            <li> `mixins: []` </li>
            <li> hooks </li>
    </details>
    <details>
        <summary>Composition API `setup()`</summary>
         <details>
            <summary>Variables que reacciona a los cambios</summary>
                <li> `ref()` para datos primitivos y nodos HTML </li>
                <li> `reactive()` para objetos </li>
        </details>
        <li> `functions()` para reemplazar `methods` </li>
        <li> `computed()` para reemplazar `computed` </li>
        <li> Exponer variables </li>
        <details>
	        <summary>Para componentes</summary>
             <li> `props`  `context` parametros de `setup()` </li>
            <li> `provide()` `inject()` como funciones de Vue para usar esos conceptos </li>
        </details>
        <details>
            <summary>¿Como usar router y Vuex en Composition API?</summary>
            <details>
            	<summary>Usando los hooks diseñados para ello</summary>
                    <li> `useRouter()` </li>
                    <li> `useStore()` </li>
            </details>
        </details>
    </details>
</details>
  
# Avanzado

<details>
	<summary>CSS</summary>
    <li> Animaciones </li>
    <details>
	    <summary>Framework</summary>
            <li> Bootstrap </li>
            <li> Style </li>
            <li> Sass </li>
    </details>
</details>
<details>
    <summary>JavaScript</summary>
        <li> Prototypes </li>
        <li> Como funciona el motor de JS </li>
        <li> Import dinamicos </li>
</details>
<li> Webpack </li>
<li> Autenticación </li>
<li> Patrones de composición </li>
<li> Validación de formularios </li>
<li> Unit testing </li>
<li>Migraciones</li>

