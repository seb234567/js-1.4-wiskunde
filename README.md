# js-1.4-wiskunde
wiskunde berekeningen in javascript

## added <script>
    function berekenInhoud(getaalA, getaalB, getaalC){
        let som = getaalA * Math.pow(getaalB, 2) * getaalC;
        console.log(som);
    }
    let kubesinhout = berekenInhoud(10, 5 ,10);
    let cilinderinhout = berekenInhoud(Math.PI , 5, 10);
    function pytagoras(getaalA, getaalB){
        let som = Math.sqrt(Math.pow(getaalA, 2) + Math.pow(getaalB, 2));
        console.log(som);
    }
    let schuinezijde = pytagoras(3, 4);
    function gemmidelt(getaalA, getaalB, getaalC, getaalD, getaalE, getaalF, getaalG){
        let som = (getaalA + getaalB + getaalC + getaalD + getaalE + getaalF + getaalG) / 7;
        console.log(som)
    }
    let gemiddeltgetaal = gemmidelt(5,3,7,9,2,1,7 )
</script>
## added function berekenInhoudkubes(getaalA, getaalB, getaalC){
        let som = getaalA * getaalB * getaalC;
        console.log(som);

## change 
function berekenInhoud(getaalA, getaalB, getaalC){
        let som = getaalA * Math.pow(getaalB, 2) * getaalC;
        onsole.log(som);
    }
 ## to 
 function berekenInhoudclinder(getaalA, getaalB, getaalC){
        let som = getaalA * Math.pow(getaalB, 2) * getaalC;
        console.log(som);
    }

## made the code moor readeble