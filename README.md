# KotlinTask-1
package com.example.myapplication

fun main (args: Array<String>){
    print("hello world");

    //defining variable
    var a : Boolean = true
    var b : Char = 'R'
    var c : Byte = 12
    var d : Short = -334
    var e : Int = 12467
    var f : Long = -1236889L
    var g : Float = 5.5887355F
    var h : Double = 7.980473892

    println(a)
    println(b)
    println(c)
    println(d)
    println(e)
    println(f)
    println(g)
    println(h)
    //Type conversion
    var x: Double = 123.45
    var y: Int = x.toInt()
    var z: Byte = y.toByte()

    println(x)
    println(y)
    println(z)

    //String datatypes
    var i: String = "Hellooo World!"
    var j: Int = i.length
    var k: Boolean = i.equals("Hello world")
    var username: String = " sOftwarica "

    println(username.trim())
    println(i);
    println(j)
    println(i.isEmpty())
    println(i.lowercase())
    println(i.uppercase())
    println(k)
    print(i.plus(" , How are you?"));
    //Array
    var age = arrayOf (1,2,3)
    println(age)
    println("the first element of age is " + age[0])
    println("the second element of age is " + age[1])
    println("the third element of age is " + age[2])

    println("****************************************")

    var name = arrayOf("Ram","Shyam","Hari")
    name[1] = "AABRITI"
    println("the first element of name is " + name[0])
    println("the second element of name is " + name[1])
    println("the third element of name is " + name[2])

    println(name.size)

    //ArrayList
    //we can add value only after our array is initialize
    var age1 = ArrayList<Int>()
    age1.add(1)
    age1.add(1,20)
    age1.add(5)
    //we can add value directly in array while initializing variables.
    var age2 = arrayListOf<Int>(1,20,5)

    var name1 = arrayListOf<String>("AABRITI","Ram","Shyam")
    name1.add("Hritik")
    name1.add(4,"Sima")

    name1.remove("Shyam")
    name1.removeAt(0)

    println(name1)

    var mixArrayList = arrayListOf<Any>("Helloo",5,2.0)
    println(mixArrayList[0]);
    println(mixArrayList[1]);
    println(mixArrayList[2]);

    //List
    val lst = listOf("one","two","three")
    println("Mutable List")
    for (i in lst.indices){
        println(lst[i])
    }




}