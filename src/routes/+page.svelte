Climate change is the number one problem in the world, yet it is the one most ignored. 
Many politicians even tried to claim that climate change wasn't even real, although even they have mostly stopped. So if everyone knows it's an issue, why isn't it being fixed?
You may have two answers to that, 1) it is, and 2) it is more challenging than that.
To answer question one, look at 
Resources: 
https://www.nature.org/en-us/what-we-do/our-priorities/tackle-climate-change/climate-change-stories/climate-change-frequently-asked-questions/
<section id="climate">
    <p>Climate change is currently the number one problem in the world, yet it is the one most ignored. If you are trying to change that, or just want to learn more about how bad it really is, look no further.</p>
</section>
<section class="pieChart">
    <div id="ElectricalGeneration">
        <h2>Electricity</h2>
</div>
<div id="Agriculture">
    <h2>Agriculture</h2>
</div>
<div id="Transportation">
    <h2>Transportation</h2>
</div>
<div id="Manufacturing">
    <h2>Manufacturing</h2>
</div>
</section>
<p style="font-size: 2em; text-align: center">*This is not a chart that accurately represents the percent of emissions! It it just a navigation circle.</p>
<style>
    #climate {
		background: linear-gradient(90deg, var(--green1), var(--green3));
        padding: 200px 4vw;
	}
	#climate h1 {
		font-size: 4.5rem;
		color: white;
	}
	#climate p {
		color: white;
		font-size: 1.5rem;
		padding-bottom: 2em;
	}
    .pieChart div{
        width: 34%;
        aspect-ratio: 1;
        transition: all .2s;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
    #Manufacturing{
        border-radius: 0 0 100% 0;
        background-color: #87cefa;
    }
    #Manufacturing:hover{
        transform: scale(1.2);
        transform-origin: top left;
        margin: 0.5em 0 0 0.5em;
    }
    
    #ElectricalGeneration{
        border-radius: 100% 0 0 0;
        background-color: #ffd700;
    }
    #Agriculture{
        border-radius: 0 100% 0 0;
        background-color: 	#9acd32;
    }
    #Transportation{
        border-radius: 0 0 0 100%;
        background-color: #f08080;
    }
    .pieChart{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
    #ElectricalGeneration:hover{
        transform: scale(1.2);
        transform-origin: bottom right;
        
        margin: 0 0.5em 0.5em 0;
    }
    #Agriculture:hover{
        transform: scale(1.2);
        transform-origin: bottom left;
        margin: 0 0.5em 0.5em 0;
    }
    #Transportation:hover{
        transform: scale(1.2);
        transform-origin: top right;
        margin: 0.5em 0.5em 0 0;
    }
    h2{
        font-size: 2.7vw;
    }
</style>