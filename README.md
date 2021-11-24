# Vue carrer path 

## Obligatorio

- Git

## Basico

<details>
<summary>HTML</summary> 
    <ul>
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
    </ul>
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
    <ul>
        <li>Métodos de arreglos</li>        
        <details>
            <summary>ES6</summary>
            <ul>
                <li>Destructuring</li>
                <li>Spread operator</li>
                <li>String literals</li>
                <li>Parametros por defecto</li>
                <li>Arrow functions</li>
                <li>Promesas</li>
                <li>Modulos</li>
            </ul>
        </details>
        <li>Event bubbling</li>
        <li>Hoisting</li>
        <li>Scopes</li>
        <details>
            <summary>Errores</summary>
            <ul>
                <li>Try/catch</li>
                <li>Instanciar un error</li>
            </ul>
        </details>
    </ul>
</details>



## Intermedio

<details>
    <summary>CSS</summary>
	<ul>
        <li>Modelo de cascada</li>
        <li>Flexbox</li>
        <li>Grid</li>
        <li>Responsive design</li>
    </ul>
</details>


<details>
   <summary> JavaScript</summary>
   <ul>
        <li>Asincronismo</li>
        <li>`this`</li>
        <li>Strict mode</li>
        <details>
            <summary>Peticiones HTTP</summary>
            <ul>
                <li>`fetch`</li>
                <li>Axios</li>
                <li>Metodos HTTP</li>
            </ul>
        </details>
    </ul>
</details>


<details>
    <summary>Manejador de paquetes</summary>
    <ul>
        <li> yarn </li>
        <li> npm </li>
    </ul>
</details>
<details>
    <summary>Conceptos de librerías</summary>
        <ul>
        <li> Virtual DOM </li>
        <li> ¿Qué es el estado? </li>
        <details>
            <summary>Ciclo de vida componentes</summary>
            <ul>
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
            </ul>
        </details>
         <details>
            <summary>Inicializar una aplicación</summary>
            <ul>
                <li> `vue.createApp()` </li>
                <li> `app.mount()` </li>
            </ul>
        </details>
        <details>
            <summary>Lenguaje de template</summary>
			<ul>
                <li> Operador de interpolación `{{ }}` </li>
                <li> `v-once()` </li>
        	</ul>
        </details>
        <details>
            <summary>Directivas de vue</summary>
			<ul>
                <li> Directiva </li>
                <li> Nombre </li>
                <li> Modificador </li>
                <li> Valor </li>
                ```jsx
                v-on:click.stop="doThis"
                //directiva:nombre.modificador="valor"
                ```
        	</ul>
        </details>
        <details>
            <summary>Usar JS dentro de HTML</summary>
			<ul>
                <li> `vbind` o el atajo `:` </li>
        	</ul>
		</details>
        <details>
            <summary>Escuchar eventos</summary>
			<ul>
                <li> `on` o el atajo `@` </li>
        	</ul>
		</details>
        <details>
            <summary>Ciclos y condicionales en componentes</summary>
			<ul>
                <li> `v-if` `v-else` </li>
                <li> `v-for` </li>
        	</ul>
		</details>
        <details>
            <summary>Formularios controlados</summary>
            <ul> 
                <details>
                    <summary>`v-model`</summary>
                    <ul>    
                        <li> Numeros </li>
                        <li> Dropdowns </li>
                        <li> Checkoboxes & Radio Buttons </li>
                        <li> Con componentes </li>
                    </ul>
                </details>
            </ul>
        </details>
         <details>
            <summary>Crear componentes con options API</summary>
			<ul>
                <li> `methods()` </li>
                <li> `data()` </li>
                <li> `computed()` </li>
                <li> `watchers()` </li>
        	</ul>
		</details>
        <details>
            <summary>Estilos dinamicos</summary>
			<ul>
                <li>`:style`</li>
        	</ul>
		</details>
        <details>
            <summary>Vue-CLI</summary>
			<ul>
                <li> Archivos `.vue` </li>
                <li> Comandos Vue </li>
        	</ul>
		</details>
        <details>
            <summary>Comunicar componentes padres-hijos</summary>
            <ul>
                <li> `props: [ ]` </li>
                <details>
                    <summary>Validacion de props</summary>
                    <ul>
                        <li> `type` `required` `default` `validator()` </li>
                	</ul>
		        </details>
                <details>
                    <summary>Eventos personalizados en componentes</summary>
			        <ul>
                        <li> `this.$emit()` </li>
                        <li> `emits: [ ]` </li>
                        <li> El padre reacciona ante el evento transmitido por los componentes hijos </li>
                	</ul>
		        </details>
                <details>
                    <summary>Pasar props a componentes que esten por debajo de los hijos</summary>
                    <ul>
                                <li> `provide()` para componentes padre </li>
                                <li> `inject()`  para componentes hijo </li>
                            </ul>
                </details>
                <details>
                    <summary>Acceder al contenido envuelto dentro de un componente</summary>
                    <ul>
                        <li> `<slot>` </li>
                        <li> `<v-slot>` para slots con nombre </li>
                        <details>
                            <ul>
                            <summary>Scoped slots</summary>
                                <li> `v-slot="propName"` </li>
                            </ul>
                        </details>
                    </ul>
                </details>
            </ul>
        </details>
        <details>
            <summary>Renderizar componentes en otra etiqueta fuera del flujo normal</summary>
            <ul>
            <li> `<telport>` </li>
            <details>
                <summary>Alcances de los componentes</summary>
                <details>
                    <summary>Alcance global</summary>
                    <ul>
                        <li> `app.component()` </li>
                    </ul>
                </details>
                <details>
                    <summary>Alcance local</summary>
                    <ul>
                        <li> `components: { }` </li>
                    </ul>
                </details>
            </details>
            </ul>
        </details>
        <li> Composición de componentes </li>
        <li> Mejores prácticas composición de componentes </li>
        <li> Componentes presentacionales y no presentacionales </li>
        <details>
            <summary>Enrutar una aplicación</summary>
                <ul>
                <details>
                    <summary>Vue-router</summary>
                    <ul>
                        <li> Crear el router `createRouter()` </li>
                        <li> Registrar rutas `routes: [ ]` </li>
                        <li> Crear enlaces `<router-link>` </li>
                        <details>
                            <summary>Agregar parametros `/ruta/:parametro/`</summary>
			                <ul>
                                <li> Acceder a los parametros `this.$route.params.parametro` </li>
                        	</ul>
		                </details>
                        <details>
                            <summary>Navegación con código</summary>
			                <ul>
                                <li> `$router.push()` </li>
                                <li> `$router.forward()` </li>
                                <li> `$router.back()` </li>
                        	</ul>
		                </details>
                        <details>
                            <summary>Navigation guards</summary>
			                <ul>
                                <li> `beforeEach` </li>
                                <li> `beforeEnter` </li>
                                <li> `beforeRouteEnter` </li>
                                <li> `beforeRouterLeave` </li>
                                <li> `afterEach` </li>
                        	</ul>
		                </details>
                    </ul>
                </details>
            </ul>
        </details>
        <details>
            <summary>Manejador de estado</summary>
            <ul>
            <details>
                <summary>VueX</summary>
			    <ul>
                    <li> Inicializar manejador de estado `createStore()` </li>
                    <li> Guardar datos `state()` </li>
                    <li> Acceder a los datos `getters` </li>
                <details>
                    <summary>Cambiar los datos `mutations`</summary>
                    <ul>
                        <li> Payload </li>
                        <li> Para ejecutar cambios en los datos `commit()` </li>
                	</ul>
		        </details>
                <li> Ejecutar código asincrono `actions` </li>
                <li> `mapActions()` `mapGetters()` para acceder a las acciones y datos guardados </li>
                <details>
                    <summary>Encapsular con modulos `modules`</summary>
			        <ul>
                        <li> Leer los datos desde modulos </li>
                	</ul>
                </details>
                <li> Cuando usar un manejador de estado y cuando no </li>
                </ul>
            </details>
        </details>
        <details>
            <summary>Re-utilizar lógica</summary>
			<ul>
                <li> `mixins: []` </li>
                <li> hooks </li>
        	</ul>
		</details>
        <details>
            <summary>Composition API `setup()`</summary>
            <ul>
                <details>
                    <summary>Variables que reacciona a los cambios</summary>
                    <ul>
                        <li> `ref()` para datos primitivos y nodos HTML </li>
                        <li> `reactive()` para objetos </li>
                    </ul>
                </details>
                <li> `functions()` para reemplazar `methods` </li>
                <li> `computed()` para reemplazar `computed` </li>
                <li> Exponer variables </li>
                <details>
                    <summary>Para componentes</summary>
                    <ul>
                        <li> `props`  `context` parametros de `setup()` </li>
                        <li> `provide()` `inject()` como funciones de Vue para usar esos conceptos </li>
                    </ul>
                </details>
                <details>
                    <summary>¿Como usar router y Vuex en Composition API?</summary>
                    <ul>
                        <details>
                            <summary>Usando los hooks diseñados para ello</summary>
                            <ul>
                                <li> `useRouter()` </li>
                                <li> `useStore()` </li>
                            </ul>
                        </details>
                    </ul>
                </details>
            </ul>
        </details>
    </ul>
</details>
  
## Avanzado


<details>
    <summary>CSS</summary>
    <ul>
        <li> Animaciones </li>
        <details>
        <summary>Frameworks</summary>
            <ul>
                <li> Bootstrap </li>
                <li> Style </li>
                <li> Sass </li>
            </ul>
        </details>
    </ul>
</details>
<details>
    <summary>JavaScript</summary>
        <ul>
            <li> Prototypes </li>
            <li> Como funciona el motor de JS </li>
            <li> Import dinamicos </li>
        </ul>
</details>
    <details>
    <summary>Adicionales</summary>
    <ul>
        <li> Webpack </li>
        <li> Autenticación </li>
        <li> Patrones de composición </li>
        <li> Validación de formularios </li>
        <li> Unit testing </li>
        <li> Migraciones </li>
    </ul>
</details>


# Recursos

## Cursos

- [Vue The Complete Guide - Maximilian Schwarzmüller ](https://www.udemy.com/course/vuejs-2-the-complete-guide/)
- [Vue JS Essentials with VueX and Vue Router - Stephen Grider](https://www.udemy.com/course/vue-js-course/)
- [Vue.js: De cero a experto](https://www.udemy.com/course/vuejs-fh/)

## Documentación
- [HTML Reference](https://htmlreference.io/)
- [CSS Reference](https://cssreference.io/)
- [JavasCript info](https://es.javascript.info/)
- [Documentacion oficial Vue](https://v3.vuejs.org/guide/introduction.html)
- [Documentación Vue Testing](https://testing-library.com/docs/vue-testing-library/intro)


## Tutoriales
- [Vue Testing con Vue Test utils](https://www.youtube.com/watch?v=QIDhzBg5eWY)
- [Guía para hacer testing](https://lmiller1990.github.io/vue-testing-handbook/v3/)
- [Patrones de diseño para la comunicación de componentes Vue.js](https://code.tutsplus.com/es/tutorials/design-patterns-for-communication-between-vuejs-component--cms-32354)

## Ideas para proyectos
- [Frontend mentor](https://www.frontendmentor.io/)
- [Picalil Challenge](https://piccalil.li/category/front-end-challenges-club/)
- [CodeWell](https://www.codewell.cc/)
- [The Best Desgings](https://www.thebestdesigns.com/)
- [Code Mentor](https://www.codementor.io/projects)
- [Dev Challenges](https://devchallenges.io/)
- [DailyUI](https://www.dailyui.co/)
- [15 Vue JS Project Ideas: Beginner to Expert (With tutorial)](https://blog.nerdjfpb.com/project-ideas-for-vue-js-beginners-to-expert/)
- [How to Build a Memory Card Game with Vue.js](https://www.freecodecamp.org/news/how-to-build-a-memory-card-game-with-vuejs/)
- [How To Build Sudoku in Vue.js](https://betterprogramming.pub/how-to-build-sudoku-in-vue-js-f97509b523ed)