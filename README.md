# Learning C# by Developing Games with Unity 2020 - Fifth Edition

1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
1. [I'm an inline-style link with title](https://www.google.com "Google's Homepage")

```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class LearningCurve : MonoBehaviour
{
    // Integer variables
    private int currentAge = 30;
    public int addedAge = 1;

    public float pi = 3.14f;
    public string firstName = "Harrison";
    public bool isAuthor = true;

    // Start is called before the first frame update
    void Start()
    {
        ComputeAge();
    }

    // Update is called once per frame
    void Update()
    {

    }

    /// <summary>
    /// Computes a modified age integer
    /// </summary>
    void ComputeAge()
    {
        Debug.Log(currentAge + addedAge);
    }
}

```
