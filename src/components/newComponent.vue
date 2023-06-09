<template>
    <div>
        <table>
            <tr>
                <th id="nombre">
                    Nombre:{{ nombre }}
                </th>
            </tr>
            <tr>
                <th id="edad">
                   Edad:{{ edad }}
                </th>
            </tr>
            <tr>
                <th id="fecha">
                     Fecha:{{ fecha }}
                </th>
            </tr>

        </table>
    </div>


    <p id="color"> Nombre:{{ nombre }} , Edad:{{ edad }}, Fecha:{{ fecha }}</p>
</template>

<script>
export default {
    name: 'newComponent',
    props: {
        nombre: String,
        edad: Number,
        fecha: Date


    },
    data() {
        return {
            
        }
    }
}

</script>

<style>

#color{
    color: blue;
}
#nombre{
    color:chartreuse;
}
#edad{
    color:blueviolet;
}
#fecha{
    color:crimson;
}
</style>