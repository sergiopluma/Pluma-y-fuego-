import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

const Home = () => { return ( <div className="min-h-screen bg-white text-gray-900 p-6"> <header className="text-center mb-12"> <h1 className="text-4xl font-bold mb-2">Pluma y Juego</h1> <p className="text-lg">Revista cultural de opinión y columnas</p> </header>

<main className="grid gap-8">
    <section>
      <h2 className="text-2xl font-semibold mb-4">Últimas Publicaciones</h2>
      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <Card>
          <CardContent className="p-4">
            <h3 className="text-xl font-semibold">La estética de la palabra</h3>
            <p className="text-sm text-gray-700 mt-2">Una reflexión sobre el poder simbólico del lenguaje en la cultura contemporánea.</p>
            <Button variant="link" className="mt-4 px-0">Leer más</Button>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-4">
            <h3 className="text-xl font-semibold">El columnismo en tiempos de redes</h3>
            <p className="text-sm text-gray-700 mt-2">Cómo han cambiado los formatos de opinión frente a la inmediatez digital.</p>
            <Button variant="link" className="mt-4 px-0">Leer más</Button>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-4">
            <h3 className="text-xl font-semibold">Memoria e identidad</h3>
            <p className="text-sm text-gray-700 mt-2">Una mirada crítica a los relatos que configuran nuestras raíces culturales.</p>
            <Button variant="link" className="mt-4 px-0">Leer más</Button>
          </CardContent>
        </Card>
      </div>
    </section>

    <section className="mt-12">
      <h2 className="text-2xl font-semibold mb-4">Sobre la Revista</h2>
      <p className="text-gray-700 max-w-3xl">
        <strong>Pluma y Juego</strong> es una revista cultural que apuesta por el pensamiento libre, el análisis agudo y la expresión creativa. Aquí convergen las voces críticas de nuestra época, con textos que van desde la columna literaria hasta el ensayo político.
      </p>
    </section>

    <section className="mt-12">
      <h2 className="text-2xl font-semibold mb-4">Contacto</h2>
      <p className="text-gray-700 mb-2">¿Quieres colaborar o enviarnos tu artículo?</p>
      <Button variant="outline">Escríbenos</Button>
    </section>
  </main>

  <footer className="mt-16 border-t pt-6 text-center text-sm text-gray-500">
    © 2025 Pluma y Juego. Todos los derechos reservados.
  </footer>
</div>

); };

export default Home;

