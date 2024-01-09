HelloWorld.cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class HelloWorld : MonoBehaviour
{
 
 void Start()
 {

 print("Hello, World!");
 }

 void Update()
 {
 }
}
Crickets.cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class Crickets : MonoBehaviour
{

 void Start()
 {
 }
 
 void Update()
 {
 
 print("crickets");
 }
}
Destroy.cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class Destroy : MonoBehaviour
{

 void Start()
 {

 Destroy(gameObject);
 }
 
 void Update()
 {
 }
}
CreatePrimitives.cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class CreatePrimitives : MonoBehaviour
{

 void Start()
 {

 GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0, 0, 0);
 GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(-0.5f, 1, 0);
 GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0.5f, 1, 0);
 GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0.5f, 2, 0);
 GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(-0.5f, 2,
0);
 GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0, 3, 0);
 }

 void Update()
 {
 }
}