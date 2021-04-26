---
about_this_resource_text: <p><strong>Description:</strong> Topics continued on solving
  problems of ordinary differential equation with initial value. Also introduced concept
  of functionals and nesting functionals.</p> <p><strong>Instructor:</strong> William
  Green</p>
course_id: 10-34-numerical-methods-applied-to-chemical-engineering-fall-2015
embedded_media:
- id: Video-YouTube-Stream
  media_location: KFq33hsMxr4
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: Video-YouTube-Stream
  type: Video
  uid: 4822fc477b6e4ea78b3c9cb6c9ad86cc
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/KFq33hsMxr4/default.jpg
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9231ca0e656bab4aa761923582047b7a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: KFq33hsMxr4
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: eaa40845c07d6f2cb52b99f4441b5de1
- id: KFq33hsMxr4.srt
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-16-ode-ivp-and-numerical-integration-4/KFq33hsMxr4.srt
  title: 3play caption file
  type: null
  uid: 5429dd4f8b416e3538e849cab823e1ea
- id: KFq33hsMxr4.pdf
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-16-ode-ivp-and-numerical-integration-4/KFq33hsMxr4.pdf
  title: 3play pdf file
  type: null
  uid: b2dc3c9bed63c65f0909c7f7c5728349
- id: Caption-3Play YouTube id-SRT
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 659031d530a9760753ff5135fafeb9d7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4ee24c2dc2a4f08ceb25f3501d4ccc13
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id1271456481
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: Video-iTunes U-MP4
  type: Video
  uid: 3548a013d72b96ebbe821aaf160a8371
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT10.34F15/MIT10_34F15_ses16_300k.mp4
  parent_uid: 571c93ac486601cc3437682ad96bc2ab
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4e60b7bb807c40cec08f898cd0cc6d2e
inline_embed_id: 78944155session16odeivpandnumericalintegration434143035
layout: video
order_index: null
parent_uid: afa0ff29750f6846eda04cb1a3d4b84a
related_resources_text: ''
short_url: session-16-ode-ivp-and-numerical-integration-4
technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-16-ode-ivp-and-numerical-integration-4
template_type: Tabbed
title: 'Session 16: ODE-IVP and Numerical Integration 4'
transcript: <p><span m='1540'>The</span> <span m='1630'>following</span> <span m='2080'>content</span>
  <span m='2560'>is</span> <span m='2680'>provided</span> <span m='3130'>under</span>
  <span m='3370'>a</span> <span m='3430'>Creative</span> <span m='3910'>Commons</span>
  <span m='4270'>license.</span> <span m='5300'>Your</span> <span m='5380'>support</span>
  <span m='5890'>will</span> <span m='6040'>help</span> <span m='6280'>MIT</span>
  <span m='6760'>OpenCourseWare</span> <span m='7510'>continue</span> <span m='7990'>to</span>
  <span m='8140'>offer</span> <span m='8470'>high</span> <span m='8680'>quality</span>
  <span m='9160'>educational</span> <span m='9820'>resources</span> <span m='10390'>for</span>
  <span m='10540'>free.</span> <span m='11600'>To</span> <span m='11620'>make</span>
  <span m='11800'>a</span> <span m='11860'>donation</span> <span m='12610'>or</span>
  <span m='12790'>to</span> <span m='12910'>view</span> <span m='13120'>additional</span>
  <span m='13540'>materials</span> <span m='14140'>from</span> <span m='14320'>hundreds</span>
  <span m='14650'>of</span> <span m='14770'>MIT</span> <span m='15130'>courses,</span>
  <span m='16460'>visit</span> <span m='16630'>MIT</span> <span m='17140'>OpenCourseWare</span>
  <span m='18100'>at</span> <span m='18250'>ocw.mit.edu.</span> </p><p><span m='24450'>PROFESSOR:</span>
  <span m='24495'>All</span> <span m='24540'>right,</span> <span m='24840'>I think</span>
  <span m='25110'>we're</span> <span m='25290'>gathered.</span> <span m='25740'>So</span>
  <span m='26160'>let's</span> <span m='26310'>get</span> <span m='26400'>going.</span>
  <span m='28270'>We</span> <span m='28350'>were</span> <span m='28440'>going</span>
  <span m='28560'>to</span> <span m='28620'>DAEs</span> <span m='29340'>today,</span>
  <span m='30300'>but</span> <span m='30450'>we</span> <span m='30510'>decided</span>
  <span m='30780'>to</span> <span m='30840'>postpone</span> <span m='31260'>for</span>
  <span m='31380'>one</span> <span m='31530'>day</span> <span m='32460'>and</span>
  <span m='32580'>do</span> <span m='32700'>a</span> <span m='32729'>little</span>
  <span m='32910'>catch</span> <span m='33210'>up</span> <span m='34260'>on</span>
  <span m='34350'>different</span> <span m='34590'>things</span> <span m='34920'>that</span>
  <span m='35040'>you</span> <span m='35100'>should</span> <span m='35280'>know.</span>
  <span m='38850'>And</span> <span m='40920'>I</span> <span m='40980'>thought</span>
  <span m='41130'>I'd</span> <span m='41250'>first</span> <span m='41790'>back</span>
  <span m='42000'>up</span> <span m='42150'>a</span> <span m='42210'>minute</span>
  <span m='43110'>and</span> <span m='45000'>recall</span> <span m='45600'>what</span>
  <span m='45720'>you've</span> <span m='45990'>learned</span> <span m='46200'>so</span>
  <span m='46350'>far.</span> <span m='47050'>So</span> <span m='48000'>we</span>
  <span m='48090'>started</span> <span m='48450'>out</span> <span m='49230'>talking</span>
  <span m='49530'>a</span> <span m='49560'>lot</span> <span m='49710'>about</span>
  <span m='49890'>linear</span> <span m='50160'>algebra</span> <span m='50970'>and,</span>
  <span m='51120'>particularly,</span> <span m='51720'>the</span> <span m='51930'>problems</span>
  <span m='52410'>of</span> <span m='52470'>this</span> <span m='52620'>type</span>
  <span m='54300'>where</span> <span m='54540'>you're</span> <span m='54720'>given</span>
  <span m='55040'>a</span> <span m='55080'>matrix</span> <span m='55500'>and</span>
  <span m='55590'>you're</span> <span m='55650'>given</span> <span m='55860'>a</span>
  <span m='55950'>vector,</span> <span m='56640'>and</span> <span m='56760'>you</span>
  <span m='56850'>want</span> <span m='56970'>to</span> <span m='57030'>figure</span>
  <span m='57180'>out</span> <span m='57240'>what</span> <span m='57330'>the</span>
  <span m='57450'>x</span> <span m='57560'>is</span> <span m='57960'>that</span> <span
  m='58080'>makes</span> <span m='58260'>this</span> <span m='58410'>equation</span>
  <span m='58740'>true.</span> </p><p><span m='60330'>And</span> <span m='60690'>you've</span>
  <span m='60890'>become</span> <span m='61140'>extremely</span> <span m='61560'>familiar</span>
  <span m='62010'>with</span> <span m='62350'>the</span> <span m='62470'>convenient</span>
  <span m='63000'>Matlab</span> <span m='64879'>backslash</span> <span m='65965'>function.</span>
  <span m='66340'>You've</span> <span m='66700'>probably</span> <span m='66930'>used
  this</span> <span m='67200'>a</span> <span m='67230'>lot</span> <span m='67350'>of</span>
  <span m='67410'>times.</span> <span m='68330'>And if you</span> <span m='68520'>remember,</span>
  <span m='69090'>this</span> <span m='69300'>is</span> <span m='69420'>one</span>
  <span m='69540'>of</span> <span m='69600'>the</span> <span m='69720'>only</span>
  <span m='69900'>problems</span> <span m='70320'>where</span> <span m='70530'>we</span>
  <span m='71430'>often</span> <span m='71760'>have</span> <span m='72870'>a</span>
  <span m='72930'>unique</span> <span m='73740'>solution.</span> <span m='74310'>We</span>
  <span m='74460'>know</span> <span m='74640'>a</span> <span m='74670'>solution</span>
  <span m='75090'>exists.</span> <span m='76320'>And</span> <span m='76620'>we</span>
  <span m='76740'>can</span> <span m='76830'>do</span> <span m='76920'>a</span> <span
  m='76950'>finite</span> <span m='77250'>number</span> <span m='77460'>of</span>
  <span m='77520'>steps</span> <span m='78630'>in</span> <span m='78750'>order</span>
  <span m='78900'>to</span> <span m='78960'>get</span> <span m='79080'>the</span>
  <span m='79140'>solution.</span> <span m='80310'>And</span> <span m='81450'>actually,</span>
  <span m='81690'>the</span> <span m='81780'>method</span> <span m='82020'>we</span>
  <span m='82110'>have</span> <span m='82230'>is</span> <span m='82320'>really</span>
  <span m='82500'>good.</span> <span m='82870'>So</span> <span m='82940'>it</span>
  <span m='83040'>almost</span> <span m='83280'>always</span> <span m='83520'>gives
  us</span> <span m='83580'>the</span> <span m='83670'>solution</span> <span m='85272'>and</span>
  <span m='85730'>to</span> <span m='86040'>machine</span> <span m='86370'>accuracy.</span>
  <span m='87580'>So</span> <span m='87630'>this</span> <span m='87780'>is</span>
  <span m='87900'>a</span> <span m='87960'>brilliant</span> <span m='88380'>method.</span>
  <span m='90030'>And</span> <span m='90210'>so</span> <span m='90540'>everything</span>
  <span m='90830'>is</span> <span m='90930'>based</span> <span m='91170'>on</span>
  <span m='91240'>this</span> <span m='91960'>in</span> <span m='92100'>our</span>
  <span m='92220'>whole</span> <span m='92370'>field,</span> <span m='92640'>actually.</span>
  </p><p><span m='95140'>So</span> <span m='95790'>we</span> <span m='95940'>learned</span>
  <span m='96120'>this</span> <span m='96240'>first.</span> <span m='96750'>We</span>
  <span m='96870'>learned</span> <span m='97050'>it</span> <span m='97110'>takes</span>
  <span m='97980'>n</span> <span m='98580'>cubed</span> <span m='100290'>operations</span>
  <span m='103200'>in</span> <span m='103350'>order</span> <span m='103530'>to</span>
  <span m='104800'>get</span> <span m='105030'>the</span> <span m='105120'>solution,</span>
  <span m='105870'>where</span> <span m='106020'>n</span> <span m='106170'>is</span>
  <span m='106320'>the</span> <span m='106410'>size</span> <span m='106680'>of</span>
  <span m='106740'>the</span> <span m='106800'>vectors.</span> <span m='111140'>And</span>
  <span m='113165'>when</span> <span m='113610'>we</span> <span m='113870'>do</span>
  <span m='113980'>the</span> <span m='114100'>solution,</span> <span m='115580'>the</span>
  <span m='115750'>x</span> <span m='116050'>we</span> <span m='116260'>get</span>
  <span m='116590'>for</span> <span m='116740'>backslash,</span> <span m='119470'>invariably,</span>
  <span m='119895'>it</span> <span m='120320'>either</span> <span m='120580'>is</span>
  <span m='120720'>a</span> <span m='120760'>solution,</span> <span m='121690'>solves</span>
  <span m='122070'>this</span> <span m='122200'>equation</span> <span m='123000'>to</span>
  <span m='123220'>machine</span> <span m='123520'>accuracy,</span> <span m='123880'>in</span>
  <span m='123920'>the</span> <span m='124020'>sense</span> <span m='124380'>that
  you</span> <span m='124530'>multiply</span> <span m='124730'>m</span> <span m='124810'>times</span>
  <span m='125110'>x, you</span> <span m='125380'>get</span> <span m='125600'>b</span>
  <span m='126320'>to</span> <span m='126460'>as</span> <span m='126580'>many</span>
  <span m='126760'>digits</span> <span m='127060'>as</span> <span m='127570'>you</span>
  <span m='127630'>can</span> <span m='127790'>read.</span> </p><p><span m='128900'>However,</span>
  <span m='129280'>we</span> <span m='129400'>talked</span> <span m='129580'>about</span>
  <span m='129759'>how</span> <span m='129910'>m</span> <span m='130110'>could</span>
  <span m='130240'>be</span> <span m='130360'>poorly</span> <span m='130780'>conditioned</span>
  <span m='132220'>so</span> <span m='132640'>that</span> <span m='132820'>there</span>
  <span m='132910'>might</span> <span m='133060'>be</span> <span m='133150'>multiple</span>
  <span m='133540'>x's</span> <span m='133870'>that</span> <span m='133990'>would</span>
  <span m='134110'>solve</span> <span m='134530'>this</span> <span m='134690'>equation</span>
  <span m='135140'>to</span> <span m='135250'>machine</span> <span m='135700'>accuracy.</span>
  <span m='136880'>And</span> <span m='137300'>so</span> <span m='137900'>that's</span>
  <span m='138170'>the</span> <span m='138230'>problem</span> <span m='138460'>with</span>
  <span m='138570'>ill</span> <span m='138830'>conditioning.</span> <span m='139800'>So</span>
  <span m='140090'>it's</span> <span m='140240'>not</span> <span m='140450'>that</span>
  <span m='140540'>it</span> <span m='140600'>doesn't</span> <span m='140840'>solve</span>
  <span m='141080'>the</span> <span m='141170'>equation.</span> <span m='141770'>It's</span>
  <span m='142220'>that</span> <span m='142640'>we're</span> <span m='142790'>not</span>
  <span m='142910'>really</span> <span m='143060'>sure</span> <span m='143270'>that's</span>
  <span m='143480'>the</span> <span m='143600'>right</span> <span m='143780'>x.</span>
  <span m='144590'>You</span> <span m='144680'>could</span> <span m='144800'>get</span>
  <span m='144980'>a</span> <span m='145070'>bunch</span> <span m='145280'>of</span>
  <span m='145380'>different</span> <span m='145550'>x's</span> <span m='145820'>that,</span>
  <span m='145910'>basically,</span> <span m='146240'>solve</span> <span m='146490'>it</span>
  <span m='146630'>as</span> <span m='146750'>well</span> <span m='146930'>as</span>
  <span m='147020'>we</span> <span m='147140'>can</span> <span m='147260'>tell.</span>
  <span m='149890'>All</span> <span m='149950'>right,</span> <span m='150130'>so do</span>
  <span m='150500'>you</span> <span m='150580'>guys</span> <span m='150730'>remember</span>
  <span m='150940'>this?</span> </p><p><span m='151986'>All</span> <span m='152360'>right,</span>
  <span m='153100'>and</span> <span m='153310'>so</span> <span m='153430'>that</span>
  <span m='153670'>also</span> <span m='154000'>implies</span> <span m='154450'>that
  if</span> <span m='154540'>you</span> <span m='154600'>make</span> <span m='154750'>a</span>
  <span m='154810'>very</span> <span m='154930'>small</span> <span m='155170'>change</span>
  <span m='155440'>in</span> <span m='155530'>b,</span> <span m='156550'>you</span>
  <span m='156640'>might</span> <span m='156760'>get</span> <span m='156880'>a</span>
  <span m='156940'>gigantic</span> <span m='157300'>change</span> <span m='157540'>in</span>
  <span m='157720'>x.</span> <span m='159520'>Because</span> <span m='159730'>even</span>
  <span m='160240'>for</span> <span m='160390'>one</span> <span m='160570'>b, you</span>
  <span m='160780'>have</span> <span m='160930'>a</span> <span m='160990'>quite</span>
  <span m='161170'>a</span> <span m='161200'>range</span> <span m='161440'>of</span>
  <span m='161500'>x's</span> <span m='161890'>that could</span> <span m='162100'>work,</span>
  <span m='163560'>all</span> <span m='163660'>right.</span> <span m='165930'>Then</span>
  <span m='166890'>we</span> <span m='167160'>try</span> <span m='167370'>to</span>
  <span m='167460'>solve</span> <span m='167670'>problems</span> <span m='168000'>like</span>
  <span m='168150'>this.</span> <span m='171880'>Right,</span> <span m='172710'>systems</span>
  <span m='173230'>of</span> <span m='173640'>equations,</span> <span m='174630'>not</span>
  <span m='174780'>just</span> <span m='174900'>linear</span> <span m='175170'>ones,</span>
  <span m='175470'>but</span> <span m='175570'>nonlinear</span> <span m='175920'>ones</span>
  <span m='176100'>as</span> <span m='176220'>well.</span> <span m='177400'>And</span>
  <span m='178350'>what</span> <span m='178530'>we</span> <span m='178650'>decided</span>
  <span m='179010'>to</span> <span m='179130'>do</span> <span m='179840'>as</span>
  <span m='179940'>one</span> <span m='180080'>of</span> <span m='180140'>our best</span>
  <span m='180380'>methods</span> <span m='180890'>is</span> <span m='181170'>Newton-Raphson,</span>
  <span m='182400'>where</span> <span m='182550'>we</span> <span m='182700'>keep</span>
  <span m='183000'>on</span> <span m='183150'>doing</span> <span m='184260'>j</span>
  <span m='186115'>backslash</span> <span m='186965'>f</span> <span m='188321'>[INAUDIBLE]</span>
  <span m='188792'>negative</span> <span m='189263'>f.</span> </p><p><span m='190680'>Right,</span>
  <span m='191670'>so</span> <span m='192150'>all</span> <span m='192330'>we</span>
  <span m='192420'>did</span> <span m='192600'>in</span> <span m='192720'>this</span>
  <span m='193500'>method,</span> <span m='193750'>a</span> <span m='194010'>lot</span>
  <span m='194220'>of</span> <span m='194280'>times,</span> <span m='195200'>is</span>
  <span m='195530'>we</span> <span m='195660'>just</span> <span m='195930'>kept</span>
  <span m='196170'>on</span> <span m='196460'>calling</span> <span m='196730'>this</span>
  <span m='196900'>method</span> <span m='197580'>over</span> <span m='197730'>and</span>
  <span m='197820'>over</span> <span m='197970'>again.</span> <span m='199410'>All</span>
  <span m='199510'>right,</span> <span m='199580'>so</span> <span m='199760'>this
  took</span> <span m='200120'>order</span> <span m='200370'>of n</span> <span m='200640'>cubes.</span>
  <span m='201520'>This</span> <span m='201670'>thing</span> <span m='201880'>is</span>
  <span m='201950'>going</span> <span m='202070'>to</span> <span m='202130'>take</span>
  <span m='202390'>order</span> <span m='202650'>of</span> <span m='203730'>n,</span>
  <span m='204730'>I</span> <span m='204790'>don't</span> <span m='204880'>know</span>
  <span m='204950'>what</span> <span m='205040'>you</span> <span m='205130'>call it,</span>
  <span m='205490'>steps</span> <span m='205850'>or</span> <span m='206287'>something.</span>
  <span m='207600'>Maybe</span> <span m='207750'>if</span> <span m='207890'>you</span>
  <span m='208100'>guys</span> <span m='208200'>have</span> <span m='208460'>a</span>
  <span m='208520'>word</span> <span m='208730'>for</span> <span m='208850'>it.</span>
  <span m='209130'>What do you</span> <span m='209310'>call</span> <span m='209550'>the</span>
  <span m='210380'>iterations?</span> <span m='211560'>Iterations.</span> <span m='213770'>So</span>
  <span m='214100'>it</span> <span m='214170'>takes</span> <span m='215810'>the</span>
  <span m='215870'>number</span> <span m='216050'>of</span> <span m='216140'>iterations</span>
  <span m='216740'>times</span> <span m='217040'>n</span> <span m='217160'>cubed.</span>
  </p><p><span m='218746'>Now,</span> <span m='219198'>if</span> <span m='219650'>you</span>
  <span m='219740'>really</span> <span m='220040'>can</span> <span m='220250'>make</span>
  <span m='220460'>Newton-Raphson</span> <span m='221000'>work,</span> <span m='222110'>and</span>
  <span m='222200'>you</span> <span m='222350'>have</span> <span m='222470'>a</span>
  <span m='222530'>really</span> <span m='222710'>great</span> <span m='222900'>initial</span>
  <span m='223160'>guess,</span> <span m='223910'>the</span> <span m='224010'>number
  of</span> <span m='224180'>iterations</span> <span m='224660'>is</span> <span m='224750'>really</span>
  <span m='224930'>tiny.</span> <span m='225440'>Because</span> <span m='225800'>Newton-Raphson</span>
  <span m='226310'>is</span> <span m='226370'>such</span> <span m='226580'>a</span>
  <span m='226610'>fantastically</span> <span m='227210'>great</span> <span m='227390'>convergence.</span>
  <span m='228440'>However,</span> <span m='229400'>we're</span> <span m='229520'>usually</span>
  <span m='229770'>not such</span> <span m='230030'>good</span> <span m='230180'>guessers.</span>
  <span m='231410'>And</span> <span m='231650'>so</span> <span m='232550'>it</span>
  <span m='232610'>might</span> <span m='232760'>take</span> <span m='232910'>a</span>
  <span m='232940'>lot</span> <span m='233090'>of</span> <span m='233150'>iterations.</span>
  <span m='233720'>And</span> <span m='233810'>in</span> <span m='233870'>fact,</span>
  <span m='234110'>we</span> <span m='234200'>use</span> <span m='234380'>the</span>
  <span m='234440'>dogleg</span> <span m='234860'>method</span> <span m='236120'>to</span>
  <span m='236210'>solve</span> <span m='236450'>this</span> <span m='237260'>as</span>
  <span m='237350'>we've</span> <span m='237470'>discussed</span> <span m='237860'>about</span>
  <span m='238130'>where</span> <span m='238250'>you</span> <span m='238700'>mix</span>
  <span m='238940'>up</span> <span m='239060'>different</span> <span m='239270'>methods.</span>
  <span m='239840'>And</span> <span m='239930'>you</span> <span m='240020'>have</span>
  <span m='240230'>a</span> <span m='240800'>trust</span> <span m='241070'>region</span>
  <span m='241490'>and</span> <span m='241580'>all</span> <span m='241700'>this</span>
  <span m='241830'>baloney.</span> <span m='242590'>And</span> <span m='242720'>so</span>
  <span m='242975'>it</span> <span m='243230'>might</span> <span m='243410'>actually</span>
  <span m='243620'>be</span> <span m='243740'>quite</span> <span m='243890'>a</span>
  <span m='243920'>lot</span> <span m='244070'>of</span> <span m='244130'>iterations</span>
  <span m='244720'>to</span> <span m='244810'>get</span> <span m='244950'>there.</span>
  </p><p><span m='249170'>And</span> <span m='250490'>then</span> <span m='250640'>we</span>
  <span m='250760'>went</span> <span m='250940'>and</span> <span m='251030'>tried</span>
  <span m='251210'>to</span> <span m='251300'>solve</span> <span m='251570'>this</span>
  <span m='251750'>problem.</span> <span m='259459'>And</span> <span m='259860'>what
  we</span> <span m='259970'>decided</span> <span m='260329'>to</span> <span m='260450'>do</span>
  <span m='261290'>for</span> <span m='261470'>both of</span> <span m='261720'>these</span>
  <span m='261890'>was</span> <span m='262010'>almost do</span> <span m='262280'>the</span>
  <span m='262370'>same</span> <span m='262580'>thing.</span> <span m='263550'>So</span>
  <span m='263600'>I</span> <span m='263650'>said,</span> <span m='263810'>well,</span>
  <span m='267670'>we</span> <span m='267790'>can really</span> <span m='268060'>solve</span>
  <span m='268330'>this</span> <span m='268540'>one</span> <span m='268810'>by</span>
  <span m='269020'>instead</span> <span m='269470'>solving</span> <span m='269830'>this.</span>
  <span m='281510'>Right,</span> <span m='282030'>that's</span> <span m='282240'>really</span>
  <span m='282450'>what</span> <span m='282570'>we</span> <span m='282990'>ended</span>
  <span m='283170'>up</span> <span m='283260'>doing.</span> </p><p><span m='284820'>That's</span>
  <span m='284970'>what</span> <span m='285090'>happens</span> <span m='285420'>inside</span>
  <span m='285735'>fsolve</span> <span m='287160'>is</span> <span m='287310'>it</span>
  <span m='287380'>converts</span> <span m='287820'>the</span> <span m='287910'>problem</span>
  <span m='288270'>of</span> <span m='288380'>finding</span> <span m='289215'>f of
  x</span> <span m='289500'>equals</span> <span m='289980'>0</span> <span m='291300'>into</span>
  <span m='291810'>a</span> <span m='291870'>minimization</span> <span m='292470'>problem</span>
  <span m='293490'>to</span> <span m='293550'>try</span> <span m='293730'>to</span>
  <span m='293820'>make</span> <span m='294360'>the</span> <span m='294680'>norm</span>
  <span m='294890'>of</span> <span m='295060'>f as</span> <span m='295270'>small as</span>
  <span m='295590'>possible.</span> <span m='296040'>Because</span> <span m='296220'>the</span>
  <span m='296340'>answer</span> <span m='296580'>will</span> <span m='296670'>be</span>
  <span m='296790'>when</span> <span m='296970'>the</span> <span m='297060'>norm</span>
  <span m='297240'>is</span> <span m='297310'>zero.</span> <span m='299320'>And</span>
  <span m='299470'>if</span> <span m='299770'>f of x</span> <span m='300130'>equals</span>
  <span m='300420'>0</span> <span m='300550'>has</span> <span m='300700'>a</span>
  <span m='300760'>solution,</span> <span m='301660'>then</span> <span m='302230'>the</span>
  <span m='302350'>global</span> <span m='302710'>minimum</span> <span m='303040'>here</span>
  <span m='304090'>is</span> <span m='304240'>a</span> <span m='304300'>solution,</span>
  <span m='304690'>as</span> <span m='304780'>long</span> <span m='304930'>as</span>
  <span m='304990'>your</span> <span m='305080'>initial</span> <span m='305320'>guess</span>
  <span m='305530'>is</span> <span m='305650'>good</span> <span m='305830'>enough</span>
  <span m='306850'>that</span> <span m='306970'>you're</span> <span m='307180'>in</span>
  <span m='307360'>the</span> <span m='307450'>valley</span> <span m='307960'>that</span>
  <span m='308140'>leads</span> <span m='308500'>to</span> <span m='309790'>the</span>
  <span m='309880'>true</span> <span m='310120'>minimum.</span> <span m='311320'>Then</span>
  <span m='311440'>this</span> <span m='311560'>will</span> <span m='311650'>work.</span>
  <span m='312590'>And</span> <span m='312610'>that's</span> <span m='312760'>actually</span>
  <span m='313000'>what</span> <span m='313420'>fsolve</span> <span m='313510'>does.</span>
  </p><p><span m='314620'>So</span> <span m='316210'>these</span> <span m='316390'>two</span>
  <span m='316540'>guys</span> <span m='316840'>get</span> <span m='317080'>kind</span>
  <span m='317200'>of</span> <span m='317290'>coupled</span> <span m='317620'>together,</span>
  <span m='318490'>the</span> <span m='318580'>minimization</span> <span m='319120'>problem</span>
  <span m='321470'>and</span> <span m='321670'>the</span> <span m='322900'>root-finding</span>
  <span m='323380'>problem,</span> <span m='323930'>or</span> <span m='324080'>the</span>
  <span m='324160'>problem</span> <span m='324410'>of</span> <span m='324670'>solving</span>
  <span m='325030'>systems</span> <span m='325180'>of</span> <span m='325330'>non-linear</span>
  <span m='325690'>equations.</span> <span m='326830'>And</span> <span m='327130'>in</span>
  <span m='327250'>both</span> <span m='327460'>of</span> <span m='327520'>them,</span>
  <span m='328060'>we're</span> <span m='328120'>going</span> <span m='328240'>to</span>
  <span m='328300'>call</span> <span m='328930'>the</span> <span m='329080'>first</span>
  <span m='329440'>method</span> <span m='329740'>a</span> <span m='329770'>million</span>
  <span m='329980'>times.</span> <span m='331400'>OK,</span> <span m='332320'>so</span>
  <span m='332470'>that's</span> <span m='332740'>the</span> <span m='333610'>way</span>
  <span m='333760'>we're</span> <span m='333880'>working</span> <span m='334150'>so</span>
  <span m='334330'>far.</span> <span m='336940'>And</span> <span m='337120'>actually,</span>
  <span m='337390'>when</span> <span m='337510'>you</span> <span m='337660'>do</span>
  <span m='337890'>fmincon,</span> <span m='339220'>which</span> <span m='339370'>was</span>
  <span m='339490'>the</span> <span m='339550'>next</span> <span m='339790'>level,</span>
  <span m='340930'>then</span> <span m='341140'>you</span> <span m='341290'>actually</span>
  <span m='341890'>end</span> <span m='342070'>up</span> <span m='342190'>looking</span>
  <span m='342490'>for</span> <span m='342640'>saddle</span> <span m='342980'>points,</span>
  <span m='343390'>which,</span> <span m='343540'>again,</span> <span m='343750'>we</span>
  <span m='343840'>look</span> <span m='343990'>for</span> <span m='344380'>as</span>
  <span m='344800'>minimizing</span> <span m='346540'>the</span> <span m='347470'>norm</span>
  <span m='347850'>of</span> <span m='347980'>a</span> <span m='348040'>gradient</span>
  <span m='349030'>squared,</span> <span m='350720'>which</span> <span m='350890'>gets
  it</span> <span m='351130'>back</span> <span m='351340'>into</span> <span m='351490'>this</span>
  <span m='351610'>kind</span> <span m='351760'>of</span> <span m='351820'>form.</span>
  <span m='353260'>And</span> <span m='353530'>so</span> <span m='353770'>they're</span>
  <span m='353920'>all</span> <span m='354100'>the</span> <span m='354190'>same</span>
  <span m='354430'>thing.</span> </p><p><span m='357470'>And</span> <span m='359080'>you</span>
  <span m='359260'>can,</span> <span m='360010'>again,</span> <span m='360340'>work</span>
  <span m='360580'>out</span> <span m='360790'>estimates</span> <span m='361270'>of</span>
  <span m='361390'>how</span> <span m='361600'>much</span> <span m='361930'>effort</span>
  <span m='362200'>it</span> <span m='362260'>takes.</span> <span m='363160'>And</span>
  <span m='363280'>it's</span> <span m='363390'>something</span> <span m='363820'>times</span>
  <span m='364150'>n</span> <span m='364300'>cubed,</span> <span m='365860'>Typically,</span>
  <span m='366430'>if</span> <span m='367510'>most</span> <span m='367750'>your</span>
  <span m='367840'>work</span> <span m='368080'>is</span> <span m='368350'>this.</span>
  <span m='369500'>Now,</span> <span m='369820'>I</span> <span m='370150'>should</span>
  <span m='370330'>make</span> <span m='370480'>a</span> <span m='370540'>comment</span>
  <span m='370870'>that,</span> <span m='371020'>in</span> <span m='371140'>practice,</span>
  <span m='372730'>that's</span> <span m='372880'>not</span> <span m='373000'>always</span>
  <span m='373180'>true.</span> <span m='374060'>So</span> <span m='374200'>in</span>
  <span m='374260'>practice,</span> <span m='374650'>sometimes,</span> <span m='376090'>although</span>
  <span m='376510'>the</span> <span m='376690'>highest</span> <span m='377080'>order</span>
  <span m='377260'>term</span> <span m='377320'>is n</span> <span m='377680'>cubed,</span>
  <span m='379310'>the</span> <span m='379500'>linear</span> <span m='379770'>algebra</span>
  <span m='380040'>programs</span> <span m='380450'>that</span> <span m='380520'>do</span>
  <span m='380640'>this</span> <span m='380820'>are</span> <span m='380880'>so</span>
  <span m='381150'>great</span> <span m='382110'>that</span> <span m='382230'>the</span>
  <span m='382330'>prefactor</span> <span m='382800'>is</span> <span m='382890'>tiny.</span>
  </p><p><span m='384370'>So</span> <span m='385530'>in</span> <span m='385650'>order</span>
  <span m='385860'>to</span> <span m='386040'>get</span> <span m='386220'>the</span>
  <span m='386340'>limit</span> <span m='386610'>where</span> <span m='386910'>the</span>
  <span m='387060'>n cubed</span> <span m='387430'>term</span> <span m='387660'>was</span>
  <span m='387780'>actually</span> <span m='387990'>dominate</span> <span m='388460'>the</span>
  <span m='388580'>CPU</span> <span m='388980'>time,</span> <span m='389280'>you</span>
  <span m='389390'>had</span> <span m='389520'>to</span> <span m='389580'>have</span>
  <span m='389670'>a</span> <span m='389700'>gigantic</span> <span m='390200'>n.</span>
  <span m='391230'>And</span> <span m='391410'>in</span> <span m='391530'>fact,</span>
  <span m='392380'>the</span> <span m='392480'>limit,</span> <span m='392700'>it's</span>
  <span m='392880'>often</span> <span m='393780'>the</span> <span m='393930'>effort</span>
  <span m='394170'>to</span> <span m='394230'>construct</span> <span m='394590'>the</span>
  <span m='394680'>matrix</span> <span m='395350'>j.</span> <span m='395770'>And so</span>
  <span m='395930'>it</span> <span m='395990'>really</span> <span m='396210'>goes</span>
  <span m='396500'>as n</span> <span m='396660'>squared.</span> <span m='397920'>So</span>
  <span m='398130'>although</span> <span m='398460'>this</span> <span m='398610'>nominally</span>
  <span m='399040'>is</span> <span m='399180'>like</span> <span m='399360'>n</span>
  <span m='399490'>cubed,</span> <span m='400350'>in</span> <span m='400440'>practice,</span>
  <span m='400920'>a</span> <span m='400950'>lot</span> <span m='401070'>of</span>
  <span m='401130'>times,</span> <span m='401380'>it's</span> <span m='401520'>n</span>
  <span m='401650'>squared.</span> <span m='404610'>And</span> <span m='404660'>I</span>
  <span m='404790'>say it</span> <span m='405000'>for</span> <span m='405120'>these</span>
  <span m='405240'>other</span> <span m='405360'>methods.</span> </p><p><span m='406680'>And</span>
  <span m='406860'>then</span> <span m='406980'>a</span> <span m='407040'>lot</span>
  <span m='407190'>of</span> <span m='407250'>them</span> <span m='408000'>get</span>
  <span m='408150'>into</span> <span m='408360'>how good</span> <span m='408540'>the</span>
  <span m='408690'>initial</span> <span m='408990'>guesses</span> <span m='409320'>are.</span>
  <span m='409620'>Because</span> <span m='409920'>the</span> <span m='410010'>number</span>
  <span m='410250'>of</span> <span m='410340'>iterations</span> <span m='410850'>can</span>
  <span m='412180'>get</span> <span m='412470'>crazy.</span> <span m='413670'>And</span>
  <span m='413820'>in</span> <span m='413880'>fact,</span> <span m='414090'>maybe,</span>
  <span m='414310'>it never</span> <span m='414540'>converges</span> <span m='415050'>if</span>
  <span m='415140'>your</span> <span m='415290'>initial</span> <span m='415560'>guess</span>
  <span m='415690'>is</span> <span m='415830'>bad.</span> <span m='416820'>So</span>
  <span m='416970'>that</span> <span m='417090'>can</span> <span m='417210'>be</span>
  <span m='417300'>a</span> <span m='417330'>really</span> <span m='417540'>critical</span>
  <span m='417870'>thing.</span> <span m='419050'>[INAUDIBLE]</span> <span m='419230'>is</span>
  <span m='419340'>better.</span> <span m='419820'>Because</span> <span m='419970'>you</span>
  <span m='420060'>can't</span> <span m='420270'>change</span> <span m='420570'>n</span>
  <span m='421170'>I</span> <span m='421230'>mean,</span> <span m='421380'>how</span>
  <span m='421450'>many</span> <span m='421610'>unknowns</span> <span m='421860'>you've</span>
  <span m='421950'>got</span> <span m='422100'>is</span> <span m='422180'>how many</span>
  <span m='422440'>unknowns</span> <span m='422610'>you've</span> <span m='422670'>got.</span>
  <span m='424470'>But</span> <span m='424620'>you</span> <span m='424740'>can</span>
  <span m='424950'>change</span> <span m='425400'>the</span> <span m='425470'>number</span>
  <span m='425640'>iterations</span> <span m='426120'>by,</span> <span m='426310'>say,</span>
  <span m='426510'>more</span> <span m='426690'>clever</span> <span m='426990'>initial</span>
  <span m='427260'>guessing.</span> <span m='428410'>And</span> <span m='428500'>that</span>
  <span m='428610'>was</span> <span m='428740'>the</span> <span m='428820'>whole</span>
  <span m='429000'>concept</span> <span m='429450'>about</span> <span m='429780'>continuation</span>
  <span m='430840'>and</span> <span m='431010'>homotopy</span> <span m='431550'>and</span>
  <span m='431640'>all</span> <span m='431710'>this</span> <span m='431790'>kind</span>
  <span m='431910'>of</span> <span m='431970'>stuff</span> <span m='432720'>was</span>
  <span m='432870'>trying</span> <span m='433110'>to</span> <span m='433230'>help</span>
  <span m='434010'>reduce</span> <span m='434340'>this</span> <span m='434870'>number.</span>
  </p><p><span m='438440'>Last</span> <span m='438710'>time,</span> <span m='439400'>we</span>
  <span m='439520'>talked</span> <span m='439790'>about</span> <span m='440750'>implicitly</span>
  <span m='441320'>solving</span> <span m='441770'>ODEs.</span> <span m='443490'>And</span>
  <span m='443850'>so</span> <span m='444060'>we</span> <span m='444180'>had</span>
  <span m='444360'>an</span> <span m='444510'>update</span> <span m='444720'>formula.</span>
  <span m='446740'>So</span> <span m='446850'>we</span> <span m='446970'>were</span>
  <span m='447060'>solving</span> <span m='447510'>an</span> <span m='447915'>ODE.</span>
  <span m='454890'>The</span> <span m='455210'>initial</span> <span m='455430'>value</span>
  <span m='455700'>problem,</span> <span m='456150'>y</span> <span m='456636'>of--</span>
  <span m='461010'>Right,</span> <span m='461700'>and</span> <span m='463660'>we</span>
  <span m='463740'>said</span> <span m='463920'>that,</span> <span m='464100'>first,</span>
  <span m='464340'>we</span> <span m='464430'>went</span> <span m='464580'>through</span>
  <span m='464880'>the</span> <span m='465200'>explicit</span> <span m='465630'>methods.</span>
  <span m='466440'>And</span> <span m='466650'>they</span> <span m='466740'>were</span>
  <span m='466950'>perfectly</span> <span m='467290'>straightforward</span> <span
  m='467880'>to</span> <span m='468000'>do.</span> <span m='468900'>And</span> <span
  m='469280'>you</span> <span m='469350'>don't</span> <span m='469530'>have</span>
  <span m='469650'>to</span> <span m='469740'>solve</span> <span m='470070'>any</span>
  <span m='470160'>systems</span> <span m='470490'>of</span> <span m='470610'>nonlinear</span>
  <span m='470770'>equations</span> <span m='471270'>to</span> <span m='471330'>do</span>
  <span m='471450'>them.</span> <span m='472020'>And</span> <span m='472140'>so</span>
  <span m='472230'>that</span> <span m='472350'>was</span> <span m='472500'>great.</span>
  </p><p><span m='473500'>But</span> <span m='473550'>then</span> <span m='473670'>we</span>
  <span m='473760'>pointed</span> <span m='474060'>out</span> <span m='474210'>that,</span>
  <span m='474300'>a</span> <span m='474330'>lot</span> <span m='474480'>of</span>
  <span m='474540'>times,</span> <span m='474780'>they're</span> <span m='474840'>numerically</span>
  <span m='475260'>unstable.</span> <span m='476980'>And</span> <span m='477060'>so</span>
  <span m='477450'>then</span> <span m='477630'>you</span> <span m='477960'>have</span>
  <span m='478200'>to</span> <span m='479300'>instead</span> <span m='479490'>use</span>
  <span m='479670'>implicit</span> <span m='480120'>methods.</span> <span m='481050'>But</span>
  <span m='481230'>the</span> <span m='481320'>implicit</span> <span m='481950'>methods</span>
  <span m='483210'>generally</span> <span m='483480'>work</span> <span m='483630'>this</span>
  <span m='483870'>way.</span> <span m='484070'>They</span> <span m='484220'>have</span>
  <span m='484350'>your new</span> <span m='484650'>value</span> <span m='484990'>of
  y.</span> <span m='485210'>What you're</span> <span m='485310'>trying</span> <span
  m='485490'>to</span> <span m='485550'>compute</span> <span m='486720'>is</span>
  <span m='486960'>your</span> <span m='487110'>current</span> <span m='487410'>value</span>
  <span m='487740'>of</span> <span m='487790'>y</span> <span m='489660'>plus</span>
  <span m='490850'>delta</span> <span m='491100'>t</span> <span m='492120'>sums</span>
  <span m='492380'>g.</span> <span m='493930'>It</span> <span m='494310'>depends</span>
  <span m='494630'>on</span> <span m='494680'>the</span> <span m='494730'>size</span>
  <span m='495060'>of</span> <span m='495120'>delta</span> <span m='495390'>t</span>
  <span m='495540'>and</span> <span m='497210'>y</span> <span m='497420'>new.</span>
  <span m='498305'>Maybe</span> <span m='498640'>y</span> <span m='498830'>old</span>
  <span m='499020'>also.</span> </p><p><span m='504000'>And</span> <span m='504090'>these</span>
  <span m='504270'>g's</span> <span m='504510'>are</span> <span m='504600'>things</span>
  <span m='504840'>like</span> <span m='505110'>the</span> <span m='505320'>Crank-Nicolson,</span>
  <span m='506670'>which</span> <span m='506870'>you're</span> <span m='506940'>going</span>
  <span m='507060'>to</span> <span m='507120'>work</span> <span m='507330'>on in</span>
  <span m='507520'>the</span> <span m='507690'>homework,</span> <span m='508590'>and</span>
  <span m='508720'>we</span> <span m='508960'>show it</span> <span m='509120'>in</span>
  <span m='509220'>class</span> <span m='509460'>too.</span> <span m='511690'>And</span>
  <span m='511850'>so</span> <span m='512039'>there's</span> <span m='512190'>different</span>
  <span m='512429'>update</span> <span m='512640'>formulas</span> <span m='513030'>of</span>
  <span m='513080'>people</span> <span m='513280'>suggesting</span> <span m='514020'>how</span>
  <span m='514140'>to</span> <span m='514200'>do</span> <span m='514289'>this.</span>
  <span m='516059'>The</span> <span m='516179'>trick</span> <span m='516450'>of</span>
  <span m='516510'>this</span> <span m='516720'>is</span> <span m='516840'>that</span>
  <span m='516990'>the</span> <span m='517110'>y</span> <span m='517289'>new</span>
  <span m='517460'>is</span> <span m='517590'>inside</span> <span m='517980'>the</span>
  <span m='518070'>function.</span> <span m='519870'>So</span> <span m='520220'>therefore,</span>
  <span m='520799'>this</span> <span m='520909'>is</span> <span m='521030'>really</span>
  <span m='523309'>another</span> <span m='525110'>problem</span> <span m='525470'>like</span>
  <span m='525620'>we</span> <span m='525740'>had</span> <span m='525860'>before.</span>
  <span m='528160'>You</span> <span m='528230'>can</span> <span m='528320'>really</span>
  <span m='528540'>rewrite</span> <span m='528980'>this</span> <span m='529520'>that</span>
  <span m='529670'>way</span> <span m='529820'>by</span> <span m='529970'>just</span>
  <span m='530120'>putting</span> <span m='530300'>this</span> <span m='530480'>on</span>
  <span m='530550'>the</span> <span m='530630'>one</span> <span m='530760'>side.</span>
  <span m='531860'>Put</span> <span m='531980'>them all</span> <span m='532070'>on</span>
  <span m='532160'>one</span> <span m='532340'>side</span> <span m='532600'>of</span>
  <span m='532700'>zero.</span> <span m='533690'>And</span> <span m='533780'>now,</span>
  <span m='533870'>I'm</span> <span m='533930'>trying</span> <span m='534080'>to</span>
  <span m='534140'>figure</span> <span m='534320'>out</span> <span m='534410'>what</span>
  <span m='534620'>y new</span> <span m='534860'>is.</span> <span m='535455'>And I'm</span>
  <span m='535820'>going</span> <span m='535950'>to</span> <span m='536010'>solve</span>
  <span m='536300'>that</span> <span m='537140'>using</span> <span m='537350'>this</span>
  <span m='537530'>method.</span> <span m='538350'>And</span> <span m='538550'>I'm
  going to</span> <span m='538640'>solve</span> <span m='538950'>that</span> <span
  m='539510'>by</span> <span m='539660'>using</span> <span m='539930'>this</span>
  <span m='540080'>method.</span> </p><p><span m='541800'>All</span> <span m='541860'>right,</span>
  <span m='542280'>so</span> <span m='542460'>now,</span> <span m='543360'>how</span>
  <span m='543510'>is the</span> <span m='543660'>scaling</span> <span m='544110'>going</span>
  <span m='544260'>to</span> <span m='544320'>go?</span> <span m='545960'>At</span>
  <span m='546230'>each</span> <span m='546680'>time</span> <span m='546880'>step,</span>
  <span m='547730'>I</span> <span m='547820'>have</span> <span m='548000'>to</span>
  <span m='548180'>solve</span> <span m='550100'>one</span> <span m='550220'>of</span>
  <span m='550280'>these</span> <span m='550490'>guys.</span> <span m='552140'>How</span>
  <span m='552200'>much</span> <span m='552380'>effort did</span> <span m='552610'>that</span>
  <span m='552990'>take?</span> <span m='555390'>We</span> <span m='555480'>did</span>
  <span m='555600'>that,</span> <span m='555810'>right.</span> <span m='555990'>Here</span>
  <span m='556130'>it is,</span> <span m='556850'>n</span> <span m='557010'>[? after
  ?]</span> <span m='557160'>times</span> <span m='557260'>n</span> <span m='557540'>squared.</span>
  <span m='559020'>And</span> <span m='559230'>then</span> <span m='560130'>how</span>
  <span m='560220'>many</span> <span m='560340'>times</span> <span m='560610'>do I</span>
  <span m='560660'>have</span> <span m='560720'>to</span> <span m='560790'>do</span>
  <span m='560980'>it?</span> </p><p><span m='563894'>AUDIENCE:</span> <span m='564131'>It's</span>
  <span m='564368'>h times</span> <span m='564842'>7</span> <span m='565316'>times</span>
  <span m='565790'>[INAUDIBLE].</span> </p><p><span m='566270'>PROFESSOR:</span> <span
  m='566345'>Right</span> <span m='566420'>it</span> <span m='566660'>depends on</span>
  <span m='566810'>how many</span> <span m='567120'>times</span> <span m='567520'>steps
  I</span> <span m='567580'>have</span> <span m='567880'>[INAUDIBLE]</span> <span
  m='568730'>my delta</span> <span m='569025'>t.</span> <span m='569320'>So</span>
  <span m='569500'>it's</span> <span m='570430'>something</span> <span m='570730'>like</span>
  <span m='571580'>t</span> <span m='571870'>final</span> <span m='573650'>minus</span>
  <span m='574000'>t</span> <span m='574150'>0</span> <span m='574590'>over</span>
  <span m='574810'>delta t.</span> <span m='575230'>That's</span> <span m='575440'>the</span>
  <span m='575500'>number</span> <span m='575710'>of</span> <span m='575770'>times</span>
  <span m='576070'>steps.</span> <span m='576350'>But</span> <span m='576550'>I have</span>
  <span m='576730'>constant</span> <span m='577120'>delta</span> <span m='577270'>t.</span>
  <span m='578230'>Times</span> <span m='580030'>the</span> <span m='580150'>number</span>
  <span m='580300'>of</span> <span m='580360'>iterations</span> <span m='580810'>that</span>
  <span m='580900'>it</span> <span m='580960'>takes</span> <span m='581260'>to</span>
  <span m='582460'>do</span> <span m='582610'>the</span> <span m='582790'>nonlinear</span>
  <span m='583150'>solve</span> <span m='584380'>times</span> <span m='584650'>n</span>
  <span m='584920'>squared,</span> <span m='586570'>which</span> <span m='586720'>is</span>
  <span m='586830'>a</span> <span m='587080'>cost</span> <span m='587470'>of</span>
  <span m='587560'>forming</span> <span m='587930'>the</span> <span m='588060'>Jacobian</span>
  <span m='588460'>matrix.</span> </p><p><span m='590940'>Now,</span> <span m='591500'>this</span>
  <span m='592430'>can</span> <span m='592550'>be</span> <span m='592640'>pretty</span>
  <span m='592850'>large.</span> <span m='593400'>So</span> <span m='593480'>as</span>
  <span m='593570'>we</span> <span m='593630'>talked</span> <span m='593840'>about,</span>
  <span m='594050'>this</span> <span m='594200'>might</span> <span m='594350'>be</span>
  <span m='594490'>as</span> <span m='594590'>big</span> <span m='594840'>10</span>
  <span m='595000'>to</span> <span m='595180'>the</span> <span m='595600'>eighth</span>
  <span m='597000'>in</span> <span m='597380'>a</span> <span m='599130'>bad</span>
  <span m='599460'>case.</span> <span m='600790'>Certainly</span> <span m='601070'>be</span>
  <span m='601160'>less</span> <span m='601310'>than</span> <span m='601400'>10 to
  the</span> <span m='601610'>eighth</span> <span m='601880'>because</span> <span
  m='602030'>otherwise,</span> <span m='602330'>you'll</span> <span m='602390'>have</span>
  <span m='602480'>numerical</span> <span m='602810'>problems.</span> <span m='603180'>Maybe,</span>
  <span m='603350'>it's</span> <span m='603470'>really</span> <span m='603680'>going</span>
  <span m='603830'>to</span> <span m='603890'>be</span> <span m='605260'>10</span>
  <span m='605600'>to</span> <span m='605940'>the sixth</span> <span m='606746'>for</span>
  <span m='607150'>a</span> <span m='607210'>real</span> <span m='607390'>problem.</span>
  <span m='608910'>So</span> <span m='608990'>you</span> <span m='609080'>have</span>
  <span m='609170'>a</span> <span m='609200'>million</span> <span m='609440'>time</span>
  <span m='609720'>steps.</span> <span m='610430'>At</span> <span m='610550'>each</span>
  <span m='610700'>times</span> <span m='610980'>step,</span> <span m='611150'>you</span>
  <span m='611210'>have</span> <span m='611300'>to</span> <span m='611360'>solve</span>
  <span m='612245'>the</span> <span m='612690'>number</span> <span m='612890'>of</span>
  <span m='613150'>iter--</span> <span m='614740'>the</span> <span m='614830'>solve</span>
  <span m='615120'>costs</span> <span m='615410'>this</span> <span m='615560'>much.</span>
  <span m='616310'>Number</span> <span m='616520'>of</span> <span m='616580'>iterations</span>
  <span m='616895'>might</span> <span m='617210'>be</span> <span m='617440'>what?</span>
  <span m='617780'>How</span> <span m='617870'>many</span> <span m='618020'>iterations</span>
  <span m='618440'>do you</span> <span m='618500'>guys</span> <span m='618680'>take</span>
  <span m='619010'>to</span> <span m='619400'>solve</span> <span m='620090'>nonlinear</span>
  <span m='620210'>equations?</span> <span m='622080'>You</span> <span m='622140'>solve</span>
  <span m='622340'>a</span> <span m='622370'>lot</span> <span m='622470'>of</span>
  <span m='622530'>them</span> <span m='622630'>now.</span> <span m='622800'>How</span>
  <span m='622890'>many</span> <span m='623010'>iterations</span> <span m='623390'>does</span>
  <span m='623540'>it</span> <span m='623720'>take?</span> </p><p><span m='626245'>AUDIENCE:</span>
  <span m='626483'>10.</span> </p><p><span m='627680'>PROFESSOR:</span> <span m='627880'>10,</span>
  <span m='628080'>does that</span> <span m='628480'>10 sound</span> <span m='628630'>right?</span>
  </p><p><span m='632258'>AUDIENCE:</span> <span m='632505'>Yeah,</span> <span m='632752'>[INAUDIBLE].</span>
  </p><p><span m='633250'>PROFESSOR:</span> <span m='633310'>You've</span> <span m='633370'>got
  an</span> <span m='633540'>initial guess</span> <span m='633840'>10.</span> <span
  m='635260'>If</span> <span m='635420'>you</span> <span m='635500'>have</span> <span
  m='635590'>a</span> <span m='635650'>medium</span> <span m='635980'>initial</span>
  <span m='636220'>guess,</span> <span m='636400'>maybe</span> <span m='636550'>100.</span>
  <span m='637620'>It</span> <span m='637760'>it's</span> <span m='637990'>more</span>
  <span m='638140'>than</span> <span m='638230'>100,</span> <span m='638500'>you're</span>
  <span m='638620'>not</span> <span m='638770'>going</span> <span m='638890'>to</span>
  <span m='638950'>converge,</span> <span m='639290'>right?</span> </p><p><span m='639470'>AUDIENCE:</span>
  <span m='639677'>Yeah.</span> </p><p><span m='640300'>PROFESSOR:</span> <span m='640450'>Yeah,
  OK.</span> <span m='640980'>So</span> <span m='641680'>this</span> <span m='641860'>is</span>
  <span m='641980'>order of</span> <span m='642220'>10</span> <span m='642400'>maybe.</span>
  <span m='643025'>So</span> <span m='643390'>the</span> <span m='643560'>million</span>
  <span m='644030'>10</span> <span m='644980'>and</span> <span m='645100'>then</span>
  <span m='645230'>n</span> <span m='645330'>squared</span> <span m='645700'>just</span>
  <span m='645880'>depends</span> <span m='646180'>on</span> <span m='646240'>how</span>
  <span m='646330'>big</span> <span m='646420'>your</span> <span m='646540'>problem</span>
  <span m='646870'>is.</span> <span m='647710'>So</span> <span m='649850'>in</span>
  <span m='650050'>my</span> <span m='650230'>group,</span> <span m='650890'>the</span>
  <span m='650980'>problems</span> <span m='651280'>we</span> <span m='651370'>typically</span>
  <span m='651700'>do,</span> <span m='652060'>n</span> <span m='652270'>is</span>
  <span m='652390'>approximately</span> <span m='652920'>200.</span> <span m='654070'>So</span>
  <span m='654190'>this</span> <span m='654330'>is like</span> <span m='654550'>200</span>
  <span m='654880'>squared.</span> <span m='657610'>And</span> <span m='657840'>then</span>
  <span m='657960'>you</span> <span m='658020'>can</span> <span m='658110'>see</span>
  <span m='658290'>that</span> <span m='658410'>the</span> <span m='658500'>number</span>
  <span m='658710'>of</span> <span m='659010'>iterations,</span> <span m='659440'>and</span>
  <span m='660270'>this is</span> <span m='660420'>maybe a</span> <span m='660810'>little
  bit</span> <span m='660900'>overestimated.</span> <span m='661350'>Maybe</span>
  <span m='661500'>I</span> <span m='661600'>can</span> <span m='661710'>get</span>
  <span m='661910'>away with</span> <span m='662120'>10 to</span> <span m='662350'>the
  fifth,</span> <span m='663660'>something</span> <span m='663890'>like</span> <span
  m='664000'>that.</span> <span m='665330'>But</span> <span m='665410'>you</span>
  <span m='665530'>can</span> <span m='665680'>see</span> <span m='665830'>it</span>
  <span m='665920'>starts</span> <span m='666100'>to</span> <span m='666140'>get</span>
  <span m='666280'>pretty</span> <span m='666460'>big.</span> </p><p><span m='668350'>But</span>
  <span m='668530'>for</span> <span m='668650'>writing</span> <span m='669100'>it,</span>
  <span m='669340'>as</span> <span m='670120'>you</span> <span m='670240'>guys are</span>
  <span m='670420'>writing</span> <span m='670660'>software,</span> <span m='671980'>it's</span>
  <span m='672130'>not</span> <span m='672280'>that</span> <span m='672610'>big</span>
  <span m='672760'>a</span> <span m='672820'>deal.</span> <span m='673090'>So</span>
  <span m='673180'>I</span> <span m='673270'>can</span> <span m='673420'>assign</span>
  <span m='673720'>it</span> <span m='673810'>as</span> <span m='674110'>part</span>
  <span m='674350'>1</span> <span m='674590'>of</span> <span m='674710'>a</span> <span
  m='675430'>three-part</span> <span m='675820'>homework</span> <span m='676060'>problem.</span>
  <span m='677180'>It's</span> <span m='677360'>the</span> <span m='677410'>right</span>
  <span m='677690'>ODE</span> <span m='677910'>solver.</span> <span m='678270'>It</span>
  <span m='678580'>solves</span> <span m='678970'>implicit</span> <span m='679300'>equations.</span>
  <span m='680560'>And</span> <span m='680680'>you</span> <span m='680740'>can</span>
  <span m='680890'>write</span> <span m='681070'>it.</span> <span m='681220'>And</span>
  <span m='681310'>the</span> <span m='681400'>reason you</span> <span m='681670'>can</span>
  <span m='681940'>is</span> <span m='682150'>because</span> <span m='682420'>you've</span>
  <span m='682560'>already</span> <span m='682870'>written</span> <span m='684460'>methods</span>
  <span m='684820'>that</span> <span m='684970'>solve</span> <span m='685090'>this.</span>
  <span m='685330'>Actually,</span> <span m='685870'>Matlab</span> <span m='686140'>did</span>
  <span m='686260'>it</span> <span m='686320'>for</span> <span m='686500'>you.</span>
  <span m='686620'>But</span> <span m='686710'>you</span> <span m='686800'>write it</span>
  <span m='687010'>yourself. I</span> <span m='687440'>assigned</span> <span m='687700'>to</span>
  <span m='687790'>the</span> <span m='687880'>[? 10:10 ?]</span> <span m='688210'>students.</span>
  <span m='689380'>So</span> <span m='689590'>you</span> <span m='689710'>write</span>
  <span m='690920'>the</span> <span m='691220'>[? backsub ?]</span> <span m='692260'>solution</span>
  <span m='692890'>to</span> <span m='692980'>solve</span> <span m='693220'>the</span>
  <span m='693590'>equations.</span> </p><p><span m='694780'>And</span> <span m='696040'>we</span>
  <span m='696430'>we've</span> <span m='696740'>already</span> <span m='696890'>wrestled</span>
  <span m='697210'>this.</span> <span m='698340'>And</span> <span m='699010'>I</span>
  <span m='699070'>think</span> <span m='699220'>you</span> <span m='699310'>guys</span>
  <span m='699500'>wrote one of</span> <span m='699720'>these</span> <span m='700020'>yourself.</span>
  <span m='700900'>And</span> <span m='701020'>also,</span> <span m='701290'>we</span>
  <span m='701380'>can use</span> <span m='701680'>fsolve,</span> <span m='702020'>which</span>
  <span m='702140'>is</span> <span m='702190'>just</span> <span m='702370'>another</span>
  <span m='702820'>little</span> <span m='703000'>bit</span> <span m='703040'>better</span>
  <span m='703240'>implementation</span> <span m='703510'>of</span> <span m='703780'>the</span>
  <span m='703840'>same</span> <span m='704020'>thing.</span> <span m='705040'>And</span>
  <span m='705190'>then</span> <span m='706570'>now,</span> <span m='706750'>you</span>
  <span m='706900'>write</span> <span m='707110'>your</span> <span m='707590'>next</span>
  <span m='707800'>level.</span> <span m='709000'>So</span> <span m='709090'>you</span>
  <span m='709150'>can</span> <span m='709240'>see</span> <span m='709360'>you're</span>
  <span m='709450'>doing</span> <span m='709850'>a</span> <span m='709930'>composite</span>
  <span m='710560'>process,</span> <span m='711070'>where</span> <span m='712180'>you're</span>
  <span m='712300'>doing</span> <span m='712540'>something</span> <span m='713670'>at</span>
  <span m='713770'>the</span> <span m='713860'>top</span> <span m='714100'>level.</span>
  <span m='714550'>It's</span> <span m='714640'>calling</span> <span m='714970'>something</span>
  <span m='715230'>at</span> <span m='715270'>a</span> <span m='715290'>lower</span>
  <span m='715570'>level.</span> <span m='715900'>That's</span> <span m='716080'>calling</span>
  <span m='716290'>something</span> <span m='716510'>at a</span> <span m='716580'>lower</span>
  <span m='716860'>level.</span> </p><p><span m='717850'>And</span> <span m='718000'>then</span>
  <span m='718150'>what</span> <span m='718240'>you</span> <span m='718330'>really</span>
  <span m='718510'>have</span> <span m='718600'>to</span> <span m='718690'>be</span>
  <span m='718840'>concerned</span> <span m='719200'>about</span> <span m='719380'>if</span>
  <span m='719470'>you're</span> <span m='719560'>worried</span> <span m='719740'>about</span>
  <span m='719980'>CPU</span> <span m='720250'>time</span> <span m='720520'>or</span>
  <span m='720580'>whether</span> <span m='720790'>the</span> <span m='720920'>thing</span>
  <span m='721030'>is</span> <span m='721150'>going</span> <span m='721270'>to</span>
  <span m='721330'>solve</span> <span m='722050'>before</span> <span m='722290'>the</span>
  <span m='722350'>homework</span> <span m='722620'>is</span> <span m='722710'>due,</span>
  <span m='723390'>is</span> <span m='725590'>how</span> <span m='726220'>big</span>
  <span m='726400'>does</span> <span m='726520'>this</span> <span m='726670'>get.</span>
  <span m='727570'>How</span> <span m='727660'>many</span> <span m='727810'>operations</span>
  <span m='728260'>are</span> <span m='728320'>you</span> <span m='728420'>really</span>
  <span m='728560'>asking</span> <span m='728770'>the</span> <span m='728830'>computer</span>
  <span m='729100'>to</span> <span m='729190'>do?</span> <span m='729780'>Now,</span>
  <span m='730000'>remember</span> <span m='730360'>the</span> <span m='730450'>computer</span>
  <span m='730690'>is</span> <span m='730840'>fast.</span> <span m='731980'>Right,</span>
  <span m='732340'>so</span> <span m='732490'>it</span> <span m='732580'>can</span>
  <span m='732700'>do</span> <span m='732820'>a</span> <span m='732880'>gigahertz</span>
  <span m='733330'>or</span> <span m='733390'>something.</span> <span m='733690'>So
  you can do</span> <span m='734020'>like</span> <span m='734260'>10</span> <span
  m='734740'>to</span> <span m='734800'>the</span> <span m='734920'>eighth</span>
  <span m='735320'>somethings</span> <span m='735850'>per</span> <span m='735970'>second.</span>
  </p><p><span m='739320'>And</span> <span m='739670'>what</span> <span m='739910'>should
  I</span> <span m='740000'>say</span> <span m='740190'>about</span> <span m='740390'>this?</span>
  <span m='741050'>I</span> <span m='741500'>have</span> <span m='741680'>not</span>
  <span m='741850'>included,</span> <span m='742220'>but I</span> <span m='742370'>should</span>
  <span m='743630'>that</span> <span m='745830'>it's--</span> <span m='747290'>well,</span>
  <span m='748480'>I'm</span> <span m='748600'>assuming</span> <span m='748930'>here</span>
  <span m='749350'>that</span> <span m='749800'>the</span> <span m='749890'>function</span>
  <span m='750160'>evaluation</span> <span m='750415'>is</span> <span m='750670'>sort</span>
  <span m='750820'>of</span> <span m='750890'>order</span> <span m='751180'>n</span>
  <span m='752210'>of</span> <span m='752380'>how</span> <span m='752440'>many</span>
  <span m='752590'>variables</span> <span m='752990'>they</span> <span m='753120'>have.</span>
  <span m='754080'>OK,</span> <span m='754460'>sometimes,</span> <span m='755260'>function</span>
  <span m='755530'>evaluations</span> <span m='755980'>are</span> <span m='756070'>much</span>
  <span m='756430'>more</span> <span m='756580'>difficult</span> <span m='756880'>than</span>
  <span m='757000'>that,</span> <span m='758380'>primarily</span> <span m='759010'>because,</span>
  <span m='759310'>sometimes,</span> <span m='759790'>they're</span> <span m='759910'>actually</span>
  <span m='760140'>including</span> <span m='760510'>further</span> <span m='760840'>nested</span>
  <span m='761140'>stuff</span> <span m='761380'>inside.</span> <span m='762550'>So</span>
  <span m='762700'>your</span> <span m='762880'>f</span> <span m='763060'>is</span>
  <span m='763180'>actually</span> <span m='763420'>coming</span> <span m='763600'>from</span>
  <span m='763750'>some</span> <span m='763900'>really</span> <span m='764050'>complicated</span>
  <span m='764500'>calculation</span> <span m='765220'>itself.</span> <span m='766090'>And</span>
  <span m='766180'>then</span> <span m='766760'>you</span> <span m='766960'>have</span>
  <span m='767210'>another</span> <span m='767320'>big</span> <span m='767500'>giant</span>
  <span m='767800'>factor</span> <span m='768190'>of</span> <span m='768790'>how</span>
  <span m='768910'>much</span> <span m='769090'>it</span> <span m='769150'>costs</span>
  <span m='769360'>to</span> <span m='769420'>do</span> <span m='769600'>f.</span>
  <span m='770971'>But on</span> <span m='771430'>this</span> <span m='772010'>right</span>
  <span m='772170'>here,</span> <span m='772480'>I'm just</span> <span m='772610'>assuming
  it</span> <span m='772810'>goes</span> <span m='773030'>as</span> <span m='773140'>n.</span>
  </p><p><span m='777900'>So</span> <span m='778760'>actually,</span> <span m='779000'>let's</span>
  <span m='779150'>just</span> <span m='779250'>multiply</span> <span m='779400'>this</span>
  <span m='779530'>out.</span> <span m='779680'>So</span> <span m='779880'>this</span>
  <span m='780030'>is</span> <span m='780150'>what,</span> <span m='780270'>10</span>
  <span m='780450'>to</span> <span m='780510'>the</span> <span m='780630'>fourth,</span>
  <span m='781460'>10</span> <span m='781730'>to the</span> <span m='782100'>10th.</span>
  <span m='782330'>So this</span> <span m='782520'>is</span> <span m='782610'>10</span>
  <span m='782790'>to</span> <span m='782880'>the 10th.</span> <span m='784320'>10</span>
  <span m='784580'>to the</span> <span m='784650'>10th</span> <span m='784920'>kind</span>
  <span m='785130'>of</span> <span m='786150'>flops.</span> <span m='788550'>But</span>
  <span m='788730'>your</span> <span m='788850'>computer</span> <span m='789210'>does</span>
  <span m='791100'>4 times</span> <span m='791330'>10 to</span> <span m='791670'>the</span>
  <span m='791760'>ninth</span> <span m='792060'>per</span> <span m='792210'>second.</span>
  <span m='792630'>Is</span> <span m='792980'>that right?</span> <span m='794231'>Is
  that</span> <span m='794650'>[? what they ?]</span> <span m='794800'>told</span>
  <span m='794880'>us,</span> <span m='795170'>four</span> <span m='795330'>gigahertz?</span>
  <span m='796240'>Yeah,</span> <span m='797080'>so</span> <span m='797380'>is</span>
  <span m='797480'>this</span> <span m='797620'>really</span> <span m='797770'>not</span>
  <span m='797920'>bad</span> <span m='798130'>with</span> <span m='798220'>just</span>
  <span m='798370'>a</span> <span m='798430'>few</span> <span m='798550'>seconds</span>
  <span m='799570'>on</span> <span m='799690'>your</span> <span m='799760'>computer.</span>
  <span m='800500'>So</span> <span m='800880'>that's</span> <span m='801130'>why</span>
  <span m='801370'>you</span> <span m='801490'>can</span> <span m='801580'>do</span>
  <span m='801670'>these</span> <span m='801790'>homework</span> <span m='802060'>problems,</span>
  <span m='802570'>and</span> <span m='802670'>you</span> <span m='802750'>still</span>
  <span m='802900'>get them</span> <span m='803050'>done.</span> <span m='803960'>And</span>
  <span m='803990'>if</span> <span m='804110'>you</span> <span m='804190'>have</span>
  <span m='804310'>even</span> <span m='804520'>[? porous ?]</span> <span m='804760'>limitations,</span>
  <span m='805330'>it</span> <span m='805390'>takes</span> <span m='805570'>1,000</span>
  <span m='805900'>times</span> <span m='806080'>longer.</span> <span m='806440'>Still,</span>
  <span m='806950'>1,000</span> <span m='807190'>[INAUDIBLE]</span> <span m='807620'>take</span>
  <span m='807730'>20</span> <span m='807910'>minutes</span> <span m='808180'>on</span>
  <span m='808240'>your</span> <span m='808300'>computer.</span> </p><p><span m='811340'>So</span>
  <span m='811550'>you're</span> <span m='811670'>OK,</span> <span m='811940'>but</span>
  <span m='812060'>you</span> <span m='812140'>can</span> <span m='812210'>see</span>
  <span m='812330'>we're</span> <span m='812450'>starting</span> <span m='812660'>to</span>
  <span m='812720'>get</span> <span m='813590'>up</span> <span m='813740'>there.</span>
  <span m='814640'>And</span> <span m='814820'>it's</span> <span m='814970'>not</span>
  <span m='815120'>that</span> <span m='815210'>hard</span> <span m='815390'>to</span>
  <span m='815450'>really</span> <span m='815690'>make</span> <span m='815900'>it</span>
  <span m='816190'>a</span> <span m='816410'>big</span> <span m='816560'>problem</span>
  <span m='817580'>if</span> <span m='817700'>you</span> <span m='817760'>do</span>
  <span m='817850'>something</span> <span m='818930'>wrong.</span> <span m='824010'>And</span>
  <span m='824240'>just</span> <span m='824390'>a</span> <span m='824480'>notation</span>
  <span m='825140'>thing,</span> <span m='828080'>a</span> <span m='828110'>lot</span>
  <span m='828350'>of</span> <span m='828410'>these</span> <span m='828620'>things</span>
  <span m='828860'>we're</span> <span m='828980'>doing</span> <span m='831740'>are</span>
  <span m='832310'>writing</span> <span m='832640'>software</span> <span m='833180'>that</span>
  <span m='833330'>takes</span> <span m='833630'>as</span> <span m='833750'>input</span>
  <span m='834110'>not</span> <span m='834440'>just</span> <span m='836690'>numbers</span>
  <span m='838220'>or</span> <span m='838370'>vectors.</span> <span m='839960'>So</span>
  <span m='840080'>those</span> <span m='840260'>are</span> <span m='840320'>things</span>
  <span m='840530'>that we</span> <span m='840650'>call</span> <span m='840800'>functions.</span>
  <span m='841680'>Right,</span> <span m='841930'>things</span> <span m='842060'>that</span>
  <span m='842150'>take</span> <span m='842540'>a</span> <span m='842630'>number</span>
  <span m='843020'>of</span> <span m='843140'>vectors and</span> <span m='843560'>input</span>
  <span m='843890'>and</span> <span m='843980'>give</span> <span m='844160'>you,</span>
  <span m='844250'>say,</span> <span m='844430'>a</span> <span m='844460'>function,</span>
  <span m='844760'>a</span> <span m='845060'>number</span> <span m='845570'>of</span>
  <span m='845690'>vectors</span> <span m='846030'>and</span> <span m='846110'>output.</span>
  </p><p><span m='847500'>But</span> <span m='847580'>oftentimes,</span> <span m='848150'>we</span>
  <span m='848270'>actually</span> <span m='848510'>want</span> <span m='848630'>to</span>
  <span m='848690'>take</span> <span m='848930'>the</span> <span m='849050'>names</span>
  <span m='849350'>of</span> <span m='849410'>functions</span> <span m='849860'>as</span>
  <span m='849980'>inputs.</span> <span m='851150'>So</span> <span m='851360'>for</span>
  <span m='851480'>example,</span> <span m='852720'>the</span> <span m='852820'>root-finding</span>
  <span m='853100'>problem,</span> <span m='853880'>it</span> <span m='853970'>takes</span>
  <span m='854180'>as</span> <span m='854320'>input</span> <span m='854590'>what</span>
  <span m='854770'>is</span> <span m='854900'>f.</span> <span m='856330'>Right,</span>
  <span m='856570'>you have</span> <span m='856720'>to</span> <span m='856810'>tell</span>
  <span m='857090'>it</span> <span m='857500'>the</span> <span m='857590'>name</span>
  <span m='857830'>of</span> <span m='857950'>a</span> <span m='858010'>function</span>
  <span m='858730'>for</span> <span m='859220'>fsolve</span> <span m='859570'>to</span>
  <span m='859690'>be</span> <span m='859780'>able</span> <span m='859930'>to</span>
  <span m='860020'>call</span> <span m='860290'>it.</span> <span m='860890'>So</span>
  <span m='861160'>fsolve</span> <span m='861670'>is</span> <span m='862190'>an</span>
  <span m='862450'>object</span> <span m='862900'>that</span> <span m='863020'>takes</span>
  <span m='863260'>as</span> <span m='863410'>input</span> <span m='863830'>the</span>
  <span m='864490'>name</span> <span m='864730'>of</span> <span m='864810'>a</span>
  <span m='864880'>function.</span> <span m='866290'>And</span> <span m='866380'>things</span>
  <span m='866700'>that do that</span> <span m='867010'>are</span> <span m='867070'>called</span>
  <span m='867340'>functionals</span> </p><p><span m='875600'>So</span> <span m='876110'>for</span>
  <span m='876230'>example,</span> <span m='876740'>this</span> <span m='876950'>one</span>
  <span m='877850'>is</span> <span m='880750'>x</span> <span m='881440'>is</span>
  <span m='881650'>equal</span> <span m='881950'>to</span> <span m='883240'>this</span>
  <span m='883460'>root-finding</span> <span m='883870'>functional,</span> <span m='885760'>fsolve.</span>
  <span m='888295'>And</span> <span m='888720'>I'm</span> <span m='888830'>going to</span>
  <span m='889150'>write with</span> <span m='889270'>square</span> <span m='889720'>brackets.</span>
  <span m='890380'>It</span> <span m='890470'>depends</span> <span m='890740'>on</span>
  <span m='890860'>f.</span> <span m='891960'>That's</span> <span m='892110'>it,</span>
  <span m='892270'>right?</span> <span m='892450'>[INAUDIBLE]</span> <span m='892904'>f.</span>
  <span m='895630'>So</span> <span m='895780'>you</span> <span m='895900'>give</span>
  <span m='896100'>it</span> <span m='896290'>the</span> <span m='896410'>function</span>
  <span m='896770'>f.</span> <span m='897550'>And</span> <span m='897940'>if</span>
  <span m='898120'>fsolve's</span> <span m='898420'>good,</span> <span m='898760'>it</span>
  <span m='898860'>should</span> <span m='898960'>be</span> <span m='899060'>able</span>
  <span m='899160'>to</span> <span m='899260'>tell</span> <span m='899380'>you</span>
  <span m='899440'>what</span> <span m='899530'>the</span> <span m='899620'>x is.</span>
  <span m='902080'>Now,</span> <span m='902100'>in</span> <span m='902190'>reality,</span>
  <span m='902520'>we</span> <span m='902640'>help</span> <span m='902820'>it</span>
  <span m='902910'>out.</span> <span m='904450'>So</span> <span m='904600'>we</span>
  <span m='904720'>give</span> <span m='904900'>it</span> <span m='905480'>x</span>
  <span m='905680'>0</span> <span m='906030'>[? 2 ?]</span> <span m='906400'>just</span>
  <span m='906590'>give</span> <span m='906760'>it</span> <span m='906970'>a</span>
  <span m='907400'>better</span> <span m='907600'>chance.</span> </p><p><span m='911690'>I</span>
  <span m='911770'>write</span> <span m='912030'>the</span> <span m='912140'>square</span>
  <span m='912350'>brackets</span> <span m='912660'>just</span> <span m='912810'>indicate</span>
  <span m='913170'>that one</span> <span m='913340'>of</span> <span m='913400'>the</span>
  <span m='913460'>things</span> <span m='913700'>inside</span> <span m='914120'>is</span>
  <span m='914210'>a</span> <span m='914270'>function,</span> <span m='915200'>not</span>
  <span m='915350'>just</span> <span m='915500'>numbers.</span> <span m='918110'>We
  do</span> <span m='918290'>this</span> <span m='918440'>a</span> <span m='918500'>lot.</span>
  <span m='920010'>So</span> <span m='920690'>you</span> <span m='920810'>guys</span>
  <span m='921020'>have</span> <span m='921110'>done</span> <span m='921260'>this</span>
  <span m='922130'>since</span> <span m='922370'>you were</span> <span m='922490'>kids.</span>
  <span m='924050'>So</span> <span m='924320'>derivatives</span> <span m='926290'>Yeah,</span>
  <span m='928310'>ddx</span> <span m='928920'>of</span> <span m='929400'>f.</span>
  <span m='933720'>So</span> <span m='934540'>we</span> <span m='934660'>have,</span>
  <span m='934870'>I don't</span> <span m='935160'>know, for</span> <span m='935530'>example,</span>
  <span m='937306'>grad</span> <span m='937740'>of</span> <span m='937800'>f.</span>
  <span m='941160'>That's</span> <span m='942840'>a</span> <span m='943090'>functional,</span>
  <span m='943860'>the</span> <span m='944000'>grad.</span> <span m='944510'>The</span>
  <span m='944650'>symbol</span> <span m='946140'>means</span> <span m='946390'>the</span>
  <span m='946510'>operator,</span> <span m='947350'>the</span> <span m='947440'>functional,</span>
  <span m='947740'>it</span> <span m='948040'>operates</span> <span m='948340'>on</span>
  <span m='948430'>functions.</span> <span m='949090'>You</span> <span m='949150'>could
  write</span> <span m='949360'>a</span> <span m='949420'>general</span> <span m='949720'>gradient</span>
  <span m='950620'>function</span> <span m='950980'>that</span> <span m='951090'>takes</span>
  <span m='951390'>any</span> <span m='953170'>scalar</span> <span m='953440'>valued</span>
  <span m='953680'>function</span> <span m='954580'>and</span> <span m='954700'>computes</span>
  <span m='954970'>the</span> <span m='955030'>gradients with</span> <span m='955360'>respect</span>
  <span m='955640'>to</span> <span m='955720'>the</span> <span m='955810'>inputs.</span>
  </p><p><span m='958810'>This</span> <span m='959020'>week,</span> <span m='959230'>we</span>
  <span m='959320'>give</span> <span m='959470'>you</span> <span m='959560'>one</span>
  <span m='959750'>that</span> <span m='959960'>computes</span> <span m='960320'>a</span>
  <span m='960500'>Jacobian.</span> <span m='960820'>Give</span> <span m='960960'>it</span>
  <span m='961010'>any</span> <span m='961270'>f</span> <span m='961420'>of</span>
  <span m='961510'>x.</span> <span m='962230'>It</span> <span m='962320'>gives</span>
  <span m='962500'>you</span> <span m='962560'>the</span> <span m='962680'>Jacobian</span>
  <span m='963565'>of f</span> <span m='964000'>with</span> <span m='964090'>respect</span>
  <span m='964350'>to</span> <span m='964590'>x.</span> <span m='965710'>So</span>
  <span m='965860'>that's</span> <span m='966040'>a</span> <span m='966100'>functional.</span>
  <span m='967270'>So</span> <span m='967840'>anyway,</span> <span m='968130'>we</span>
  <span m='968240'>do</span> <span m='968350'>a</span> <span m='968380'>lot</span>
  <span m='968530'>with</span> <span m='968630'>functionals.</span> <span m='969220'>You've</span>
  <span m='969420'>been</span> <span m='969640'>using</span> <span m='969790'>them</span>
  <span m='969910'>all</span> <span m='970000'>the</span> <span m='970060'>time.</span>
  <span m='970500'>I'm</span> <span m='970750'>just</span> <span m='970900'>trying</span>
  <span m='971230'>get</span> <span m='971310'>you to</span> <span m='971510'>think</span>
  <span m='971680'>about</span> <span m='971830'>abstractly.</span> <span m='972730'>And</span>
  <span m='972820'>then</span> <span m='972940'>there's</span> <span m='973060'>a</span>
  <span m='973150'>whole</span> <span m='973360'>math</span> <span m='974440'>about</span>
  <span m='974960'>functionals.</span> <span m='976090'>And</span> <span m='976210'>there's</span>
  <span m='976330'>a</span> <span m='976390'>whole</span> <span m='976510'>thing</span>
  <span m='976690'>called</span> <span m='976840'>calculus</span> <span m='977230'>of</span>
  <span m='977290'>variations.</span> <span m='977910'>It's</span> <span m='978010'>all</span>
  <span m='978130'>about,</span> <span m='978940'>if</span> <span m='979300'>the</span>
  <span m='979390'>objects</span> <span m='979660'>you're</span> <span m='979750'>worrying</span>
  <span m='979960'>about</span> <span m='980080'>are</span> <span m='980140'>functionals,</span>
  <span m='980680'>not</span> <span m='980860'>functions,</span> <span m='982090'>then</span>
  <span m='982210'>you</span> <span m='982300'>have</span> <span m='982420'>another</span>
  <span m='982690'>whole</span> <span m='983350'>bunch</span> <span m='983560'>of</span>
  <span m='983620'>theorems</span> <span m='984130'>and</span> <span m='984610'>stuff</span>
  <span m='984850'>you</span> <span m='984910'>can</span> <span m='985030'>do</span>
  <span m='985090'>with</span> <span m='985180'>that,</span> <span m='986020'>which</span>
  <span m='986200'>you'll</span> <span m='986290'>probably</span> <span m='986530'>end
  up</span> <span m='986630'>doing</span> <span m='986950'>before</span> <span m='987220'>you</span>
  <span m='987280'>get</span> <span m='987370'>out</span> <span m='987430'>of</span>
  <span m='987490'>this</span> <span m='987610'>place.</span> <span m='988570'>But</span>
  <span m='988740'>I'm</span> <span m='988960'>not</span> <span m='989090'>going</span>
  <span m='989240'>to do that</span> <span m='989450'>right</span> <span m='989610'>now.</span>
  </p><p><span m='992740'>I</span> <span m='992980'>would</span> <span m='993130'>comment</span>
  <span m='993550'>that</span> <span m='994360'>one</span> <span m='994660'>kind</span>
  <span m='994810'>of</span> <span m='994880'>functional</span> <span m='995320'>that's</span>
  <span m='995500'>particularly</span> <span m='995920'>important</span> <span m='996220'>to</span>
  <span m='996340'>a</span> <span m='996370'>lot</span> <span m='996520'>of</span>
  <span m='996580'>people</span> <span m='997660'>in</span> <span m='997810'>your</span>
  <span m='997930'>research</span> <span m='1001800'>is</span> <span m='1003030'>the</span>
  <span m='1003840'>fact</span> <span m='1004170'>that</span> <span m='1004560'>the</span>
  <span m='1005040'>energy</span> <span m='1006390'>of</span> <span m='1006750'>any</span>
  <span m='1007170'>molecule</span> <span m='1009120'>is</span> <span m='1009360'>a</span>
  <span m='1009750'>functional</span> <span m='1010380'>of</span> <span m='1010680'>the</span>
  <span m='1010800'>electron</span> <span m='1011190'>density.</span> <span m='1016660'>And</span>
  <span m='1016780'>this</span> <span m='1016960'>is</span> <span m='1017020'>the</span>
  <span m='1017110'>basis</span> <span m='1017380'>of</span> <span m='1017470'>what's</span>
  <span m='1017590'>called</span> <span m='1017710'>density</span> <span m='1018070'>functional</span>
  <span m='1018400'>theory.</span> </p><p><span m='1029160'>And</span> <span m='1029460'>so</span>
  <span m='1029670'>this</span> <span m='1029819'>is</span> <span m='1029910'>why</span>
  <span m='1030210'>a</span> <span m='1030270'>lot</span> <span m='1030420'>of</span>
  <span m='1030480'>people,</span> <span m='1031180'>you</span> <span m='1031530'>and</span>
  <span m='1031670'>many</span> <span m='1031829'>of</span> <span m='1031950'>you</span>
  <span m='1032069'>included,</span> <span m='1032760'>are</span> <span m='1032880'>going</span>
  <span m='1033000'>to</span> <span m='1033060'>end</span> <span m='1033210'>up</span>
  <span m='1033359'>using</span> <span m='1033540'>computer</span> <span m='1033810'>programs</span>
  <span m='1034260'>that are</span> <span m='1034349'>trying</span> <span m='1034530'>to</span>
  <span m='1034619'>find</span> <span m='1035834'>what</span> <span m='1036089'>the</span>
  <span m='1036290'>electron</span> <span m='1036599'>density</span> <span m='1036960'>shape</span>
  <span m='1037289'>is,</span> <span m='1038150'>things</span> <span m='1038369'>like</span>
  <span m='1038460'>molecular</span> <span m='1038849'>orbitals</span> <span m='1039154'>and
  stuff.</span> <span m='1039460'>You've</span> <span m='1039569'>probably</span>
  <span m='1039810'>heard</span> <span m='1039960'>these</span> <span m='1040079'>before.</span>
  <span m='1041490'>And</span> <span m='1041730'>then</span> <span m='1041940'>there's</span>
  <span m='1042089'>the</span> <span m='1042750'>functional</span> <span m='1043095'>that</span>
  <span m='1043440'>gives</span> <span m='1043560'>the</span> <span m='1043650'>energy
  of the</span> <span m='1043950'>molecule.</span> <span m='1044215'>And</span> <span
  m='1044480'>what</span> <span m='1044579'>you</span> <span m='1044640'>care</span>
  <span m='1044790'>about,</span> <span m='1044940'>mostly,</span> <span m='1045210'>is</span>
  <span m='1045329'>energy,</span> <span m='1045730'>because</span> <span m='1045810'>that</span>
  <span m='1045930'>connects</span> <span m='1046319'>to</span> <span m='1047730'>all</span>
  <span m='1047880'>your</span> <span m='1048000'>thermo.</span> <span m='1048510'>You're</span>
  <span m='1048600'>doing</span> <span m='1048780'>[? 1040, ?]</span> <span m='1049200'>it's</span>
  <span m='1049320'>all</span> <span m='1049470'>about</span> <span m='1050160'>the</span>
  <span m='1050220'>energies.</span> <span m='1051870'>And</span> <span m='1051960'>once</span>
  <span m='1052110'>you</span> <span m='1052170'>know</span> <span m='1052260'>all</span>
  <span m='1052380'>the</span> <span m='1052470'>energies,</span> <span m='1052860'>you
  can</span> <span m='1052980'>actually</span> <span m='1053190'>compute</span> <span
  m='1053490'>the</span> <span m='1053580'>entropies</span> <span m='1053880'>and</span>
  <span m='1053970'>all kinds</span> <span m='1054120'>of stuff</span> <span m='1054430'>too.</span>
  </p><p><span m='1055730'>And</span> <span m='1058560'>so</span> <span m='1058710'>this</span>
  <span m='1058900'>is</span> <span m='1059430'>one</span> <span m='1059820'>application
  that's</span> <span m='1060120'>really</span> <span m='1060270'>important.</span>
  <span m='1061120'>It</span> <span m='1061140'>was</span> <span m='1061320'>a</span>
  <span m='1061350'>little</span> <span m='1061530'>surprising</span> <span m='1062130'>this</span>
  <span m='1062310'>was</span> <span m='1062430'>true</span> <span m='1062880'>and</span>
  <span m='1063750'>able</span> <span m='1063890'>to</span> <span m='1064000'>be</span>
  <span m='1064110'>proven</span> <span m='1064350'>to</span> <span m='1064410'>be</span>
  <span m='1064500'>true.</span> <span m='1064900'>And</span> <span m='1065000'>so</span>
  <span m='1065010'>the</span> <span m='1065100'>guy who</span> <span m='1065420'>did</span>
  <span m='1065580'>that</span> <span m='1066360'>got</span> <span m='1066510'>the</span>
  <span m='1066570'>Nobel</span> <span m='1066900'>Prize--</span> <span m='1067200'>his
  name was</span> <span m='1067500'>Cohen--</span> <span m='1067860'>a</span> <span
  m='1068160'>few</span> <span m='1068460'>years</span> <span m='1068690'>ago.</span>
  </p><p><span m='1071540'>Actually,</span> <span m='1071890'>in</span> <span m='1072390'>liquid</span>
  <span m='1072780'>phase</span> <span m='1072960'>stuff,</span> <span m='1073260'>you
  work</span> <span m='1073470'>with</span> <span m='1073560'>Professor</span> <span
  m='1074100'>Blankschtein.</span> <span m='1075180'>They</span> <span m='1075300'>also</span>
  <span m='1075510'>have</span> <span m='1075630'>a</span> <span m='1075690'>version</span>
  <span m='1075960'>of</span> <span m='1076050'>this</span> <span m='1076680'>for</span>
  <span m='1077070'>properties</span> <span m='1077430'>of</span> <span m='1077520'>solution.</span>
  <span m='1078530'>And</span> <span m='1078640'>then</span> <span m='1078750'>where</span>
  <span m='1078870'>it's</span> <span m='1079170'>not</span> <span m='1079290'>the</span>
  <span m='1079350'>electron</span> <span m='1079680'>density,</span> <span m='1079980'>but</span>
  <span m='1080080'>it's</span> <span m='1080160'>actually</span> <span m='1080370'>the</span>
  <span m='1080430'>density</span> <span m='1080880'>of</span> <span m='1081060'>the</span>
  <span m='1081540'>material</span> <span m='1082050'>in</span> <span m='1082140'>the</span>
  <span m='1082650'>solution</span> <span m='1083100'>phase.</span> <span m='1083780'>Maybe</span>
  <span m='1083900'>Professor</span> <span m='1084100'>[? Swan ?]</span> <span m='1084410'>too.</span>
  <span m='1084540'>You</span> <span m='1084620'>guys</span> <span m='1084780'>do</span>
  <span m='1084880'>that?</span> <span m='1085620'>Yeah,</span> <span m='1085800'>so</span>
  <span m='1086250'>if you</span> <span m='1086380'>work</span> <span m='1086600'>with
  Professor</span> <span m='1086820'>[? Swan, ?]</span> <span m='1086990'>you</span>
  <span m='1087090'>might</span> <span m='1087180'>learn</span> <span m='1087330'>about</span>
  <span m='1087480'>that</span> <span m='1087650'>too.</span> </p><p><span m='1088390'>So</span>
  <span m='1088490'>that's</span> <span m='1088560'>one</span> <span m='1088740'>where</span>
  <span m='1088890'>the</span> <span m='1089520'>actual</span> <span m='1089820'>functional</span>
  <span m='1090110'>is</span> <span m='1090330'>like</span> <span m='1090480'>a</span>
  <span m='1090540'>big</span> <span m='1090750'>focus</span> <span m='1091170'>of</span>
  <span m='1091230'>the</span> <span m='1092640'>entire</span> <span m='1092850'>project.</span>
  <span m='1094520'>And</span> <span m='1094620'>the</span> <span m='1094740'>key</span>
  <span m='1094890'>is</span> <span m='1094980'>that</span> <span m='1095070'>this</span>
  <span m='1095250'>is</span> <span m='1095340'>a</span> <span m='1095400'>function.</span>
  <span m='1096110'>The density</span> <span m='1096400'>is</span> <span m='1096600'>a</span>
  <span m='1096630'>function</span> <span m='1096930'>of</span> <span m='1096990'>the</span>
  <span m='1097050'>position.</span> <span m='1098100'>And</span> <span m='1098250'>then</span>
  <span m='1098430'>the</span> <span m='1099000'>functional</span> <span m='1099300'>converts</span>
  <span m='1099580'>that</span> <span m='1099960'>into</span> <span m='1100140'>a</span>
  <span m='1100200'>number.</span> <span m='1106025'>That's</span> <span m='1106460'>all</span>
  <span m='1106730'>page</span> <span m='1106970'>one</span> <span m='1107150'>here.</span>
  </p><p><span m='1109850'>Now,</span> <span m='1110220'>I'm</span> <span m='1110370'>going
  to</span> <span m='1110520'>sort</span> <span m='1110910'>of</span> <span m='1110970'>change</span>
  <span m='1111240'>topics,</span> <span m='1111630'>but it's</span> <span m='1111920'>related.</span>
  <span m='1113280'>It's</span> <span m='1114330'>about</span> <span m='1114570'>the</span>
  <span m='1114690'>connections</span> <span m='1115410'>between</span> <span m='1115950'>numerical</span>
  <span m='1116310'>integration,</span> <span m='1117360'>interpolation,</span> <span
  m='1118200'>and</span> <span m='1118470'>basis</span> <span m='1118860'>functions.</span>
  <span m='1120150'>These</span> <span m='1120270'>things</span> <span m='1120480'>are</span>
  <span m='1120570'>all</span> <span m='1121020'>intimately</span> <span m='1121440'>tied</span>
  <span m='1121650'>up</span> <span m='1121740'>together.</span> <span m='1122010'>So</span>
  <span m='1122160'>I'll try</span> <span m='1122310'>to</span> <span m='1122400'>show</span>
  <span m='1122580'>you.</span> <span m='1123540'>So</span> <span m='1124410'>we</span>
  <span m='1124500'>try</span> <span m='1124650'>to</span> <span m='1124940'>solve</span>
  <span m='1125220'>a</span> <span m='1125310'>numerical</span> <span m='1125760'>integral.</span>
  </p><p><span m='1140320'>And</span> <span m='1140440'>then</span> <span m='1140710'>let's</span>
  <span m='1140920'>look</span> <span m='1141040'>at</span> <span m='1141100'>what</span>
  <span m='1141250'>we're</span> <span m='1141340'>really</span> <span m='1141670'>doing.</span>
  <span m='1143170'>When</span> <span m='1143320'>we're</span> <span m='1143410'>doing</span>
  <span m='1143740'>this,</span> <span m='1144340'>we</span> <span m='1144460'>typically</span>
  <span m='1144970'>only</span> <span m='1145270'>do</span> <span m='1145420'>a</span>
  <span m='1145480'>few</span> <span m='1145810'>function</span> <span m='1146140'>evaluations.</span>
  <span m='1147190'>So</span> <span m='1147370'>we</span> <span m='1147460'>have</span>
  <span m='1147640'>a</span> <span m='1147700'>few</span> <span m='1148180'>points</span>
  <span m='1149050'>where</span> <span m='1149200'>we</span> <span m='1149320'>know</span>
  <span m='1149560'>the</span> <span m='1149680'>numbers</span> <span m='1151050'>f</span>
  <span m='1151450'>of</span> <span m='1151580'>tn.</span> <span m='1152260'>We've</span>
  <span m='1152410'>picked</span> <span m='1153190'>a</span> <span m='1153250'>few</span>
  <span m='1153490'>t's.</span> <span m='1154570'>We</span> <span m='1154700'>evaluated</span>
  <span m='1154965'>f.</span> <span m='1156190'>And</span> <span m='1156370'>from</span>
  <span m='1156670'>those</span> <span m='1156940'>few</span> <span m='1157330'>points,</span>
  <span m='1158710'>that</span> <span m='1158860'>small</span> <span m='1159100'>number
  of</span> <span m='1159380'>function</span> <span m='1159710'>evaluations,</span>
  <span m='1160150'>we</span> <span m='1160240'>want</span> <span m='1160360'>to</span>
  <span m='1160420'>get</span> <span m='1160570'>a</span> <span m='1160600'>good</span>
  <span m='1160780'>estimate</span> <span m='1161200'>of</span> <span m='1161320'>this</span>
  <span m='1161440'>whole</span> <span m='1161640'>integral.</span> </p><p><span m='1163000'>Now,</span>
  <span m='1163180'>it's</span> <span m='1163270'>a</span> <span m='1163330'>little</span>
  <span m='1163540'>goofy,</span> <span m='1163930'>actually,</span> <span m='1164170'>if</span>
  <span m='1164230'>you</span> <span m='1164290'>think</span> <span m='1164470'>about</span>
  <span m='1164540'>what</span> <span m='1164620'>we're</span> <span m='1164740'>trying</span>
  <span m='1164950'>to</span> <span m='1165040'>do.</span> <span m='1165970'>So</span>
  <span m='1166160'>suppose</span> <span m='1166390'>you're</span> <span m='1166480'>trying</span>
  <span m='1166630'>to</span> <span m='1166690'>do</span> <span m='1166780'>an</span>
  <span m='1166870'>integral</span> <span m='1167200'>from</span> <span m='1167350'>negative</span>
  <span m='1167680'>1</span> <span m='1167890'>to</span> <span m='1167980'>1.</span>
  <span m='1169180'>We</span> <span m='1169270'>have</span> <span m='1169390'>some</span>
  <span m='1169540'>function</span> <span m='1169930'>that has</span> <span m='1170110'>a</span>
  <span m='1170230'>point</span> <span m='1170560'>here,</span> <span m='1170890'>a</span>
  <span m='1170920'>point</span> <span m='1171190'>here,</span> <span m='1171550'>a
  point</span> <span m='1171970'>here.</span> <span m='1174070'>And</span> <span m='1174220'>just</span>
  <span m='1174430'>for</span> <span m='1174970'>concreteness,</span> <span m='1175285'>let's</span>
  <span m='1175600'>say</span> <span m='1175780'>this</span> <span m='1175970'>is</span>
  <span m='1176050'>1</span> <span m='1176200'>over</span> <span m='1176340'>26.</span>
  <span m='1177010'>And</span> <span m='1177130'>this</span> <span m='1177310'>is</span>
  <span m='1177730'>1.</span> <span m='1178000'>And</span> <span m='1178270'>this</span>
  <span m='1178390'>is</span> <span m='1178480'>1 over</span> <span m='1178925'>26.</span>
  <span m='1179900'>And</span> <span m='1180060'>I</span> <span m='1180160'>have</span>
  <span m='1180250'>a</span> <span m='1180340'>particular</span> <span m='1180760'>function</span>
  <span m='1181060'>in</span> <span m='1181120'>mind</span> <span m='1181390'>that</span>
  <span m='1181480'>has</span> <span m='1181660'>those</span> <span m='1182005'>three</span>
  <span m='1182350'>points.</span> </p><p><span m='1183700'>Now,</span> <span m='1184310'>the</span>
  <span m='1184420'>first</span> <span m='1184660'>thing</span> <span m='1184750'>to</span>
  <span m='1184810'>keep</span> <span m='1184990'>in</span> <span m='1185050'>mind</span>
  <span m='1185620'>is</span> <span m='1185740'>there's</span> <span m='1185890'>an</span>
  <span m='1185980'>infinite</span> <span m='1186370'>number</span> <span m='1186640'>of</span>
  <span m='1186700'>functions</span> <span m='1188140'>that</span> <span m='1188440'>go</span>
  <span m='1188590'>through</span> <span m='1188770'>those</span> <span m='1188910'>three</span>
  <span m='1189100'>points.</span> <span m='1191990'>Now,</span> <span m='1193160'>what</span>
  <span m='1193430'>we've</span> <span m='1193640'>been</span> <span m='1193790'>doing</span>
  <span m='1195290'>is</span> <span m='1195570'>we've</span> <span m='1195850'>been</span>
  <span m='1197180'>fitting</span> <span m='1198590'>some</span> <span m='1198920'>function</span>
  <span m='1200150'>to</span> <span m='1200360'>these</span> <span m='1200570'>points</span>
  <span m='1201840'>and</span> <span m='1201860'>then</span> <span m='1202760'>integrating</span>
  <span m='1203360'>that</span> <span m='1203510'>function</span> <span m='1203780'>that</span>
  <span m='1203870'>we</span> <span m='1203960'>fitted.</span> <span m='1205930'>So</span>
  <span m='1206060'>when</span> <span m='1206180'>you're</span> <span m='1206330'>in</span>
  <span m='1206390'>high</span> <span m='1206510'>school,</span> <span m='1206720'>you</span>
  <span m='1206820'>did</span> <span m='1206950'>the</span> <span m='1207020'>rectangle</span>
  <span m='1207530'>rule</span> <span m='1207740'>and</span> <span m='1207830'>what</span>
  <span m='1207950'>the</span> <span m='1208010'>function</span> <span m='1208370'>was</span>
  <span m='1208580'>used</span> <span m='1209840'>was</span> <span m='1211560'>this</span>
  <span m='1213250'>and</span> <span m='1213410'>this.</span> <span m='1215720'>And</span>
  <span m='1215850'>you</span> <span m='1215940'>knew</span> <span m='1216120'>the</span>
  <span m='1216240'>integral</span> <span m='1216420'>of</span> <span m='1216660'>this</span>
  <span m='1216870'>function</span> <span m='1217820'>and</span> <span m='1217980'>the
  integral</span> <span m='1218170'>of this</span> <span m='1218410'>function.</span>
  <span m='1220220'>And</span> <span m='1220350'>you</span> <span m='1220470'>added</span>
  <span m='1220680'>them</span> <span m='1220830'>up.</span> <span m='1221760'>And</span>
  <span m='1222690'>you</span> <span m='1222830'>decided</span> <span m='1223320'>from</span>
  <span m='1223440'>the</span> <span m='1223530'>rectangle</span> <span m='1224010'>rule</span>
  <span m='1224940'>that</span> <span m='1225090'>the</span> <span m='1225170'>integral</span>
  <span m='1225340'>was</span> <span m='1225580'>equal</span> <span m='1225810'>to</span>
  <span m='1226610'>1</span> <span m='1227090'>and</span> <span m='1227310'>1/26.</span>
  </p><p><span m='1233290'>But</span> <span m='1233440'>then</span> <span m='1233710'>some</span>
  <span m='1233890'>other</span> <span m='1234040'>people</span> <span m='1234400'>in</span>
  <span m='1234460'>high</span> <span m='1234580'>school</span> <span m='1234760'>are</span>
  <span m='1234820'>a</span> <span m='1234850'>little</span> <span m='1234980'>smarter.</span>
  <span m='1235880'>And</span> <span m='1235900'>they</span> <span m='1236020'>said</span>
  <span m='1237130'>it's</span> <span m='1237250'>not</span> <span m='1237350'>so</span>
  <span m='1237460'>smart</span> <span m='1237780'>[INAUDIBLE].</span> <span m='1238690'>This</span>
  <span m='1238780'>thing</span> <span m='1238930'>was</span> <span m='1239020'>symmetrical</span>
  <span m='1239470'>to</span> <span m='1239560'>begin</span> <span m='1239800'>with.
  And</span> <span m='1240140'>now,</span> <span m='1240250'>I'm</span> <span m='1240370'>fitting
  it</span> <span m='1240520'>with</span> <span m='1240610'>a</span> <span m='1240700'>function</span>
  <span m='1240930'>that's</span> <span m='1241270'>wildly</span> <span m='1241650'>unsymmetrical.</span>
  <span m='1242890'>So</span> <span m='1243130'>let's</span> <span m='1243340'>instead</span>
  <span m='1244150'>not</span> <span m='1244390'>evaluate</span> <span m='1244750'>those</span>
  <span m='1244960'>points.</span> <span m='1245840'>Let's</span> <span m='1245920'>instead</span>
  <span m='1246280'>evaluate</span> <span m='1246700'>the</span> <span m='1246790'>midpoints.</span>
  <span m='1247270'>And</span> <span m='1247360'>maybe</span> <span m='1247510'>we</span>
  <span m='1247640'>find</span> <span m='1247900'>out</span> <span m='1248020'>that</span>
  <span m='1248140'>the</span> <span m='1248230'>midpoint</span> <span m='1248560'>values</span>
  <span m='1248800'>are</span> <span m='1248920'>here and</span> <span m='1249340'>here.</span>
  <span m='1251060'>And</span> <span m='1251170'>so</span> <span m='1251860'>I</span>
  <span m='1251950'>would</span> <span m='1256060'>assume</span> <span m='1256330'>that</span>
  <span m='1256420'>the</span> <span m='1256510'>function</span> <span m='1256730'>is</span>
  <span m='1256780'>just</span> <span m='1256960'>a</span> <span m='1257030'>flat
  line.</span> <span m='1258910'>That</span> <span m='1259270'>looks</span> <span
  m='1259400'>not</span> <span m='1259570'>so</span> <span m='1259690'>good</span>
  <span m='1259840'>either,</span> <span m='1260220'>because it</span> <span m='1260330'>doesn't</span>
  <span m='1260610'>get</span> <span m='1260710'>through</span> <span m='1260800'>these</span>
  <span m='1260950'>points.</span> </p><p><span m='1261190'>But</span> <span m='1261350'>anyway,</span>
  <span m='1261760'>for</span> <span m='1261850'>the two</span> <span m='1262030'>points</span>
  <span m='1262400'>I</span> <span m='1262500'>knew,</span> <span m='1262690'>if I</span>
  <span m='1262970'>only used those</span> <span m='1263190'>two</span> <span m='1263350'>points,</span>
  <span m='1263680'>that</span> <span m='1263770'>would</span> <span m='1263860'>be</span>
  <span m='1263950'>the</span> <span m='1264040'>midpoint</span> <span m='1264430'>method.</span>
  <span m='1265240'>And</span> <span m='1265360'>I</span> <span m='1265420'>would</span>
  <span m='1265510'>get</span> <span m='1265660'>the</span> <span m='1265860'>I</span>
  <span m='1266070'>midpoint</span> <span m='1266620'>method.</span> <span m='1267800'>And</span>
  <span m='1268270'>I'd</span> <span m='1268390'>get</span> <span m='1268510'>something.</span>
  <span m='1268870'>And</span> <span m='1268960'>I</span> <span m='1269020'>did</span>
  <span m='1269170'>it</span> <span m='1269320'>for</span> <span m='1269470'>this</span>
  <span m='1269590'>particular</span> <span m='1269920'>function</span> <span m='1270220'>I</span>
  <span m='1270250'>have</span> <span m='1270370'>in</span> <span m='1270460'>mind.</span>
  <span m='1271390'>And</span> <span m='1271510'>it</span> <span m='1271570'>was</span>
  <span m='1271840'>8</span> <span m='1272080'>over</span> <span m='1272240'>29.</span>
  </p><p><span m='1275220'>And</span> <span m='1275610'>then</span> <span m='1276030'>some</span>
  <span m='1276260'>other</span> <span m='1276320'>people</span> <span m='1276450'>say,</span>
  <span m='1276600'>well,</span> <span m='1276690'>let's</span> <span m='1276870'>use</span>
  <span m='1276990'>the</span> <span m='1277050'>trapezoid</span> <span m='1277590'>rule.</span>
  <span m='1278030'>So</span> <span m='1278070'>let's</span> <span m='1278580'>approximate</span>
  <span m='1279090'>the</span> <span m='1279180'>function</span> <span m='1279440'>is</span>
  <span m='1280230'>this</span> <span m='1281730'>over</span> <span m='1281910'>the</span>
  <span m='1281970'>interval,</span> <span m='1284020'>which</span> <span m='1284140'>looks</span>
  <span m='1284320'>kind</span> <span m='1284470'>of</span> <span m='1284530'>sensible.</span>
  <span m='1285670'>And</span> <span m='1285820'>if</span> <span m='1285880'>you</span>
  <span m='1285970'>do</span> <span m='1286090'>that,</span> <span m='1286430'>it</span>
  <span m='1286530'>turns</span> <span m='1286630'>out</span> <span m='1286750'>you</span>
  <span m='1286810'>get</span> <span m='1286900'>the</span> <span m='1286960'>same</span>
  <span m='1287140'>numbers</span> <span m='1287580'>as you</span> <span m='1287620'>do
  with</span> <span m='1287840'>the rectangle</span> <span m='1288020'>rule.</span>
  <span m='1288370'>So</span> <span m='1289330'>I</span> <span m='1289390'>trapezoid.</span>
  </p><p><span m='1294830'>Now,</span> <span m='1295700'>let</span> <span m='1295820'>me</span>
  <span m='1295880'>just</span> <span m='1296570'>as</span> <span m='1296750'>a</span>
  <span m='1296930'>warning,</span> <span m='1298700'>if</span> <span m='1298790'>you</span>
  <span m='1298850'>just</span> <span m='1299000'>do</span> <span m='1299090'>the</span>
  <span m='1299180'>rectangle</span> <span m='1299465'>rule and</span> <span m='1299750'>then</span>
  <span m='1299870'>the</span> <span m='1299940'>trapezoid</span> <span m='1300120'>rule,</span>
  <span m='1300290'>and you</span> <span m='1300470'>got</span> <span m='1300570'>the</span>
  <span m='1300650'>same</span> <span m='1300800'>number</span> <span m='1301000'>both</span>
  <span m='1301160'>times,</span> <span m='1301490'>you</span> <span m='1301580'>might</span>
  <span m='1302030'>be</span> <span m='1302210'>tempted</span> <span m='1302540'>to</span>
  <span m='1302600'>conclude</span> <span m='1302960'>you</span> <span m='1303020'>have</span>
  <span m='1303110'>converged.</span> <span m='1304370'>And</span> <span m='1304460'>you</span>
  <span m='1304560'>have</span> <span m='1304640'>the</span> <span m='1304730'>true</span>
  <span m='1304880'>solution,</span> <span m='1305270'>because</span> <span m='1305420'>you</span>
  <span m='1305480'>did</span> <span m='1305690'>two</span> <span m='1305900'>methods</span>
  <span m='1306230'>of</span> <span m='1306380'>really</span> <span m='1306560'>different</span>
  <span m='1306800'>orders,</span> <span m='1307730'>and</span> <span m='1307820'>you</span>
  <span m='1307890'>got</span> <span m='1308000'>exactly</span> <span m='1308330'>the</span>
  <span m='1308390'>same</span> <span m='1308540'>number.</span> <span m='1309680'>And</span>
  <span m='1309800'>you're</span> <span m='1309890'>super</span> <span m='1310160'>happy,</span>
  <span m='1310520'>and</span> <span m='1310610'>you're</span> <span m='1310940'>ready</span>
  <span m='1311150'>to</span> <span m='1311270'>publish</span> <span m='1311570'>your</span>
  <span m='1311660'>paper.</span> </p><p><span m='1314030'>But</span> <span m='1314210'>of</span>
  <span m='1314300'>course,</span> <span m='1314570'>the</span> <span m='1314660'>function</span>
  <span m='1315050'>might</span> <span m='1315170'>not</span> <span m='1315320'>look</span>
  <span m='1315550'>like</span> <span m='1315640'>this.</span> <span m='1315830'>So</span>
  <span m='1315910'>the</span> <span m='1315980'>particular</span> <span m='1316340'>function</span>
  <span m='1316730'>that I</span> <span m='1316820'>always</span> <span m='1317030'>had</span>
  <span m='1317180'>in</span> <span m='1317240'>mind</span> <span m='1318270'>was</span>
  <span m='1318390'>f</span> <span m='1318530'>of</span> <span m='1318800'>t</span>
  <span m='1320510'>is</span> <span m='1320630'>equal</span> <span m='1320810'>to</span>
  <span m='1320870'>1</span> <span m='1321200'>over</span> <span m='1321410'>1</span>
  <span m='1321680'>plus</span> <span m='1322010'>25</span> <span m='1322560'>t</span>
  <span m='1322940'>squared.</span> <span m='1325520'>OK,</span> <span m='1325840'>that</span>
  <span m='1325960'>was</span> <span m='1326080'>just</span> <span m='1326200'>the</span>
  <span m='1326290'>function</span> <span m='1326560'>I</span> <span m='1326620'>had</span>
  <span m='1326740'>in</span> <span m='1326800'>mind.</span> <span m='1327460'>And</span>
  <span m='1327610'>the</span> <span m='1327700'>way</span> <span m='1327820'>that</span>
  <span m='1327970'>function</span> <span m='1328270'>looks</span> <span m='1328480'>like</span>
  <span m='1328810'>is</span> <span m='1334761'>like that.</span> <span m='1336690'>And</span>
  <span m='1337080'>the</span> <span m='1337180'>real</span> <span m='1337360'>integral
  of</span> <span m='1337630'>that</span> <span m='1337770'>function,</span> <span
  m='1338240'>which</span> <span m='1338290'>you</span> <span m='1338380'>guys</span>
  <span m='1338650'>if</span> <span m='1338750'>you</span> <span m='1339040'>remember</span>
  <span m='1339340'>how</span> <span m='1339520'>do</span> <span m='1339650'>it from</span>
  <span m='1339905'>high school,</span> <span m='1340160'>you can</span> <span m='1340420'>actually</span>
  <span m='1340660'>evaluate</span> <span m='1340900'>that</span> <span m='1341050'>integral.</span>
  <span m='1341950'>It's</span> <span m='1342220'>nothing</span> <span m='1342490'>to</span>
  <span m='1342580'>do</span> <span m='1342730'>with</span> <span m='1343690'>either</span>
  <span m='1344200'>8/29</span> <span m='1344980'>or</span> <span m='1345420'>1</span>
  <span m='1345600'>in</span> <span m='1345670'>126.</span> <span m='1346860'>It's</span>
  <span m='1346970'>something</span> <span m='1347080'>completely</span> <span m='1347350'>different.</span>
  </p><p><span m='1348020'>Now,</span> <span m='1348760'>those</span> <span m='1348970'>of</span>
  <span m='1349090'>you</span> <span m='1349330'>who</span> <span m='1349480'>went</span>
  <span m='1349630'>to</span> <span m='1349720'>really</span> <span m='1349900'>advanced</span>
  <span m='1350170'>high</span> <span m='1350290'>schools,</span> <span m='1350530'>you</span>
  <span m='1350590'>also</span> <span m='1350800'>learned</span> <span m='1350960'>Simpson's</span>
  <span m='1351310'>rule</span> <span m='1351460'>too.</span> <span m='1352135'>And</span>
  <span m='1352450'>Simpson's</span> <span m='1352770'>rule</span> <span m='1352930'>says</span>
  <span m='1353070'>let's</span> <span m='1353200'>fit</span> <span m='1353370'>it</span>
  <span m='1353500'>to</span> <span m='1353790'>a</span> <span m='1353890'>parabola.</span>
  <span m='1355150'>And</span> <span m='1355330'>so</span> <span m='1355450'>that</span>
  <span m='1355630'>would</span> <span m='1355790'>give</span> <span m='1356290'>you</span>
  <span m='1356450'>something</span> <span m='1356610'>like</span> <span m='1356710'>this.</span>
  <span m='1358930'>And</span> <span m='1359050'>if</span> <span m='1359140'>you</span>
  <span m='1359230'>do</span> <span m='1359350'>Simpson's</span> <span m='1359740'>rule,</span>
  <span m='1361090'>I</span> <span m='1361160'>ended</span> <span m='1361300'>up</span>
  <span m='1361390'>getting</span> <span m='1361590'>this</span> <span m='1361870'>if</span>
  <span m='1361960'>I</span> <span m='1362050'>did</span> <span m='1362305'>the</span>
  <span m='1362560'>arithmetic</span> <span m='1363040'>right.</span> <span m='1366390'>1</span>
  <span m='1366720'>and</span> <span m='1367060'>1/3</span> <span m='1368290'>plus</span>
  <span m='1369100'>2/78.</span> <span m='1371420'>Who</span> <span m='1371620'>knew?</span>
  <span m='1372520'>OK,</span> <span m='1373570'>which</span> <span m='1373720'>also</span>
  <span m='1373960'>has</span> <span m='1374110'>little</span> <span m='1374650'>relation</span>
  <span m='1375070'>to</span> <span m='1375130'>the</span> <span m='1375220'>true</span>
  <span m='1375370'>value</span> <span m='1375640'>of the</span> <span m='1375770'>integral.</span>
  </p><p><span m='1377870'>Now,</span> <span m='1378050'>if you're</span> <span m='1378200'>smart,</span>
  <span m='1378540'>and you</span> <span m='1378660'>did</span> <span m='1378900'>trapezoid</span>
  <span m='1379460'>and</span> <span m='1379590'>then</span> <span m='1379680'>I</span>
  <span m='1380000'>it</span> <span m='1380090'>to</span> <span m='1380180'>Simpson's,</span>
  <span m='1381150'>then</span> <span m='1381260'>you</span> <span m='1381320'>say,</span>
  <span m='1381630'>oh</span> <span m='1381730'>my</span> <span m='1381830'>goodness,</span>
  <span m='1382640'>these</span> <span m='1382790'>are</span> <span m='1382850'>not</span>
  <span m='1383030'>really</span> <span m='1383180'>that</span> <span m='1383510'>similar.</span>
  <span m='1383990'>And</span> <span m='1384110'>so</span> <span m='1384260'>I'm</span>
  <span m='1384350'>not</span> <span m='1384500'>converged,</span> <span m='1384820'>and</span>
  <span m='1384910'>I'd</span> <span m='1385010'>better</span> <span m='1385190'>do</span>
  <span m='1385250'>something</span> <span m='1385550'>else.</span> <span m='1388324'>So</span>
  <span m='1390236'>I</span> <span m='1390720'>just want</span> <span m='1390940'>you</span>
  <span m='1391110'>to be</span> <span m='1391230'>aware</span> <span m='1391650'>when</span>
  <span m='1391800'>we</span> <span m='1391890'>do</span> <span m='1392010'>these</span>
  <span m='1392160'>rules,</span> <span m='1392910'>what</span> <span m='1393090'>we're</span>
  <span m='1393210'>actually</span> <span m='1393510'>doing</span> <span m='1393900'>is</span>
  <span m='1393990'>we're</span> <span m='1394090'>fitting</span> <span m='1396090'>our</span>
  <span m='1396240'>points</span> <span m='1397830'>to</span> <span m='1398130'>some</span>
  <span m='1398610'>continuous</span> <span m='1399030'>function</span> <span m='1399360'>that</span>
  <span m='1399450'>we</span> <span m='1399510'>know</span> <span m='1399630'>how</span>
  <span m='1399720'>to</span> <span m='1399780'>integrate.</span> <span m='1401040'>And</span>
  <span m='1401130'>then</span> <span m='1401220'>we</span> <span m='1401310'>do</span>
  <span m='1401400'>the</span> <span m='1401490'>analytical</span> <span m='1401880'>integral</span>
  <span m='1402180'>of</span> <span m='1402240'>that</span> <span m='1402720'>function,</span>
  <span m='1404160'>which</span> <span m='1404310'>is</span> <span m='1404400'>a</span>
  <span m='1404430'>fine</span> <span m='1404730'>thing</span> <span m='1404910'>to</span>
  <span m='1405000'>do.</span> </p><p><span m='1405570'>But</span> <span m='1405720'>just</span>
  <span m='1405870'>be</span> <span m='1405960'>aware</span> <span m='1406710'>that</span>
  <span m='1407130'>it's</span> <span m='1407280'>like</span> <span m='1408540'>extrapolation.</span>
  <span m='1409350'>It's</span> <span m='1409500'>like</span> <span m='1409680'>we're</span>
  <span m='1409770'>imagining</span> <span m='1410280'>what</span> <span m='1410370'>the</span>
  <span m='1410460'>function</span> <span m='1410650'>is</span> <span m='1410730'>doing</span>
  <span m='1410940'>between</span> <span m='1411180'>these</span> <span m='1411300'>points,</span>
  <span m='1412150'>when</span> <span m='1412560'>we</span> <span m='1412710'>actually</span>
  <span m='1413370'>haven't</span> <span m='1413700'>tested</span> <span m='1414090'>it.</span>
  <span m='1414610'>Now,</span> <span m='1414790'>we</span> <span m='1415260'>could.
  We</span> <span m='1415350'>could just</span> <span m='1415440'>call</span> <span
  m='1415620'>more</span> <span m='1415770'>points.</span> <span m='1416280'>We</span>
  <span m='1416370'>could</span> <span m='1416460'>calculate.</span> <span m='1417620'>But</span>
  <span m='1417760'>that would</span> <span m='1417910'>cost us</span> <span m='1418170'>more</span>
  <span m='1418320'>function</span> <span m='1418550'>evals.</span> <span m='1418850'>And</span>
  <span m='1418950'>we're</span> <span m='1419760'>trying</span> <span m='1419940'>to</span>
  <span m='1420000'>save</span> <span m='1420140'>our</span> <span m='1420240'>computer</span>
  <span m='1420540'>time.</span> <span m='1421140'>So</span> <span m='1421440'>we</span>
  <span m='1421500'>want</span> <span m='1421620'>to</span> <span m='1421680'>finish</span>
  <span m='1421890'>off</span> <span m='1422010'>before</span> <span m='1422250'>the</span>
  <span m='1422340'>TG</span> <span m='1422710'>so we can</span> <span m='1422840'>go</span>
  <span m='1422940'>buy</span> <span m='1423030'>some</span> <span m='1423150'>beer.</span>
  <span m='1423900'>And</span> <span m='1424020'>so</span> <span m='1429240'>we</span>
  <span m='1429330'>have</span> <span m='1429420'>to</span> <span m='1429540'>take</span>
  <span m='1429850'>some</span> <span m='1430050'>choices</span> <span m='1430410'>about</span>
  <span m='1430560'>what</span> <span m='1430650'>to</span> <span m='1430740'>do.</span>
  <span m='1431370'>And</span> <span m='1431610'>we</span> <span m='1431820'>can't</span>
  <span m='1431950'>do</span> <span m='1432150'>an</span> <span m='1432250'>infinite</span>
  <span m='1432450'>number</span> <span m='1432510'>of</span> <span m='1432570'>points</span>
  <span m='1432840'>for</span> <span m='1432930'>sure.</span> </p><p><span m='1434370'>All</span>
  <span m='1434430'>right,</span> <span m='1434550'>so in</span> <span m='1434730'>all</span>
  <span m='1434850'>these</span> <span m='1434970'>methods,</span> <span m='1435570'>what</span>
  <span m='1435690'>we're</span> <span m='1435780'>doing</span> <span m='1436080'>is</span>
  <span m='1436190'>we're</span> <span m='1436290'>approximating</span> <span m='1437910'>our</span>
  <span m='1438090'>true</span> <span m='1438330'>f</span> <span m='1439110'>with</span>
  <span m='1439290'>some</span> <span m='1439500'>approximate</span> <span m='1439770'>f,</span>
  <span m='1441060'>which</span> <span m='1441270'>is</span> <span m='1441390'>equal</span>
  <span m='1441630'>to a</span> <span m='1441930'>sum</span> <span m='1443580'>of</span>
  <span m='1443810'>some</span> <span m='1443920'>basis</span> <span m='1444300'>functions</span>
  <span m='1451890'>like</span> <span m='1452040'>this.</span> <span m='1452820'>So</span>
  <span m='1453030'>we</span> <span m='1453090'>pick</span> <span m='1453250'>some</span>
  <span m='1453390'>basis</span> <span m='1453660'>functions.</span> <span m='1453990'>We</span>
  <span m='1454080'>know</span> <span m='1454200'>how</span> <span m='1454320'>to</span>
  <span m='1454980'>integrate.</span> <span m='1455820'>We</span> <span m='1455970'>fit,</span>
  <span m='1456630'>somehow</span> <span m='1457080'>determine</span> <span m='1457440'>what</span>
  <span m='1457530'>these</span> <span m='1457610'>c's</span> <span m='1457980'>are.</span>
  <span m='1458730'>And</span> <span m='1458910'>then</span> <span m='1459060'>we</span>
  <span m='1459150'>decide</span> <span m='1459510'>that</span> <span m='1459630'>the</span>
  <span m='1459750'>integral</span> <span m='1460890'>is</span> <span m='1461100'>equal</span>
  <span m='1461310'>to</span> <span m='1461490'>the</span> <span m='1461610'>integral</span>
  <span m='1462080'>of</span> <span m='1462330'>f</span> <span m='1462822'>tilde,</span>
  <span m='1467060'>not</span> <span m='1467260'>the</span> <span m='1467350'>actual</span>
  <span m='1467560'>original</span> <span m='1468000'>f.</span> </p><p><span m='1469360'>And
  then</span> <span m='1469600'>that's</span> <span m='1469780'>actually</span> <span
  m='1470210'>going</span> <span m='1470350'>to</span> <span m='1470410'>be</span>
  <span m='1470530'>the</span> <span m='1470650'>sum</span> <span m='1471690'>of</span>
  <span m='1472090'>ck</span> <span m='1472580'>times the</span> <span m='1472900'>integral.</span>
  <span m='1477230'>And</span> <span m='1477250'>we</span> <span m='1477340'>carefully</span>
  <span m='1477700'>chose</span> <span m='1478090'>basis</span> <span m='1478330'>functions</span>
  <span m='1478630'>that</span> <span m='1478720'>we</span> <span m='1478780'>don't</span>
  <span m='1478930'>how</span> <span m='1479010'>to</span> <span m='1479070'>do</span>
  <span m='1479170'>this</span> <span m='1479340'>integral;</span> <span m='1479710'>analytically.</span>
  <span m='1482260'>So</span> <span m='1482860'>we</span> <span m='1482950'>just</span>
  <span m='1483100'>plug</span> <span m='1483340'>that</span> <span m='1483620'>in,</span>
  <span m='1483760'>and</span> <span m='1483850'>we</span> <span m='1483910'>just</span>
  <span m='1484030'>have</span> <span m='1484120'>to</span> <span m='1484330'>figure</span>
  <span m='1484540'>out</span> <span m='1484630'>that</span> <span m='1484750'>the
  c's</span> <span m='1484990'>are</span> <span m='1486680'>to</span> <span m='1486780'>get</span>
  <span m='1486900'>this</span> <span m='1486990'>to</span> <span m='1487080'>work.</span>
  <span m='1488040'>OK,</span> <span m='1488160'>so</span> <span m='1488250'>that's</span>
  <span m='1488370'>what</span> <span m='1488490'>you</span> <span m='1488580'>really</span>
  <span m='1488820'>did</span> <span m='1489750'>when</span> <span m='1489900'>you're</span>
  <span m='1489990'>doing</span> <span m='1490170'>this</span> <span m='1490290'>trapezoid</span>
  <span m='1490350'>rule</span> <span m='1490750'>and</span> <span m='1490850'>Simpson's</span>
  <span m='1491110'>rule,</span> <span m='1491290'>and</span> <span m='1491460'>all
  that</span> <span m='1491670'>kind of</span> <span m='1491790'>stuff.</span> <span
  m='1492630'>And</span> <span m='1492750'>it's</span> <span m='1492840'>just</span>
  <span m='1492990'>different</span> <span m='1493200'>choices</span> <span m='1493530'>of</span>
  <span m='1493590'>what</span> <span m='1493710'>the</span> <span m='1493800'>basis</span>
  <span m='1494070'>functions</span> <span m='1494440'>were</span> <span m='1495010'>that</span>
  <span m='1495380'>you</span> <span m='1495750'>used.</span> </p><p><span m='1499680'>Now,</span>
  <span m='1500010'>there's</span> <span m='1500130'>a</span> <span m='1500190'>lot</span>
  <span m='1500340'>of</span> <span m='1500400'>choices</span> <span m='1500760'>about</span>
  <span m='1500970'>how</span> <span m='1501120'>to</span> <span m='1501660'>do</span>
  <span m='1501780'>that</span> <span m='1501930'>kind</span> <span m='1502110'>of</span>
  <span m='1502170'>approximation</span> <span m='1503820'>to</span> <span m='1503940'>make
  f</span> <span m='1504230'>tildes</span> <span m='1504630'>that</span> <span m='1504720'>are</span>
  <span m='1504780'>sort</span> <span m='1504960'>of</span> <span m='1505020'>like</span>
  <span m='1505220'>f's</span> <span m='1506490'>with</span> <span m='1506610'>some</span>
  <span m='1507030'>limited</span> <span m='1507300'>amount</span> <span m='1507510'>of</span>
  <span m='1507630'>information.</span> <span m='1509320'>And</span> <span m='1510090'>it</span>
  <span m='1510480'>generally</span> <span m='1510690'>has</span> <span m='1510860'>to
  do with</span> <span m='1511080'>how</span> <span m='1511230'>many</span> <span
  m='1511410'>k's</span> <span m='1511740'>we</span> <span m='1511860'>have.</span>
  <span m='1512140'>So</span> <span m='1512220'>if</span> <span m='1512400'>k</span>
  <span m='1513510'>is</span> <span m='1513690'>less</span> <span m='1513990'>than</span>
  <span m='1514180'>n,</span> <span m='1515080'>then</span> <span m='1515100'>it's</span>
  <span m='1515190'>really</span> <span m='1515400'>an</span> <span m='1515460'>approximation.</span>
  <span m='1515845'>Because</span> <span m='1516230'>there's</span> <span m='1516430'>no</span>
  <span m='1516660'>way</span> <span m='1517050'>that we</span> <span m='1517230'>would</span>
  <span m='1517380'>expect</span> <span m='1518820'>that</span> <span m='1518910'>with</span>
  <span m='1519030'>just</span> <span m='1519180'>a</span> <span m='1519240'>few</span>
  <span m='1519420'>parameters,</span> <span m='1520690'>we</span> <span m='1520800'>could</span>
  <span m='1520920'>get</span> <span m='1521070'>a</span> <span m='1521100'>lot</span>
  <span m='1521400'>f</span> <span m='1521710'>of</span> <span m='1522020'>tn.</span>
  <span m='1522780'>So</span> <span m='1522960'>we</span> <span m='1523050'>would</span>
  <span m='1523170'>expect</span> <span m='1524400'>that</span> <span m='1525220'>f</span>
  <span m='1525682'>tilde</span> <span m='1526144'>of</span> <span m='1526606'>tn</span>
  <span m='1527790'>is</span> <span m='1527970'>not</span> <span m='1528330'>equal</span>
  <span m='1528630'>to</span> <span m='1529386'>f</span> <span m='1529812'>of</span>
  <span m='1530240'>tn,</span> <span m='1530870'>at</span> <span m='1530940'>least</span>
  <span m='1531120'>not</span> <span m='1531300'>at</span> <span m='1531390'>all</span>
  <span m='1531510'>the</span> <span m='1531600'>points.</span> <span m='1532710'>Because</span>
  <span m='1533040'>if</span> <span m='1533230'>n</span> <span m='1533480'>is--</span>
  <span m='1534030'>if</span> <span m='1534240'>we</span> <span m='1534300'>have</span>
  <span m='1534420'>a</span> <span m='1534450'>lot</span> <span m='1534600'>of</span>
  <span m='1534660'>points</span> <span m='1535560'>and</span> <span m='1535650'>we</span>
  <span m='1535740'>only</span> <span m='1535890'>have</span> <span m='1535980'>a</span>
  <span m='1536040'>few</span> <span m='1536190'>parameters,</span> <span m='1536670'>we</span>
  <span m='1536760'>don't</span> <span m='1536910'>expect</span> <span m='1537180'>to
  be</span> <span m='1537350'>able to</span> <span m='1537450'>fit</span> <span m='1537600'>it</span>
  <span m='1537660'>perfectly.</span> </p><p><span m='1540900'>So</span> <span m='1541720'>we</span>
  <span m='1541790'>know</span> <span m='1542040'>this</span> <span m='1542290'>is</span>
  <span m='1542360'>what</span> <span m='1542460'>we</span> <span m='1542580'>expect.</span>
  <span m='1543410'>It</span> <span m='1543540'>might</span> <span m='1543750'>happen</span>
  <span m='1544110'>if,</span> <span m='1544770'>by</span> <span m='1544890'>some</span>
  <span m='1545130'>luck,</span> <span m='1545940'>we</span> <span m='1546060'>chose</span>
  <span m='1546320'>a</span> <span m='1546420'>basis</span> <span m='1546640'>function</span>
  <span m='1546970'>which was</span> <span m='1547120'>actually</span> <span m='1547410'>the</span>
  <span m='1547500'>true</span> <span m='1547680'>function</span> <span m='1549032'>f,</span>
  <span m='1549500'>then</span> <span m='1549610'>it</span> <span m='1549700'>would</span>
  <span m='1549790'>actually</span> <span m='1550000'>fit</span> <span m='1550120'>perfectly.</span>
  <span m='1550510'>But</span> <span m='1550700'>most</span> <span m='1550850'>of</span>
  <span m='1550930'>the</span> <span m='1551120'>time, not.</span> <span m='1554100'>By</span>
  <span m='1554580'>Murphy's</span> <span m='1554890'>Law,</span> <span m='1555070'>in</span>
  <span m='1555160'>fact,</span> <span m='1555370'>it's going to be</span> <span m='1555530'>completely</span>
  <span m='1555810'>wrong.</span> <span m='1557740'>But</span> <span m='1558400'>this</span>
  <span m='1558580'>is</span> <span m='1558670'>not</span> <span m='1558820'>such</span>
  <span m='1559000'>a</span> <span m='1559030'>bad</span> <span m='1559180'>idea.</span>
  <span m='1560440'>We</span> <span m='1560610'>may</span> <span m='1561040'>come</span>
  <span m='1561160'>back</span> <span m='1561280'>to</span> <span m='1561370'>this</span>
  <span m='1561490'>later.</span> </p><p><span m='1563020'>Another</span> <span m='1563320'>possibility</span>
  <span m='1563800'>is</span> <span m='1563890'>to choose</span> <span m='1564040'>k</span>
  <span m='1564480'>equals</span> <span m='1564860'>to n.</span> <span m='1566890'>And</span>
  <span m='1568240'>then</span> <span m='1569140'>usually,</span> <span m='1571540'>we</span>
  <span m='1571630'>can</span> <span m='1571810'>force</span> <span m='1576330'>f</span>
  <span m='1576740'>tilde of</span> <span m='1577150'>tn</span> <span m='1577410'>to</span>
  <span m='1577650'>equal</span> <span m='1580260'>f</span> <span m='1580740'>of</span>
  <span m='1581065'>tn.</span> <span m='1581390'>So</span> <span m='1581640'>at the</span>
  <span m='1581760'>points</span> <span m='1582090'>that</span> <span m='1582180'>we</span>
  <span m='1582300'>have,</span> <span m='1583130'>if</span> <span m='1583320'>we</span>
  <span m='1583470'>have</span> <span m='1583560'>enough</span> <span m='1583690'>parameters</span>
  <span m='1584310'>equal</span> <span m='1584580'>to</span> <span m='1584670'>the</span>
  <span m='1584760'>number</span> <span m='1585090'>of</span> <span m='1585180'>points,</span>
  <span m='1586110'>then</span> <span m='1586530'>often,</span> <span m='1586860'>we</span>
  <span m='1586920'>can</span> <span m='1587010'>get</span> <span m='1587130'>an</span>
  <span m='1587190'>exact</span> <span m='1587640'>fit.</span> <span m='1587880'>We</span>
  <span m='1587970'>can</span> <span m='1588120'>force</span> <span m='1588420'>the</span>
  <span m='1588540'>function</span> <span m='1588840'>to</span> <span m='1588900'>go</span>
  <span m='1589050'>through</span> <span m='1589200'>all</span> <span m='1589290'>the</span>
  <span m='1589400'>points.</span> <span m='1591510'>And</span> <span m='1592320'>when</span>
  <span m='1592440'>we</span> <span m='1592530'>do</span> <span m='1592680'>this,</span>
  <span m='1593500'>this</span> <span m='1593910'>is</span> <span m='1594030'>called</span>
  <span m='1594570'>interpolation.</span> </p><p><span m='1603480'>Now,</span> <span
  m='1604650'>when</span> <span m='1604980'>should</span> <span m='1605160'>you</span>
  <span m='1605220'>do</span> <span m='1605370'>the</span> <span m='1605490'>one</span>
  <span m='1605700'>or</span> <span m='1605760'>the</span> <span m='1605880'>other?</span>
  <span m='1606620'>When</span> <span m='1606800'>should</span> <span m='1606930'>I</span>
  <span m='1607020'>make</span> <span m='1607440'>k</span> <span m='1607710'>as</span>
  <span m='1607830'>big</span> <span m='1608010'>as</span> <span m='1608130'>n?</span>
  <span m='1608310'>Or</span> <span m='1608400'>when</span> <span m='1608660'>should
  I</span> <span m='1608720'>use</span> <span m='1608840'>k</span> <span m='1609080'>less
  than</span> <span m='1609360'>n?</span> <span m='1610170'>A</span> <span m='1610230'>really</span>
  <span m='1610440'>crucial</span> <span m='1610770'>thing</span> <span m='1611070'>is</span>
  <span m='1611370'>whether</span> <span m='1611610'>you</span> <span m='1611760'>really</span>
  <span m='1612030'>believe</span> <span m='1612270'>your</span> <span m='1612390'>points.</span>
  <span m='1613820'>If</span> <span m='1613920'>you</span> <span m='1614040'>really</span>
  <span m='1614340'>believe</span> <span m='1614670'>you</span> <span m='1614760'>know</span>
  <span m='1615000'>f of</span> <span m='1615390'>tn</span> <span m='1616050'>to</span>
  <span m='1616290'>a</span> <span m='1616440'>very,</span> <span m='1616810'>very</span>
  <span m='1617040'>high</span> <span m='1617220'>number</span> <span m='1617430'>of</span>
  <span m='1617490'>significant</span> <span m='1617850'>figures,</span> <span m='1618780'>then</span>
  <span m='1619200'>it</span> <span m='1619350'>make</span> <span m='1619480'>sense.</span>
  <span m='1620160'>You</span> <span m='1620250'>know</span> <span m='1620400'>that's</span>
  <span m='1620610'>true,</span> <span m='1621070'>so</span> <span m='1621120'>you</span>
  <span m='1621210'>should</span> <span m='1621330'>force</span> <span m='1621630'>your</span>
  <span m='1622290'>fitting</span> <span m='1622530'>function</span> <span m='1622860'>to</span>
  <span m='1622920'>actually</span> <span m='1623490'>match</span> <span m='1623830'>that.</span>
  </p><p><span m='1625170'>However,</span> <span m='1625530'>if</span> <span m='1625590'>you</span>
  <span m='1625650'>get</span> <span m='1625800'>the</span> <span m='1626080'>f of</span>
  <span m='1626395'>tn,</span> <span m='1626710'>for</span> <span m='1626730'>example,</span>
  <span m='1627030'>from</span> <span m='1627210'>an</span> <span m='1627300'>experiment</span>
  <span m='1628650'>or</span> <span m='1628800'>from</span> <span m='1628980'>a</span>
  <span m='1629040'>stochastic</span> <span m='1629550'>simulation</span> <span m='1630120'>that</span>
  <span m='1630240'>has</span> <span m='1630390'>some</span> <span m='1630480'>noise</span>
  <span m='1630750'>in</span> <span m='1630870'>it,</span> <span m='1631890'>then</span>
  <span m='1632940'>you</span> <span m='1633150'>might</span> <span m='1633360'>not</span>
  <span m='1633570'>really</span> <span m='1633810'>want</span> <span m='1633960'>to</span>
  <span m='1634020'>do</span> <span m='1634170'>this.</span> <span m='1634410'>Because</span>
  <span m='1634800'>you'll</span> <span m='1634920'>be</span> <span m='1635120'>fitting</span>
  <span m='1635340'>the</span> <span m='1635430'>noise</span> <span m='1636630'>in</span>
  <span m='1636750'>the</span> <span m='1636840'>experiment</span> <span m='1637230'>as</span>
  <span m='1637350'>well.</span> <span m='1638530'>And</span> <span m='1638550'>then</span>
  <span m='1638730'>you</span> <span m='1638820'>might</span> <span m='1638910'>want</span>
  <span m='1639030'>to</span> <span m='1639090'>use</span> <span m='1639360'>a</span>
  <span m='1643170'>smaller</span> <span m='1643410'>number</span> <span m='1643620'>of</span>
  <span m='1643740'>parameters</span> <span m='1644280'>to</span> <span m='1644400'>make</span>
  <span m='1644580'>the</span> <span m='1644700'>fits.</span> <span m='1645690'>OK,</span>
  <span m='1645990'>so</span> <span m='1646110'>you</span> <span m='1646200'>can</span>
  <span m='1646290'>do</span> <span m='1646410'>either</span> <span m='1646590'>one.</span>
  <span m='1646850'>You're</span> <span m='1647100'>in</span> <span m='1647190'>charge.</span>
  <span m='1648240'>Right,</span> <span m='1648420'>you</span> <span m='1648540'>get</span>
  <span m='1648630'>the</span> <span m='1648720'>problem.</span> <span m='1649920'>If</span>
  <span m='1650160'>somebody</span> <span m='1650430'>tells</span> <span m='1650670'>you,</span>
  <span m='1650760'>please</span> <span m='1650940'>give</span> <span m='1651060'>me</span>
  <span m='1651120'>this</span> <span m='1651240'>integral,</span> <span m='1651840'>they</span>
  <span m='1651900'>don't</span> <span m='1652020'>care</span> <span m='1652170'>how</span>
  <span m='1652260'>you</span> <span m='1652350'>do</span> <span m='1652530'>it.</span>
  <span m='1653610'>They</span> <span m='1653730'>just</span> <span m='1653820'>want</span>
  <span m='1653940'>you to</span> <span m='1654030'>come</span> <span m='1654150'>back</span>
  <span m='1654330'>and</span> <span m='1654420'>give</span> <span m='1654540'>them
  the</span> <span m='1654660'>true value</span> <span m='1655010'>of</span> <span
  m='1655130'>the</span> <span m='1655210'>integral</span> <span m='1656730'>to</span>
  <span m='1656820'>some</span> <span m='1656970'>significant</span> <span m='1657300'>figures.</span>
  <span m='1659030'>So</span> <span m='1659260'>it's</span> <span m='1659410'>up</span>
  <span m='1659520'>to</span> <span m='1659610'>you</span> <span m='1659700'>to</span>
  <span m='1659870'>decide</span> <span m='1660150'>what</span> <span m='1660240'>to</span>
  <span m='1660330'>do.</span> <span m='1660610'>So</span> <span m='1660710'>you</span>
  <span m='1660810'>can</span> <span m='1660910'>decide</span> <span m='1661020'>what</span>
  <span m='1661110'>to</span> <span m='1661200'>do.</span> </p><p><span m='1662440'>What</span>
  <span m='1662490'>a</span> <span m='1662550'>lot</span> <span m='1662700'>of</span>
  <span m='1662760'>people</span> <span m='1663060'>do</span> <span m='1663240'>in</span>
  <span m='1663330'>the</span> <span m='1663390'>math</span> <span m='1663660'>world</span>
  <span m='1663960'>is</span> <span m='1664650'>this</span> <span m='1664800'>one,</span>
  <span m='1665250'>interpolation,</span> <span m='1666420'>where</span> <span m='1666630'>you're</span>
  <span m='1666870'>assuming</span> <span m='1667290'>that</span> <span m='1667410'>the</span>
  <span m='1667530'>f of</span> <span m='1667890'>tn's</span> <span m='1668070'>are</span>
  <span m='1668130'>known</span> <span m='1668700'>exactly.</span> <span m='1670490'>And</span>
  <span m='1670910'>so</span> <span m='1671040'>your</span> <span m='1671160'>function</span>
  <span m='1671400'>evaluating</span> <span m='1671730'>function</span> <span m='1672030'>is</span>
  <span m='1672120'>great.</span> <span m='1673560'>And</span> <span m='1673920'>in</span>
  <span m='1674070'>that</span> <span m='1674190'>case,</span> <span m='1674460'>you</span>
  <span m='1674550'>can</span> <span m='1674700'>write</span> <span m='1674850'>down</span>
  <span m='1675060'>this</span> <span m='1675210'>nice</span> <span m='1675540'>linear</span>
  <span m='1675840'>equation.</span> <span m='1677920'>So</span> <span m='1677940'>we're</span>
  <span m='1678000'>trying</span> <span m='1678210'>to</span> <span m='1678300'>make</span>
  <span m='1678540'>f of</span> <span m='1678960'>tn</span> <span m='1680310'>with</span>
  <span m='1680420'>a</span> <span m='1680490'>true</span> <span m='1680640'>function</span>
  <span m='1681440'>to</span> <span m='1681520'>be</span> <span m='1681860'>equal</span>
  <span m='1682110'>to</span> <span m='1683320'>ck</span> <span m='1683900'>phi</span>
  <span m='1684250'>n of</span> <span m='1684450'>t.</span> <span m='1686006'>Sorry,</span>
  <span m='1686408'>phi</span> <span m='1686810'>k of</span> <span m='1686990'>t.</span>
  <span m='1692260'>Which</span> <span m='1692590'>n</span> <span m='1692770'>in</span>
  <span m='1692890'>[INAUDIBLE]</span> <span m='1693260'>k is</span> <span m='1693550'>equal</span>
  <span m='1693730'>to</span> <span m='1693850'>n.</span> </p><p><span m='1694790'>And</span>
  <span m='1696010'>I</span> <span m='1696100'>can</span> <span m='1696310'>rewrite</span>
  <span m='1696730'>this</span> <span m='1697090'>this</span> <span m='1697450'>way.</span>
  <span m='1697900'>This</span> <span m='1698080'>is</span> <span m='1698200'>like</span>
  <span m='1699220'>a</span> <span m='1699250'>set</span> <span m='1699430'>of</span>
  <span m='1699520'>numbers.</span> <span m='1700760'>So</span> <span m='1700780'>I</span>
  <span m='1700840'>can</span> <span m='1700990'>write</span> <span m='1701200'>as
  a</span> <span m='1701260'>vector.</span> <span m='1701570'>I'll</span> <span m='1701660'>call
  it</span> <span m='1701900'>y.</span> <span m='1703540'>And</span> <span m='1704110'>this</span>
  <span m='1704350'>thing</span> <span m='1704590'>has</span> <span m='1704740'>two</span>
  <span m='1704920'>indices</span> <span m='1705280'>on</span> <span m='1705430'>it,</span>
  <span m='1705520'>so</span> <span m='1705670'>it</span> <span m='1705730'>looks</span>
  <span m='1705880'>like</span> <span m='1705970'>a</span> <span m='1706030'>matrix.</span>
  <span m='1707300'>So</span> <span m='1707380'>I'll</span> <span m='1707470'>call</span>
  <span m='1707710'>that</span> <span m='1708460'>m.</span> <span m='1710384'>And</span>
  <span m='1710865'>c</span> <span m='1712330'>is</span> <span m='1712560'>my</span>
  <span m='1712670'>vector</span> <span m='1713060'>of unknown</span> <span m='1713360'>parameters.</span>
  <span m='1714620'>And</span> <span m='1714930'>wow,</span> <span m='1715180'>I</span>
  <span m='1715240'>know</span> <span m='1715330'>how</span> <span m='1715390'>to</span>
  <span m='1715480'>solve</span> <span m='1715660'>this</span> <span m='1715780'>one.</span>
  <span m='1717560'>So</span> <span m='1717740'>c</span> <span m='1717940'>is</span>
  <span m='1718090'>equal</span> <span m='1718300'>to</span> <span m='1719950'>m</span>
  <span m='1720070'>backslash</span> <span m='1720550'>y.</span> </p><p><span m='1726200'>Now,</span>
  <span m='1726440'>for</span> <span m='1726560'>this</span> <span m='1726740'>to</span>
  <span m='1726920'>work</span> <span m='1727910'>and</span> <span m='1728030'>have</span>
  <span m='1728240'>a</span> <span m='1728420'>unique</span> <span m='1728780'>solution,</span>
  <span m='1729770'>I</span> <span m='1729830'>need</span> <span m='1730020'>m</span>
  <span m='1730160'>not</span> <span m='1730370'>to</span> <span m='1730430'>be</span>
  <span m='1730520'>singular.</span> <span m='1732200'>And</span> <span m='1732320'>what</span>
  <span m='1732440'>that</span> <span m='1732560'>means</span> <span m='1732890'>is</span>
  <span m='1733010'>that</span> <span m='1733100'>the</span> <span m='1733220'>columns</span>
  <span m='1733820'>of</span> <span m='1733940'>m</span> <span m='1734090'>have</span>
  <span m='1734210'>to</span> <span m='1734300'>be</span> <span m='1734430'>linearly</span>
  <span m='1734690'>independent.</span> <span m='1735530'>So</span> <span m='1735680'>what</span>
  <span m='1735770'>are</span> <span m='1735830'>the</span> <span m='1735920'>columns</span>
  <span m='1736310'>of</span> <span m='1736410'>m?</span> <span m='1737120'>They</span>
  <span m='1737390'>are</span> <span m='1741450'>phi</span> <span m='1741775'>k</span>
  <span m='1742400'>of</span> <span m='1742700'>t1,</span> <span m='1744400'>phi</span>
  <span m='1744560'>k</span> <span m='1745070'>of</span> <span m='1745340'>t2,</span>
  <span m='1748530'>phi</span> <span m='1748730'>k</span> <span m='1749940'>of</span>
  <span m='1750090'>tn.</span> <span m='1754160'>And</span> <span m='1754310'>I</span>
  <span m='1754400'>want</span> <span m='1754610'>that</span> <span m='1754760'>this</span>
  <span m='1755000'>column</span> <span m='1756680'>is</span> <span m='1757250'>not</span>
  <span m='1758380'>a</span> <span m='1759000'>sum</span> <span m='1760640'>of</span>
  <span m='1760820'>the</span> <span m='1760880'>other</span> <span m='1761060'>columns.</span>
  </p><p><span m='1776030'>So</span> <span m='1776080'>this</span> <span m='1776260'>is</span>
  <span m='1776380'>kind</span> <span m='1776530'>of</span> <span m='1776630'>requirement</span>
  <span m='1777790'>for</span> <span m='1777910'>j</span> <span m='1778100'>not equal</span>
  <span m='1778508'>[? to k ?]</span> <span m='1779732'>This</span> <span m='1780140'>is</span>
  <span m='1780330'>kind</span> <span m='1780450'>of a</span> <span m='1780510'>requirement</span>
  <span m='1780990'>if</span> <span m='1781110'>I'm going</span> <span m='1781240'>to</span>
  <span m='1781300'>do</span> <span m='1781410'>this</span> <span m='1781530'>kind</span>
  <span m='1781680'>of</span> <span m='1781740'>procedure</span> <span m='1782250'>is</span>
  <span m='1782430'>I</span> <span m='1782520'>can't</span> <span m='1782920'>choose</span>
  <span m='1784260'>a</span> <span m='1784320'>set</span> <span m='1784470'>of</span>
  <span m='1784530'>basis</span> <span m='1784860'>functions</span> <span m='1786390'>that's</span>
  <span m='1786600'>going</span> <span m='1786750'>to</span> <span m='1786900'>have</span>
  <span m='1787710'>one</span> <span m='1787830'>of</span> <span m='1787890'>them</span>
  <span m='1788010'>be</span> <span m='1788160'>a</span> <span m='1788220'>linear</span>
  <span m='1788430'>combination</span> <span m='1788850'>of</span> <span m='1788920'>the</span>
  <span m='1788970'>other</span> <span m='1789120'>ones.</span> <span m='1789810'>Because</span>
  <span m='1790050'>then I'm</span> <span m='1790310'>going to get a</span> <span
  m='1790350'>singular</span> <span m='1790620'>matrix.</span> <span m='1790980'>My</span>
  <span m='1791070'>whole</span> <span m='1791190'>process</span> <span m='1791580'>is</span>
  <span m='1791670'>going to</span> <span m='1791760'>have a</span> <span m='1791790'>big</span>
  <span m='1791910'>problem</span> <span m='1792210'>right</span> <span m='1792300'>from</span>
  <span m='1792390'>the</span> <span m='1792450'>beginning.</span> <span m='1793540'>So</span>
  <span m='1793560'>I</span> <span m='1793620'>have</span> <span m='1793740'>to</span>
  <span m='1793810'>ensure</span> <span m='1794220'>that</span> <span m='1794350'>this</span>
  <span m='1794520'>is</span> <span m='1794610'>not</span> <span m='1794850'>true.</span>
  <span m='1796290'>Yeah,</span> <span m='1796660'>that</span> <span m='1796790'>this</span>
  <span m='1797130'>is</span> <span m='1797220'>true.</span> <span m='1797550'>These</span>
  <span m='1797700'>are</span> <span m='1797760'>not</span> <span m='1797970'>equal</span>
  <span m='1798585'>to</span> <span m='1798900'>some</span> <span m='1799080'>of</span>
  <span m='1799140'>them.</span> </p><p><span m='1802400'>Another</span> <span m='1802700'>way</span>
  <span m='1802820'>to</span> <span m='1802910'>write</span> <span m='1803210'>that</span>
  <span m='1807890'>is</span> <span m='1808010'>to</span> <span m='1812260'>choose</span>
  <span m='1812540'>the</span> <span m='1813910'>the</span> <span m='1814010'>columns</span>
  <span m='1814370'>that</span> <span m='1814450'>phi</span> <span m='1814570'>to</span>
  <span m='1814670'>be</span> <span m='1814820'>orthogonal</span> <span m='1815390'>to</span>
  <span m='1815510'>each</span> <span m='1815660'>other.</span> <span m='1817070'>And</span>
  <span m='1817180'>so</span> <span m='1817300'>I</span> <span m='1817370'>can</span>
  <span m='1817490'>write</span> <span m='1817670'>it</span> <span m='1817700'>this</span>
  <span m='1817880'>way.</span> <span m='1834760'>OK,</span> <span m='1836020'>so</span>
  <span m='1836200'>I</span> <span m='1836260'>want</span> <span m='1836440'>them</span>
  <span m='1836560'>to</span> <span m='1836800'>be</span> <span m='1836920'>orthogonal</span>
  <span m='1837340'>to</span> <span m='1837400'>each</span> <span m='1837520'>other.</span>
  </p><p><span m='1838220'>And</span> <span m='1838240'>then</span> <span m='1838330'>you</span>
  <span m='1838410'>can</span> <span m='1838540'>see</span> <span m='1838660'>how</span>
  <span m='1838780'>this</span> <span m='1838920'>kind</span> <span m='1839020'>of</span>
  <span m='1839190'>generalizes.</span> <span m='1839585'>If</span> <span m='1839980'>I</span>
  <span m='1840130'>had</span> <span m='1840250'>a</span> <span m='1840280'>lot</span>
  <span m='1840460'>of</span> <span m='1840520'>t's,</span> <span m='1841320'>this</span>
  <span m='1841450'>would</span> <span m='1841690'>sort</span> <span m='1841900'>of</span>
  <span m='1842280'>look</span> <span m='1842470'>like</span> <span m='1843080'>the</span>
  <span m='1843210'>integral</span> <span m='1844310'>of</span> <span m='1844740'>phi</span>
  <span m='1845020'>k</span> <span m='1845300'>of</span> <span m='1845480'>t,</span>
  <span m='1846010'>phi</span> <span m='1846510'>j</span> <span m='1846997'>of t</span>
  <span m='1848458'>is equal</span> <span m='1848945'>to 0.</span> <span m='1855770'>And</span>
  <span m='1856040'>so</span> <span m='1856190'>this</span> <span m='1856460'>gives</span>
  <span m='1856640'>the</span> <span m='1856700'>idea</span> <span m='1857030'>of</span>
  <span m='1857480'>orthogonal</span> <span m='1858050'>functions.</span> <span m='1858770'>So</span>
  <span m='1858890'>this</span> <span m='1859100'>is</span> <span m='1859220'>orthogonal</span>
  <span m='1860030'>functions,</span> <span m='1861390'>and</span> <span m='1861530'>my</span>
  <span m='1861680'>discrete</span> <span m='1861980'>point's</span> <span m='1862320'>tn.</span>
  <span m='1863490'>And</span> <span m='1863810'>this</span> <span m='1863990'>is</span>
  <span m='1864110'>the</span> <span m='1864230'>general</span> <span m='1864590'>concept</span>
  <span m='1865080'>of</span> <span m='1865270'>orthogonal</span> <span m='1865580'>functions.</span>
  </p><p><span m='1867410'>And</span> <span m='1867590'>then</span> <span m='1867890'>when</span>
  <span m='1868070'>I</span> <span m='1868130'>define</span> <span m='1868490'>it</span>
  <span m='1868550'>this</span> <span m='1868730'>way,</span> <span m='1868880'>I</span>
  <span m='1869030'>need</span> <span m='1869190'>to</span> <span m='1869300'>actually</span>
  <span m='1870090'>decide</span> <span m='1870410'>my</span> <span m='1870590'>own</span>
  <span m='1870830'>a's</span> <span m='1871070'>and</span> <span m='1871160'>b's</span>
  <span m='1871430'>that</span> <span m='1871520'>I</span> <span m='1871580'>want</span>
  <span m='1871700'>to</span> <span m='1871760'>use.</span> <span m='1873000'>And</span>
  <span m='1873265'>if you</span> <span m='1873530'>use</span> <span m='1873800'>different</span>
  <span m='1874010'>ones,</span> <span m='1874270'>you</span> <span m='1874320'>actually</span>
  <span m='1874640'>have</span> <span m='1874730'>different</span> <span m='1874970'>rules</span>
  <span m='1875630'>about</span> <span m='1875750'>what's</span> <span m='1875890'>orthogonal</span>
  <span m='1876340'>to</span> <span m='1876400'>each</span> <span m='1876560'>other.</span>
  <span m='1877280'>And</span> <span m='1877460'>also,</span> <span m='1878360'>sometimes,</span>
  <span m='1878780'>people</span> <span m='1879070'>are</span> <span m='1879740'>fishy,</span>
  <span m='1880040'>and</span> <span m='1880130'>they</span> <span m='1880220'>[?
  spit ?]</span> <span m='1880480'>a</span> <span m='1880520'>little</span> <span
  m='1880790'>w</span> <span m='1881190'>of</span> <span m='1881800'>t</span> <span
  m='1882030'>in</span> <span m='1882140'>here</span> <span m='1883430'>just</span>
  <span m='1883620'>to</span> <span m='1883700'>do,</span> <span m='1884120'>because</span>
  <span m='1884300'>they</span> <span m='1884600'>have</span> <span m='1884730'>some</span>
  <span m='1884810'>special</span> <span m='1885110'>problem</span> <span m='1885440'>where</span>
  <span m='1885540'>this</span> <span m='1885640'>w</span> <span m='1885890'>keeps</span>
  <span m='1886060'>showing</span> <span m='1886340'>up</span> <span m='1886460'>or</span>
  <span m='1886550'>something,</span> <span m='1886790'>and</span> <span m='1886880'>they</span>
  <span m='1886970'>want</span> <span m='1887090'>to</span> <span m='1887420'>do</span>
  <span m='1887510'>that.</span> <span m='1887690'>But</span> <span m='1887820'>that's</span>
  <span m='1888200'>up</span> <span m='1888250'>to</span> <span m='1888350'>them.</span>
  <span m='1889650'>All</span> <span m='1889770'>right,</span> <span m='1890020'>we</span>
  <span m='1890180'>won't</span> <span m='1890320'>specify</span> <span m='1890680'>that.</span>
  </p><p><span m='1890800'>But</span> <span m='1891160'>this</span> <span m='1891310'>is</span>
  <span m='1891370'>the</span> <span m='1891490'>general</span> <span m='1891730'>idea</span>
  <span m='1891910'>of</span> <span m='1892060'>making</span> <span m='1892450'>basis</span>
  <span m='1892840'>functions</span> <span m='1893200'>orthogonal</span> <span m='1893230'>to
  each</span> <span m='1893650'>other.</span> <span m='1895540'>And</span> <span m='1895800'>it's</span>
  <span m='1895930'>very</span> <span m='1896200'>analogous</span> <span m='1896710'>to</span>
  <span m='1896770'>making</span> <span m='1896980'>vectors</span> <span m='1897280'>orthogonal</span>
  <span m='1897370'>to</span> <span m='1897840'>each</span> <span m='1898000'>other,</span>
  <span m='1898250'>which</span> <span m='1898300'>is</span> <span m='1898390'>what</span>
  <span m='1898510'>we</span> <span m='1898600'>did</span> <span m='1898750'>here.</span>
  <span m='1898990'>These</span> <span m='1899170'>are</span> <span m='1899260'>actually</span>
  <span m='1899500'>vectors.</span> <span m='1901140'>Right,</span> <span m='1901730'>it's</span>
  <span m='1901840'>just</span> <span m='1901990'>as</span> <span m='1902140'>the</span>
  <span m='1902200'>vector</span> <span m='1902440'>gets</span> <span m='1902620'>longer</span>
  <span m='1902980'>and</span> <span m='1903070'>longer,</span> <span m='1903430'>it</span>
  <span m='1903490'>gets</span> <span m='1903640'>more</span> <span m='1903790'>and</span>
  <span m='1903880'>more</span> <span m='1904000'>like</span> <span m='1904150'>the</span>
  <span m='1904210'>continuous</span> <span m='1904660'>function,</span> <span m='1904990'>and
  we</span> <span m='1905050'>have</span> <span m='1905140'>more</span> <span m='1905420'>t
  points.</span> <span m='1906580'>And</span> <span m='1906670'>eventually,</span>
  <span m='1907000'>it</span> <span m='1907060'>looks</span> <span m='1907240'>like</span>
  <span m='1907330'>that</span> <span m='1907430'>integral</span> <span m='1908420'>as</span>
  <span m='1908560'>you</span> <span m='1908660'>go</span> <span m='1908720'>to</span>
  <span m='1908780'>infinity.</span> </p><p><span m='1912340'>So</span> <span m='1912490'>anyway,</span>
  <span m='1912700'>so</span> <span m='1912820'>a</span> <span m='1912850'>lot</span>
  <span m='1912970'>of</span> <span m='1913030'>times,</span> <span m='1913310'>people</span>
  <span m='1913540'>will</span> <span m='1913660'>choose</span> <span m='1914800'>functions</span>
  <span m='1915220'>which</span> <span m='1915340'>are</span> <span m='1915430'>designed</span>
  <span m='1915880'>to</span> <span m='1915940'>be</span> <span m='1916000'>orthogonal.</span>
  <span m='1917290'>And</span> <span m='1917620'>one</span> <span m='1917800'>way</span>
  <span m='1917890'>to</span> <span m='1917980'>do</span> <span m='1918130'>it</span>
  <span m='1918220'>is</span> <span m='1918420'>just to</span> <span m='1918820'>go</span>
  <span m='1919030'>with</span> <span m='1919180'>a</span> <span m='1919240'>continuous</span>
  <span m='1919630'>one</span> <span m='1919720'>to</span> <span m='1919780'>start.</span>
  <span m='1922690'>Now,</span> <span m='1923230'>we</span> <span m='1923380'>can</span>
  <span m='1923560'>choose</span> <span m='1923800'>any</span> <span m='1923950'>basis</span>
  <span m='1924250'>functions</span> <span m='1924520'>we</span> <span m='1924670'>want.</span>
  <span m='1925570'>Over</span> <span m='1925810'>here,</span> <span m='1925990'>we</span>
  <span m='1926080'>already</span> <span m='1926290'>chose</span> <span m='1926530'>a</span>
  <span m='1926590'>whole</span> <span m='1926710'>bunch.</span> <span m='1927430'>You</span>
  <span m='1927520'>guys</span> <span m='1927700'>have</span> <span m='1927790'>done</span>
  <span m='1927940'>this</span> <span m='1928060'>already.</span> <span m='1929180'>I
  don't know</span> <span m='1929380'>if</span> <span m='1929470'>you</span> <span
  m='1929550'>knew</span> <span m='1929680'>you were</span> <span m='1929800'>doing</span>
  <span m='1929990'>it.</span> <span m='1930070'>But</span> <span m='1930160'>you</span>
  <span m='1930220'>chose</span> <span m='1930430'>a</span> <span m='1930490'>lot</span>
  <span m='1930610'>of</span> <span m='1930670'>different</span> <span m='1930880'>basis</span>
  <span m='1931230'>functions</span> <span m='1931300'>completely</span> <span m='1931570'>different</span>
  <span m='1931780'>from</span> <span m='1931900'>each</span> <span m='1932020'>other.</span>
  <span m='1933260'>You</span> <span m='1933310'>can</span> <span m='1933430'>choose</span>
  <span m='1933670'>the</span> <span m='1933730'>different</span> <span m='1933940'>ones</span>
  <span m='1934180'>if</span> <span m='1934240'>you</span> <span m='1934330'>want.</span>
  </p><p><span m='1936170'>And</span> <span m='1938440'>one</span> <span m='1938890'>popular</span>
  <span m='1939490'>choice</span> <span m='1940080'>is</span> <span m='1940180'>polynomials.</span>
  <span m='1941680'>But</span> <span m='1942010'>it's</span> <span m='1942130'>not</span>
  <span m='1942370'>the</span> <span m='1942460'>only</span> <span m='1942670'>choice.</span>
  <span m='1943180'>And</span> <span m='1943330'>in</span> <span m='1943420'>fact,</span>
  <span m='1944110'>a</span> <span m='1944140'>little bit</span> <span m='1944380'>later,</span>
  <span m='1944710'>we're</span> <span m='1944890'>going</span> <span m='1945040'>to,</span>
  <span m='1945755'>in</span> <span m='1946200'>the</span> <span m='1946290'>homework</span>
  <span m='1946500'>problem</span> <span m='1946830'>six,</span> <span m='1947180'>I</span>
  <span m='1947230'>think</span> <span m='1947410'>we're</span> <span m='1947470'>going</span>
  <span m='1947590'>to</span> <span m='1947650'>have</span> <span m='1947920'>a</span>
  <span m='1948220'>problem</span> <span m='1948550'>where</span> <span m='1948640'>you
  have</span> <span m='1948760'>to</span> <span m='1948850'>use</span> <span m='1948940'>a</span>
  <span m='1949000'>different</span> <span m='1949210'>kind</span> <span m='1949330'>of</span>
  <span m='1949390'>basis</span> <span m='1949600'>functions.</span> <span m='1950530'>You</span>
  <span m='1950590'>can</span> <span m='1950710'>use</span> <span m='1950800'>any</span>
  <span m='1950920'>basis</span> <span m='1951250'>functions</span> <span m='1951370'>you</span>
  <span m='1951460'>want.</span> <span m='1952150'>And</span> <span m='1952240'>there's</span>
  <span m='1952390'>kind</span> <span m='1952600'>of</span> <span m='1952660'>ones</span>
  <span m='1952900'>that</span> <span m='1953020'>match</span> <span m='1953320'>naturally</span>
  <span m='1953710'>to</span> <span m='1953770'>the</span> <span m='1953890'>problem.</span>
  </p><p><span m='1955110'>However,</span> <span m='1956800'>people</span> <span m='1957010'>know</span>
  <span m='1957160'>a</span> <span m='1957190'>lot</span> <span m='1957310'>about</span>
  <span m='1957400'>polynomials.</span> <span m='1958930'>And</span> <span m='1959140'>so</span>
  <span m='1960760'>they've</span> <span m='1961090'>decided</span> <span m='1961580'>to
  use</span> <span m='1961710'>polynomials</span> <span m='1961960'>a</span> <span
  m='1962180'>lot.</span> <span m='1962770'>And</span> <span m='1962950'>so</span>
  <span m='1963310'>that's</span> <span m='1963670'>the</span> <span m='1963760'>most</span>
  <span m='1963940'>common</span> <span m='1964270'>choice</span> <span m='1964530'>for</span>
  <span m='1964660'>numerical</span> <span m='1964990'>integration is</span> <span
  m='1965470'>polynomials.</span> <span m='1966500'>One</span> <span m='1966740'>thing</span>
  <span m='1966880'>is</span> <span m='1967070'>polynomials</span> <span m='1967440'>are</span>
  <span m='1967570'>super</span> <span m='1967840'>easy</span> <span m='1968050'>to</span>
  <span m='1968170'>integrate,</span> <span m='1968870'>because</span> <span m='1969030'>that</span>
  <span m='1969080'>was</span> <span m='1969190'>the</span> <span m='1969250'>first</span>
  <span m='1969460'>thing</span> <span m='1969580'>you</span> <span m='1969640'>learned,</span>
  <span m='1970150'>right,</span> <span m='1970630'>how</span> <span m='1970720'>to
  do</span> <span m='1970880'>the</span> <span m='1971100'>intervals</span> <span
  m='1971320'>of</span> <span m='1971500'>polynomials.</span> <span m='1972700'>And</span>
  <span m='1972940'>also,</span> <span m='1973630'>they're</span> <span m='1973750'>easy</span>
  <span m='1973960'>to</span> <span m='1974020'>evaluate.</span> <span m='1974830'>It</span>
  <span m='1974920'>only</span> <span m='1975040'>takes</span> <span m='1975250'>n</span>
  <span m='1975370'>operations</span> <span m='1975655'>to</span> <span m='1975940'>evaluate</span>
  <span m='1976090'>a</span> <span m='1976250'>polynomial</span> <span m='1976900'>of</span>
  <span m='1977280'>nth</span> <span m='1977530'>order.</span> <span m='1978340'>And</span>
  <span m='1979000'>there's</span> <span m='1979180'>a</span> <span m='1979240'>ton</span>
  <span m='1979390'>of</span> <span m='1979490'>theorems,</span> <span m='1980590'>and</span>
  <span m='1981490'>things</span> <span m='1981670'>are</span> <span m='1981730'>known</span>
  <span m='1981940'>about</span> <span m='1982090'>polynomials.</span> <span m='1982470'>We</span>
  <span m='1982600'>have</span> <span m='1982690'>all</span> <span m='1982780'>kinds</span>
  <span m='1982930'>of</span> <span m='1982990'>special</span> <span m='1983290'>properties.</span>
  <span m='1983800'>And</span> <span m='1983890'>we</span> <span m='1983950'>have</span>
  <span m='1984040'>all</span> <span m='1984100'>kinds</span> <span m='1984280'>of</span>
  <span m='1984340'>convenient</span> <span m='1984640'>tools</span> <span m='1984850'>for</span>
  <span m='1984940'>handling</span> <span m='1985240'>them.</span> <span m='1985420'>So</span>
  <span m='1986110'>let's</span> <span m='1986230'>go</span> <span m='1986350'>with</span>
  <span m='1986620'>polynomials</span> <span m='1986830'>for</span> <span m='1986950'>now.</span>
  </p><p><span m='1988710'>Now,</span> <span m='1988860'>I</span> <span m='1988920'>want</span>
  <span m='1989040'>to</span> <span m='1989130'>warn</span> <span m='1989370'>you,</span>
  <span m='1989460'>though,</span> <span m='1990390'>that</span> <span m='1991690'>how
  you</span> <span m='1992090'>order</span> <span m='1992310'>polynomials</span> <span
  m='1992490'>are</span> <span m='1992730'>really</span> <span m='1993030'>not</span>
  <span m='1993360'>very</span> <span m='1993600'>good</span> <span m='1996030'>fitting</span>
  <span m='1996240'>functions</span> <span m='1997230'>or</span> <span m='1997330'>interpolating</span>
  <span m='1997950'>functions</span> <span m='1998640'>for</span> <span m='1998790'>a</span>
  <span m='1998820'>lot</span> <span m='1998940'>of</span> <span m='1999000'>problems.</span>
  <span m='2000020'>And</span> <span m='2000230'>in</span> <span m='2000290'>particular,</span>
  <span m='2001400'>for</span> <span m='2001580'>this</span> <span m='2001790'>one</span>
  <span m='2001980'>I</span> <span m='2002420'>showed</span> <span m='2002710'>here</span>
  <span m='2003070'>where</span> <span m='2003380'>this</span> <span m='2003560'>is</span>
  <span m='2003650'>the</span> <span m='2003740'>function.</span> <span m='2005620'>Here,</span>
  <span m='2006540'>that</span> <span m='2006710'>function,</span> <span m='2009980'>you</span>
  <span m='2010100'>can</span> <span m='2010400'>try</span> <span m='2010640'>to</span>
  <span m='2010700'>fit</span> <span m='2010910'>that</span> <span m='2011360'>with</span>
  <span m='2011600'>higher</span> <span m='2011840'>and</span> <span m='2011900'>higher</span>
  <span m='2012110'>order</span> <span m='2012320'>polynomials.</span> <span m='2012890'>So</span>
  <span m='2013070'>I</span> <span m='2013130'>can</span> <span m='2013280'>have</span>
  <span m='2013350'>my</span> <span m='2013490'>function.</span> <span m='2018670'>The</span>
  <span m='2018790'>function</span> <span m='2019030'>value</span> <span m='2019920'>at</span>
  <span m='2020080'>0 is</span> <span m='2020440'>1.</span> <span m='2021700'>So</span>
  <span m='2022090'>the</span> <span m='2022360'>function</span> <span m='2022630'>looks</span>
  <span m='2022840'>kind</span> <span m='2023020'>of</span> <span m='2023080'>reasonable.</span>
  <span m='2027060'>Like that,</span> <span m='2027300'>symmetrical,</span> <span
  m='2028120'>better</span> <span m='2028410'>than</span> <span m='2028780'>I</span>
  <span m='2028850'>drew</span> <span m='2029130'>it.</span> </p><p><span m='2030650'>And</span>
  <span m='2031670'>you</span> <span m='2031790'>can</span> <span m='2031910'>put</span>
  <span m='2032470'>some</span> <span m='2032780'>number</span> <span m='2033000'>of</span>
  <span m='2033040'>points</span> <span m='2033310'>in</span> <span m='2033410'>here.</span>
  <span m='2036300'>And</span> <span m='2036420'>then</span> <span m='2036600'>you</span>
  <span m='2036750'>can</span> <span m='2036930'>do</span> <span m='2037170'>an</span>
  <span m='2037290'>interpolating</span> <span m='2037555'>polynomial</span> <span
  m='2038340'>that</span> <span m='2038550'>goes</span> <span m='2038780'>through</span>
  <span m='2038940'>all</span> <span m='2039030'>the</span> <span m='2039090'>points.</span>
  <span m='2041640'>And</span> <span m='2041790'>if</span> <span m='2041880'>you</span>
  <span m='2041940'>do</span> <span m='2042160'>it</span> <span m='2043760'>for</span>
  <span m='2043890'>this</span> <span m='2044100'>one</span> <span m='2045030'>with</span>
  <span m='2045270'>five</span> <span m='2045660'>points,</span> <span m='2047400'>you'll</span>
  <span m='2047520'>get</span> <span m='2047640'>something</span> <span m='2047880'>that</span>
  <span m='2047930'>looks</span> <span m='2048120'>like</span> <span m='2048730'>this.</span>
  <span m='2051409'>It</span> <span m='2051570'>goes</span> <span m='2051820'>negative,</span>
  <span m='2054190'>comes</span> <span m='2054400'>up</span> <span m='2054520'>like</span>
  <span m='2054670'>this,</span> <span m='2055436'>goes</span> <span m='2055820'>negative</span>
  <span m='2056159'>again.</span> <span m='2058150'>So</span> <span m='2059260'>that's</span>
  <span m='2060540'>one</span> <span m='2060909'>you</span> <span m='2060969'>get</span>
  <span m='2061090'>if you</span> <span m='2061179'>use</span> <span m='2061360'>five</span>
  <span m='2061570'>points</span> <span m='2063280'>across</span> <span m='2063520'>this</span>
  <span m='2063679'>interval.</span> <span m='2063969'>If</span> <span m='2064090'>you</span>
  <span m='2064210'>use</span> <span m='2064389'>10</span> <span m='2064659'>points,</span>
  <span m='2066040'>then</span> <span m='2066159'>you</span> <span m='2066250'>get</span>
  <span m='2066340'>one</span> <span m='2066489'>that</span> <span m='2066610'>looks</span>
  <span m='2066790'>like</span> <span m='2066940'>this</span> <span m='2081179'>where</span>
  <span m='2081239'>the</span> <span m='2081320'>peak</span> <span m='2081560'>value</span>
  <span m='2081800'>here</span> <span m='2081960'>is</span> <span m='2082110'>two</span>
  <span m='2082949'>where</span> <span m='2083170'>as the</span> <span m='2083270'>max</span>
  <span m='2083510'>of the</span> <span m='2083630'>original</span> <span m='2083719'>function's</span>
  <span m='2084020'>just</span> <span m='2084170'>one.</span> <span m='2085280'>And</span>
  <span m='2085400'>the</span> <span m='2085530'>original</span> <span m='2085820'>function's</span>
  <span m='2086449'>always</span> <span m='2086719'>positive,</span> <span m='2087170'>but</span>
  <span m='2087590'>they</span> <span m='2087710'>both</span> <span m='2087949'>go</span>
  <span m='2088100'>negative.</span> </p><p><span m='2089520'>So</span> <span m='2090830'>even</span>
  <span m='2091400'>within</span> <span m='2091909'>the</span> <span m='2092030'>range</span>
  <span m='2092449'>of</span> <span m='2092510'>the</span> <span m='2092600'>interpolation,</span>
  <span m='2094130'>the</span> <span m='2094219'>polynomials</span> <span m='2094699'>can</span>
  <span m='2094790'>have</span> <span m='2094909'>wild</span> <span m='2095360'>swings.</span>
  <span m='2096590'>And</span> <span m='2096889'>so</span> <span m='2096949'>this</span>
  <span m='2097040'>first</span> <span m='2097320'>one</span> <span m='2097420'>was</span>
  <span m='2097460'>for</span> <span m='2097670'>a</span> <span m='2097700'>fifth</span>
  <span m='2097930'>order</span> <span m='2099290'>polynomial,</span> <span m='2100740'>or</span>
  <span m='2100880'>maybe</span> <span m='2101030'>fourth</span> <span m='2101280'>order,</span>
  <span m='2101660'>five</span> <span m='2101840'>points.</span> <span m='2103280'>And</span>
  <span m='2103400'>this</span> <span m='2103550'>one</span> <span m='2103670'>is</span>
  <span m='2103790'>for</span> <span m='2104000'>the</span> <span m='2104090'>next</span>
  <span m='2105170'>10th</span> <span m='2105390'>order</span> <span m='2105650'>or</span>
  <span m='2105830'>9th</span> <span m='2106330'>order</span> <span m='2106630'>polynomial.</span>
  <span m='2107350'>I'm</span> <span m='2107450'>not</span> <span m='2107550'>sure</span>
  <span m='2107650'>which</span> <span m='2107730'>one.</span> <span m='2109950'>Yes.</span>
  </p><p><span m='2110260'>AUDIENCE:</span> <span m='2110390'>What</span> <span m='2110520'>points</span>
  <span m='2110650'>are</span> <span m='2111040'>these</span> <span m='2111430'>polynomials</span>
  <span m='2111873'>trying to</span> <span m='2112316'>fit?</span> <span m='2112760'>Or
  does it</span> <span m='2113140'>seem like</span> <span m='2113310'>[INAUDIBLE]?</span>
  </p><p><span m='2115430'>PROFESSOR:</span> <span m='2115595'>So</span> <span m='2115760'>I</span>
  <span m='2116030'>didn't</span> <span m='2116180'>draw</span> <span m='2116330'>very</span>
  <span m='2116480'>well.</span> <span m='2118220'>When</span> <span m='2118460'>you</span>
  <span m='2118560'>guys</span> <span m='2118880'>go</span> <span m='2119000'>home,</span>
  <span m='2119240'>do</span> <span m='2119780'>this.</span> <span m='2119960'>Right,</span>
  <span m='2120100'>on</span> <span m='2120200'>Matlab</span> <span m='2120320'>it
  will</span> <span m='2120470'>take you</span> <span m='2120650'>a</span> <span m='2120720'>minute</span>
  <span m='2123100'>to</span> <span m='2123200'>solve</span> <span m='2123500'>this</span>
  <span m='2123680'>equation</span> <span m='2125380'>where</span> <span m='2125520'>you</span>
  <span m='2125590'>put</span> <span m='2125790'>in</span> <span m='2125920'>the</span>
  <span m='2126070'>function</span> <span m='2126400'>values</span> <span m='2126720'>here.</span>
  <span m='2127870'>And</span> <span m='2129700'>put</span> <span m='2129900'>in</span>
  <span m='2130030'>the</span> <span m='2130150'>polynomial</span> <span m='2131440'>values</span>
  <span m='2131740'>that</span> <span m='2131860'>[INAUDIBLE]</span> <span m='2133670'>here</span>
  <span m='2133980'>for</span> <span m='2134370'>the</span> <span m='2134910'>monomials,</span>
  <span m='2136110'>t</span> <span m='2136680'>to</span> <span m='2136800'>the</span>
  <span m='2136890'>first</span> <span m='2137100'>power,</span> <span m='2137270'>to
  the</span> <span m='2137430'>second</span> <span m='2137530'>power,</span> <span
  m='2137970'>to the</span> <span m='2138255'>third power,</span> <span m='2138540'>like
  that.</span> <span m='2139340'>And</span> <span m='2139440'>just</span> <span m='2139590'>do</span>
  <span m='2139710'>it,</span> <span m='2139980'>and</span> <span m='2140240'>you</span>
  <span m='2140330'>can</span> <span m='2140440'>get</span> <span m='2140540'>the</span>
  <span m='2140610'>[? pot ?]</span> <span m='2140760'>yourself.</span> </p><p><span
  m='2143250'>And</span> <span m='2143790'>just</span> <span m='2144020'>to</span>
  <span m='2144210'>convince</span> <span m='2144330'>yourself</span> <span m='2144630'>about</span>
  <span m='2144810'>the</span> <span m='2144900'>problem,</span> <span m='2145230'>and</span>
  <span m='2145430'>this</span> <span m='2145520'>is</span> <span m='2145650'>very</span>
  <span m='2145830'>important</span> <span m='2146280'>to</span> <span m='2146400'>keep</span>
  <span m='2146550'>in</span> <span m='2146640'>mind.</span> <span m='2147720'>Because</span>
  <span m='2147930'>we're</span> <span m='2148020'>so</span> <span m='2148200'>used</span>
  <span m='2148350'>to</span> <span m='2148410'>using</span> <span m='2148620'>polynomials</span>
  <span m='2149070'>that</span> <span m='2149100'>think</span> <span m='2149250'>they're</span>
  <span m='2149370'>the</span> <span m='2149460'>solution</span> <span m='2149730'>to</span>
  <span m='2149790'>everything.</span> <span m='2150150'>And</span> <span m='2150240'>Excel</span>
  <span m='2150540'>does them</span> <span m='2150780'>great.</span> <span m='2151830'>But</span>
  <span m='2152340'>it's</span> <span m='2152460'>not</span> <span m='2152760'>this</span>
  <span m='2152880'>solution to</span> <span m='2153330'>everything.</span> <span
  m='2155010'>Nonetheless,</span> <span m='2155295'>we're</span> <span m='2155580'>going
  to</span> <span m='2155840'>plow</span> <span m='2156120'>on</span> <span m='2156590'>and</span>
  <span m='2156750'>keep</span> <span m='2156890'>using</span> <span m='2157110'>them
  for</span> <span m='2157260'>a</span> <span m='2157290'>few</span> <span m='2157410'>minutes.</span>
  </p><p><span m='2162790'>So</span> <span m='2164490'>one</span> <span m='2165090'>possibility</span>
  <span m='2166380'>when</span> <span m='2166530'>I'm</span> <span m='2166620'>choosing</span>
  <span m='2166890'>this</span> <span m='2166990'>basis</span> <span m='2167320'>set</span>
  <span m='2168200'>is</span> <span m='2168480'>I</span> <span m='2168570'>could</span>
  <span m='2168820'>choose</span> <span m='2169920'>what</span> <span m='2170040'>are</span>
  <span m='2170070'>called</span> <span m='2170280'>monomials,</span> <span m='2174140'>which</span>
  <span m='2174320'>is</span> <span m='2174500'>phi</span> <span m='2174910'>k</span>
  <span m='2175460'>is</span> <span m='2175640'>equal</span> <span m='2175910'>to</span>
  <span m='2176180'>x</span> <span m='2176480'>to</span> <span m='2176570'>the</span>
  <span m='2176690'>k minus</span> <span m='2176930'>1.</span> <span m='2181370'>And</span>
  <span m='2182060'>this</span> <span m='2182270'>one</span> <span m='2182810'>is</span>
  <span m='2182930'>super</span> <span m='2183230'>simple.</span> <span m='2186200'>And</span>
  <span m='2186940'>so</span> <span m='2187210'>a</span> <span m='2187240'>lot</span>
  <span m='2187400'>of</span> <span m='2187460'>times</span> <span m='2187760'>it</span>
  <span m='2187820'>satisfies</span> <span m='2188390'>this</span> <span m='2188540'>orthogonality</span>
  <span m='2189290'>thing,</span> <span m='2189760'>which</span> <span m='2189880'>I</span>
  <span m='2189940'>showed</span> <span m='2190170'>you</span> <span m='2190250'>before.</span>
  <span m='2192170'>But</span> <span m='2193580'>it's</span> <span m='2194580'>a</span>
  <span m='2194690'>really</span> <span m='2194900'>bad</span> <span m='2195140'>choice</span>
  <span m='2195410'>usually.</span> </p><p><span m='2196280'>And</span> <span m='2196430'>what</span>
  <span m='2196580'>it</span> <span m='2196670'>is</span> <span m='2196970'>is</span>
  <span m='2197090'>that</span> <span m='2197300'>the</span> <span m='2197900'>matrix</span>
  <span m='2198480'>you</span> <span m='2198580'>have</span> <span m='2198620'>to</span>
  <span m='2198740'>solve</span> <span m='2199520'>for</span> <span m='2199640'>this</span>
  <span m='2199770'>interpolation,</span> <span m='2201170'>if</span> <span m='2201350'>you</span>
  <span m='2201410'>have</span> <span m='2201560'>evenly-spaced</span> <span m='2203030'>points</span>
  <span m='2203780'>and</span> <span m='2203930'>you</span> <span m='2204050'>have</span>
  <span m='2205930'>x to the</span> <span m='2206280'>k,</span> <span m='2206960'>it</span>
  <span m='2207050'>turns</span> <span m='2207230'>out</span> <span m='2207320'>that</span>
  <span m='2207440'>this</span> <span m='2207650'>matrix</span> <span m='2208250'>usually</span>
  <span m='2209330'>has</span> <span m='2209570'>a</span> <span m='2209630'>condition</span>
  <span m='2210170'>number</span> <span m='2211010'>that</span> <span m='2211100'>grows</span>
  <span m='2211430'>exponentially</span> <span m='2212120'>with</span> <span m='2212240'>the</span>
  <span m='2212330'>number</span> <span m='2213430'>of</span> <span m='2213620'>terms</span>
  <span m='2213900'>in your</span> <span m='2214070'>basis,</span> <span m='2215430'>the</span>
  <span m='2215530'>number</span> <span m='2215670'>of</span> <span m='2215890'>how</span>
  <span m='2216020'>many</span> <span m='2216170'>monomials</span> <span m='2216590'>you</span>
  <span m='2216650'>include.</span> <span m='2217880'>So</span> <span m='2218810'>condition
  numbers</span> <span m='2219250'>that</span> <span m='2219350'>grow</span> <span
  m='2219530'>exponentially</span> <span m='2220010'>is</span> <span m='2220490'>really</span>
  <span m='2220670'>bad</span> <span m='2220850'>idea.</span> <span m='2223400'>So</span>
  <span m='2223550'>this</span> <span m='2223730'>is</span> <span m='2224060'>not</span>
  <span m='2224300'>what</span> <span m='2224390'>people</span> <span m='2224660'>use.</span>
  <span m='2225540'>So</span> <span m='2225590'>you</span> <span m='2225680'>might</span>
  <span m='2225800'>be</span> <span m='2225890'>tempted</span> <span m='2226190'>to</span>
  <span m='2226280'>do</span> <span m='2226430'>this,</span> <span m='2226710'>and</span>
  <span m='2226810'>maybe</span> <span m='2226820'>you</span> <span m='2226910'>did</span>
  <span m='2227030'>it</span> <span m='2227090'>once</span> <span m='2228020'>in</span>
  <span m='2228110'>your</span> <span m='2228200'>life.</span> <span m='2228540'>I</span>
  <span m='2228640'>won't</span> <span m='2228920'>blame</span> <span m='2229200'>you</span>
  <span m='2229410'>if</span> <span m='2229680'>you</span> <span m='2229820'>did.</span>
  <span m='2230180'>But</span> <span m='2230840'>it's</span> <span m='2230990'>not
  a</span> <span m='2231160'>really</span> <span m='2231300'>smart</span> <span m='2231500'>idea.</span>
  </p><p><span m='2231980'>So</span> <span m='2232220'>instead,</span> <span m='2233270'>a</span>
  <span m='2233330'>lot</span> <span m='2233540'>of</span> <span m='2233600'>the</span>
  <span m='2233660'>mathematicians</span> <span m='2234350'>of</span> <span m='2234680'>the</span>
  <span m='2235040'>1700s</span> <span m='2235400'>and</span> <span m='2235490'>1800s</span>
  <span m='2235970'>spent</span> <span m='2236120'>a</span> <span m='2236150'>lot</span>
  <span m='2236270'>of</span> <span m='2236330'>time</span> <span m='2236510'>worrying</span>
  <span m='2236730'>about</span> <span m='2236930'>this.</span> <span m='2239040'>And</span>
  <span m='2240080'>they'd</span> <span m='2240410'>end</span> <span m='2240590'>up</span>
  <span m='2240680'>deciding</span> <span m='2243080'>to</span> <span m='2243200'>use</span>
  <span m='2243410'>other</span> <span m='2243620'>polynomials</span> <span m='2244010'>that</span>
  <span m='2244250'>have</span> <span m='2244430'>people's</span> <span m='2244730'>names</span>
  <span m='2244970'>on</span> <span m='2245060'>them.</span> <span m='2246050'>So</span>
  <span m='2247190'>a</span> <span m='2247250'>guy</span> <span m='2247580'>named</span>
  <span m='2254100'>Lagrange,</span> <span m='2254570'>the</span> <span m='2254630'>same</span>
  <span m='2254840'>guy</span> <span m='2255020'>who</span> <span m='2255080'>did</span>
  <span m='2255200'>the</span> <span m='2255260'>multiplier.</span> <span m='2258340'>He</span>
  <span m='2258550'>suggested</span> <span m='2259020'>some</span> <span m='2259120'>polynomials.</span>
  <span m='2260920'>They're</span> <span m='2261070'>kind</span> <span m='2261220'>of</span>
  <span m='2261280'>complicated.</span> <span m='2261760'>They're given</span> <span
  m='2261990'>in</span> <span m='2262090'>the</span> <span m='2262150'>book.</span>
  </p><p><span m='2263140'>But</span> <span m='2263320'>what</span> <span m='2263470'>they</span>
  <span m='2263590'>really</span> <span m='2263890'>are</span> <span m='2264740'>is</span>
  <span m='2265030'>I'm</span> <span m='2265420'>taking the</span> <span m='2265540'>monomial</span>
  <span m='2265880'>basis</span> <span m='2266360'>set,</span> <span m='2267440'>and</span>
  <span m='2267560'>I'm</span> <span m='2267670'>making</span> <span m='2267940'>a
  new</span> <span m='2268060'>basis</span> <span m='2268370'>set.</span> <span m='2269650'>So</span>
  <span m='2269800'>I</span> <span m='2269890'>want</span> <span m='2270180'>phi</span>
  <span m='2271330'>l</span> <span m='2272350'>to</span> <span m='2272470'>be</span>
  <span m='2272650'>equal</span> <span m='2272920'>to</span> <span m='2273130'>the</span>
  <span m='2273190'>sum</span> <span m='2274070'>dlk</span> <span m='2276222'>of</span>
  <span m='2277074'>phi</span> <span m='2277500'>k,</span> <span m='2278430'>where</span>
  <span m='2278750'>this</span> <span m='2278980'>phi</span> <span m='2279250'>k</span>
  <span m='2279610'>it</span> <span m='2279740'>the</span> <span m='2280000'>monomials.</span>
  <span m='2282640'>So</span> <span m='2282790'>really,</span> <span m='2283120'>you</span>
  <span m='2283270'>can</span> <span m='2283360'>choose</span> <span m='2283570'>any</span>
  <span m='2283710'>d</span> <span m='2283870'>you</span> <span m='2283990'>want.</span>
  <span m='2285250'>You're</span> <span m='2285310'>just</span> <span m='2285400'>taking</span>
  <span m='2285630'>linear</span> <span m='2285850'>combinations</span> <span m='2286510'>of</span>
  <span m='2287050'>the</span> <span m='2287140'>original</span> <span m='2287440'>monomial</span>
  <span m='2287930'>basis</span> <span m='2288260'>set</span> <span m='2288960'>to</span>
  <span m='2289090'>make</span> <span m='2289270'>up</span> <span m='2289360'>polynomials.</span>
  <span m='2290920'>And</span> <span m='2291070'>if</span> <span m='2291130'>you</span>
  <span m='2291190'>cleverly</span> <span m='2291610'>choose</span> <span m='2291880'>the</span>
  <span m='2292000'>d,</span> <span m='2292690'>you</span> <span m='2292780'>can</span>
  <span m='2292910'>choose</span> <span m='2293110'>it to</span> <span m='2293220'>have</span>
  <span m='2293330'>special</span> <span m='2293620'>properties.</span> </p><p><span
  m='2294610'>So</span> <span m='2294850'>Lagrange</span> <span m='2295450'>gave</span>
  <span m='2295880'>a</span> <span m='2296260'>certain</span> <span m='2296680'>choice
  of</span> <span m='2297040'>the</span> <span m='2297160'>d</span> <span m='2298375'>that</span>
  <span m='2298780'>is</span> <span m='2299050'>brilliant</span> <span m='2299620'>in</span>
  <span m='2299770'>the</span> <span m='2299830'>sense</span> <span m='2300220'>that,</span>
  <span m='2300550'>when</span> <span m='2300700'>you</span> <span m='2301090'>solve</span>
  <span m='2301480'>the</span> <span m='2301600'>problem</span> <span m='2302620'>m</span>
  <span m='2303130'>times</span> <span m='2303460'>c</span> <span m='2303820'>is</span>
  <span m='2303970'>equal</span> <span m='2304210'>to</span> <span m='2304450'>y</span>
  <span m='2305500'>to</span> <span m='2305620'>try</span> <span m='2305740'>to</span>
  <span m='2305830'>do</span> <span m='2305920'>your</span> <span m='2306100'>interpolation,</span>
  <span m='2307300'>it</span> <span m='2307420'>turns</span> <span m='2307720'>out</span>
  <span m='2308350'>that</span> <span m='2308530'>the</span> <span m='2308620'>c's</span>
  <span m='2309010'>you</span> <span m='2309130'>want,</span> <span m='2309610'>ck,</span>
  <span m='2310570'>is</span> <span m='2310750'>equal</span> <span m='2311050'>to</span>
  <span m='2311400'>f of</span> <span m='2311810'>tk.</span> <span m='2314440'>So</span>
  <span m='2314540'>you</span> <span m='2314590'>don't have to</span> <span m='2314800'>do</span>
  <span m='2314950'>any</span> <span m='2315100'>work</span> <span m='2316020'>to</span>
  <span m='2316110'>solve</span> <span m='2316410'>what the</span> <span m='2316510'>c's</span>
  <span m='2316720'>are.</span> <span m='2317310'>It's</span> <span m='2317440'>just</span>
  <span m='2317590'>the</span> <span m='2317760'>f</span> <span m='2318220'>values</span>
  <span m='2318640'>directly.</span> <span m='2319930'>No</span> <span m='2320080'>chance</span>
  <span m='2320380'>for</span> <span m='2320470'>condition</span> <span m='2320830'>numbers,</span>
  <span m='2321640'>no</span> <span m='2321760'>problems,</span> <span m='2322420'>that's</span>
  <span m='2322780'>it.</span> <span m='2324530'>So</span> <span m='2324650'>that's</span>
  <span m='2325310'>the</span> <span m='2325730'>Lagrange</span> <span m='2326025'>polynomials.</span>
  </p><p><span m='2327790'>Now,</span> <span m='2328160'>Newton</span> <span m='2329720'>had</span>
  <span m='2329900'>a</span> <span m='2329960'>different</span> <span m='2330320'>idea.</span>
  <span m='2331500'>So</span> <span m='2331610'>this</span> <span m='2332090'>is</span>
  <span m='2332240'>for</span> <span m='2333674'>Lagrange</span> <span m='2334151'>polynomials.</span>
  <span m='2340352'>If you</span> <span m='2340840'>choose a</span> <span m='2341300'>Lagrangian</span>
  <span m='2341580'>[? polynomial ?]</span> <span m='2342010'>basis,</span> <span
  m='2344510'>then</span> <span m='2344680'>this</span> <span m='2344830'>is</span>
  <span m='2345020'>it.</span> <span m='2345200'>And you do a</span> <span m='2345570'>square</span>
  <span m='2345880'>system.</span> <span m='2346650'>That's</span> <span m='2346860'>it.</span>
  <span m='2347950'>If</span> <span m='2348040'>you</span> <span m='2348100'>choose</span>
  <span m='2348430'>the</span> <span m='2348550'>Newton,</span> <span m='2350250'>even</span>
  <span m='2350500'>he</span> <span m='2350680'>got</span> <span m='2350830'>into</span>
  <span m='2350980'>this</span> <span m='2351130'>business</span> <span m='2351430'>too.</span>
  <span m='2352065'>And</span> <span m='2352430'>he</span> <span m='2352600'>made</span>
  <span m='2352750'>some</span> <span m='2352840'>polynomials.</span> <span m='2353770'>And</span>
  <span m='2353860'>he</span> <span m='2354040'>made</span> <span m='2354250'>ones</span>
  <span m='2354670'>that</span> <span m='2355780'>have</span> <span m='2355960'>a</span>
  <span m='2355990'>special</span> <span m='2356290'>property</span> <span m='2356800'>that</span>
  <span m='2356950'>if</span> <span m='2358690'>you</span> <span m='2358750'>solve</span>
  <span m='2359110'>it--</span> <span m='2359830'>so</span> <span m='2359950'>he</span>
  <span m='2360070'>chose</span> <span m='2360280'>a</span> <span m='2360310'>different</span>
  <span m='2360550'>d.</span> <span m='2361270'>You</span> <span m='2361520'>still
  have</span> <span m='2361890'>to</span> <span m='2361980'>do</span> <span m='2362170'>some</span>
  <span m='2362600'>solve.</span> <span m='2363460'>You</span> <span m='2363550'>get</span>
  <span m='2363670'>the</span> <span m='2363800'>solution.</span> </p><p><span m='2365620'>And</span>
  <span m='2365830'>then</span> <span m='2366070'>you</span> <span m='2366130'>decide</span>
  <span m='2366520'>that</span> <span m='2367420'>I</span> <span m='2367480'>don't</span>
  <span m='2367630'>like</span> <span m='2367780'>that</span> <span m='2367870'>interpretation.</span>
  <span m='2368500'>I</span> <span m='2368530'>want</span> <span m='2368680'>to</span>
  <span m='2368740'>put</span> <span m='2368860'>some</span> <span m='2368950'>more</span>
  <span m='2369100'>points</span> <span m='2369400'>in.</span> <span m='2370060'>I'm</span>
  <span m='2370150'>going</span> <span m='2370270'>to</span> <span m='2370330'>do</span>
  <span m='2370420'>a</span> <span m='2370480'>few</span> <span m='2370600'>more</span>
  <span m='2370720'>function</span> <span m='2371020'>evaluations.</span> <span m='2372130'>I'm</span>
  <span m='2372280'>going</span> <span m='2372350'>to</span> <span m='2372460'>add</span>
  <span m='2372610'>some</span> <span m='2372760'>more.</span> <span m='2373420'>So</span>
  <span m='2374010'>from</span> <span m='2374230'>the</span> <span m='2374320'>first</span>
  <span m='2374590'>solve,</span> <span m='2374890'>I</span> <span m='2374980'>have</span>
  <span m='2375260'>the</span> <span m='2375310'>values</span> <span m='2375510'>of</span>
  <span m='2375730'>c1,</span> <span m='2376270'>c2,</span> <span m='2376840'>c3,</span>
  <span m='2378010'>up</span> <span m='2378490'>to</span> <span m='2378820'>c</span>
  <span m='2379150'>the</span> <span m='2379240'>number</span> <span m='2379420'>of</span>
  <span m='2379480'>points</span> <span m='2379750'>I</span> <span m='2379810'>had</span>
  <span m='2379960'>initially.</span> </p><p><span m='2381550'>And</span> <span m='2381700'>now,</span>
  <span m='2382120'>I</span> <span m='2382210'>want</span> <span m='2382360'>to</span>
  <span m='2382420'>add</span> <span m='2383380'>one</span> <span m='2383530'>more</span>
  <span m='2383860'>data</span> <span m='2384070'>point,</span> <span m='2384510'>or</span>
  <span m='2384720'>add</span> <span m='2384880'>one</span> <span m='2385060'>more</span>
  <span m='2385390'>f</span> <span m='2385680'>of</span> <span m='2385800'>tn,</span>
  <span m='2386080'>one</span> <span m='2386470'>more</span> <span m='2386710'>function</span>
  <span m='2387030'>evaluation.</span> <span m='2388000'>I</span> <span m='2388090'>want</span>
  <span m='2388210'>to</span> <span m='2388270'>figure</span> <span m='2388420'>out</span>
  <span m='2388480'>with</span> <span m='2388600'>c of</span> <span m='2389030'>n
  plus</span> <span m='2389300'>1 is,</span> <span m='2390065'>what</span> <span m='2390560'>the</span>
  <span m='2390670'>next</span> <span m='2390820'>one</span> <span m='2390970'>is.</span>
  <span m='2391330'>It</span> <span m='2391720'>turns</span> <span m='2392170'>out</span>
  <span m='2392890'>that</span> <span m='2393010'>it's</span> <span m='2393160'>his</span>
  <span m='2393370'>polynomials.</span> <span m='2394420'>The</span> <span m='2394510'>values</span>
  <span m='2394930'>these</span> <span m='2394990'>c's</span> <span m='2395410'>don't</span>
  <span m='2395650'>change</span> <span m='2396310'>when</span> <span m='2396850'>I</span>
  <span m='2396890'>make</span> <span m='2397060'>this</span> <span m='2397210'>matrix</span>
  <span m='2397540'>a</span> <span m='2397570'>little bit</span> <span m='2397750'>bigger</span>
  <span m='2398260'>by</span> <span m='2398410'>adding</span> <span m='2398650'>one</span>
  <span m='2398830'>more</span> <span m='2399140'>y.</span> <span m='2401060'>And</span>
  <span m='2401180'>I</span> <span m='2401300'>add</span> <span m='2402920'>one</span>
  <span m='2403100'>more</span> <span m='2403250'>parameter.</span> <span m='2404060'>And</span>
  <span m='2404210'>I</span> <span m='2404360'>make</span> <span m='2404630'>one</span>
  <span m='2404780'>more</span> <span m='2404900'>row</span> <span m='2405110'>in</span>
  <span m='2405170'>the</span> <span m='2405230'>matrix,</span> <span m='2405830'>one</span>
  <span m='2406130'>more</span> <span m='2406370'>column in</span> <span m='2406670'>the</span>
  <span m='2406760'>matrix.</span> </p><p><span m='2408070'>When</span> <span m='2408230'>I</span>
  <span m='2408290'>do</span> <span m='2408440'>that,</span> <span m='2409220'>it's</span>
  <span m='2409370'>a</span> <span m='2409460'>unique</span> <span m='2409820'>property</span>
  <span m='2410360'>that</span> <span m='2411740'>none</span> <span m='2411950'>of</span>
  <span m='2412010'>these</span> <span m='2412160'>other</span> <span m='2412350'>c's</span>
  <span m='2412645'>change.</span> <span m='2412940'>The</span> <span m='2413030'>solution</span>
  <span m='2413300'>is</span> <span m='2413360'>going</span> <span m='2413480'>to</span>
  <span m='2413540'>be</span> <span m='2413630'>the</span> <span m='2413720'>same,</span>
  <span m='2413960'>except</span> <span m='2414190'>for</span> <span m='2414550'>the</span>
  <span m='2414770'>n plus</span> <span m='2415010'>one</span> <span m='2415300'>[?
  level. ?]</span> <span m='2416030'>So</span> <span m='2416150'>then</span> <span
  m='2416330'>I</span> <span m='2416390'>can</span> <span m='2416510'>write</span>
  <span m='2416660'>a</span> <span m='2416730'>neat, cute</span> <span m='2417020'>little</span>
  <span m='2417170'>equation</span> <span m='2417530'>just</span> <span m='2417680'>for</span>
  <span m='2417770'>the</span> <span m='2417860'>n plus</span> <span m='2418070'>1</span>
  <span m='2418280'>one.</span> <span m='2418580'>I</span> <span m='2418640'>don't</span>
  <span m='2418820'>have</span> <span m='2418910'>to</span> <span m='2419080'>mess</span>
  <span m='2419300'>with</span> <span m='2419380'>the</span> <span m='2419480'>previous</span>
  <span m='2419780'>ones.</span> <span m='2420920'>And</span> <span m='2421100'>so</span>
  <span m='2421280'>I'm</span> <span m='2421340'>just</span> <span m='2421550'>adding</span>
  <span m='2421840'>a basis</span> <span m='2421990'>function</span> <span m='2422240'>that</span>
  <span m='2422300'>sort</span> <span m='2422480'>of</span> <span m='2422540'>polishes</span>
  <span m='2422810'>up</span> <span m='2423260'>my</span> <span m='2423470'>original</span>
  <span m='2423820'>fit.</span> <span m='2425350'>So</span> <span m='2425560'>that's</span>
  <span m='2425710'>a</span> <span m='2425730'>nice</span> <span m='2425930'>property</span>
  <span m='2426250'>too.</span> </p><p><span m='2428180'>Whereas</span> <span m='2428570'>with</span>
  <span m='2429310'>the</span> <span m='2429810'>Lagrange</span> <span m='2430190'>ones,</span>
  <span m='2430490'>you</span> <span m='2430550'>have</span> <span m='2430640'>to</span>
  <span m='2430730'>recompute</span> <span m='2431060'>everything.</span> <span m='2432110'>And</span>
  <span m='2432200'>all</span> <span m='2432290'>the</span> <span m='2432360'>c's</span>
  <span m='2432540'>will</span> <span m='2432620'>change.</span> <span m='2438870'>Actually,</span>
  <span m='2439050'>the</span> <span m='2439140'>c's</span> <span m='2439240'>won't</span>
  <span m='2439570'>change.</span> <span m='2440030'>I take</span> <span m='2440140'>that</span>
  <span m='2440260'>back.</span> <span m='2440710'>You add</span> <span m='2441060'>points.</span>
  <span m='2441440'>The</span> <span m='2441540'>c's</span> <span m='2441700'>won't</span>
  <span m='2441820'>change,</span> <span m='2442450'>but</span> <span m='2442600'>the</span>
  <span m='2442720'>actual</span> <span m='2442930'>polynomials</span> <span m='2443410'>will</span>
  <span m='2443500'>change.</span> <span m='2444010'>The</span> <span m='2444100'>d</span>
  <span m='2444310'>will</span> <span m='2444400'>change.</span> <span m='2445720'>Because</span>
  <span m='2445930'>the</span> <span m='2446020'>d</span> <span m='2446380'>depends</span>
  <span m='2446860'>on</span> <span m='2447820'>the</span> <span m='2448120'>choice</span>
  <span m='2448510'>of</span> <span m='2448570'>the</span> <span m='2448900'>time</span>
  <span m='2449200'>points</span> <span m='2449970'>in</span> <span m='2450030'>a</span>
  <span m='2450210'>complicated</span> <span m='2450410'>way</span> <span m='2451100'>in</span>
  <span m='2451530'>Lagrange.</span> </p><p><span m='2456370'>So</span> <span m='2456720'>now,</span>
  <span m='2456900'>you</span> <span m='2456990'>start</span> <span m='2457170'>to</span>
  <span m='2457230'>think,</span> <span m='2457480'>oh</span> <span m='2457580'>my</span>
  <span m='2457680'>goodness,</span> <span m='2457890'>I</span> <span m='2457920'>have</span>
  <span m='2458010'>all</span> <span m='2458130'>these</span> <span m='2458250'>choices,</span>
  <span m='2458640'>I</span> <span m='2458700'>can</span> <span m='2458790'>use</span>
  <span m='2458940'>Lagrange.</span> <span m='2459450'>I</span> <span m='2459520'>could</span>
  <span m='2459620'>use</span> <span m='2459810'>Newton.</span> <span m='2460200'>I</span>
  <span m='2460260'>could</span> <span m='2460380'>use</span> <span m='2460530'>monomials.</span>
  <span m='2461550'>Maybe,</span> <span m='2461760'>I</span> <span m='2461850'>should</span>
  <span m='2462480'>go</span> <span m='2462570'>back</span> <span m='2462690'>to</span>
  <span m='2462780'>bed.</span> <span m='2463740'>And</span> <span m='2465690'>you</span>
  <span m='2466170'>think,</span> <span m='2466470'>well,</span> <span m='2466720'>could</span>
  <span m='2466880'>someone</span> <span m='2467040'>just</span> <span m='2467150'>tell</span>
  <span m='2467250'>me</span> <span m='2467370'>what</span> <span m='2467460'>the</span>
  <span m='2467520'>best</span> <span m='2467730'>one</span> <span m='2467880'>is?</span>
  <span m='2468120'>And I'll just</span> <span m='2468420'>do</span> <span m='2468510'>that</span>
  <span m='2468690'>one.</span> <span m='2468810'>I</span> <span m='2468870'>don't</span>
  <span m='2469210'>need</span> <span m='2469380'>to</span> <span m='2469440'>learn</span>
  <span m='2469590'>about</span> <span m='2469710'>all</span> <span m='2469800'>this</span>
  <span m='2469920'>historical</span> <span m='2470430'>stuff</span> <span m='2470730'>about</span>
  <span m='2471090'>development</span> <span m='2471500'>of</span> <span m='2471560'>polynomial</span>
  <span m='2472020'>mathematics.</span> <span m='2473220'>I'd</span> <span m='2473280'>just</span>
  <span m='2473550'>like</span> <span m='2473720'>you to</span> <span m='2473830'>just</span>
  <span m='2474000'>tell</span> <span m='2474120'>me</span> <span m='2474240'>what</span>
  <span m='2474360'>the</span> <span m='2474450'>answer</span> <span m='2474720'>is.</span>
  </p><p><span m='2475450'>So</span> <span m='2475680'>Gauss,</span> <span m='2477120'>typically,</span>
  <span m='2478650'>figured</span> <span m='2478920'>out</span> <span m='2479040'>what</span>
  <span m='2479150'>the</span> <span m='2479220'>best</span> <span m='2479430'>on</span>
  <span m='2479550'>is.</span> <span m='2480940'>And</span> <span m='2481050'>he</span>
  <span m='2481170'>said,</span> <span m='2481440'>you</span> <span m='2481500'>know,</span>
  <span m='2482490'>if</span> <span m='2482610'>we're</span> <span m='2482670'>going</span>
  <span m='2482790'>to</span> <span m='2482940'>do</span> <span m='2483030'>integrals,</span>
  <span m='2486050'>we'd</span> <span m='2486240'>really</span> <span m='2486450'>like</span>
  <span m='2486600'>to</span> <span m='2486720'>just</span> <span m='2487190'>write</span>
  <span m='2487440'>our</span> <span m='2487620'>integrals</span> <span m='2487930'>this</span>
  <span m='2488030'>way.</span> <span m='2488340'>So our</span> <span m='2488460'>approximate</span>
  <span m='2489180'>value</span> <span m='2491350'>to</span> <span m='2491450'>be</span>
  <span m='2491820'>equal</span> <span m='2492030'>to</span> <span m='2492150'>some</span>
  <span m='2492390'>weight</span> <span m='2492600'>functions</span> <span m='2494060'>times</span>
  <span m='2494490'>the</span> <span m='2494580'>function</span> <span m='2494910'>evaluations</span>
  <span m='2495240'>at</span> <span m='2495570'>some</span> <span m='2495630'>times.</span>
  <span m='2498340'>Right,</span> <span m='2498580'>that's</span> <span m='2498740'>easy</span>
  <span m='2499040'>to</span> <span m='2499100'>evaluate.</span> <span m='2500170'>That</span>
  <span m='2500610'>would</span> <span m='2500720'>be</span> <span m='2500840'>good.</span>
  <span m='2501360'>If</span> <span m='2501490'>I</span> <span m='2501560'>pre-computed</span>
  <span m='2502040'>the</span> <span m='2502160'>weight</span> <span m='2502280'>functions</span>
  <span m='2502640'>[? and ?]</span> <span m='2502700'>the</span> <span m='2502820'>times,</span>
  <span m='2503780'>then</span> <span m='2503900'>I</span> <span m='2503960'>put</span>
  <span m='2504110'>any</span> <span m='2504260'>function</span> <span m='2504590'>f</span>
  <span m='2504740'>in</span> <span m='2504830'>here,</span> <span m='2505560'>I</span>
  <span m='2505660'>could</span> <span m='2505760'>just</span> <span m='2505860'>do
  this</span> <span m='2506030'>like</span> <span m='2506180'>zip.</span> <span m='2507530'>It's</span>
  <span m='2507700'>one</span> <span m='2507920'>dot</span> <span m='2508100'>product</span>
  <span m='2509260'>of</span> <span m='2509380'>the f</span> <span m='2509800'>of
  tn's</span> <span m='2510090'>I'll</span> <span m='2510520'>have</span> <span m='2510710'>the</span>
  <span m='2510800'>solution.</span> <span m='2511580'>So</span> <span m='2511790'>I</span>
  <span m='2511880'>want</span> <span m='2512030'>to</span> <span m='2512090'>do</span>
  <span m='2512210'>that.</span> </p><p><span m='2512360'>So</span> <span m='2512480'>what's</span>
  <span m='2512660'>the</span> <span m='2512750'>best</span> <span m='2512990'>possible</span>
  <span m='2513500'>choices</span> <span m='2513950'>of</span> <span m='2514040'>the</span>
  <span m='2514130'>w's</span> <span m='2514520'>and</span> <span m='2514620'>the
  t's</span> <span m='2515390'>to</span> <span m='2515510'>make</span> <span m='2515660'>this</span>
  <span m='2515840'>really</span> <span m='2516190'>be</span> <span m='2516680'>close?</span>
  <span m='2517660'>Well,</span> <span m='2518410'>the</span> <span m='2518500'>problem</span>
  <span m='2518720'>is</span> <span m='2519120'>that</span> <span m='2519240'>there's</span>
  <span m='2519370'>an</span> <span m='2519440'>infinite</span> <span m='2519490'>number</span>
  <span m='2519670'>of</span> <span m='2519730'>functions</span> <span m='2520220'>that</span>
  <span m='2520320'>somebody</span> <span m='2520420'>might</span> <span m='2520540'>want</span>
  <span m='2520660'>to</span> <span m='2520720'>integrate.</span> <span m='2521860'>I</span>
  <span m='2521920'>can't</span> <span m='2522100'>do</span> <span m='2522190'>them</span>
  <span m='2522310'>all.</span> <span m='2522910'>So</span> <span m='2523030'>he</span>
  <span m='2523180'>said,</span> <span m='2523390'>let's</span> <span m='2523600'>just</span>
  <span m='2523780'>find</span> <span m='2524080'>the</span> <span m='2524200'>one</span>
  <span m='2525130'>that</span> <span m='2525280'>works</span> <span m='2526870'>for</span>
  <span m='2527170'>as</span> <span m='2527320'>many</span> <span m='2527990'>monomials</span>
  <span m='2528910'>as</span> <span m='2529090'>possible</span> <span m='2531200'>to</span>
  <span m='2531310'>the</span> <span m='2531400'>highest</span> <span m='2531700'>order,</span>
  <span m='2532220'>as</span> <span m='2532960'>far</span> <span m='2533200'>out as</span>
  <span m='2533410'>I</span> <span m='2533470'>can</span> <span m='2533590'>go.</span>
  <span m='2534790'>And</span> <span m='2534970'>it</span> <span m='2535060'>turns</span>
  <span m='2535300'>out</span> <span m='2535420'>I</span> <span m='2538080'>have</span>
  <span m='2538330'>nw's.</span> <span m='2540310'>I</span> <span m='2540370'>have</span>
  <span m='2540580'>nt's.</span> <span m='2541750'>So</span> <span m='2541900'>I</span>
  <span m='2541960'>have</span> <span m='2542080'>two</span> <span m='2542320'>n</span>
  <span m='2542500'>parameters</span> <span m='2542895'>that</span> <span m='2543290'>I</span>
  <span m='2543470'>can</span> <span m='2543580'>fiddle</span> <span m='2543760'>around</span>
  <span m='2544000'>with.</span> <span m='2545280'>And</span> <span m='2545610'>so</span>
  <span m='2545970'>I</span> <span m='2546060'>should</span> <span m='2546210'>get</span>
  <span m='2546390'>something</span> <span m='2546750'>like</span> <span m='2546960'>two</span>
  <span m='2547230'>n's</span> <span m='2547650'>in</span> <span m='2547740'>my</span>
  <span m='2547830'>polynomials,</span> <span m='2548270'>maybe</span> <span m='2548400'>2n</span>
  <span m='2548670'>minus</span> <span m='2548920'>1.</span> </p><p><span m='2550560'>So</span>
  <span m='2551000'>what</span> <span m='2551150'>I</span> <span m='2551240'>want</span>
  <span m='2551510'>is</span> <span m='2551690'>that</span> <span m='2553100'>I</span>
  <span m='2553220'>want</span> <span m='2553400'>to</span> <span m='2553460'>choose</span>
  <span m='2553970'>this</span> <span m='2554630'>so</span> <span m='2554990'>that</span>
  <span m='2556040'>for</span> <span m='2556430'>the</span> <span m='2556640'>monomial</span>
  <span m='2557300'>1,</span> <span m='2558110'>and</span> <span m='2558280'>the monomial</span>
  <span m='2558490'>t,</span> <span m='2559060'>and</span> <span m='2559160'>the monomial</span>
  <span m='2559460'>t</span> <span m='2559810'>squared,</span> <span m='2561350'>that</span>
  <span m='2561980'>this</span> <span m='2562250'>i</span> <span m='2562550'>is</span>
  <span m='2562670'>actually</span> <span m='2562880'>going</span> <span m='2563000'>to</span>
  <span m='2563060'>be</span> <span m='2563120'>exact.</span> <span m='2565270'>So</span>
  <span m='2566030'>what</span> <span m='2566350'>I</span> <span m='2566480'>want</span>
  <span m='2567480'>is</span> <span m='2567750'>for</span> <span m='2567930'>the</span>
  <span m='2568020'>monomial</span> <span m='2568460'>1,</span> <span m='2569190'>I</span>
  <span m='2569280'>want</span> <span m='2569460'>the</span> <span m='2569550'>summation</span>
  <span m='2571060'>of</span> <span m='2571260'>wn.</span> <span m='2572970'>My</span>
  <span m='2573270'>f</span> <span m='2574080'>for</span> <span m='2574250'>the</span>
  <span m='2574360'>monomial</span> <span m='2574570'>1</span> <span m='2574800'>is</span>
  <span m='2574890'>always</span> <span m='2575130'>1.</span> <span m='2575760'>So</span>
  <span m='2575940'>it's</span> <span m='2576060'>times</span> <span m='2576360'>1.</span>
  <span m='2577620'>I</span> <span m='2577710'>want</span> <span m='2577950'>this</span>
  <span m='2578160'>to</span> <span m='2578250'>equal</span> <span m='2578560'>the</span>
  <span m='2578730'>integral</span> <span m='2579240'>from</span> <span m='2579450'>a</span>
  <span m='2579600'>to</span> <span m='2579690'>b</span> <span m='2580940'>of</span>
  <span m='2581560'>1dt,</span> <span m='2584430'>which</span> <span m='2584580'>is</span>
  <span m='2584670'>b</span> <span m='2584880'>minus</span> <span m='2584970'>a.</span>
  <span m='2586330'>OK,</span> <span m='2586830'>so</span> <span m='2586940'>that</span>
  <span m='2587070'>gives</span> <span m='2587240'>me</span> <span m='2587310'>one</span>
  <span m='2587520'>equation</span> <span m='2587880'>for</span> <span m='2587970'>the</span>
  <span m='2588060'>w's.</span> </p><p><span m='2589730'>Then</span> <span m='2591380'>for</span>
  <span m='2591590'>the</span> <span m='2591830'>next</span> <span m='2592130'>one,</span>
  <span m='2593120'>I</span> <span m='2593180'>want</span> <span m='2593340'>the</span>
  <span m='2593420'>summation</span> <span m='2594450'>wn</span> <span m='2595310'>times</span>
  <span m='2595790'>tn</span> <span m='2597700'>to</span> <span m='2598160'>equal
  the</span> <span m='2598580'>integral</span> <span m='2598920'>of</span> <span m='2599260'>a
  to</span> <span m='2599630'>b</span> <span m='2600092'>of</span> <span m='2600554'>t.</span>
  <span m='2601478'>dt,</span> <span m='2602870'>which</span> <span m='2602990'>is</span>
  <span m='2603140'>equal</span> <span m='2603380'>to</span> <span m='2604490'>b</span>
  <span m='2604710'>squared</span> <span m='2605140'>over</span> <span m='2605570'>a</span>
  <span m='2606430'>number</span> <span m='2606860'>2</span> <span m='2607840'>minus</span>
  <span m='2608330'>a squared</span> <span m='2608570'>over</span> <span m='2608720'>2</span>
  <span m='2608930'>if I</span> <span m='2609050'>did</span> <span m='2609140'>my</span>
  <span m='2609890'>calculus</span> <span m='2610250'>correctly.</span> <span m='2612390'>And</span>
  <span m='2613140'>so</span> <span m='2613350'>there's</span> <span m='2613530'>another</span>
  <span m='2613790'>question.</span> <span m='2614050'>I have</span> <span m='2614310'>another</span>
  <span m='2614520'>question</span> <span m='2614820'>for</span> <span m='2614910'>these</span>
  <span m='2615030'>guys.</span> <span m='2615420'>And</span> <span m='2615540'>I</span>
  <span m='2615600'>keep</span> <span m='2615780'>going</span> <span m='2616230'>until</span>
  <span m='2616410'>I</span> <span m='2616470'>get</span> <span m='2616560'>enough</span>
  <span m='2616740'>equations that</span> <span m='2617160'>determine</span> <span
  m='2617520'>all</span> <span m='2617610'>the</span> <span m='2617680'>w's</span>
  <span m='2618000'>and</span> <span m='2618090'>c's.</span> <span m='2619620'>All</span>
  <span m='2619710'>right,</span> <span m='2620080'>so</span> <span m='2620230'>I
  do it</span> <span m='2620530'>for t</span> <span m='2620640'>squared.</span> <span
  m='2620895'>So</span> <span m='2621150'>I</span> <span m='2621493'>can</span> <span
  m='2621836'>wn</span> <span m='2623454'>tn</span> <span m='2624220'>squared</span>
  <span m='2624475'>is</span> <span m='2624730'>equal</span> <span m='2625070'>to</span>
  <span m='2625865'>[INAUDIBLE]</span> <span m='2626290'>b</span> <span m='2627500'>t
  squared</span> <span m='2627910'>dt,</span> <span m='2629410'>and</span> <span m='2629500'>so</span>
  <span m='2629560'>on,</span> <span m='2630360'>OK.</span> </p><p><span m='2632260'>And</span>
  <span m='2632470'>so</span> <span m='2632600'>if</span> <span m='2632640'>you</span>
  <span m='2632710'>do</span> <span m='2632860'>this</span> <span m='2633220'>process,</span>
  <span m='2634360'>you</span> <span m='2634510'>get</span> <span m='2635050'>the</span>
  <span m='2635620'>weights</span> <span m='2636220'>and</span> <span m='2636370'>the</span>
  <span m='2636460'>points</span> <span m='2637000'>to</span> <span m='2637120'>use</span>
  <span m='2637840'>that</span> <span m='2637960'>will</span> <span m='2638080'>give</span>
  <span m='2638200'>you</span> <span m='2638260'>what's</span> <span m='2638410'>called</span>
  <span m='2638560'>the</span> <span m='2638650'>Gaussian</span> <span m='2639040'>quadrature</span>
  <span m='2639340'>rule.</span> <span m='2640950'>Now,</span> <span m='2641210'>the</span>
  <span m='2641340'>brilliant</span> <span m='2641670'>thing</span> <span m='2641820'>about</span>
  <span m='2642090'>this</span> <span m='2642990'>is</span> <span m='2643170'>that</span>
  <span m='2643550'>by</span> <span m='2643650'>this</span> <span m='2643850'>setup,</span>
  <span m='2645470'>it's</span> <span m='2645650'>going</span> <span m='2645770'>to</span>
  <span m='2645860'>be</span> <span m='2645980'>exact</span> <span m='2646610'>for</span>
  <span m='2646850'>integrating</span> <span m='2647300'>any</span> <span m='2647480'>polynomial</span>
  <span m='2648320'>up</span> <span m='2648770'>to</span> <span m='2649010'>order</span>
  <span m='2649310'>2n</span> <span m='2649820'>minus</span> <span m='2650190'>1.</span>
  <span m='2653347'>So</span> <span m='2653800'>if</span> <span m='2653950'>I</span>
  <span m='2654910'>choose</span> <span m='2655780'>three,</span> <span m='2657480'>here</span>
  <span m='2657810'>I'll</span> <span m='2657900'>be</span> <span m='2657990'>able</span>
  <span m='2658110'>to</span> <span m='2658200'>determine--</span> <span m='2658930'>if
  I</span> <span m='2659050'>choose</span> <span m='2659310'>three</span> <span m='2659520'>points,</span>
  <span m='2660570'>I'll</span> <span m='2660660'>have</span> <span m='2660810'>six</span>
  <span m='2661050'>parameters.</span> <span m='2662550'>So</span> <span m='2662790'>I'll</span>
  <span m='2662880'>be</span> <span m='2663000'>able</span> <span m='2663150'>determine</span>
  <span m='2663690'>up</span> <span m='2663940'>to</span> <span m='2666900'>the</span>
  <span m='2667070'>11--</span> <span m='2668230'>11th</span> <span m='2668525'>order</span>
  <span m='2668820'>polynomial</span> <span m='2668960'>would</span> <span m='2669090'>integrate</span>
  <span m='2669340'>exactly.</span> </p><p><span m='2673610'>No,</span> <span m='2674260'>that's</span>
  <span m='2674390'>wrong.</span> <span m='2676482'>n's</span> <span m='2676926'>only</span>
  <span m='2677370'>3.</span> <span m='2678480'>I</span> <span m='2678550'>have</span>
  <span m='2678710'>six</span> <span m='2678950'>parameters.</span> <span m='2681370'>I
  can't</span> <span m='2681655'>do</span> <span m='2681940'>this.</span> <span m='2682420'>2</span>
  <span m='2682590'>times</span> <span m='2682800'>3</span> <span m='2683050'>minus</span>
  <span m='2683420'>1,</span> <span m='2683470'>what's</span> <span m='2683847'>that?</span>
  <span m='2684601'>5,</span> <span m='2684980'>there</span> <span m='2685435'>we</span>
  <span m='2685890'>go.</span> <span m='2686800'>To</span> <span m='2687255'>the</span>
  <span m='2687710'>fifth</span> <span m='2688170'>order</span> <span m='2688410'>polynomial</span>
  <span m='2689406'>integrate</span> <span m='2689770'>exactly,</span> <span m='2690180'>I'll</span>
  <span m='2690240'>have</span> <span m='2690330'>an</span> <span m='2690410'>[? error
  ?]</span> <span m='2690600'>for</span> <span m='2690730'>sixth</span> <span m='2691170'>order</span>
  <span m='2691330'>polynomial.</span> </p><p><span m='2692580'>So</span> <span m='2694570'>this</span>
  <span m='2694810'>is</span> <span m='2695140'>a</span> <span m='2695350'>rule.</span>
  <span m='2696280'>So</span> <span m='2697120'>before,</span> <span m='2697390'>if</span>
  <span m='2697660'>I</span> <span m='2697750'>gave</span> <span m='2697930'>you</span>
  <span m='2697990'>three</span> <span m='2698200'>points</span> <span m='2698770'>like</span>
  <span m='2698980'>here,</span> <span m='2701760'>most of</span> <span m='2702090'>you</span>
  <span m='2702160'>probably</span> <span m='2702400'>would</span> <span m='2702520'>use</span>
  <span m='2702630'>Simpson's</span> <span m='2702940'>rule.</span> <span m='2703720'>Fit</span>
  <span m='2704040'>this</span> <span m='2704220'>to</span> <span m='2704350'>a</span>
  <span m='2704380'>parabola.</span> <span m='2705295'>It</span> <span m='2705610'>has</span>
  <span m='2705780'>three</span> <span m='2705930'>parameters,</span> <span m='2706390'>a,</span>
  <span m='2706840'>ax</span> <span m='2707290'>squared</span> <span m='2707590'>plus</span>
  <span m='2707770'>bx</span> <span m='2707970'>plus c,</span> <span m='2709030'>right,</span>
  <span m='2709210'>for</span> <span m='2709410'>a</span> <span m='2709480'>second</span>
  <span m='2709720'>order</span> <span m='2710230'>polynomial.</span> <span m='2711100'>I
  would</span> <span m='2711280'>fit</span> <span m='2711450'>it.</span> <span m='2711580'>Then</span>
  <span m='2711700'>I'd</span> <span m='2711790'>integrate</span> <span m='2712120'>that.</span>
  <span m='2712330'>That would</span> <span m='2712510'>be the</span> <span m='2712600'>normal</span>
  <span m='2712840'>thing that</span> <span m='2713110'>a</span> <span m='2713140'>lot</span>
  <span m='2713260'>of</span> <span m='2713320'>people would</span> <span m='2713560'>do.</span>
  <span m='2714710'>I</span> <span m='2714810'>don't</span> <span m='2714910'>know</span>
  <span m='2715010'>if</span> <span m='2715110'>you</span> <span m='2715210'>would</span>
  <span m='2715310'>do</span> <span m='2715410'>that.</span> <span m='2715510'>But</span>
  <span m='2715610'>a</span> <span m='2715710'>lot</span> <span m='2715810'>of</span>
  <span m='2715910'>people</span> <span m='2716010'>would</span> <span m='2716110'>do</span>
  <span m='2716210'>that.</span> <span m='2717490'>So</span> <span m='2718030'>that</span>
  <span m='2718150'>would</span> <span m='2718240'>be</span> <span m='2718400'>that</span>
  <span m='2718570'>what</span> <span m='2718720'>you would</span> <span m='2718810'>get.</span>
  </p><p><span m='2719110'>And</span> <span m='2719230'>what</span> <span m='2719410'>[?
  error ?]</span> <span m='2719590'>would</span> <span m='2719740'>you</span> <span
  m='2719840'>get?</span> <span m='2720100'>You'd</span> <span m='2720200'>have</span>
  <span m='2720320'>error</span> <span m='2720590'>that</span> <span m='2720700'>would</span>
  <span m='2720790'>be</span> <span m='2720890'>the</span> <span m='2720980'>scale</span>
  <span m='2721690'>of</span> <span m='2722500'>the</span> <span m='2722590'>width</span>
  <span m='2722800'>of</span> <span m='2722860'>the</span> <span m='2722920'>intervals
  to</span> <span m='2723250'>the</span> <span m='2723340'>fourth</span> <span m='2723580'>power.</span>
  <span m='2725110'>Right,</span> <span m='2725290'>because</span> <span m='2725770'>Simpson's</span>
  <span m='2725980'>rule</span> <span m='2726090'>exact</span> <span m='2726720'>up</span>
  <span m='2726850'>to</span> <span m='2726970'>the</span> <span m='2727030'>cubic.</span>
  <span m='2728430'>You guys</span> <span m='2728610'>remember</span> <span m='2728820'>this</span>
  <span m='2729120'>from</span> <span m='2729590'>high</span> <span m='2729960'>school?</span>
  <span m='2731500'>I</span> <span m='2731560'>don't</span> <span m='2731650'>know</span>
  <span m='2731710'>if you</span> <span m='2731770'>remember</span> <span m='2732010'>delta
  t</span> <span m='2732400'>to the</span> <span m='2732540'>fourth.</span> <span
  m='2733160'>Yeah,</span> <span m='2733550'>OK.</span> </p><p><span m='2734170'>So</span>
  <span m='2734940'>Simpson's</span> <span m='2735310'>rule</span> <span m='2737530'>has</span>
  <span m='2737830'>an</span> <span m='2738140'>order</span> <span m='2738700'>of</span>
  <span m='2738790'>delta</span> <span m='2739045'>t</span> <span m='2739300'>to</span>
  <span m='2739420'>the</span> <span m='2739540'>fourth.</span> <span m='2741260'>But</span>
  <span m='2741580'>Gauss's</span> <span m='2743950'>method</span> <span m='2745090'>has</span>
  <span m='2745330'>order</span> <span m='2745595'>of</span> <span m='2745860'>delta</span>
  <span m='2746345'>t</span> <span m='2746830'>to</span> <span m='2746980'>the</span>
  <span m='2747070'>sixth.</span> <span m='2748530'>So</span> <span m='2748900'>this</span>
  <span m='2749080'>is</span> <span m='2749230'>for</span> <span m='2749350'>three</span>
  <span m='2749550'>points.</span> <span m='2752130'>In</span> <span m='2752250'>Gauss's</span>
  <span m='2752530'>method,</span> <span m='2752740'>you</span> <span m='2752830'>can</span>
  <span m='2752920'>extend</span> <span m='2753280'>it</span> <span m='2753580'>to</span>
  <span m='2753700'>as</span> <span m='2753760'>many</span> <span m='2753910'>points
  as</span> <span m='2754210'>you</span> <span m='2754270'>want.</span> <span m='2756550'>All</span>
  <span m='2756610'>right,</span> <span m='2757030'>so</span> <span m='2757180'>that's</span>
  <span m='2757600'>kind</span> <span m='2757750'>of</span> <span m='2757810'>nice.</span>
  <span m='2758220'>You only do</span> <span m='2758460'>three</span> <span m='2758620'>points,</span>
  <span m='2758920'>you</span> <span m='2758980'>get</span> <span m='2759890'>[? error
  ?]</span> <span m='2760280'>of the</span> <span m='2760450'>sixth</span> <span m='2760900'>order.</span>
  <span m='2762160'>So</span> <span m='2762260'>that</span> <span m='2762370'>seems</span>
  <span m='2762730'>pretty</span> <span m='2762940'>efficient.</span> <span m='2764030'>So</span>
  <span m='2764080'>people</span> <span m='2764350'>kept</span> <span m='2764530'>going.</span>
  </p><p><span m='2765305'>And</span> <span m='2765790'>so</span> <span m='2766140'>the</span>
  <span m='2766320'>very,</span> <span m='2766740'>very</span> <span m='2766780'>popular</span>
  <span m='2767170'>one</span> <span m='2768490'>use,</span> <span m='2768760'>actually,</span>
  <span m='2769750'>seven</span> <span m='2770050'>points</span> <span m='2770290'>for</span>
  <span m='2770390'>Gauss.</span> <span m='2774940'>So</span> <span m='2775090'>you'd</span>
  <span m='2775300'>be</span> <span m='2775450'>able</span> <span m='2775600'>to</span>
  <span m='2775720'>get</span> <span m='2775870'>to</span> <span m='2778020'>the</span>
  <span m='2778200'>n</span> <span m='2778980'>minus</span> <span m='2779250'>1.</span>
  <span m='2780270'>So you'd</span> <span m='2780430'>be</span> <span m='2780570'>exact</span>
  <span m='2780900'>for</span> <span m='2781050'>13.</span> <span m='2783220'>So</span>
  <span m='2783320'>if</span> <span m='2783420'>you</span> <span m='2783520'>have</span>
  <span m='2783620'>delta t to</span> <span m='2783870'>the</span> <span m='2783960'>14th</span>
  <span m='2784350'>power</span> <span m='2785490'>as</span> <span m='2785620'>your</span>
  <span m='2786120'>error,</span> <span m='2786832'>that's</span> <span m='2787190'>pretty</span>
  <span m='2787370'>good.</span> <span m='2788450'>And</span> <span m='2791280'>then</span>
  <span m='2791430'>what</span> <span m='2791550'>people</span> <span m='2791790'>often</span>
  <span m='2792120'>do</span> <span m='2792270'>is</span> <span m='2792420'>they'll</span>
  <span m='2793560'>add</span> <span m='2793770'>eight</span> <span m='2793920'>more</span>
  <span m='2794100'>points.</span> </p><p><span m='2796760'>And</span> <span m='2796850'>they</span>
  <span m='2796940'>make</span> <span m='2797120'>another</span> <span m='2797420'>method</span>
  <span m='2798230'>that</span> <span m='2798320'>uses</span> <span m='2798650'>all</span>
  <span m='2798770'>these</span> <span m='2798890'>points.</span> <span m='2799220'>It's</span>
  <span m='2799310'>called</span> <span m='2799710'>[? Conrad's ?]</span> <span m='2804980'>method.</span>
  <span m='2805280'>He</span> <span m='2805350'>made</span> <span m='2805520'>another</span>
  <span m='2805730'>method</span> <span m='2806000'>that</span> <span m='2806300'>gives</span>
  <span m='2806480'>you</span> <span m='2806540'>the</span> <span m='2806600'>best</span>
  <span m='2806810'>possible</span> <span m='2807200'>solution</span> <span m='2807530'>if</span>
  <span m='2807620'>you</span> <span m='2807710'>had</span> <span m='2807800'>the</span>
  <span m='2807890'>15</span> <span m='2808190'>points,</span> <span m='2808730'>given</span>
  <span m='2808940'>that</span> <span m='2809070'>7</span> <span m='2809240'>of</span>
  <span m='2809300'>them</span> <span m='2809420'>are</span> <span m='2809480'>already</span>
  <span m='2809660'>fixed</span> <span m='2809900'>by</span> <span m='2810020'>the</span>
  <span m='2810110'>Gauss</span> <span m='2810380'>procedure.</span> <span m='2812090'>And</span>
  <span m='2812420'>so</span> <span m='2812600'>you</span> <span m='2812690'>can</span>
  <span m='2812840'>get</span> <span m='2813020'>the</span> <span m='2813110'>integral</span>
  <span m='2813740'>using</span> <span m='2814790'>Gauss's</span> <span m='2815150'>method</span>
  <span m='2816340'>and</span> <span m='2816500'>using</span> <span m='2816860'>[?
  Conrad's ?]</span> <span m='2817310'>method.</span> </p><p><span m='2827480'>So</span>
  <span m='2828890'>you</span> <span m='2829010'>can</span> <span m='2829120'>compute</span>
  <span m='2829340'>the</span> <span m='2829490'>i</span> <span m='2829840'>using</span>
  <span m='2830170'>Gauss's</span> <span m='2830460'>method,</span> <span m='2831020'>the</span>
  <span m='2831260'>seven</span> <span m='2831590'>points,</span> <span m='2832665'>the
  i</span> <span m='2833110'>with</span> <span m='2833240'>the</span> <span m='2833300'>[?
  Conrad ?]</span> <span m='2833760'>method.</span> <span m='2834700'>I</span> <span
  m='2834890'>don't</span> <span m='2834950'>know how</span> <span m='2835070'>to
  spell</span> <span m='2835330'>his name,</span> <span m='2835580'>Actually</span>
  <span m='2835750'>I</span> <span m='2836240'>think it's</span> <span m='2836400'>like
  this.</span> <span m='2838260'>15</span> <span m='2838610'>points.</span> <span
  m='2839930'>And</span> <span m='2840050'>then</span> <span m='2840170'>you</span>
  <span m='2840230'>can</span> <span m='2840350'>take</span> <span m='2840500'>the</span>
  <span m='2840590'>difference</span> <span m='2840860'>between</span> <span m='2841100'>these</span>
  <span m='2841220'>two.</span> <span m='2842690'>And</span> <span m='2842840'>if</span>
  <span m='2842900'>these</span> <span m='2843050'>two</span> <span m='2843170'>are</span>
  <span m='2843230'>really</span> <span m='2843440'>similar,</span> <span m='2844080'>then</span>
  <span m='2844130'>you</span> <span m='2844190'>might</span> <span m='2844310'>think</span>
  <span m='2844510'>your</span> <span m='2844630'>integral's</span> <span m='2844850'>pretty</span>
  <span m='2845030'>good.</span> <span m='2845940'>Because</span> <span m='2846100'>they're</span>
  <span m='2846160'>pretty</span> <span m='2846320'>different</span> <span m='2846560'>methods,</span>
  <span m='2847980'>and</span> <span m='2848410'>if</span> <span m='2848510'>they</span>
  <span m='2848600'>get</span> <span m='2848690'>the</span> <span m='2848780'>same</span>
  <span m='2848880'>number,</span> <span m='2849200'>you're</span> <span m='2849350'>good.</span>
  <span m='2849770'>And</span> <span m='2850180'>people</span> <span m='2850360'>have</span>
  <span m='2850510'>done</span> <span m='2850640'>a</span> <span m='2850670'>lot</span>
  <span m='2850790'>of</span> <span m='2851030'>numerical</span> <span m='2851390'>studies</span>
  <span m='2851690'>in</span> <span m='2851750'>this</span> <span m='2851870'>particular</span>
  <span m='2852260'>case,</span> <span m='2852530'>because</span> <span m='2852770'>it's</span>
  <span m='2852860'>used</span> <span m='2853070'>a</span> <span m='2853100'>lot</span>
  <span m='2853910'>in</span> <span m='2854030'>actual</span> <span m='2854300'>practice.</span>
  </p><p><span m='2855350'>And</span> <span m='2855470'>it</span> <span m='2855530'>turns</span>
  <span m='2855800'>out</span> <span m='2856610'>that</span> <span m='2856790'>the</span>
  <span m='2857050'>[? error ?]</span> <span m='2859750'>is</span> <span m='2859910'>almost</span>
  <span m='2860270'>always</span> <span m='2862280'>less</span> <span m='2862580'>than</span>
  <span m='2862760'>this</span> <span m='2863090'>quantity</span> <span m='2863580'>to</span>
  <span m='2863710'>the</span> <span m='2863750'>3</span> <span m='2863990'>Gauss</span>
  <span m='2864170'>power.</span> <span m='2865760'>So</span> <span m='2865940'>you</span>
  <span m='2866060'>have</span> <span m='2866210'>an</span> <span m='2866300'>error</span>
  <span m='2866690'>estimate.</span> <span m='2868480'>So</span> <span m='2869060'>you</span>
  <span m='2869510'>do</span> <span m='2869780'>15</span> <span m='2870080'>function</span>
  <span m='2870350'>evaluations.</span> <span m='2871760'>You</span> <span m='2872030'>get</span>
  <span m='2872270'>a</span> <span m='2872300'>pretty</span> <span m='2872570'>accurate</span>
  <span m='2874010'>value</span> <span m='2874310'>for</span> <span m='2874400'>your</span>
  <span m='2874520'>integral,</span> <span m='2874770'>maybe,</span> <span m='2875410'>if</span>
  <span m='2875540'>you</span> <span m='2875600'>can</span> <span m='2875740'>be</span>
  <span m='2875780'>fit</span> <span m='2876170'>well</span> <span m='2876350'>with</span>
  <span m='2877520'>whatever</span> <span m='2877760'>order</span> <span m='2877970'>polynomial,</span>
  <span m='2879480'>13th</span> <span m='2879930'>order</span> <span m='2879990'>polynomial.</span>
  <span m='2882120'>13th</span> <span m='2882510'>order</span> <span m='2882610'>polynomial,</span>
  <span m='2882750'>yeah.</span> </p><p><span m='2884850'>And</span> <span m='2887490'>so</span>
  <span m='2887720'>any function</span> <span m='2887850'>that can</span> <span m='2888060'>be</span>
  <span m='2888210'>fit</span> <span m='2888510'>pretty</span> <span m='2888720'>well</span>
  <span m='2888840'>with</span> <span m='2888940'>the</span> <span m='2888980'>13th</span>
  <span m='2889290'>order</span> <span m='2889600'>polynomial,</span> <span m='2889690'>you</span>
  <span m='2889900'>should</span> <span m='2889980'>get</span> <span m='2890100'>pretty</span>
  <span m='2890250'>good</span> <span m='2890410'>value in the</span> <span m='2890720'>integral.</span>
  <span m='2891700'>And</span> <span m='2891900'>you</span> <span m='2891960'>can</span>
  <span m='2892080'>check</span> <span m='2892860'>by</span> <span m='2893040'>comparing</span>
  <span m='2893460'>to the</span> <span m='2893560'>[? Conrad ?]</span> <span m='2893880'>estimate,</span>
  <span m='2894210'>which</span> <span m='2894390'>uses</span> <span m='2894510'>a</span>
  <span m='2894540'>lot</span> <span m='2894690'>more</span> <span m='2894810'>points.</span>
  <span m='2895550'>And</span> <span m='2895840'>if two of</span> <span m='2896190'>these</span>
  <span m='2896340'>guys</span> <span m='2896580'>give</span> <span m='2896670'>the</span>
  <span m='2896790'>same</span> <span m='2896940'>number</span> <span m='2897950'>or</span>
  <span m='2898350'>pretty</span> <span m='2898620'>close,</span> <span m='2899190'>then</span>
  <span m='2899340'>you're</span> <span m='2899400'>pretty</span> <span m='2899550'>confident</span>
  <span m='2899950'>that</span> <span m='2900090'>you're</span> <span m='2900850'>good.</span>
  <span m='2901110'>And</span> <span m='2901180'>there's</span> <span m='2901270'>even</span>
  <span m='2901410'>a</span> <span m='2901500'>math</span> <span m='2901720'>proof</span>
  <span m='2901940'>about</span> <span m='2902000'>this</span> <span m='2902600'>particular</span>
  <span m='2902770'>one.</span> <span m='2903360'>So</span> <span m='2903510'>this</span>
  <span m='2903690'>is</span> <span m='2903810'>like</span> <span m='2903990'>really</span>
  <span m='2904230'>popular,</span> <span m='2906630'>and</span> <span m='2906720'>it's</span>
  <span m='2906810'>a lot better</span> <span m='2907130'>than</span> <span m='2907320'>Simpson's</span>
  <span m='2907580'>rule,</span> <span m='2908310'>but</span> <span m='2908430'>it's</span>
  <span m='2908550'>kind of</span> <span m='2908810'>complicated.</span> </p><p><span
  m='2909690'>And</span> <span m='2909780'>part</span> <span m='2909960'>of</span>
  <span m='2910020'>it</span> <span m='2910170'>you</span> <span m='2910290'>have</span>
  <span m='2910380'>to</span> <span m='2910500'>recompute</span> <span m='2911100'>these</span>
  <span m='2911870'>tn's</span> <span m='2912510'>and</span> <span m='2912840'>wn's</span>
  <span m='2913740'>for</span> <span m='2913890'>the</span> <span m='2913980'>kind</span>
  <span m='2914100'>of</span> <span m='2914160'>problem</span> <span m='2914520'>you</span>
  <span m='2914740'>have.</span> <span m='2915000'>Yeah.</span> </p><p><span m='2915666'>AUDIENCE:</span>
  <span m='2915818'>If</span> <span m='2915970'>you're</span> <span m='2916122'>using</span>
  <span m='2917034'>15</span> <span m='2917490'>points</span> <span m='2918402'>already,</span>
  <span m='2921360'>why</span> <span m='2921610'>not</span> <span m='2921990'>just</span>
  <span m='2922240'>split</span> <span m='2922670'>your</span> <span m='2922930'>step</span>
  <span m='2923560'>size</span> <span m='2924015'>smaller?</span> <span m='2925440'>And</span>
  <span m='2925925'>if you</span> <span m='2926410'>did that,</span> <span m='2926850'>how
  would</span> <span m='2927295'>the error</span> <span m='2927740'>[INAUDIBLE]</span>
  <span m='2928185'>the</span> <span m='2928630'>simplest?</span> <span m='2929075'>Use</span>
  <span m='2929965'>a</span> <span m='2930410'>trapezoid.</span> </p><p><span m='2930860'>PROFESSOR:</span>
  <span m='2931075'>Trapezoid</span> <span m='2931290'>or</span> <span m='2931380'>Simpson's</span>
  <span m='2931560'>rule of</span> <span m='2931840'>something</span> <span m='2932150'>like
  that.</span> <span m='2932370'>Yes.</span> </p><p><span m='2932590'>AUDIENCE:</span>
  <span m='2932802'>How</span> <span m='2933014'>would the</span> <span m='2933438'>error
  with</span> <span m='2933862'>those 15</span> <span m='2934286'>steps</span> <span
  m='2934710'>using</span> <span m='2935070'>trapezoid</span> <span m='2935556'>compare</span>
  <span m='2936042'>to</span> <span m='2937500'>[? Conrad ?]</span> <span m='2937986'>and</span>
  <span m='2938472'>Gauss?</span> </p><p><span m='2939450'>PROFESSOR:</span> <span
  m='2939615'>So</span> <span m='2941190'>we</span> <span m='2941280'>should probably</span>
  <span m='2941520'>do</span> <span m='2941610'>the</span> <span m='2941730'>math.</span>
  <span m='2942190'>So</span> <span m='2942605'>say</span> <span m='2943020'>we</span>
  <span m='2943110'>did</span> <span m='2943260'>Simpson's</span> <span m='2943470'>rule,</span>
  <span m='2944520'>and</span> <span m='2944670'>we</span> <span m='2944790'>have</span>
  <span m='2945060'>delta</span> <span m='2945495'>t,</span> <span m='2946410'>and</span>
  <span m='2946650'>we</span> <span m='2947730'>divide</span> <span m='2948180'>it</span>
  <span m='2949140'>by</span> <span m='2949290'>15</span> <span m='2949770'>or</span>
  <span m='2949860'>something.</span> <span m='2951960'>Then</span> <span m='2952830'>we</span>
  <span m='2952920'>can</span> <span m='2953010'>figure</span> <span m='2953160'>out</span>
  <span m='2953220'>what</span> <span m='2953310'>this</span> <span m='2953520'>is,</span>
  <span m='2954120'>but</span> <span m='2954270'>it's</span> <span m='2954360'>still</span>
  <span m='2954570'>going</span> <span m='2954690'>to</span> <span m='2954750'>have</span>
  <span m='2954840'>the</span> <span m='2954900'>scaling</span> <span m='2956910'>to</span>
  <span m='2957030'>the</span> <span m='2957120'>fourth</span> <span m='2957420'>power.</span>
  <span m='2958270'>So</span> <span m='2958290'>the</span> <span m='2958380'>prefactor</span>
  <span m='2958635'>will</span> <span m='2958890'>be</span> <span m='2958980'>really</span>
  <span m='2959160'>tiny,</span> <span m='2959460'>because</span> <span m='2959610'>it</span>
  <span m='2959690'>will</span> <span m='2959760'>be</span> <span m='2959970'>1/15</span>
  <span m='2960450'>to</span> <span m='2960510'>the</span> <span m='2960570'>fourth</span>
  <span m='2960780'>power.</span> </p><p><span m='2962320'>But</span> <span m='2962430'>the</span>
  <span m='2962580'>scaling</span> <span m='2963840'>is</span> <span m='2963960'>bad.</span>
  <span m='2964410'>So</span> <span m='2964590'>that</span> <span m='2964920'>if</span>
  <span m='2965070'>I</span> <span m='2965190'>decide</span> <span m='2965580'>that</span>
  <span m='2965670'>my</span> <span m='2965790'>integral's</span> <span m='2966060'>not</span>
  <span m='2966180'>good</span> <span m='2966330'>enough, and</span> <span m='2966730'>I</span>
  <span m='2966830'>need</span> <span m='2966840'>to</span> <span m='2966930'>do</span>
  <span m='2967080'>more</span> <span m='2967260'>points</span> <span m='2967620'>as</span>
  <span m='2967680'>I</span> <span m='2967830'>double</span> <span m='2968070'>the</span>
  <span m='2968130'>number</span> <span m='2968280'>of</span> <span m='2968340'>points</span>
  <span m='2969780'>to</span> <span m='2969870'>get</span> <span m='2969990'>better</span>
  <span m='2970170'>accuracy,</span> <span m='2972100'>my</span> <span m='2972310'>thing</span>
  <span m='2972680'>won't</span> <span m='2972870'>improve</span> <span m='2973230'>that</span>
  <span m='2973380'>much.</span> <span m='2973650'>Because</span> <span m='2973870'>it's
  still</span> <span m='2973970'>only</span> <span m='2974260'>going</span> <span
  m='2974460'>to use</span> <span m='2974550'>the fourth</span> <span m='2974770'>power,</span>
  <span m='2975430'>whereas</span> <span m='2975690'>the</span> <span m='2975780'>Gauss'</span>
  <span m='2976040'>one</span> <span m='2976190'>say</span> <span m='2976320'>it's</span>
  <span m='2976410'>going</span> <span m='2976590'>use the</span> <span m='2976650'>sixth</span>
  <span m='2976860'>power</span> <span m='2977110'>if I</span> <span m='2977270'>only</span>
  <span m='2977370'>use</span> <span m='2977470'>the</span> <span m='2977520'>three</span>
  <span m='2977700'>points.</span> <span m='2978330'>Where</span> <span m='2978480'>we</span>
  <span m='2978540'>use</span> <span m='2978660'>15</span> <span m='2978930'>points,</span>
  <span m='2979140'>is</span> <span m='2979230'>going</span> <span m='2979350'>to</span>
  <span m='2979420'>get</span> <span m='2979600'>scale</span> <span m='2979870'>to
  some</span> <span m='2980100'>16th</span> <span m='2980460'>power or</span> <span
  m='2980840'>15th</span> <span m='2981030'>power</span> <span m='2981420'>or</span>
  <span m='2981690'>some</span> <span m='2981870'>really</span> <span m='2982020'>high</span>
  <span m='2982200'>power.</span> </p><p><span m='2983110'>So</span> <span m='2983640'>for</span>
  <span m='2983790'>doing</span> <span m='2984030'>sequences,</span> <span m='2985590'>the</span>
  <span m='2985890'>Gauss'</span> <span m='2986140'>one</span> <span m='2986300'>is</span>
  <span m='2986370'>a</span> <span m='2986400'>lot</span> <span m='2986550'>better.</span>
  <span m='2987880'>However,</span> <span m='2988770'>what</span> <span m='2988860'>people</span>
  <span m='2989070'>do</span> <span m='2989190'>is</span> <span m='2989670'>they</span>
  <span m='2990840'>usually</span> <span m='2991110'>pre-solve</span> <span m='2991830'>the</span>
  <span m='2991950'>system</span> <span m='2992220'>of</span> <span m='2992280'>equations.</span>
  <span m='2992730'>Because</span> <span m='2992880'>this system of</span> <span m='2993150'>equation</span>
  <span m='2993540'>does</span> <span m='2993720'>not</span> <span m='2993990'>depend.</span>
  <span m='2995520'>When</span> <span m='2995640'>you</span> <span m='2995700'>do
  it with</span> <span m='2995840'>the</span> <span m='2995970'>monomials,</span>
  <span m='2996480'>it</span> <span m='2997100'>doesn't</span> <span m='2997320'>depend</span>
  <span m='2997530'>what</span> <span m='2997940'>f</span> <span m='2998190'>is.</span>
  <span m='2998310'>You</span> <span m='2998400'>can</span> <span m='2998490'>figure</span>
  <span m='2998640'>out</span> <span m='2998700'>the</span> <span m='2998820'>optimal</span>
  <span m='2999150'>t's and</span> <span m='2999480'>w's</span> <span m='3000040'>ahead</span>
  <span m='3000190'>of</span> <span m='3000260'>time.</span> <span m='3001550'>And</span>
  <span m='3001670'>so</span> <span m='3001910'>they</span> <span m='3002060'>[INAUDIBLE]</span>
  <span m='3002270'>tables</span> <span m='3002660'>of</span> <span m='3002730'>them</span>
  <span m='3003110'>depending</span> <span m='3003530'>on</span> <span m='3004930'>where</span>
  <span m='3005130'>you</span> <span m='3005210'>want</span> <span m='3005330'>to</span>
  <span m='3005390'>go.</span> <span m='3005900'>People</span> <span m='3006120'>recomputed</span>
  <span m='3006620'>them,</span> <span m='3007580'>and</span> <span m='3007760'>then</span>
  <span m='3007910'>you</span> <span m='3007970'>can</span> <span m='3008060'>get
  them</span> <span m='3008210'>that</span> <span m='3008360'>way.</span> </p><p><span
  m='3011480'>Time</span> <span m='3011630'>is</span> <span m='3011720'>running</span>
  <span m='3011890'>out.</span> <span m='3012050'>I</span> <span m='3012130'>just</span>
  <span m='3012260'>want</span> <span m='3012340'>to</span> <span m='3013460'>jump</span>
  <span m='3013760'>up.</span> <span m='3016820'>Now,</span> <span m='3017075'>for</span>
  <span m='3017330'>single</span> <span m='3017690'>integrals,</span> <span m='3018590'>I</span>
  <span m='3018680'>didn't have</span> <span m='3018950'>to tell</span> <span m='3019100'>you
  and of</span> <span m='3019310'>this.</span> <span m='3019520'>Because</span> <span
  m='3019700'>you</span> <span m='3019780'>could have just</span> <span m='3020040'>solved</span>
  <span m='3020350'>it</span> <span m='3020420'>with</span> <span m='3020510'>your</span>
  <span m='3020710'>ODE</span> <span m='3021015'>solver.</span> <span m='3022960'>So</span>
  <span m='3023450'>you</span> <span m='3023520'>can</span> <span m='3023610'>just</span>
  <span m='3023730'>go</span> <span m='3023870'>to</span> <span m='3023960'>ode15s</span>
  <span m='3024770'>or</span> <span m='3025460'>ode45,</span> <span m='3026870'>and</span>
  <span m='3027260'>you'll</span> <span m='3027470'>get</span> <span m='3027620'>good</span>
  <span m='3027740'>enough.</span> <span m='3028400'>It</span> <span m='3028460'>won't</span>
  <span m='3028590'>be</span> <span m='3028700'>as</span> <span m='3028820'>efficient</span>
  <span m='3029190'>as</span> <span m='3029240'>Gaussian.</span> <span m='3030080'>But</span>
  <span m='3030170'>who</span> <span m='3030260'>cares.</span> <span m='3031220'>You</span>
  <span m='3031280'>still</span> <span m='3031430'>get</span> <span m='3031550'>a</span>
  <span m='3031610'>good</span> <span m='3031730'>answer.</span> <span m='3032210'>You</span>
  <span m='3032290'>can</span> <span m='3032440'>report</span> <span m='3032740'>to</span>
  <span m='3032810'>your</span> <span m='3032900'>boss.</span> <span m='3033440'>It'll</span>
  <span m='3033500'>take you</span> <span m='3033680'>three</span> <span m='3033860'>minutes</span>
  <span m='3035130'>to</span> <span m='3035510'>call</span> <span m='3035810'>it</span>
  <span m='3036000'>e45</span> <span m='3036410'>to integrate</span> <span m='3036890'>the</span>
  <span m='3037090'>one-dimensional</span> <span m='3037500'>integral.</span> </p><p><span
  m='3038360'>The</span> <span m='3038480'>real</span> <span m='3038690'>challenge</span>
  <span m='3039050'>comes</span> <span m='3039230'>with</span> <span m='3039310'>the</span>
  <span m='3039380'>multidimensional</span> <span m='3039680'>integrals.</span> <span
  m='3040640'>So</span> <span m='3042370'>in</span> <span m='3042500'>a</span> <span
  m='3042530'>lot</span> <span m='3042740'>of</span> <span m='3042800'>problems,</span>
  <span m='3043470'>we</span> <span m='3043490'>have</span> <span m='3043580'>more</span>
  <span m='3043760'>than</span> <span m='3043910'>one</span> <span m='3044210'>variable</span>
  <span m='3044580'>we</span> <span m='3044660'>want</span> <span m='3044810'>to</span>
  <span m='3044870'>integrate</span> <span m='3045230'>over.</span> <span m='3047600'>And</span>
  <span m='3047930'>so if</span> <span m='3048080'>you</span> <span m='3048170'>have</span>
  <span m='3049280'>an</span> <span m='3049430'>integral,</span> <span m='3050900'>say,
  of</span> <span m='3051190'>a</span> <span m='3051380'>to</span> <span m='3051520'>b</span>
  <span m='3052730'>from</span> <span m='3052940'>the</span> <span m='3053030'>lower</span>
  <span m='3053360'>bound</span> <span m='3055070'>of</span> <span m='3056780'>x</span>
  <span m='3057210'>to</span> <span m='3057370'>upper</span> <span m='3057580'>bound</span>
  <span m='3057790'>of</span> <span m='3057920'>x.</span> <span m='3058620'>So this
  is</span> <span m='3058940'>dx,</span> <span m='3059875'>dy,</span> <span m='3061195'>f
  of</span> <span m='3061690'>xy.</span> <span m='3063520'>This</span> <span m='3063670'>is</span>
  <span m='3063760'>the kind</span> <span m='3063970'>of</span> <span m='3064030'>integral</span>
  <span m='3064330'>that</span> <span m='3064630'>you</span> <span m='3064750'>might</span>
  <span m='3064900'>need</span> <span m='3065020'>to</span> <span m='3065110'>do</span>
  <span m='3065260'>sometimes.</span> <span m='3067350'>OK,</span> <span m='3067760'>because
  you</span> <span m='3067840'>might</span> <span m='3067940'>have</span> <span m='3068050'>two</span>
  <span m='3068200'>variables</span> <span m='3068370'>that</span> <span m='3068470'>you</span>
  <span m='3068530'>want</span> <span m='3068620'>to</span> <span m='3068690'>integrate</span>
  <span m='3068980'>over.</span> </p><p><span m='3070180'>And</span> <span m='3070930'>so</span>
  <span m='3071100'>how</span> <span m='3071420'>we</span> <span m='3071560'>do</span>
  <span m='3071740'>this,</span> <span m='3073960'>the</span> <span m='3074050'>best</span>
  <span m='3074230'>way</span> <span m='3074320'>to</span> <span m='3074360'>think</span>
  <span m='3074530'>about it,</span> <span m='3074750'>I</span> <span m='3074800'>think,</span>
  <span m='3075070'>is</span> <span m='3075190'>that</span> <span m='3075720'>f of</span>
  <span m='3075880'>x</span> <span m='3078570'>is</span> <span m='3078780'>equal</span>
  <span m='3079020'>to</span> <span m='3079320'>the</span> <span m='3079470'>integral</span>
  <span m='3081680'>of</span> <span m='3082135'>l of</span> <span m='3082590'>x</span>
  <span m='3082860'>u of</span> <span m='3083318'>x</span> <span m='3084692'>dy</span>
  <span m='3086066'>f</span> <span m='3086982'>of</span> <span m='3087440'>xy.</span>
  <span m='3090600'>And</span> <span m='3090770'>then,</span> <span m='3091110'>if</span>
  <span m='3091280'>I</span> <span m='3091400'>knew</span> <span m='3091580'>what</span>
  <span m='3091670'>that</span> <span m='3091820'>was,</span> <span m='3092600'>I</span>
  <span m='3092720'>would</span> <span m='3092840'>evaluate</span> <span m='3093260'>that</span>
  <span m='3093450'>say</span> <span m='3093600'>with a</span> <span m='3093930'>Gaussian</span>
  <span m='3094160'>quadrature</span> <span m='3094690'>or</span> <span m='3094740'>something.</span>
  <span m='3094990'>So</span> <span m='3095120'>I'd</span> <span m='3095240'>say</span>
  <span m='3096040'>that</span> <span m='3096180'>this</span> <span m='3096360'>i</span>
  <span m='3096640'>2d</span> <span m='3098180'>is</span> <span m='3098300'>approximately</span>
  <span m='3098780'>equal</span> <span m='3099080'>to</span> <span m='3099410'>the</span>
  <span m='3099530'>sum</span> <span m='3100070'>of</span> <span m='3100160'>some</span>
  <span m='3100370'>weights--</span> <span m='3101540'>I'll</span> <span m='3101770'>label</span>
  <span m='3102120'>them x</span> <span m='3102290'>just to</span> <span m='3102920'>remind</span>
  <span m='3103360'>you</span> <span m='3103430'>where they</span> <span m='3103610'>came</span>
  <span m='3103790'>from--</span> <span m='3106680'>times</span> <span m='3107920'>f</span>
  <span m='3109165'>of</span> <span m='3109580'>xn.</span> <span m='3112190'>And</span>
  <span m='3112310'>I</span> <span m='3112370'>would</span> <span m='3112520'>use,
  say,</span> <span m='3112960'>Gaussian</span> <span m='3113460'>quadrature</span>
  <span m='3113910'>to figure out what</span> <span m='3114200'>the</span> <span m='3114290'>best</span>
  <span m='3114500'>value</span> <span m='3114690'>of the</span> <span m='3114790'>x's</span>
  <span m='3115150'>and the</span> <span m='3115330'>y's</span> <span m='3115440'>are</span>
  <span m='3115670'>to</span> <span m='3115730'>use.</span> </p><p><span m='3117110'>And</span>
  <span m='3117260'>then</span> <span m='3117680'>I</span> <span m='3117800'>would</span>
  <span m='3117950'>actually</span> <span m='3118250'>evaluate</span> <span m='3118700'>this</span>
  <span m='3118880'>guy</span> <span m='3119780'>with</span> <span m='3120020'>a</span>
  <span m='3120200'>quadrature</span> <span m='3120590'>two.</span> <span m='3121730'>So</span>
  <span m='3121910'>I'd</span> <span m='3122150'>say</span> <span m='3122390'>f</span>
  <span m='3122540'>of</span> <span m='3122680'>xk</span> <span m='3124004'>or</span>
  <span m='3124800'>xn</span> <span m='3126900'>is</span> <span m='3127090'>equal</span>
  <span m='3127390'>to</span> <span m='3127660'>the</span> <span m='3127840'>integral</span>
  <span m='3128270'>from</span> <span m='3128560'>l</span> <span m='3128800'>of</span>
  <span m='3128920'>xn</span> <span m='3129975'>to</span> <span m='3130370'>u</span>
  <span m='3130600'>of</span> <span m='3130720'>xn</span> <span m='3132790'>dy</span>
  <span m='3133620'>f</span> <span m='3133880'>of</span> <span m='3134140'>xn</span>
  <span m='3136000'>y.</span> <span m='3137100'>And</span> <span m='3137950'>so</span>
  <span m='3138160'>this</span> <span m='3138400'>itself,</span> <span m='3138790'>I</span>
  <span m='3138880'>would</span> <span m='3139030'>give</span> <span m='3139180'>it</span>
  <span m='3139660'>another</span> <span m='3139900'>quadrature.</span> <span m='3140260'>This</span>
  <span m='3140620'>is</span> <span m='3140830'>going</span> <span m='3140950'>to
  be</span> <span m='3141010'>equal</span> <span m='3141250'>some</span> <span m='3141700'>other</span>
  <span m='3141880'>weights.</span> <span m='3144390'>nj</span> <span m='3147364'>f</span>
  <span m='3147860'>of</span> <span m='3148140'>xn</span> <span m='3149880'>yj.</span>
  <span m='3152495'>Is</span> <span m='3152920'>that</span> <span m='3153010'>all</span>
  <span m='3153390'>right?</span> </p><p><span m='3154910'>And</span> <span m='3155060'>so</span>
  <span m='3155150'>this</span> <span m='3155360'>is</span> <span m='3155450'>nested</span>
  <span m='3155900'>inside</span> <span m='3156230'>this.</span> <span m='3157130'>So</span>
  <span m='3157280'>now,</span> <span m='3157430'>I</span> <span m='3157490'>have</span>
  <span m='3157640'>a</span> <span m='3157700'>double</span> <span m='3158030'>loop.</span>
  <span m='3160350'>So</span> <span m='3160490'>if</span> <span m='3160610'>I</span>
  <span m='3160700'>took</span> <span m='3160940'>me,</span> <span m='3162230'>I</span>
  <span m='3162290'>don't</span> <span m='3162380'>know,</span> <span m='3162540'>15</span>
  <span m='3162830'>points,</span> <span m='3163570'>15</span> <span m='3163820'>function</span>
  <span m='3164030'>evaluations</span> <span m='3164510'>to</span> <span m='3164600'>get</span>
  <span m='3164730'>a</span> <span m='3164750'>good</span> <span m='3164860'>number</span>
  <span m='3165050'>for</span> <span m='3165150'>my</span> <span m='3165290'>integral</span>
  <span m='3165740'>in</span> <span m='3165860'>one</span> <span m='3166010'>dimension,</span>
  <span m='3167120'>then</span> <span m='3167300'>it</span> <span m='3167360'>might</span>
  <span m='3167660'>take</span> <span m='3167930'>me</span> <span m='3171460'>15</span>
  <span m='3171740'>squared</span> <span m='3171950'>function</span> <span m='3172190'>evaluations</span>
  <span m='3172910'>to</span> <span m='3173060'>get</span> <span m='3173240'>a</span>
  <span m='3173300'>pretty</span> <span m='3173450'>good</span> <span m='3173570'>integral</span>
  <span m='3173750'>for</span> <span m='3173880'>two.</span> <span m='3175240'>15</span>
  <span m='3175520'>might</span> <span m='3175640'>be</span> <span m='3175730'>a</span>
  <span m='3175760'>little</span> <span m='3175910'>optimistic,</span> <span m='3176450'>so</span>
  <span m='3176580'>maybe</span> <span m='3176900'>100</span> <span m='3177260'>is</span>
  <span m='3177350'>more</span> <span m='3177500'>like</span> <span m='3177700'>if</span>
  <span m='3177830'>you</span> <span m='3177980'>really want</span> <span m='3178100'>a</span>
  <span m='3178160'>good</span> <span m='3178250'>number.</span> <span m='3179210'>So</span>
  <span m='3179570'>I need</span> <span m='3179750'>101</span> <span m='3180230'>dimension,</span>
  <span m='3180680'>100</span> <span m='3181070'>in</span> <span m='3181395'>the</span>
  <span m='3181720'>second</span> <span m='3182100'>dimension</span> <span m='3182370'>squared.</span>
  <span m='3182650'>Because</span> <span m='3182800'>I</span> <span m='3182880'>subdivided</span>
  <span m='3183220'>the integral</span> <span m='3183560'>into</span> <span m='3183710'>six</span>
  <span m='3184310'>equal</span> <span m='3184520'>pieces,</span> <span m='3184910'>say.</span>
  <span m='3186020'>And</span> <span m='3186170'>then</span> <span m='3186980'>now,</span>
  <span m='3187190'>so</span> <span m='3187340'>this</span> <span m='3187460'>is</span>
  <span m='3187550'>OK.</span> <span m='3188030'>So</span> <span m='3188180'>you</span>
  <span m='3188270'>can</span> <span m='3188360'>do</span> <span m='3188450'>this.</span>
  <span m='3188980'>It's</span> <span m='3189110'>only</span> <span m='3189290'>10,000</span>
  <span m='3189800'>function</span> <span m='3190040'>evaluations.</span> <span m='3190640'>No</span>
  <span m='3190760'>problem,</span> <span m='3191090'>you've got</span> <span m='3191210'>a</span>
  <span m='3191270'>good</span> <span m='3191440'>gigahertz</span> <span m='3191750'>computer.</span>
  </p><p><span m='3193630'>Now,</span> <span m='3194120'>in</span> <span m='3194240'>reality,</span>
  <span m='3194500'>in</span> <span m='3194760'>a</span> <span m='3194860'>lot</span>
  <span m='3194960'>of</span> <span m='3195060'>them,</span> <span m='3195260'>we</span>
  <span m='3195360'>do</span> <span m='3195460'>have</span> <span m='3195560'>a</span>
  <span m='3195660'>lot</span> <span m='3195760'>more</span> <span m='3196190'>dimensions</span>
  <span m='3196610'>than</span> <span m='3196730'>that.</span> <span m='3197100'>So</span>
  <span m='3197630'>in</span> <span m='3197720'>my</span> <span m='3197870'>life,</span>
  <span m='3198170'>I</span> <span m='3198200'>do</span> <span m='3198350'>a</span>
  <span m='3198380'>lot</span> <span m='3198590'>of</span> <span m='3198680'>electronic</span>
  <span m='3199040'>structure</span> <span m='3199310'>integrals.</span> <span m='3200420'>We</span>
  <span m='3200480'>have</span> <span m='3200750'>integrals</span> <span m='3200990'>that</span>
  <span m='3201110'>are</span> <span m='3201620'>dx</span> <span m='3202100'>1d</span>
  <span m='3203390'>y1</span> <span m='3203780'>d</span> <span m='3204050'>z1</span>
  <span m='3204890'>for</span> <span m='3204980'>the</span> <span m='3205070'>first</span>
  <span m='3205310'>electron</span> <span m='3205940'>interacting</span> <span m='3206230'>with</span>
  <span m='3206720'>a</span> <span m='3206780'>second.</span> <span m='3210670'>And</span>
  <span m='3212130'>then</span> <span m='3212250'>something</span> <span m='3212510'>that</span>
  <span m='3212770'>I'm</span> <span m='3212880'>trying</span> <span m='3213030'>to</span>
  <span m='3213090'>integrate.</span> <span m='3214820'>It</span> <span m='3214890'>depends
  on,</span> <span m='3215220'>say,</span> <span m='3215340'>the</span> <span m='3215430'>distance</span>
  <span m='3215790'>between</span> <span m='3217110'>electron</span> <span m='3217500'>one</span>
  <span m='3217920'>and</span> <span m='3218160'>electron</span> <span m='3218520'>two.</span>
  <span m='3221250'>OK,</span> <span m='3221970'>so</span> <span m='3222120'>this</span>
  <span m='3222300'>is</span> <span m='3222360'>actually</span> <span m='3222670'>six</span>
  <span m='3222900'>integrals.</span> </p><p><span m='3226386'>And</span> <span m='3226890'>so</span>
  <span m='3227040'>instead</span> <span m='3227280'>of</span> <span m='3227340'>being</span>
  <span m='3227520'>a</span> <span m='3227610'>2</span> <span m='3227820'>in</span>
  <span m='3227880'>the</span> <span m='3227970'>exponent,</span> <span m='3228720'>this</span>
  <span m='3228870'>is</span> <span m='3228930'>going</span> <span m='3229050'>to</span>
  <span m='3229110'>be</span> <span m='3229200'>like</span> <span m='3229380'>a</span>
  <span m='3229550'>6</span> <span m='3229920'>in the</span> <span m='3230150'>exponent.</span>
  <span m='3231700'>So</span> <span m='3231890'>now,</span> <span m='3232060'>this</span>
  <span m='3232210'>is</span> <span m='3232320'>10</span> <span m='3232480'>to the</span>
  <span m='3232590'>12th.</span> <span m='3234350'>That</span> <span m='3234450'>means</span>
  <span m='3234520'>that</span> <span m='3234580'>just</span> <span m='3234760'>evaluating</span>
  <span m='3235330'>one</span> <span m='3235540'>integral</span> <span m='3235870'>this</span>
  <span m='3236050'>way</span> <span m='3237270'>might</span> <span m='3237460'>take</span>
  <span m='3237670'>me</span> <span m='3237790'>100</span> <span m='3238060'>seconds</span>
  <span m='3239040'>if</span> <span m='3239170'>I</span> <span m='3239230'>can</span>
  <span m='3239380'>evaluate</span> <span m='3239740'>the</span> <span m='3239830'>functions</span>
  <span m='3240880'>like</span> <span m='3241060'>that.</span> <span m='3242350'>But</span>
  <span m='3242500'>in</span> <span m='3242590'>fact,</span> <span m='3243070'>the</span>
  <span m='3243190'>functions</span> <span m='3243490'>I</span> <span m='3243520'>want</span>
  <span m='3243740'>to</span> <span m='3243840'>evaluate</span> <span m='3243990'>here,</span>
  <span m='3244150'>these</span> <span m='3244300'>guys</span> <span m='3244540'>will</span>
  <span m='3244660'>take</span> <span m='3245200'>multiple</span> <span m='3245590'>operations</span>
  <span m='3246100'>to</span> <span m='3246250'>evaluate</span> <span m='3246550'>the</span>
  <span m='3246610'>function.</span> <span m='3247910'>And</span> <span m='3248020'>so</span>
  <span m='3248930'>this</span> <span m='3249090'>turns</span> <span m='3249320'>out</span>
  <span m='3249410'>I</span> <span m='3249490'>can't</span> <span m='3249640'>do.</span>
  <span m='3249790'>I</span> <span m='3249960'>can't</span> <span m='3250180'>even</span>
  <span m='3250240'>do one</span> <span m='3250330'>integral</span> <span m='3250750'>this</span>
  <span m='3250870'>way</span> <span m='3251940'>with</span> <span m='3252205'>its</span>
  <span m='3252470'>six</span> <span m='3252720'>integrals</span> <span m='3252980'>deep.</span>
  </p><p><span m='3254270'>And</span> <span m='3254510'>so</span> <span m='3255530'>this</span>
  <span m='3255740'>is</span> <span m='3256040'>the</span> <span m='3256160'>general</span>
  <span m='3256550'>problem</span> <span m='3258490'>of</span> <span m='3258970'>multidimensional</span>
  <span m='3259430'>integration.</span> <span m='3259850'>It's</span> <span m='3259910'>called</span>
  <span m='3260090'>the</span> <span m='3260180'>curse</span> <span m='3260480'>of</span>
  <span m='3260540'>dimensionality.</span> <span m='3261500'>Each</span> <span m='3261830'>time</span>
  <span m='3262040'>you</span> <span m='3262130'>add</span> <span m='3262310'>one</span>
  <span m='3262490'>more</span> <span m='3262760'>integral,</span> <span m='3263880'>you're</span>
  <span m='3264050'>nested</span> <span m='3264320'>there.</span> <span m='3264680'>All
  of</span> <span m='3264900'>a sudden,</span> <span m='3265160'>the</span> <span
  m='3265310'>effort</span> <span m='3265580'>goes</span> <span m='3265760'>up</span>
  <span m='3266090'>tremendously</span> <span m='3266420'>and</span> <span m='3266750'>more,</span>
  <span m='3268220'>a</span> <span m='3268250'>couple</span> <span m='3268430'>of</span>
  <span m='3268500'>orders of</span> <span m='3268640'>magnitude</span> <span m='3269050'>more.</span>
  <span m='3270410'>And</span> <span m='3270620'>so</span> <span m='3271370'>we'll</span>
  <span m='3271520'>come</span> <span m='3271670'>back</span> <span m='3271970'>later</span>
  <span m='3272180'>in</span> <span m='3272240'>the</span> <span m='3272300'>class</span>
  <span m='3273050'>about</span> <span m='3273440'>how</span> <span m='3274300'>to</span>
  <span m='3274370'>deal</span> <span m='3274520'>with</span> <span m='3274610'>cases</span>
  <span m='3274850'>like</span> <span m='3274970'>this</span> <span m='3275150'>when</span>
  <span m='3275270'>you</span> <span m='3275330'>have</span> <span m='3275480'>high</span>
  <span m='3275600'>dimensionality</span> <span m='3276170'>cases</span> <span m='3276830'>to</span>
  <span m='3276920'>try</span> <span m='3277070'>to</span> <span m='3277160'>get</span>
  <span m='3277250'>better</span> <span m='3277460'>scaling.</span> <span m='3278390'>Instead</span>
  <span m='3278630'>of</span> <span m='3278720'>having</span> <span m='3278930'>it</span>
  <span m='3278990'>being</span> <span m='3279200'>exponential,</span> <span m='3280240'>it</span>
  <span m='3280500'>was</span> <span m='3280640'>really</span> <span m='3280790'>100</span>
  <span m='3281000'>to</span> <span m='3281140'>the</span> <span m='3281450'>n</span>
  <span m='3281750'>right</span> <span m='3282155'>now,</span> <span m='3283323'>100
  to</span> <span m='3283746'>the n</span> <span m='3284170'>dimensions.</span> <span
  m='3287060'>[? Can we ?]</span> <span m='3287540'>figure</span> <span m='3287720'>out</span>
  <span m='3287840'>some</span> <span m='3287990'>better</span> <span m='3288140'>way</span>
  <span m='3288230'>to</span> <span m='3288290'>do</span> <span m='3288410'>it.</span>
  <span m='3290070'>All</span> <span m='3290170'>right,</span> <span m='3290540'>thank</span>
  <span m='3290780'>you.</span> </p>
type: course
uid: 571c93ac486601cc3437682ad96bc2ab

---
None