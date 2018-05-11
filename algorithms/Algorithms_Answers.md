Add your answers to the Algorithms exercises here.
I.
a) O(n)
b) O(n)
c) O(n^3)
d) O(n^2)
e) O(n^4)
f) O(1)
g) O(1)

II.
a)
function max(arr) {
let diff = 0;
for (let i = 0; i < arr.length; i++)
{
for (let j = arr.length-1; j > i; j--)
{
if(arr[j] > arr[i] && diff < (j - i))
diff = j - i;
}
}
return diff;
}
b)

III.
a) O(n^2)
b)
