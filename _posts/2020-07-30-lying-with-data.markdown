---
layout: post
title: Lying with data
date: 2020-07-30 05:00:00 +0200
description: It's not hard to spin data to tell the story you want it to. But the simple truth is that we don't know if ivermectin is an effective therapy for Covid-19 or not.  
img: iver.png
tags: [Covid-19, data, publishing, ivermectin]
---

<h2>It's not hard to spin data to tell the story you want it to. Is ivermectin an effective therapy for Covid-19? The simple truth is that we don't know.<h2>

<h3>For more on ivermectin and Covid-19, check out <a href="https://www.isglobal.org/en/healthisglobal/-/custom-blog-portlet/ivermectin-and-covid-19-how-a-flawed-database-shaped-the-covid-19-response-of-several-latin-american-countries/2877257/0">this article</a>.</h3>



<div style='vertical-align:bottom; display:inline;'>
<p><a href="https://www.isglobal.org/en/our-team/-/profiles/7304" target="_blank"><img style='vertical-align:bottom;' src='../assets/img/carlos_circle.png' height='35'>
<b>Carlos Chaccour</b></a>, Assistant Research Professor at <a href="https://isglobal.org">ISGlobal</a> and Chief Scientific Officer of <a href="https://bohemiaconsortium.org/">BOHEMIA</a>

<div style='vertical-align:bottom; display:inline;'>
<p><a href="https://twitter.com/joethebrew" target="_blank"><img style='vertical-align:bottom;' src='../assets/img/joe_circle.png' height='35'>
<b>Joe Brew</b></a>, Data scientist at <a href="https://hyfeapp.com">Hyfe</a> and <a href="https://databrew.cc">Databrew</a>  

<p><b>Summary: </b>Ivermectin may or may not be an effective therapy for Covid-19. <b>We don’t know.</b> And we probably won’t know with any degree of confidence until the results of some randomized, controlled trials come in. In the meantime, the data can be twisted to conform with one’s prior beliefs. This is an article about confirmation bias, using the case of ivermectin.</p>



<p>
<strong>What’s going on with ivermectin in Latin America?</strong>
</p>
<p>
Although the very limited evidence supports the use of ivermectin against COVID-19, this antiparasitic has been included in the national therapeutic guidelines for COVID-19 in <a href="https://www.gob.pe/institucion/minsa/normas-legales/563764-270-2020-minsa">Peru</a> and <a href="https://docs.google.com/document/d/1iHO3TtZVU_0sT7QdewTu_ju4Yv3lvLCAtyjF6UixvUI/edit">Bolivia</a> and in sub-national guidelines in <a href="http://www.tribunadonorte.com.br/noticia/sms-natal-adota-uso-da-ivermectina-contra-a-covid-19/481745">Brazil</a>. There is also broadspread interest in its use in <a href="http://www.sochinf.cl/portal/templates/sochinf2008/documentos/2020/Comunicado_SOCHINF_Ivemectina.pdf">Chile</a>. This surge in demand has caused some serious issues like mass administration of <a href="https://elpais.com/sociedad/2020-06-19/un-grupo-evangelico-peruano-inyecta-un-medicamento-veterinario-a-miles-de-personas.html">veterinary formulations</a> to thousands of vulnerable populations and the selling of <a href="https://elcomercio.pe/lima/sucesos/intervienen-farmacia-en-sjm-que-vendia-invermectina-adulterada-y-medicamentos-sustraidos-del-estado-noticia/">poor-quality/counterfeit</a> formulations. Mass use of ivermectin is not exempt from risks, including a false sense of security that may hamper social distancing or even more complex <a href="https://www.nature.com/articles/s41577-020-0330-5">immunological changes</a> that might affect the way our body responds to viruses.
</p>
<p>
<strong>So, is ivermectin in Latin America saving lives?</strong>
</p>
<p>
Some are arguing that ivermectin is reducing mortality among Covid-19 patients. Proponents are pointing out that the ratio of deaths per confirmed cases (aka “case fatality rate” or CFR) appears lower in those <a href="https://twitter.com/jjchamie/status/1275115603573997571">countries where ivermectin is being promoted</a>. The below chart shows CFR among 5 ivermectin-promoting countries (Brazil, Peru, Dominican Republic, Honduras, Bolivia) vs. CFR among 10 countries not promoting ivermectin (Mexico, Canada, Chile, Cuba, Argentina, Nicaragua, Colombia, Panama, Uruguay, Venezuela)
</p>
<p>


<img src="../assets/img/lying_with_data/5.png" width="" alt="Deaths per confirmed cases" title="Deaths per confirmed cases">

</p>
<p>
Much of the above is driven by the large, most affected countries, namely Brazil (a country apparently “promoting” ivermectin) versus Mexico (ivermectin-averse): the former has seen a recent decline in the CFR, whereas the latter’s CFR remains high.
</p>
<p>


<img src="../assets/img/lying_with_data/15.png" width="" alt="Deaths per confirmed cases" title="Deaths per confirmed cases">

</p>
<p>
<strong>Wow, it looks like ivermectin is really great! We should be administering ivermectin everywhere, right?</strong>
</p>
<p>
Not quite. These country-level comparisons are subject to all sorts of biases, making it difficult to deduce meaningful inference. Testing strategies and rates are very different by country; the percentage of true Covid-19 deaths that different countries’ data systems capture are variable; we don’t know the extent to which ivermectin is actually being used in each country; and perhaps most importantly, there is “ecological fallacy”.
</p>
<p>
<strong>What is ecological fallacy?</strong>
</p>
<p>
Ecological fallacy is when you make some conclusion about something at the individual level (ie, that ivermectin reduces Covid-19 mortality) using non-individual data. It’s a classic “correlation does not mean causation” issue. That is, just because things are associated does not necessarily mean that one thing causes the other.
</p>
<p>
Maybe an example would be useful: one might stumble upon a <a href="https://twitter.com/jjchamie/status/1275443510649339910">Brazil vs. Mexico chart online</a> and conclude that ivermectin is an effective therapy. But, by the same reasoning, one might look at the same chart and conclude that speaking Portuguese reduces mortality, and speaking Spanish increases it. The point is, we can’t <em>really</em> know about causality without individual-level data. And the best individual-level data is the kind generated from experiments, not observations.
</p>
<p>
<strong>But “ecological” data is better than no data, right?</strong>
</p>
<p>
Maybe. Maybe not. We need to tell the whole story, and the case fatality rate is only part of the story. And it’s a part of the story that makes ivermectin look <em>good</em>. There are other indicators that make ivermectin look <em>bad</em>.
</p>
<p>
<strong>Okay, show me some data that makes ivermectin look bad.</strong>
</p>
<p>
Here you go. Instead of looking at case fatality rate (which is subject to testing rates), let’s instead just look at Covid-19 deaths per population.
</p>
<p>




<img src="../assets/img/lying_with_data/11.png" width="" alt="Daily deaths per million - Brazil vs. Mexico" title="Daily deaths per million - Brazil vs. Mexico">

</p>
<p>
The blue line (ivermectin-promoting Brazil) no longer looks so much better than the orange line (ivermectin-averse Mexico). Why is it that this chart is so different from the previous one? It’s partly due to the fact that Brazil has been apparently finding <em>many</em> cases, whereas Mexico has been missing them (see below).
</p>
<p>





<img src="../assets/img/lying_with_data/13.png" width="" alt="New daily cases per million" title="New daily cases per million">


</p>
<p>
Could it simply be that the scale of the outbreak (rather than just testing capacity) is much greater in Brazil? Sure. But we don't know that. What we do know is that the test positivity rate in Mexico is <a href="https://www.elfinanciero.com.mx/salud/en-mexico-el-50-de-la-pruebas-de-covid-19-dan-positivo-es-la-mayor-tasa-a-nivel-global">exceptionally high</a>, suggesting that there are many undetected cases.
</p>
<p>
<strong>But that’s just 2 countries. What about the countries from the original chart?</strong>
</p>
<p>
Here you go.
</p>
<p>


<img src="../assets/img/lying_with_data/10.png" width="" alt="New daily deaths per million" title="New daily deaths per million">


</p>
<p>
<strong>Wow. It looked like ivermectin decreases mortality. Now it looks like ivermectin increases mortality.</strong> <strong>I’m confused.</strong>
</p>
<p>
You should be.
</p>
<p>
Do you see what just happened? None of the above is a lie, but not all of it can be true.
</p>
<p>
Doctors and public health authorities are facing an unprecedented surge in deaths due to a single disease. Their urgency to act is not to be judged harshly as it is based on an honest desire to alleviate suffering. Compassionate use of drugs outside their approved label is a common figure for desperate circumstances, including patients with untreatable diseases, COVID-19 being one of them. However, even compassionate use in patients with stage IV cancer is heavily regulated under the fundamental <em>primum non nocere</em> (first do no harm) principle. No drug is exempt of potential harm, and when used at population level, this potential harm increases proportionally with the number of people treated.
</p>
<p>
This pandemic has (rightfully!) brought a strong sense or urgency upon us. But this rush has led to some mistakes that have caused great confusion and sometimes harm. This includes the rise and downfall of hydroxychloroquine,  fraudulent data shaping some important global health action or suggestions to use <a href="https://www.fda.gov/consumers/articulos-en-espanol/peligro-no-beba-la-solucion-mineral-milagrosa-o-productos-similares">“miraculous” medicines</a> based on disinfectants. A recent <a href="https://www.thelancet.com/journals/langlo/article/PIIS2214-109X(20)30260-6/fulltext">editorial</a> in The Lancet Global Health mentions what appears to be a paradoxical lesson learned <em>a need to slow down</em>, “When research, writing, and peer review are rushed, the consequences can be damaging”.
</p>
<p>
There is urgent need for good quality information, there is urgent need for rapid randomized controlled trials that can and <strong>must</strong> be done in the current epicenter of the pandemic which allows for quick recruitment and completion. There is additional need to answer basic science questions and above all, there is an urgent need to avoid the temptation of thinking that “bigger” data means “better” data.
</p>
