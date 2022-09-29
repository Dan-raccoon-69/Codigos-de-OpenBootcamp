Scanner datos = new Scanner(System.in);
        /**
         * Usando un if, crear una condición que compare si la variable numeroIf es positivo, negativo, o 0.
           Pista: Los números inferiores a 0 son negativos y los superiores, positivos.
         */
        
        System.out.println("Positivo, negativo o cero: " + "\n");
        int numeroIf;
        System.out.println("Escribe un numero: ");
        numeroIf = datos.nextInt();
        
        if(numeroIf == 0){
            System.out.println("El numero es 0.");
        }else if(numeroIf > 0){
            System.out.println("El numero es positivo.");
        }else{
            System.out.println("El numero es negativo.");
        }
        
        
        
        /**
         * Crea un bucle While, este bucle tendrá que tener como condición que la variable numeroWhile sea inferior a 3, 
         * el bloque de código que tendrá el bucle deberá:
            Incrementar el valor de la variable en uno cada vez que se ejecute.
            Mostrarlo por pantalla cada vez que se ejecute.
         */
        
        
        System.out.println("While" + "\n");
        int numeroWhile;
        System.out.println("Escribe un numero: ");
        numeroWhile = datos.nextInt();
        
        while(numeroWhile < 3){
            numeroWhile++;
            System.out.println(numeroWhile + " ");
        }
        
        
        
        
        /**
         * Para el bucle Do While, deberás crear la misma estructura que en el While, pero solo se debe ejecutar una vez.
         */
        
        System.out.println("Do while" + "\n");
        int numeroDoWhile = 2;
        do{
            numeroDoWhile++;
            System.out.println(numeroWhile + " ");
        }while(numeroDoWhile < 3);
        
        
        
        
        /**
         * Para el bucle For, crea una variable numeroFor, esta variable tendrá como valor 0 y su condición será que la variable sea igual o menor que 3,
         * se irá incrementando en 1 su valor cada vez que se ejecute y deberá mostrarse por pantalla.
         */
        
        System.out.println("For" + "\n");
        for(int numeroFor = 0; numeroFor <=3; numeroFor++){
            System.out.println(numeroFor + " ");
        }
        
        
        
        /**
         * Por último, para el Switch, deberás crear la variable estacion, y distintos case para las cuatro estaciones del año. 
         * Dependiendo del valor de la variable estacion se deberá mandar un mensaje por consola informando de la estación en la que está.
         * También habrá que poner un default para cuando el valor de la variable no sea una estación.
         */
        
        String estacion;
        System.out.println("Switch" + "\n");
        System.out.println("Estación del año: ");
        estacion = datos.next();
        
        switch(estacion){
            case "1":
                System.out.println("Estación primavera");
                break;
            case "2":
                System.out.println("Estación verano");
                break;
            case "3":
                System.out.println("Estación otoño");
                break;
            case "4":
                System.out.println("Estación invierno");
                break;
            default:
                System.out.println("Error de variable.");
        }
        
