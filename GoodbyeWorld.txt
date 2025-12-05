using UnityEngine;

public class MainProj : MonoBehaviour
{
	public string dispStr = "HelloWorld";
	
	private void Start()
	{
		Debug.Log($"Output string is : {dispStr}");
	}
}