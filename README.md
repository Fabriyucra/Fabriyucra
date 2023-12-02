
## Hola, Soy Fabricio 👋

```typescript
class Desarrollador {
    private nombre: string;
    private estudios: string;
    private experiencia: string;
    private habilidades: string[];
    private frontend: string[];
    private backend: string[];
    private basesDeDatos: string[];
    private controlDeVersiones: string;

    constructor() {
    this.nombre = "Fabricio";
    this.estudios =
    "Estudio la Tecnicatura en Desarrollo web en la Universidad Nacional de la Matanza y la Tecnicatura en Aplicaciones Móviles.";
    this.experiencia = "Desarrollador de software desde enero de 2021.";

    this.habilidades = [
    "Experiencia y conocimiento sólido en programación orientada a objetos, con habilidades probadas en la construcción de software de alta calidad.",
    "Profundo entendimiento del ciclo de vida de un producto, desde la concepción y diseño hasta el desarrollo, prueba, implementación y mantenimiento.",
    "Capacidad para aplicar principios de desarrollo ágil y buenas prácticas de ingeniería de software para garantizar la entrega eficiente y exitosa de productos."];

    this.frontend = [
    "Experiencia en desarrollo frontend (HTML, CSS, JavaScript, Jquery, Boostrap)",
    "Conocimiento de frameworks y bibliotecas populares como Angular, React."];

    this.backend = [
    "Experiencia en desarrollo backend con C#, Framework: .NET, ApiRest (Experiencia laboral)",
    "Experiencia en desarrollo backend con Kotlin (Experiencia laboral)",
    "Conocimientos básicos Java, framework: Sprint (Universidad)",
    "Conocimientos básicos Php (Universidad)"];

    this.basesDeDatos = [
    "Competencia en el diseño y gestión de bases de datos SQL (MySQL, PostgreSQL).",
    "NoSQL (MongoDB, Firebase)."];

    this.controlDeVersiones = "Uso efectivo de sistemas de control de versiones como Git.";
    }

    public imprimirDatos(): void {
        console.log(`Hola Soy ${this.nombre} 👋\n`);
        console.log(`🙋🏻‍♂️ ${this.estudios}`);
        console.log(`🧑🏻‍💻 ${this.experiencia}\n`);
        console.log("Habilidades:");
        this.habilidades.forEach(habilidad => console.log(habilidad));
        console.log("\nFrontend:");
        this.frontend.forEach(item => console.log(item));
        console.log("\nBackend:");
        this.backend.forEach(item => console.log(item));
        console.log("\nDatabases:");
        this.basesDeDatos.forEach(item => console.log(item));
        console.log("\nSistemas de control de versiones:");
        console.log(this.controlDeVersiones);
    }
}

const fabricio = new Desarrollador();
fabricio.imprimirDatos();
```
## Get in touch
