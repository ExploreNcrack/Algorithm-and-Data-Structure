# Quick Find [eager approach]

## Memory Cost: O(N)


* Initialize a size N integer array with their index number as the data storage to support the implementation
* *p* and *q* are connected if and only if they have the same content(id) in their index array

**Find** 
* Check if the index "p" and "q" in the id integer array have the same content. 
**Cost: O(1)**

**Union** 
* To merge components containing *p* and *q*. Change all entries whose id equals **id[p]** to **id[q]**
**Cost: O(N)**

## Advantage
Providing a very efficient way for the **find** operation, very simple data structure is needed to implement 

## Disadvantage
Not a very optimistic cost for the **Union** operation

## Example
![](https://github.com/ExploreNcrack/Algorithm-and-Data-Structure/blob/master/SET%20THEORY/Dynamic%20Connectivity/Union%20Find/Quick%20Find/quick_find1.png)
</br>
</br>
![](https://github.com/ExploreNcrack/Algorithm-and-Data-Structure/blob/master/SET%20THEORY/Dynamic%20Connectivity/Union%20Find/Quick%20Find/quick_find2.png)
</br>
</br>
![](https://github.com/ExploreNcrack/Algorithm-and-Data-Structure/blob/master/SET%20THEORY/Dynamic%20Connectivity/Union%20Find/Quick%20Find/quick_find3.png)
</br>
</br>
![](https://github.com/ExploreNcrack/Algorithm-and-Data-Structure/blob/master/SET%20THEORY/Dynamic%20Connectivity/Union%20Find/Quick%20Find/quick_find4.png)
</br>
</br>
![](https://github.com/ExploreNcrack/Algorithm-and-Data-Structure/blob/master/SET%20THEORY/Dynamic%20Connectivity/Union%20Find/Quick%20Find/quick_find5.png)
