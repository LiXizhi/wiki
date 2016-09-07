# wiki
A public wiki website that allow each user to have create its own website. It uses github as one of its data source for storing wiki content. 

> The wiki page of this project also contains the root search index

{% exercise %}
Define a variable `x` equal to 10.
{% initial %}
var x =
{% solution %}
var x = 10;
{% validation %}
assert(x == 10);
{% context %}
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
{% endexercise %}