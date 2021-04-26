---
about_this_resource_text: <p><strong>Description:</strong> This lecture continued
  on the topic of solving nonlinear equations, introducing quasi Newton-Raphson method
  and Boyden's method.</p> <p><strong>Instructor:</strong> James Swan</p>
course_id: 10-34-numerical-methods-applied-to-chemical-engineering-fall-2015
embedded_media:
- id: Video-YouTube-Stream
  media_location: 8kPUI5HoVxg
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: Video-YouTube-Stream
  type: Video
  uid: 08b92e005fe2352559cdbc3379520bc3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/8kPUI5HoVxg/default.jpg
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d11cc22d8575079b8ec711949c21eac0
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id1271456481
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: Video-iTunes U-MP4
  type: Video
  uid: 88cd91459cda21ac116a55a43d260fc6
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 8kPUI5HoVxg
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1b1843caf4dd2faafaf81a5b238e4fe9
- id: 8kPUI5HoVxg.srt
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-8-quasi-newton-raphson-methods/8kPUI5HoVxg.srt
  title: 3play caption file
  type: null
  uid: dea895faa88afee1cc3aef38c2bfe8a2
- id: 8kPUI5HoVxg.pdf
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-8-quasi-newton-raphson-methods/8kPUI5HoVxg.pdf
  title: 3play pdf file
  type: null
  uid: 5c867712a2eebc808f59a290c8efc232
- id: Caption-3Play YouTube id-SRT
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 8313071c936fc00819d61d37fbfa73d1
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0424575f9fd7ea5f36da904ab334b8fb
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT10.34F15/MIT10_34F15_ses08_300k.mp4
  parent_uid: 44db3d5653762ccc6b2e9efc295dfe51
  title: Video-Internet Archive-MP4
  type: Video
  uid: fbd1b77f1262eaaacad5d5c175f52cb2
inline_embed_id: 66511156session8quasinewtonraphsonmethods21490271
layout: video
order_index: null
parent_uid: afa0ff29750f6846eda04cb1a3d4b84a
related_resources_text: ''
short_url: session-8-quasi-newton-raphson-methods
technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-8-quasi-newton-raphson-methods
template_type: Tabbed
title: 'Session 8: Quasi-Newton-Raphson Methods'
transcript: <p><span m='1540'>The</span> <span m='1630'>following</span> <span m='2080'>content</span>
  <span m='2560'>is</span> <span m='2680'>provided</span> <span m='3130'>under</span>
  <span m='3370'>a</span> <span m='3430'>Creative</span> <span m='3910'>Commons</span>
  <span m='4270'>license.</span> <span m='5300'>Your</span> <span m='5380'>support</span>
  <span m='5890'>will</span> <span m='6040'>help</span> <span m='6280'>MIT</span>
  <span m='6760'>OpenCourseWare</span> <span m='7510'>continue</span> <span m='7990'>to</span>
  <span m='8140'>offer</span> <span m='8470'>high-quality</span> <span m='9160'>educational</span>
  <span m='9820'>resources</span> <span m='10390'>for</span> <span m='10540'>free.</span>
  <span m='11600'>To</span> <span m='11620'>make</span> <span m='11800'>a</span> <span
  m='11860'>donation</span> <span m='12610'>or</span> <span m='12790'>to</span> <span
  m='12910'>view</span> <span m='13120'>additional</span> <span m='13540'>materials</span>
  <span m='14140'>from</span> <span m='14320'>hundreds</span> <span m='14650'>of</span>
  <span m='14770'>MIT</span> <span m='15130'>courses,</span> <span m='16460'>visit</span>
  <span m='16630'>MIT</span> <span m='17140'>OpenCourseWare</span> <span m='18100'>at</span>
  <span m='18250'>ocw.mit.edu.</span> </p><p></p><p><span m='24660'>JAMES SWAN:</span>
  <span m='24830'>OK.</span> <span m='27280'>Should we</span> <span m='27570'>begin?</span>
  <span m='30280'>Let</span> <span m='30370'>me</span> <span m='30490'>remind</span>
  <span m='30790'>you,</span> <span m='31300'>we</span> <span m='31540'>switched</span>
  <span m='32619'>topics.</span> <span m='33070'>We</span> <span m='33160'>transitioned</span>
  <span m='33910'>from</span> <span m='34090'>linear</span> <span m='34420'>algebra,</span>
  <span m='35110'>solving</span> <span m='35500'>systems</span> <span m='35890'>of</span>
  <span m='35980'>linear</span> <span m='36310'>equations,</span> <span m='36880'>to</span>
  <span m='37000'>solving</span> <span m='37330'>systems</span> <span m='37750'>of</span>
  <span m='37840'>nonlinear</span> <span m='38530'>equations.</span> <span m='39220'>And</span>
  <span m='40630'>it</span> <span m='40690'>turns</span> <span m='40960'>out,</span>
  <span m='41860'>linear</span> <span m='42160'>algebra</span> <span m='42520'>is</span>
  <span m='42670'>at</span> <span m='42760'>the</span> <span m='42880'>core</span>
  <span m='43300'>of</span> <span m='43420'>the</span> <span m='43540'>way</span>
  <span m='43750'>that</span> <span m='43900'>we're</span> <span m='43960'>going</span>
  <span m='44080'>to</span> <span m='44140'>solve</span> <span m='44500'>these</span>
  <span m='44710'>equations.</span> </p><p><span m='45380'>We</span> <span m='45480'>need</span>
  <span m='45610'>iterative</span> <span m='46060'>approaches.</span> <span m='47380'>These</span>
  <span m='47500'>problems</span> <span m='47770'>are</span> <span m='47830'>complicated.</span>
  <span m='48530'>We</span> <span m='48630'>don't</span> <span m='48640'>know</span>
  <span m='48760'>how</span> <span m='48880'>many</span> <span m='49090'>solutions</span>
  <span m='49640'>there</span> <span m='49720'>could</span> <span m='49870'>be.</span>
  <span m='50680'>We</span> <span m='50740'>have</span> <span m='50830'>no</span>
  <span m='50950'>idea</span> <span m='51160'>where</span> <span m='51310'>those</span>
  <span m='51430'>solutions</span> <span m='51940'>could</span> <span m='52060'>be</span>
  <span m='52180'>located.</span> <span m='52970'>We</span> <span m='53070'>have</span>
  <span m='53080'>no</span> <span m='53230'>exact</span> <span m='53800'>ways</span>
  <span m='54130'>of</span> <span m='54190'>finding</span> <span m='54700'>them.</span>
  <span m='55460'>We</span> <span m='55570'>use</span> <span m='55780'>iterative</span>
  <span m='56140'>methods</span> <span m='56590'>to</span> <span m='56770'>transform</span>
  <span m='57790'>non-linear</span> <span m='58360'>equations</span> <span m='59140'>into</span>
  <span m='60130'>simpler</span> <span m='60550'>problems,</span> <span m='61190'>right?</span>
  <span m='62110'>Iterates</span> <span m='62950'>of</span> <span m='63160'>systems</span>
  <span m='63640'>of</span> <span m='63760'>linear</span> <span m='64150'>equations.</span>
  </p><p><span m='64849'>And</span> <span m='64950'>the</span> <span m='64989'>key</span>
  <span m='65230'>to</span> <span m='65379'>that</span> <span m='65650'>was</span>
  <span m='67120'>the</span> <span m='67210'>Newton-Raphson</span> <span m='67900'>method.</span>
  <span m='69680'>So</span> <span m='69830'>I'm going</span> <span m='69950'>to</span>
  <span m='70010'>pick</span> <span m='70160'>up</span> <span m='70310'>where</span>
  <span m='70430'>we</span> <span m='70550'>left</span> <span m='70790'>off</span>
  <span m='71000'>with</span> <span m='71090'>the</span> <span m='71180'>Newton-Raphson</span>
  <span m='71750'>method,</span> <span m='72390'>and</span> <span m='72490'>we're</span>
  <span m='72560'>going</span> <span m='72690'>find</span> <span m='72890'>out</span>
  <span m='73010'>ways</span> <span m='73520'>of</span> <span m='74570'>being</span>
  <span m='74870'>less</span> <span m='75650'>Newton-Raphson-y</span> <span m='77030'>in</span>
  <span m='77180'>order</span> <span m='77420'>to</span> <span m='77810'>overcome</span>
  <span m='78410'>some</span> <span m='79610'>difficulties</span> <span m='80420'>with</span>
  <span m='80600'>the</span> <span m='80690'>method,</span> <span m='81050'>shortcomings</span>
  <span m='81740'>of</span> <span m='81830'>the</span> <span m='81950'>method.</span>
  <span m='82610'>There</span> <span m='82760'>are</span> <span m='82790'>a</span>
  <span m='82820'>number</span> <span m='83150'>of</span> <span m='83240'>them</span>
  <span m='83450'>that</span> <span m='83600'>have</span> <span m='83750'>to</span>
  <span m='83870'>be</span> <span m='83990'>overcome</span> <span m='84530'>in</span>
  <span m='84650'>various</span> <span m='85070'>ways.</span> </p><p><span m='85340'>And</span>
  <span m='85490'>you sort</span> <span m='85610'>of</span> <span m='85670'>choose</span>
  <span m='86270'>these</span> <span m='87120'>so-called</span> <span m='87520'>quasi-</span>
  <span m='88010'>Newton-Raphson</span> <span m='88730'>methods</span> <span m='89660'>as</span>
  <span m='89870'>you</span> <span m='89960'>need</span> <span m='90110'>them.</span>
  <span m='90670'>OK,</span> <span m='91010'>so</span> <span m='91220'>you'll</span>
  <span m='91430'>find</span> <span m='91730'>out.</span> <span m='91940'>You</span>
  <span m='92060'>try</span> <span m='92180'>to</span> <span m='92270'>solve</span>
  <span m='92520'>a</span> <span m='92600'>problem.</span> <span m='93030'>And</span>
  <span m='93840'>the</span> <span m='94020'>Newton-Raphson</span> <span m='94550'>method</span>
  <span m='95520'>presents</span> <span m='95900'>some</span> <span m='96140'>difficulty,</span>
  <span m='96800'>you might</span> <span m='97190'>resort</span> <span m='97580'>to</span>
  <span m='97740'>a</span> <span m='97830'>quasi</span> <span m='98120'>Newton-Raphson</span>
  <span m='98750'>method</span> <span m='99050'>instead.</span> </p><p><span m='99980'>Built</span>
  <span m='100280'>into</span> <span m='100640'>MATLAB</span> <span m='101630'>is</span>
  <span m='102260'>non-linear</span> <span m='102890'>equations</span> <span m='103390'>solver.</span>
  <span m='104060'>fsolve.</span> <span m='104790'>OK,</span> <span m='104990'>it's</span>
  <span m='105170'>going</span> <span m='105290'>to</span> <span m='105350'>happily</span>
  <span m='105980'>solve</span> <span m='106460'>systems</span> <span m='106970'>of</span>
  <span m='107090'>nonlinear</span> <span m='107600'>equations</span> <span m='108080'>for
  you,</span> <span m='108410'>and</span> <span m='108530'>it's going to</span> <span
  m='108560'>use</span> <span m='108770'>this</span> <span m='108980'>methodology</span>
  <span m='109670'>to</span> <span m='109790'>do</span> <span m='109970'>it.</span>
  <span m='110520'>It's going</span> <span m='110640'>to</span> <span m='110740'>use</span>
  <span m='110930'>various</span> <span m='111410'>aspects</span> <span m='111920'>of</span>
  <span m='111980'>these</span> <span m='112160'>quasi-</span> <span m='112520'>Newton-Raphson</span>
  <span m='113180'>methods</span> <span m='113630'>to</span> <span m='113750'>do</span>
  <span m='113930'>it.</span> <span m='113990'>I'll</span> <span m='114110'>sort</span>
  <span m='114290'>of</span> <span m='114350'>point</span> <span m='114650'>out</span>
  <span m='115280'>places</span> <span m='115700'>where</span> <span m='116150'>fsolve</span>
  <span m='116780'>will</span> <span m='117050'>take</span> <span m='117380'>from</span>
  <span m='117650'>our</span> <span m='117890'>lecture</span> <span m='118430'>and</span>
  <span m='118670'>implement</span> <span m='119090'>them</span> <span m='119240'>for</span>
  <span m='119450'>you.</span> </p><p><span m='119560'>It</span> <span m='119600'>will</span>
  <span m='119720'>even</span> <span m='119930'>use</span> <span m='120050'>some</span>
  <span m='120170'>more</span> <span m='120320'>complicated</span> <span m='120860'>methods</span>
  <span m='121310'>that</span> <span m='121430'>we'll</span> <span m='121520'>talk</span>
  <span m='121760'>about</span> <span m='121970'>later</span> <span m='122270'>on</span>
  <span m='122480'>in</span> <span m='122570'>the</span> <span m='122660'>context</span>
  <span m='123170'>of</span> <span m='123260'>optimization</span> <span m='123680'>.</span>
  <span m='124850'>Somebody</span> <span m='125150'>asked</span> <span m='127310'>an</span>
  <span m='127430'>interesting</span> <span m='127910'>question,</span> <span m='128210'>which</span>
  <span m='128360'>is</span> <span m='128660'>how</span> <span m='128870'>many</span>
  <span m='129110'>of</span> <span m='129199'>these</span> <span m='129410'>nonlinear</span>
  <span m='129889'>equations</span> <span m='130460'>am</span> <span m='130580'>I</span>
  <span m='130639'>going</span> <span m='130789'>to</span> <span m='130850'>want</span>
  <span m='130970'>to</span> <span m='131060'>solve</span> <span m='132110'>at</span>
  <span m='132260'>once?</span> <span m='132890'>Right?</span> </p><p><span m='133280'>Like</span>
  <span m='133820'>I</span> <span m='133880'>have</span> <span m='134000'>a</span>
  <span m='134060'>system</span> <span m='134420'>of</span> <span m='134540'>these</span>
  <span m='134750'>equations.</span> <span m='135590'>What</span> <span m='135770'>does</span>
  <span m='135950'>a</span> <span m='136010'>big</span> <span m='136250'>system</span>
  <span m='136760'>of</span> <span m='136850'>nonlinear</span> <span m='137420'>equations</span>
  <span m='137990'>look</span> <span m='138200'>like?</span> <span m='138800'>And</span>
  <span m='138890'>just</span> <span m='139040'>like</span> <span m='139220'>with</span>
  <span m='139340'>linear</span> <span m='139700'>equations,</span> <span m='140210'>it's</span>
  <span m='140390'>as</span> <span m='140510'>big</span> <span m='140780'>as</span>
  <span m='140900'>you</span> <span m='141080'>can</span> <span m='141470'>imagine.</span>
  <span m='142170'>So</span> <span m='142970'>one</span> <span m='143750'>case</span>
  <span m='144170'>you</span> <span m='144290'>could</span> <span m='144410'>think</span>
  <span m='144620'>about</span> <span m='144890'>is</span> <span m='145040'>trying</span>
  <span m='145370'>to</span> <span m='145490'>solve,</span> <span m='146390'>for</span>
  <span m='146510'>example,</span> <span m='147060'>the</span> <span m='147140'>steady</span>
  <span m='147890'>Navia-Stokes</span> <span m='148710'>equations.</span> <span m='149450'>That's</span>
  <span m='149630'>a</span> <span m='149720'>nonlinear</span> <span m='150500'>partial</span>
  <span m='150980'>differential</span> <span m='151490'>equation</span> <span m='152480'>for</span>
  <span m='152630'>the</span> <span m='152720'>velocity</span> <span m='153290'>field</span>
  <span m='153710'>and</span> <span m='153800'>the</span> <span m='153890'>pressure</span>
  <span m='154430'>in</span> <span m='154550'>a</span> <span m='154610'>fluid.</span>
  </p><p><span m='155710'>And</span> <span m='155830'>a</span> <span m='155900'>at</span>
  <span m='156140'>Reynolds</span> <span m='156530'>number,</span> <span m='156800'>that</span>
  <span m='156950'>non-linearity</span> <span m='158480'>is</span> <span m='158600'>going</span>
  <span m='158720'>to</span> <span m='158780'>present</span> <span m='159170'>itself</span>
  <span m='159710'>in</span> <span m='159830'>terms</span> <span m='160160'>of</span>
  <span m='160280'>inertial</span> <span m='160820'>terms</span> <span m='161360'>that</span>
  <span m='162330'>may</span> <span m='162690'>even</span> <span m='163040'>dominate</span>
  <span m='163700'>the</span> <span m='163820'>flow</span> <span m='164090'>characteristics</span>
  <span m='164890'>in</span> <span m='165200'>many</span> <span m='165440'>places.</span>
  <span m='166190'>We'll</span> <span m='166460'>learn</span> <span m='166730'>ways</span>
  <span m='167030'>of</span> <span m='167120'>discretizing</span> <span m='167870'>partial</span>
  <span m='168200'>differential</span> <span m='168650'>equations</span> <span m='169250'>like</span>
  <span m='169490'>that.</span> <span m='170400'>And</span> <span m='170480'>so</span>
  <span m='170630'>then,</span> <span m='171380'>at</span> <span m='171710'>each</span>
  <span m='171950'>point</span> <span m='172190'>in</span> <span m='172280'>the</span>
  <span m='172370'>fluid</span> <span m='172670'>we're</span> <span m='172820'>interested</span>
  <span m='173330'>in,</span> <span m='173580'>we're</span> <span m='173680'>going</span>
  <span m='173690'>to</span> <span m='173750'>have</span> <span m='173900'>a</span>
  <span m='173960'>non-linear</span> <span m='174500'>equation</span> <span m='174980'>that</span>
  <span m='175100'>we</span> <span m='175190'>have</span> <span m='175370'>to</span>
  <span m='175490'>solve.</span> </p><p><span m='176090'>So there's</span> <span m='176420'>going</span>
  <span m='176540'>to</span> <span m='176600'>be</span> <span m='176660'>a</span>
  <span m='176680'>system</span> <span m='177140'>of</span> <span m='177260'>these</span>
  <span m='177440'>non-linear</span> <span m='177950'>equations</span> <span m='178520'>that</span>
  <span m='178640'>are</span> <span m='178700'>coupled</span> <span m='179150'>together.</span>
  <span m='179870'>How</span> <span m='179990'>many</span> <span m='180140'>points</span>
  <span m='180440'>are</span> <span m='180530'>there</span> <span m='180650'>going</span>
  <span m='180770'>to</span> <span m='180860'>be?</span> <span m='181070'>That's</span>
  <span m='181280'>up</span> <span m='181400'>to</span> <span m='181550'>you,</span>
  <span m='182480'>OK?</span> <span m='183320'>And</span> <span m='183530'>so</span>
  <span m='183670'>you're going to</span> <span m='183890'>need</span> <span m='184070'>methods</span>
  <span m='184520'>like</span> <span m='184760'>this</span> <span m='185030'>to</span>
  <span m='185150'>solve</span> <span m='185490'>that.</span> <span m='185680'>It</span>
  <span m='185750'>sounds</span> <span m='185990'>very</span> <span m='186170'>complicated.</span>
  <span m='186770'>So</span> <span m='186920'>a</span> <span m='186950'>lot</span>
  <span m='187100'>of</span> <span m='187190'>times</span> <span m='187520'>in</span>
  <span m='187700'>fluid</span> <span m='187940'>mechanics,</span> <span m='188420'>we</span>
  <span m='188510'>have</span> <span m='188870'>better</span> <span m='189050'>ways</span>
  <span m='189320'>of</span> <span m='189440'>going</span> <span m='189680'>about</span>
  <span m='189920'>doing</span> <span m='190250'>it.</span> <span m='190470'>But</span>
  <span m='190520'>in</span> <span m='190640'>principle,</span> <span m='191600'>we've</span>
  <span m='191720'>have</span> <span m='191840'>any</span> <span m='191990'>number</span>
  <span m='192770'>of</span> <span m='192890'>nonlinear</span> <span m='193400'>equations</span>
  <span m='193850'>that</span> <span m='193940'>we</span> <span m='194060'>want</span>
  <span m='194210'>to</span> <span m='194270'>solve.</span> </p><p><span m='198820'>We</span>
  <span m='198920'>discussed</span> <span m='199110'>last</span> <span m='199500'>time,</span>
  <span m='199840'>the</span> <span m='199860'>new</span> <span m='200100'>Newton-Raphson</span>
  <span m='200490'>method,</span> <span m='201040'>which</span> <span m='201180'>was</span>
  <span m='201390'>based</span> <span m='201720'>around</span> <span m='201930'>the</span>
  <span m='202050'>idea</span> <span m='202350'>of</span> <span m='202470'>linearization.</span>
  <span m='203310'>We</span> <span m='203370'>have</span> <span m='203490'>these</span>
  <span m='203640'>nonlinear</span> <span m='204300'>equations.</span> <span m='206290'>We</span>
  <span m='206410'>don't</span> <span m='206530'>know</span> <span m='206620'>what</span>
  <span m='206710'>to</span> <span m='206800'>do</span> <span m='206920'>with</span>
  <span m='207040'>them.</span> <span m='207190'>So</span> <span m='207340'>let's</span>
  <span m='207580'>linearize</span> <span m='208360'>them,</span> <span m='208720'>right?</span>
  </p><p><span m='209350'>If</span> <span m='209470'>we</span> <span m='209560'>have</span>
  <span m='209650'>some</span> <span m='209860'>guess</span> <span m='210190'>for</span>
  <span m='210340'>the</span> <span m='210430'>solution,</span> <span m='210850'>which</span>
  <span m='211590'>isn't</span> <span m='211780'>perfect,</span> <span m='212260'>but</span>
  <span m='212410'>it's</span> <span m='212530'>our</span> <span m='212620'>best</span>
  <span m='212860'>possible</span> <span m='213310'>guess.</span> <span m='214150'>Let's</span>
  <span m='214360'>look</span> <span m='214540'>at</span> <span m='214600'>the</span>
  <span m='214690'>function</span> <span m='215110'>and</span> <span m='215200'>find</span>
  <span m='215670'>a</span> <span m='215770'>linearized</span> <span m='216550'>form</span>
  <span m='216880'>of</span> <span m='216940'>the</span> <span m='217030'>function</span>
  <span m='217490'>and</span> <span m='217600'>see</span> <span m='217780'>where</span>
  <span m='217890'>that</span> <span m='218020'>linearized</span> <span m='218620'>form</span>
  <span m='219010'>has</span> <span m='219250'>an</span> <span m='219340'>intercept.</span>
  <span m='220490'>And</span> <span m='221860'>we</span> <span m='221980'>just</span>
  <span m='222160'>have</span> <span m='222310'>an</span> <span m='222400'>Ansatz.</span>
  <span m='222880'>We</span> <span m='223030'>guess</span> <span m='223360'>that</span>
  <span m='223540'>this</span> <span m='223720'>is</span> <span m='223840'>a</span>
  <span m='223900'>better</span> <span m='224530'>solution</span> <span m='225160'>than</span>
  <span m='225310'>the</span> <span m='225400'>one</span> <span m='225580'>we</span>
  <span m='225730'>had</span> <span m='225940'>before.</span> <span m='226660'>And</span>
  <span m='226780'>we</span> <span m='226960'>iterate.</span> </p><p><span m='228610'>It</span>
  <span m='228700'>turns</span> <span m='229030'>out</span> <span m='229150'>you</span>
  <span m='229330'>can</span> <span m='229510'>prove</span> <span m='230740'>that</span>
  <span m='230890'>this</span> <span m='231100'>sort</span> <span m='231520'>of</span>
  <span m='231640'>a</span> <span m='231700'>strategy--</span> <span m='232540'>this</span>
  <span m='232750'>Newton-Raphson</span> <span m='233560'>strategy</span> <span m='234520'>is</span>
  <span m='234700'>locally</span> <span m='235310'>convergent.</span> <span m='236440'>If</span>
  <span m='236620'>I</span> <span m='236680'>start</span> <span m='237160'>with</span>
  <span m='237340'>a</span> <span m='237400'>guess</span> <span m='237730'>sufficiently</span>
  <span m='238330'>close</span> <span m='238720'>to</span> <span m='238840'>the</span>
  <span m='238960'>root,</span> <span m='239710'>you</span> <span m='239830'>can</span>
  <span m='239980'>prove</span> <span m='240250'>mathematically</span> <span m='241420'>that</span>
  <span m='241540'>this</span> <span m='241720'>procedure</span> <span m='242410'>will</span>
  <span m='242680'>terminate</span> <span m='244390'>with</span> <span m='244600'>a</span>
  <span m='244660'>solution</span> <span m='245170'>at</span> <span m='245320'>the</span>
  <span m='245440'>root,</span> <span m='245740'>right?</span> <span m='245980'>It's</span>
  <span m='246130'>going</span> <span m='246280'>to</span> <span m='246370'>approach</span>
  <span m='246940'>after</span> <span m='247180'>an</span> <span m='247270'>infinite</span>
  <span m='247570'>number</span> <span m='247820'>of</span> <span m='247860'>iterates,</span>
  <span m='248510'>the</span> <span m='248670'>root.</span> </p><p><span m='250060'>That's</span>
  <span m='250240'>wonderful.</span> <span m='250980'>It's</span> <span m='251150'>locally</span>
  <span m='251620'>convergent,</span> <span m='252130'>not</span> <span m='252310'>globally</span>
  <span m='252850'>convergent.</span> <span m='253200'>So</span> <span m='253550'>this</span>
  <span m='253630'>is</span> <span m='253720'>one</span> <span m='253840'>of</span>
  <span m='253930'>those</span> <span m='254080'>problems</span> <span m='254500'>that</span>
  <span m='254620'>we</span> <span m='254710'>discussed.</span> <span m='257230'>Take</span>
  <span m='257440'>a</span> <span m='257500'>second</span> <span m='257800'>here,</span>
  <span m='258269'>right?</span> <span m='258519'>Here's</span> <span m='258670'>your</span>
  <span m='258760'>Newton-Raphson</span> <span m='259055'>formula.</span> <span m='259660'>You've</span>
  <span m='259720'>got</span> <span m='259839'>it</span> <span m='259959'>on</span>
  <span m='260079'>your</span> <span m='260200'>slides.</span> <span m='260860'>Take</span>
  <span m='261070'>a</span> <span m='261100'>second</span> <span m='261399'>here</span>
  <span m='262150'>and--</span> <span m='263800'>this</span> <span m='263950'>is</span>
  <span m='264040'>sort</span> <span m='264220'>of</span> <span m='264280'>interesting.</span>
  <span m='264830'>Derive</span> <span m='265090'>the</span> <span m='265180'>Babylonian</span>
  <span m='265720'>method,</span> <span m='266410'>right?</span> </p><p><span m='266620'>Turns
  out</span> <span m='266930'>the</span> <span m='267000'>Babylonians</span> <span
  m='267640'>didn't</span> <span m='267760'>know</span> <span m='267880'>anything</span>
  <span m='268150'>about</span> <span m='268360'>Newton-Raphson</span> <span m='269080'>but</span>
  <span m='269200'>they</span> <span m='269290'>had</span> <span m='269410'>some</span>
  <span m='269560'>good</span> <span m='269740'>guesses</span> <span m='270280'>for</span>
  <span m='270430'>how</span> <span m='270550'>to</span> <span m='270640'>find</span>
  <span m='270940'>square</span> <span m='271270'>roots,</span> <span m='272170'>right?</span>
  <span m='272410'>Find</span> <span m='272620'>the</span> <span m='272740'>roots</span>
  <span m='273040'>of</span> <span m='273130'>an</span> <span m='273220'>equation</span>
  <span m='273640'>like</span> <span m='273850'>this.</span> <span m='274330'>See</span>
  <span m='274540'>that</span> <span m='274750'>you</span> <span m='275050'>understand</span>
  <span m='275500'>the</span> <span m='275590'>new</span> <span m='275710'>Newton-Raphson</span>
  <span m='276090'>method</span> <span m='276370'>by</span> <span m='276700'>deriving</span>
  <span m='277060'>the</span> <span m='277150'>Babylonian</span> <span m='277720'>method,</span>
  <span m='278470'>right?</span> <span m='278860'>The</span> <span m='279160'>iterative</span>
  <span m='279580'>method</span> <span m='279910'>for</span> <span m='280060'>finding</span>
  <span m='280510'>the</span> <span m='280600'>square</span> <span m='280900'>root</span>
  <span m='281110'>of</span> <span m='281230'>s</span> <span m='281980'>as</span>
  <span m='282160'>the</span> <span m='282280'>root</span> <span m='282580'>of</span>
  <span m='282730'>this</span> <span m='282940'>equation.</span> <span m='283715'>Can</span>
  <span m='283980'>you</span> <span m='284090'>do it?</span> </p><p><span m='284410'>[SIDE
  CONVERSATION]</span> </p><p></p><p><span m='366880'>JAMES SWAN:</span> <span m='367045'>Yes,</span>
  <span m='367210'>you</span> <span m='367300'>know</span> <span m='367380'>how</span>
  <span m='367470'>to</span> <span m='367610'>do</span> <span m='367730'>this,</span>
  <span m='368070'>right?</span> <span m='369460'>So</span> <span m='369580'>calculate</span>
  <span m='369970'>the</span> <span m='370060'>derivative.</span> <span m='370570'>The</span>
  <span m='370660'>derivative</span> <span m='371020'>is</span> <span m='371170'>2x.</span>
  <span m='372460'>Here's</span> <span m='372610'>our</span> <span m='372700'>formula</span>
  <span m='373180'>for</span> <span m='373300'>the</span> <span m='373420'>iterative</span>
  <span m='373720'>method.</span> <span m='374790'>Right?</span> <span m='375610'>So</span>
  <span m='375790'>it's</span> <span m='376240'>f</span> <span m='376480'>of</span>
  <span m='376630'>x</span> <span m='377110'>over</span> <span m='377350'>f</span>
  <span m='377470'>prime</span> <span m='377770'>of</span> <span m='377890'>x.</span>
  <span m='378940'>That</span> <span m='379090'>sets</span> <span m='379360'>the</span>
  <span m='379480'>magnitude</span> <span m='380050'>of</span> <span m='380140'>the</span>
  <span m='380260'>stop.</span> <span m='381040'>The</span> <span m='381130'>direction</span>
  <span m='381700'>is</span> <span m='382030'>minus</span> <span m='382720'>this</span>
  <span m='382930'>magnitude.</span> <span m='383590'>It's</span> <span m='383740'>in</span>
  <span m='383860'>one</span> <span m='384070'>d,</span> <span m='384290'>so</span>
  <span m='384460'>we</span> <span m='384520'>either</span> <span m='384700'>go</span>
  <span m='384820'>left</span> <span m='385090'>or</span> <span m='385180'>we</span>
  <span m='385300'>go</span> <span m='385450'>right.</span> </p><p><span m='386470'>Minus</span>
  <span m='386930'>sets</span> <span m='387190'>the</span> <span m='387280'>direction.</span>
  <span m='388210'>We</span> <span m='388360'>add</span> <span m='388480'>that</span>
  <span m='388630'>to</span> <span m='388750'>our</span> <span m='388840'>previous</span>
  <span m='389260'>guess.</span> <span m='389770'>And</span> <span m='390100'>we</span>
  <span m='390220'>have</span> <span m='390340'>our</span> <span m='390400'>new</span>
  <span m='390610'>iterate,</span> <span m='391180'>right?</span> <span m='391560'>You</span>
  <span m='391690'>substitute</span> <span m='391975'>f</span> <span m='392260'>and</span>
  <span m='392750'>f</span> <span m='392890'>prime,</span> <span m='393730'>and</span>
  <span m='393850'>you</span> <span m='393940'>can</span> <span m='394120'>simplify</span>
  <span m='394630'>this</span> <span m='394840'>down</span> <span m='395140'>to</span>
  <span m='395230'>the</span> <span m='395320'>Babylonian</span> <span m='395890'>method,</span>
  <span m='396190'>which</span> <span m='396370'>said</span> <span m='397870'>take</span>
  <span m='398110'>the</span> <span m='398260'>average</span> <span m='399340'>of</span>
  <span m='399580'>x</span> <span m='400210'>and</span> <span m='400510'>s</span>
  <span m='400750'>over</span> <span m='401020'>x.</span> <span m='401740'>If</span>
  <span m='401920'>I'm</span> <span m='402070'>at</span> <span m='402190'>the</span>
  <span m='402280'>root,</span> <span m='402490'>both</span> <span m='402730'>of</span>
  <span m='402790'>these</span> <span m='402970'>should</span> <span m='403240'>be</span>
  <span m='403960'>square</span> <span m='404320'>root</span> <span m='404590'>of</span>
  <span m='404830'>s.</span> <span m='405510'>And</span> <span m='405610'>this</span>
  <span m='405760'>quantity</span> <span m='406150'>should</span> <span m='406360'>be</span>
  <span m='406510'>zero</span> <span m='406990'>exactly,</span> <span m='407740'>right?</span>
  <span m='408856'>And</span> <span m='409430'>you'll</span> <span m='409550'>get</span>
  <span m='409730'>your</span> <span m='409820'>solution.</span> </p><p><span m='410550'>So</span>
  <span m='411950'>that's</span> <span m='412160'>the</span> <span m='412370'>Babylonian</span>
  <span m='412760'>method,</span> <span m='413090'>right?</span> <span m='413600'>It's
  just</span> <span m='414110'>an</span> <span m='414230'>extension</span> <span m='414650'>of</span>
  <span m='414740'>the</span> <span m='414830'>Newton-Raphson</span> <span m='415370'>method.</span>
  <span m='415580'>It was</span> <span m='415670'>pretty</span> <span m='415910'>good</span>
  <span m='416120'>back</span> <span m='416330'>in</span> <span m='416420'>the</span>
  <span m='416510'>day,</span> <span m='416750'>right?</span> <span m='416960'>Quadratic</span>
  <span m='417470'>convergence</span> <span m='418100'>to</span> <span m='418250'>the</span>
  <span m='418340'>square</span> <span m='418610'>root</span> <span m='418760'>of</span>
  <span m='418850'>a</span> <span m='418910'>number.</span> <span m='420450'>I</span>
  <span m='420590'>mentioned</span> <span m='421100'>early</span> <span m='421410'>on</span>
  <span m='422060'>computers</span> <span m='422540'>got</span> <span m='422660'>really</span>
  <span m='422900'>good</span> <span m='423220'>in</span> <span m='423350'>computing</span>
  <span m='423980'>square</span> <span m='424280'>roots</span> <span m='424850'>at</span>
  <span m='425030'>one</span> <span m='425270'>point,</span> <span m='425600'>because</span>
  <span m='425870'>somebody</span> <span m='427490'>did</span> <span m='427670'>something</span>
  <span m='428210'>kind</span> <span m='428390'>of</span> <span m='428450'>magic.</span>
  </p><p><span m='429380'>They</span> <span m='429530'>came</span> <span m='429680'>up</span>
  <span m='429800'>with</span> <span m='429980'>a</span> <span m='430100'>scheme</span>
  <span m='430640'>for</span> <span m='430790'>getting</span> <span m='430970'>good</span>
  <span m='431150'>initial</span> <span m='431480'>guesses</span> <span m='432290'>for</span>
  <span m='432440'>the</span> <span m='432530'>square</span> <span m='432830'>root.</span>
  <span m='433240'>This</span> <span m='433330'>iterative</span> <span m='433670'>method</span>
  <span m='434030'>has</span> <span m='434240'>to</span> <span m='434360'>start</span>
  <span m='434810'>with</span> <span m='434960'>some</span> <span m='435140'>initial</span>
  <span m='435500'>guess.</span> <span m='435950'>If it</span> <span m='436010'>starts</span>
  <span m='436340'>far</span> <span m='436610'>away,</span> <span m='437380'>it'll</span>
  <span m='437510'>take</span> <span m='437690'>more</span> <span m='437960'>iterations</span>
  <span m='438530'>to</span> <span m='438650'>get</span> <span m='438860'>there.</span>
  <span m='439320'>It'll</span> <span m='439370'>get</span> <span m='439580'>there,</span>
  <span m='440250'>but</span> <span m='440550'>it's going</span> <span m='440660'>to</span>
  <span m='440760'>take</span> <span m='440930'>more</span> <span m='441080'>iterations</span>
  <span m='441620'>to</span> <span m='441710'>get</span> <span m='441890'>there.</span>
  <span m='442800'>That's</span> <span m='442880'>undesirable</span> <span m='443520'>if</span>
  <span m='443600'>you're</span> <span m='443690'>trying</span> <span m='443870'>to</span>
  <span m='443990'>do</span> <span m='444110'>fast</span> <span m='444470'>calculations.</span>
  </p><p><span m='445280'>So somebody</span> <span m='445550'>came</span> <span m='445700'>up</span>
  <span m='445790'>with</span> <span m='445880'>some</span> <span m='446030'>magic</span>
  <span m='446420'>scheme,</span> <span m='446840'>using</span> <span m='447140'>floating</span>
  <span m='447530'>point</span> <span m='447770'>mathematics,</span> <span m='448460'>right?</span>
  <span m='448610'>They</span> <span m='448820'>masked</span> <span m='449330'>some</span>
  <span m='449600'>of</span> <span m='449660'>the</span> <span m='450320'>bits</span>
  <span m='450890'>in</span> <span m='451040'>the</span> <span m='451130'>digits</span>
  <span m='451520'>of</span> <span m='451580'>these</span> <span m='451820'>numbers.</span>
  <span m='452720'>A</span> <span m='452780'>special</span> <span m='453320'>number</span>
  <span m='453650'>to</span> <span m='453800'>mask</span> <span m='454250'>those</span>
  <span m='454490'>bits.</span> <span m='455120'>They</span> <span m='455240'>found</span>
  <span m='455480'>that</span> <span m='455750'>using</span> <span m='456080'>optimization,</span>
  <span m='456770'>it</span> <span m='456830'>turns</span> <span m='457100'>out.</span>
  </p><p><span m='457880'>And</span> <span m='458030'>they</span> <span m='458120'>got</span>
  <span m='458240'>really</span> <span m='458570'>good</span> <span m='458690'>initial</span>
  <span m='459050'>guesses,</span> <span m='459590'>and</span> <span m='459710'>then</span>
  <span m='459830'>it</span> <span m='459890'>would</span> <span m='459980'>take</span>
  <span m='460250'>one</span> <span m='460460'>or</span> <span m='460520'>two</span>
  <span m='460700'>iterations</span> <span m='461360'>with</span> <span m='462080'>the</span>
  <span m='462200'>Newton-Raphson</span> <span m='462740'>method</span> <span m='463040'>to</span>
  <span m='463160'>get</span> <span m='464000'>16</span> <span m='464420'>digits</span>
  <span m='464690'>of</span> <span m='464780'>accuracy.</span> <span m='465450'>That's</span>
  <span m='465590'>pretty</span> <span m='465800'>good.</span> <span m='467990'>But</span>
  <span m='468110'>good</span> <span m='468260'>initial</span> <span m='468590'>guesses</span>
  <span m='468920'>are</span> <span m='469010'>important.</span> <span m='469620'>We'll</span>
  <span m='469670'>talk</span> <span m='469880'>about</span> <span m='470030'>that</span>
  <span m='470150'>next</span> <span m='470420'>week</span> <span m='470600'>on</span>
  <span m='470750'>Wednesday.</span> <span m='471260'>Where</span> <span m='471380'>do</span>
  <span m='471470'>those</span> <span m='471650'>good</span> <span m='471800'>initial</span>
  <span m='472160'>guesses</span> <span m='472520'>come</span> <span m='472760'>from?</span>
  </p><p><span m='473670'>But</span> <span m='474620'>sometimes</span> <span m='474920'>we</span>
  <span m='475000'>don't</span> <span m='475130'>have</span> <span m='475310'>those</span>
  <span m='475520'>available</span> <span m='475940'>to</span> <span m='476090'>us.</span>
  <span m='476340'>So</span> <span m='476450'>what</span> <span m='476600'>are</span>
  <span m='476690'>some</span> <span m='476840'>other</span> <span m='476990'>ways</span>
  <span m='477260'>that</span> <span m='477380'>we</span> <span m='477500'>can</span>
  <span m='477590'>improve</span> <span m='478010'>the</span> <span m='478160'>Newton-Raphson</span>
  <span m='478660'>method?</span> <span m='478890'>That</span> <span m='478990'>will</span>
  <span m='479090'>be</span> <span m='479210'>the</span> <span m='479300'>topic</span>
  <span m='479660'>of</span> <span m='479720'>today's</span> <span m='480080'>lecture.</span>
  <span m='482730'>What's</span> <span m='483030'>the</span> <span m='483090'>Newton-Raphson</span>
  <span m='483600'>method</span> <span m='483870'>look</span> <span m='484080'>like</span>
  <span m='484230'>graphically</span> <span m='484950'>in</span> <span m='485100'>many</span>
  <span m='485340'>dimensions.</span> <span m='486060'>We</span> <span m='486180'>talked</span>
  <span m='486420'>about</span> <span m='486600'>this</span> <span m='486780'>Jacobian.</span>
  <span m='488130'>Right,</span> <span m='488310'>when</span> <span m='488430'>we're</span>
  <span m='488520'>trying</span> <span m='488700'>to</span> <span m='489150'>find</span>
  <span m='489510'>the</span> <span m='489600'>roots</span> <span m='490200'>of</span>
  <span m='490350'>a</span> <span m='490380'>non-linear</span> <span m='491070'>equation</span>
  <span m='492480'>where</span> <span m='492870'>our</span> <span m='492990'>function</span>
  <span m='493500'>has</span> <span m='493890'>more</span> <span m='494250'>than</span>
  <span m='494430'>one</span> <span m='494670'>dimension--</span> <span m='495390'>let's</span>
  <span m='495510'>say</span> <span m='495630'>it</span> <span m='495690'>has</span>
  <span m='495960'>two</span> <span m='496140'>dimensions.</span> <span m='496670'>So</span>
  <span m='496770'>we</span> <span m='496870'>have</span> <span m='496970'>an</span>
  <span m='497070'>f</span> <span m='497130'>1</span> <span m='497370'>and</span>
  <span m='497490'>an</span> <span m='497630'>f</span> <span m='497870'>2.</span>
  <span m='498700'>And</span> <span m='498810'>our</span> <span m='499010'>unknowns</span>
  <span m='499770'>our</span> <span m='500040'>x</span> <span m='500295'>1</span>
  <span m='500550'>and</span> <span m='500690'>x</span> <span m='501120'>2,</span>
  <span m='501270'>they live</span> <span m='501450'>in</span> <span m='501510'>the</span>
  <span m='501690'>x1</span> <span m='501990'>x2</span> <span m='502410'>plane,</span>
  <span m='503090'>right?</span> </p><p><span m='503870'>f1</span> <span m='504420'>might</span>
  <span m='504630'>be</span> <span m='504780'>this</span> <span m='505430'>say</span>
  <span m='505700'>bowl-shaped</span> <span m='506400'>function.</span> <span m='507060'>I've</span>
  <span m='507210'>sketched</span> <span m='507660'>out</span> <span m='507780'>in</span>
  <span m='507880'>red,</span> <span m='508200'>right?</span> <span m='508350'>It's</span>
  <span m='508590'>three</span> <span m='508830'>dimensional.</span> <span m='509400'>It's</span>
  <span m='509510'>some</span> <span m='509700'>surface</span> <span m='510240'>here.</span>
  <span m='511380'>Right?</span> <span m='511540'>We</span> <span m='511650'>have</span>
  <span m='511770'>some</span> <span m='511950'>initial</span> <span m='512280'>guess</span>
  <span m='512580'>for</span> <span m='512700'>the</span> <span m='512820'>solution.</span>
  <span m='514350'>We</span> <span m='514500'>go</span> <span m='514679'>up</span>
  <span m='514799'>to</span> <span m='514919'>the</span> <span m='515010'>function,</span>
  <span m='515400'>and</span> <span m='515490'>we</span> <span m='515610'>find</span>
  <span m='516700'>a</span> <span m='516750'>linearization</span> <span m='517620'>of</span>
  <span m='517770'>it,</span> <span m='517860'>which</span> <span m='518039'>is</span>
  <span m='518100'>not</span> <span m='518280'>a</span> <span m='518340'>line</span>
  <span m='519030'>but</span> <span m='519179'>a</span> <span m='519240'>plane.</span>
  <span m='520200'>And</span> <span m='520320'>that</span> <span m='520470'>plane</span>
  <span m='520950'>intersects</span> <span m='521669'>the</span> <span m='521820'>x</span>
  <span m='522059'>1,</span> <span m='522299'>x</span> <span m='522539'>2</span> <span
  m='522720'>plane</span> <span m='523110'>at</span> <span m='523230'>a</span> <span
  m='523309'>line.</span> </p><p><span m='524900'>And</span> <span m='525000'>our</span>
  <span m='525090'>next</span> <span m='525300'>best</span> <span m='525540'>guess</span>
  <span m='525870'>is</span> <span m='525960'>going</span> <span m='526080'>to</span>
  <span m='526140'>live</span> <span m='526350'>somewhere</span> <span m='526710'>on</span>
  <span m='526860'>this</span> <span m='527070'>line.</span> <span m='528210'>Where</span>
  <span m='528480'>on</span> <span m='528630'>this</span> <span m='528810'>line</span>
  <span m='529170'>depends</span> <span m='529680'>on</span> <span m='530400'>the</span>
  <span m='530490'>linearization</span> <span m='531210'>of</span> <span m='531300'>f</span>
  <span m='531460'>2.</span> <span m='531880'>Right?</span> <span m='532410'>So</span>
  <span m='532530'>we</span> <span m='532590'>got</span> <span m='532680'>to</span>
  <span m='532770'>draw</span> <span m='532950'>the</span> <span m='533040'>same</span>
  <span m='533250'>picture</span> <span m='533550'>for</span> <span m='533850'>f</span>
  <span m='533930'>2, but</span> <span m='534030'>I'm</span> <span m='534120'>not</span>
  <span m='534210'>going</span> <span m='534360'>to</span> <span m='534420'>do</span>
  <span m='534510'>that</span> <span m='534660'>for</span> <span m='534840'>you.</span>
  <span m='535030'>So</span> <span m='535200'>let's</span> <span m='535350'>say,</span>
  <span m='535980'>this</span> <span m='536220'>is</span> <span m='536340'>where</span>
  <span m='537030'>the</span> <span m='537150'>equivalent</span> <span m='537660'>line</span>
  <span m='538080'>from</span> <span m='538290'>f</span> <span m='538470'>2</span>
  <span m='539400'>intersects</span> <span m='540330'>the</span> <span m='540420'>line</span>
  <span m='540690'>from</span> <span m='540900'>f</span> <span m='541200'>1,</span>
  <span m='541500'>right?</span> </p><p><span m='542070'>So</span> <span m='542440'>the</span>
  <span m='542850'>two</span> <span m='543060'>linearizations</span> <span m='543870'>intersect</span>
  <span m='544350'>here.</span> <span m='544650'>That's</span> <span m='544890'>our</span>
  <span m='544980'>next</span> <span m='545250'>best</span> <span m='545490'>guess.</span>
  <span m='546460'>We</span> <span m='546540'>go</span> <span m='546660'>back</span>
  <span m='546870'>up</span> <span m='546990'>to</span> <span m='547110'>the</span>
  <span m='547200'>curve.</span> <span m='547860'>We</span> <span m='547980'>find</span>
  <span m='548310'>the</span> <span m='548400'>plane</span> <span m='548880'>that's</span>
  <span m='549120'>tangent</span> <span m='549570'>to</span> <span m='549690'>the</span>
  <span m='549810'>curve.</span> <span m='550680'>We</span> <span m='550800'>figure</span>
  <span m='551070'>out</span> <span m='551160'>where</span> <span m='551370'>it</span>
  <span m='551460'>intersects.</span> <span m='552600'>The</span> <span m='552720'>x
  1</span> <span m='552960'>x</span> <span m='553050'>2</span> <span m='553450'>plane.</span>
  <span m='553840'>That's</span> <span m='554040'>a</span> <span m='554130'>line.</span>
  <span m='554610'>We</span> <span m='554730'>find</span> <span m='554940'>the</span>
  <span m='555030'>point</span> <span m='555300'>on</span> <span m='555390'>the</span>
  <span m='555500'>line</span> <span m='555970'>that's</span> <span m='556050'>our</span>
  <span m='556110'>next</span> <span m='556350'>best</span> <span m='556590'>guess,</span>
  <span m='557280'>and</span> <span m='557400'>continue.</span> </p><p><span m='558300'>Finding</span>
  <span m='558690'>that</span> <span m='558900'>intersection</span> <span m='559680'>in</span>
  <span m='559800'>the</span> <span m='559920'>plane</span> <span m='560370'>is</span>
  <span m='560520'>the</span> <span m='560670'>act</span> <span m='560960'>of</span>
  <span m='561060'>computing</span> <span m='562020'>Jacobian</span> <span m='562560'>inverse</span>
  <span m='563480'>times</span> <span m='564150'>f.</span> <span m='564944'>OK?</span>
  <span m='570380'>If</span> <span m='570500'>we</span> <span m='571100'>project</span>
  <span m='571550'>down</span> <span m='572030'>to</span> <span m='572180'>just</span>
  <span m='572420'>the</span> <span m='572690'>x 1</span> <span m='572960'>x</span>
  <span m='573230'>2</span> <span m='573770'>plane,</span> <span m='574100'>and</span>
  <span m='574190'>we</span> <span m='574280'>draw</span> <span m='574520'>the</span>
  <span m='574610'>curves</span> <span m='575360'>where</span> <span m='575600'>f</span>
  <span m='576065'>1</span> <span m='576950'>equals</span> <span m='577250'>0,</span>
  <span m='577730'>and</span> <span m='577860'>f</span> <span m='578060'>2</span>
  <span m='578330'>equals</span> <span m='578630'>zero,</span> <span m='579890'>right?</span>
  <span m='580250'>Then</span> <span m='580430'>each</span> <span m='580640'>of</span>
  <span m='580700'>these</span> <span m='580940'>iterates,</span> <span m='581300'>we</span>
  <span m='581390'>start</span> <span m='581600'>with</span> <span m='581720'>an</span>
  <span m='581810'>initial</span> <span m='582200'>guess.</span> <span m='582950'>We</span>
  <span m='583070'>find</span> <span m='583370'>the</span> <span m='583490'>planes</span>
  <span m='584900'>that</span> <span m='585020'>are</span> <span m='585110'>tangent</span>
  <span m='585650'>to</span> <span m='585770'>these</span> <span m='586010'>curves,</span>
  <span m='586550'>or</span> <span m='586640'>to</span> <span m='586790'>these</span>
  <span m='586940'>surfaces.</span> <span m='588200'>And</span> <span m='588320'>where</span>
  <span m='588500'>they</span> <span m='588690'>intersect</span> <span m='589220'>the</span>
  <span m='589370'>x</span> <span m='589680'>1</span> <span m='589945'>x 2</span>
  <span m='590210'>plane.</span> </p><p><span m='590600'>Those</span> <span m='590810'>give</span>
  <span m='590990'>us</span> <span m='591110'>these</span> <span m='591320'>lines.</span>
  <span m='591930'>And</span> <span m='592040'>the</span> <span m='592130'>intersection</span>
  <span m='592390'>of the</span> <span m='592650'>lines</span> <span m='593120'>give</span>
  <span m='593270'>us</span> <span m='593390'>our</span> <span m='593450'>next</span>
  <span m='593720'>approximation.</span> <span m='595050'>And</span> <span m='595150'>so</span>
  <span m='595160'>our</span> <span m='595250'>function</span> <span m='595760'>steps</span>
  <span m='596350'>along</span> <span m='596870'>in</span> <span m='596960'>the</span>
  <span m='597080'>x1</span> <span m='597380'>and</span> <span m='597500'>x2</span>
  <span m='597890'>plane.</span> <span m='598160'>It</span> <span m='598250'>takes</span>
  <span m='598430'>some</span> <span m='598670'>path</span> <span m='598970'>through</span>
  <span m='599180'>that</span> <span m='599360'>plane.</span> <span m='600650'>And</span>
  <span m='600740'>eventually</span> <span m='601310'>it</span> <span m='601360'>will</span>
  <span m='601520'>approach</span> <span m='601940'>this</span> <span m='602120'>locally</span>
  <span m='602470'>unique</span> <span m='602750'>solution.</span> <span m='603930'>So</span>
  <span m='603980'>that's</span> <span m='604160'>what</span> <span m='604250'>this</span>
  <span m='604430'>iterative</span> <span m='604820'>method</span> <span m='605150'>is</span>
  <span m='605270'>doing,</span> <span m='605570'>right?</span> <span m='605900'>It's
  navigating</span> <span m='606650'>this</span> <span m='606770'>multidimensional</span>
  <span m='607610'>space,</span> <span m='608600'>right?</span> <span m='608750'>It</span>
  <span m='608840'>moves</span> <span m='609440'>where</span> <span m='609590'>it</span>
  <span m='609680'>has</span> <span m='610070'>to</span> <span m='610520'>to</span>
  <span m='611420'>satisfy</span> <span m='612230'>these</span> <span m='612500'>linearized</span>
  <span m='613250'>equations,</span> <span m='614320'>right?</span> <span m='614930'>Producing</span>
  <span m='615410'>ever</span> <span m='615620'>better</span> <span m='615890'>approximations</span>
  <span m='616790'>for</span> <span m='617030'>a</span> <span m='617100'>root.</span>
  </p><p><span m='618610'>Start</span> <span m='618880'>close.</span> <span m='619600'>It'll</span>
  <span m='619780'>converge</span> <span m='620230'>fast.</span> <span m='621230'>How</span>
  <span m='621430'>fast?</span> <span m='622510'>Quadratically.</span> <span m='623920'>And</span>
  <span m='624130'>you</span> <span m='624250'>can</span> <span m='624370'>prove</span>
  <span m='624670'>this.</span> <span m='625540'>I'll</span> <span m='625630'>prove</span>
  <span m='625840'>it</span> <span m='625930'>in</span> <span m='626050'>1D.</span>
  <span m='626620'>You</span> <span m='626710'>might</span> <span m='626860'>think</span>
  <span m='627040'>about</span> <span m='627250'>the</span> <span m='627370'>multidimensional</span>
  <span m='628180'>case,</span> <span m='628800'>but</span> <span m='628900'>I'll</span>
  <span m='628990'>show</span> <span m='629170'>you</span> <span m='629260'>in</span>
  <span m='629380'>one</span> <span m='629560'>dimension.</span> <span m='630980'>So</span>
  <span m='631080'>the</span> <span m='631180'>Newton-Raphson</span> <span m='631540'>method</span>
  <span m='631810'>said,</span> <span m='632360'>xi</span> <span m='632740'>plus</span>
  <span m='633070'>1</span> <span m='633430'>is</span> <span m='633580'>equal</span>
  <span m='633910'>to</span> <span m='634250'>xi</span> <span m='635440'>minus</span>
  <span m='635920'>f</span> <span m='636070'>of</span> <span m='636190'>xi</span>
  <span m='636520'>over</span> <span m='636730'>f</span> <span m='636910'>prime</span>
  <span m='637300'>of</span> <span m='637420'>xi.</span> </p><p><span m='638460'>I'm</span>
  <span m='638530'>going</span> <span m='638650'>to</span> <span m='638710'>subtract</span>
  <span m='639970'>the</span> <span m='640150'>root,</span> <span m='640570'>the</span>
  <span m='640750'>exact</span> <span m='641290'>root</span> <span m='641560'>from</span>
  <span m='641770'>both</span> <span m='641980'>sides</span> <span m='642340'>of</span>
  <span m='642430'>this</span> <span m='642610'>equation.</span> <span m='644320'>So</span>
  <span m='644440'>this</span> <span m='644710'>is</span> <span m='644890'>the</span>
  <span m='645640'>absolute</span> <span m='646240'>error</span> <span m='646930'>in</span>
  <span m='647050'>the</span> <span m='647230'>i</span> <span m='647470'>plus</span>
  <span m='647830'>1</span> <span m='648070'>approximation.</span> <span m='649900'>It's</span>
  <span m='650050'>equal</span> <span m='650320'>to</span> <span m='650440'>this.</span>
  <span m='652300'>And</span> <span m='652390'>we're</span> <span m='652450'>going</span>
  <span m='652570'>to</span> <span m='652630'>do</span> <span m='652780'>a</span>
  <span m='652810'>little</span> <span m='653050'>trick,</span> <span m='653620'>OK?</span>
  </p><p><span m='654940'>The</span> <span m='655030'>value</span> <span m='655330'>of</span>
  <span m='655420'>the</span> <span m='655540'>function</span> <span m='655940'>at</span>
  <span m='655980'>the</span> <span m='656070'>root</span> <span m='656370'>is</span>
  <span m='656560'>exactly</span> <span m='657130'>equal</span> <span m='657400'>to</span>
  <span m='657520'>zero,</span> <span m='659280'>and</span> <span m='659370'>I'm</span>
  <span m='659460'>going</span> <span m='659580'>to</span> <span m='659640'>expand</span>
  <span m='660300'>this</span> <span m='661410'>as</span> <span m='661560'>a</span>
  <span m='661650'>Taylor</span> <span m='662010'>series,</span> <span m='663090'>about</span>
  <span m='663420'>the</span> <span m='663540'>point</span> <span m='664280'>xy.</span>
  <span m='665820'>So</span> <span m='666000'>f</span> <span m='666180'>of</span>
  <span m='666330'>xi</span> <span m='667320'>plus</span> <span m='667760'>f</span>
  <span m='668010'>prime</span> <span m='668310'>of</span> <span m='668450'>xi</span>
  <span m='669690'>times</span> <span m='669960'>x</span> <span m='670150'>star</span>
  <span m='670410'>minus</span> <span m='670740'>xi,</span> <span m='671040'>plus</span>
  <span m='671400'>this</span> <span m='671560'>second</span> <span m='671970'>order</span>
  <span m='672210'>term</span> <span m='672540'>as</span> <span m='672660'>well.</span>
  <span m='672990'>Plus</span> <span m='673740'>cubic</span> <span m='674160'>terms</span>
  <span m='674880'>in</span> <span m='675030'>this</span> <span m='675210'>Taylor</span>
  <span m='675510'>expansion,</span> <span m='676110'>right?</span> <span m='676310'>All</span>
  <span m='676560'>of</span> <span m='676650'>those</span> <span m='676920'>need</span>
  <span m='677100'>to</span> <span m='677190'>sum</span> <span m='677400'>up</span>
  <span m='677550'>and</span> <span m='677640'>be</span> <span m='677700'>equal</span>
  <span m='677940'>to</span> <span m='678060'>0,</span> <span m='678480'>Because</span>
  <span m='678870'>f</span> <span m='679050'>of</span> <span m='679170'>x</span> <span
  m='679320'>star</span> <span m='679890'>by</span> <span m='680010'>definition</span>
  <span m='680730'>is</span> <span m='680820'>zero.</span> <span m='681250'>x</span>
  <span m='681720'>star is the</span> <span m='681830'>root.</span> </p><p><span m='684000'>And</span>
  <span m='684150'>buried</span> <span m='684600'>in</span> <span m='684720'>this</span>
  <span m='684930'>expression</span> <span m='685620'>here</span> <span m='688860'>is</span>
  <span m='688980'>a</span> <span m='689040'>quantity</span> <span m='690060'>which</span>
  <span m='690240'>can</span> <span m='690390'>be</span> <span m='690540'>related</span>
  <span m='691020'>to</span> <span m='691350'>xi</span> <span m='692070'>minus</span>
  <span m='692430'>f of xi</span> <span m='693210'>over</span> <span m='693480'>f</span>
  <span m='693660'>prime</span> <span m='694050'>minus</span> <span m='694380'>x</span>
  <span m='694660'>star.</span> <span m='694950'>It's</span> <span m='695100'>right</span>
  <span m='695280'>here,</span> <span m='695470'>right?</span> <span m='695970'>xi</span>
  <span m='696360'>minus</span> <span m='696690'>x</span> <span m='696840'>star,</span>
  <span m='697770'>xi</span> <span m='698400'>minus</span> <span m='698730'>x</span>
  <span m='698910'>star.</span> <span m='699250'>I've</span> <span m='699610'>got</span>
  <span m='699990'>to</span> <span m='700050'>divide</span> <span m='700470'>through</span>
  <span m='700830'>by</span> <span m='701070'>f</span> <span m='701250'>prime.</span>
  <span m='701820'>Divide</span> <span m='702220'>through</span> <span m='702600'>by</span>
  <span m='702770'>f</span> <span m='702840'>prime,</span> <span m='703170'>and</span>
  <span m='703260'>I</span> <span m='703320'>get</span> <span m='703560'>f</span>
  <span m='703800'>over</span> <span m='704040'>f</span> <span m='704190'>prime.</span>
  <span m='704550'>That's</span> <span m='704790'>this</span> <span m='704910'>guy</span>
  <span m='705240'>here.</span> </p><p><span m='706320'>Those</span> <span m='706590'>things</span>
  <span m='707130'>are</span> <span m='707310'>equal</span> <span m='707730'>in</span>
  <span m='707850'>magnitude</span> <span m='708660'>then,</span> <span m='709890'>to</span>
  <span m='710010'>this</span> <span m='710190'>second</span> <span m='710580'>order</span>
  <span m='710820'>term</span> <span m='711120'>here.</span> <span m='711380'>So</span>
  <span m='711520'>they</span> <span m='711620'>are</span> <span m='711660'>equal</span>
  <span m='711930'>in</span> <span m='712020'>magnitude</span> <span m='712590'>to</span>
  <span m='712740'>1/2,</span> <span m='714240'>the</span> <span m='714330'>second</span>
  <span m='714720'>derivative</span> <span m='715260'>of</span> <span m='715410'>f,</span>
  <span m='715920'>divided</span> <span m='716280'>by</span> <span m='716460'>f</span>
  <span m='716610'>prime,</span> <span m='717510'>times</span> <span m='717780'>xi</span>
  <span m='718380'>minus</span> <span m='718500'>x</span> <span m='718690'>star</span>
  <span m='719010'>squared.</span> </p><p><span m='720000'>And</span> <span m='720120'>then</span>
  <span m='720270'>these</span> <span m='720480'>cubic</span> <span m='720780'>terms,</span>
  <span m='721200'>well,</span> <span m='721290'>they're</span> <span m='721440'>still</span>
  <span m='721710'>around.</span> <span m='722230'>But</span> <span m='722370'>they're</span>
  <span m='722490'>going</span> <span m='722610'>to</span> <span m='722670'>be</span>
  <span m='722760'>small</span> <span m='723330'>as</span> <span m='723480'>I</span>
  <span m='723540'>get</span> <span m='723720'>close</span> <span m='724260'>to</span>
  <span m='724620'>the</span> <span m='724770'>actual</span> <span m='725160'>root.</span>
  <span m='725610'>So</span> <span m='725760'>they're</span> <span m='725880'>negligible,</span>
  <span m='726750'>right?</span> <span m='727440'>Compared</span> <span m='727740'>to</span>
  <span m='727830'>these</span> <span m='727950'>second</span> <span m='728250'>order</span>
  <span m='728430'>terms,</span> <span m='728730'>they</span> <span m='728820'>can</span>
  <span m='728970'>be</span> <span m='729060'>neglected.</span> <span m='731115'>And</span>
  <span m='731610'>you</span> <span m='731700'>should</span> <span m='731850'>convince</span>
  <span m='732210'>yourself</span> <span m='732660'>that</span> <span m='732810'>I</span>
  <span m='732870'>can</span> <span m='733020'>apply</span> <span m='733410'>some</span>
  <span m='733650'>of</span> <span m='733740'>the</span> <span m='733860'>norm</span>
  <span m='734340'>properties</span> <span m='735000'>that</span> <span m='735120'>we</span>
  <span m='735240'>used</span> <span m='735510'>before,</span> <span m='736260'>OK?</span>
  <span m='736740'>To</span> <span m='736860'>the</span> <span m='736980'>absolute</span>
  <span m='737370'>value.</span> <span m='737730'>The</span> <span m='737910'>absolute</span>
  <span m='738220'>values</span> <span m='738505'>is</span> <span m='738790'>the</span>
  <span m='738810'>norm</span> <span m='739230'>of</span> <span m='739320'>a</span>
  <span m='739350'>scalar.</span> </p><p><span m='740940'>So</span> <span m='741240'>these</span>
  <span m='741390'>norm</span> <span m='741690'>properties</span> <span m='742200'>tell</span>
  <span m='742410'>me</span> <span m='742620'>that</span> <span m='742830'>this</span>
  <span m='743040'>quantity</span> <span m='743550'>has</span> <span m='743760'>to</span>
  <span m='743880'>be</span> <span m='744000'>less</span> <span m='744300'>than</span>
  <span m='744480'>or</span> <span m='744570'>equal</span> <span m='744930'>to,</span>
  <span m='746100'>right?</span> <span m='746940'>This</span> <span m='747150'>ratio</span>
  <span m='747690'>of</span> <span m='747780'>derivatives</span> <span m='749490'>multiplied</span>
  <span m='750150'>by</span> <span m='751410'>the</span> <span m='751800'>absolute</span>
  <span m='752280'>error</span> <span m='752670'>in</span> <span m='752820'>step</span>
  <span m='753090'>i</span> <span m='753390'>squared.</span> <span m='753990'>And</span>
  <span m='754140'>I'll</span> <span m='754230'>divide</span> <span m='754690'>by</span>
  <span m='754860'>that</span> <span m='755040'>absolute</span> <span m='755460'>error</span>
  <span m='755600'>in</span> <span m='755670'>step</span> <span m='755940'>i</span>
  <span m='756120'>squared.</span> </p><p><span m='757590'>So</span> <span m='757770'>taking</span>
  <span m='758040'>the</span> <span m='758130'>limit</span> <span m='758400'>is</span>
  <span m='758520'>i</span> <span m='758670'>goes</span> <span m='758910'>to</span>
  <span m='759030'>infinity,</span> <span m='760440'>this</span> <span m='760680'>ratio</span>
  <span m='761370'>here</span> <span m='762240'>is</span> <span m='762390'>bound</span>
  <span m='762870'>by</span> <span m='763080'>a</span> <span m='763140'>constant.</span>
  <span m='765520'>This</span> <span m='765600'>is</span> <span m='766050'>a</span>
  <span m='766140'>definition</span> <span m='766950'>for</span> <span m='767340'>the</span>
  <span m='767490'>rate</span> <span m='767700'>of</span> <span m='767790'>convergence.</span>
  <span m='768450'>It</span> <span m='768540'>says</span> <span m='768750'>I</span>
  <span m='768810'>take</span> <span m='768990'>the</span> <span m='769110'>absolute</span>
  <span m='769780'>error</span> <span m='770300'>in</span> <span m='770430'>step</span>
  <span m='770750'>i</span> <span m='770910'>plus</span> <span m='771210'>1.</span>
  <span m='771930'>I</span> <span m='772020'>divide</span> <span m='772440'>it</span>
  <span m='772530'>by</span> <span m='772860'>the</span> <span m='773040'>absolute</span>
  <span m='773580'>error</span> <span m='773730'>in</span> <span m='773820'>step</span>
  <span m='774100'>i</span> <span m='774390'>squared.</span> <span m='775350'>And</span>
  <span m='775470'>it will</span> <span m='775650'>always</span> <span m='775920'>be</span>
  <span m='776040'>smaller</span> <span m='776550'>than</span> <span m='776700'>some</span>
  <span m='776940'>constant,</span> <span m='777540'>as</span> <span m='777720'>i</span>
  <span m='777900'>goes</span> <span m='778170'>to</span> <span m='778320'>infinity.</span>
  </p><p><span m='780100'>So it</span> <span m='780210'>converges</span> <span m='780720'>quadratically,</span>
  <span m='781640'>right?</span> <span m='782370'>If</span> <span m='784320'>the</span>
  <span m='784470'>relative</span> <span m='785100'>error</span> <span m='785820'>in</span>
  <span m='785940'>step</span> <span m='786300'>i</span> <span m='787680'>was</span>
  <span m='787920'>order</span> <span m='788750'>10</span> <span m='788940'>to</span>
  <span m='789060'>the</span> <span m='789150'>minus</span> <span m='789480'>1, then</span>
  <span m='790230'>the</span> <span m='790290'>relative</span> <span m='790710'>error</span>
  <span m='790820'>in</span> <span m='790910'>step i</span> <span m='791340'>plus</span>
  <span m='791640'>1</span> <span m='791880'>will</span> <span m='791970'>be</span>
  <span m='792120'>order</span> <span m='792690'>10</span> <span m='792880'>to</span>
  <span m='792950'>the</span> <span m='793020'>minus</span> <span m='793450'>2.</span>
  <span m='794490'>Because</span> <span m='794700'>they</span> <span m='794760'>got</span>
  <span m='794880'>to</span> <span m='794940'>be</span> <span m='795030'>bound</span>
  <span m='795240'>by</span> <span m='795390'>this</span> <span m='795540'>constant.</span>
  </p><p><span m='796410'>If</span> <span m='796500'>the</span> <span m='796590'>relative</span>
  <span m='797040'>error</span> <span m='797310'>in step</span> <span m='797610'>i</span>
  <span m='797940'>was</span> <span m='798270'>10</span> <span m='798450'>to</span>
  <span m='798510'>the</span> <span m='798600'>minus</span> <span m='798900'>2,</span>
  <span m='799240'>the</span> <span m='799350'>relative</span> <span m='799740'>error</span>
  <span m='799830'>in</span> <span m='799930'>step</span> <span m='800200'>i</span>
  <span m='800400'>plus</span> <span m='800730'>1,</span> <span m='801590'>has</span>
  <span m='801720'>got</span> <span m='801840'>to</span> <span m='801930'>be</span>
  <span m='802020'>order</span> <span m='802650'>10</span> <span m='802800'>to</span>
  <span m='802860'>the</span> <span m='802950'>minus</span> <span m='803280'>4,</span>
  <span m='804000'>or</span> <span m='804150'>smaller,</span> <span m='804870'>right?</span>
  <span m='805170'>Because</span> <span m='805350'>I</span> <span m='805440'>square</span>
  <span m='805980'>the</span> <span m='806070'>quantity</span> <span m='806520'>down</span>
  <span m='806760'>here.</span> <span m='807810'>I</span> <span m='807870'>get</span>
  <span m='808020'>to</span> <span m='808200'>double</span> <span m='808740'>the</span>
  <span m='808860'>number</span> <span m='809220'>of</span> <span m='809340'>accurate</span>
  <span m='809880'>digits</span> <span m='810450'>with</span> <span m='810660'>each</span>
  <span m='810870'>iteration.</span> </p><p><span m='814050'>And</span> <span m='814140'>this</span>
  <span m='814290'>will</span> <span m='814390'>hold</span> <span m='814710'>so</span>
  <span m='814890'>long</span> <span m='815220'>as</span> <span m='815340'>the</span>
  <span m='815460'>derivative</span> <span m='817020'>evaluated</span> <span m='817950'>at</span>
  <span m='818160'>the</span> <span m='818280'>root</span> <span m='818550'>is</span>
  <span m='818640'>not</span> <span m='818820'>equal</span> <span m='819030'>to</span>
  <span m='819180'>zero.</span> <span m='819660'>If the</span> <span m='819750'>derivative</span>
  <span m='820170'>evaluated</span> <span m='820500'>at</span> <span m='820830'>the
  root</span> <span m='821100'>is</span> <span m='821190'>equal</span> <span m='821400'>to</span>
  <span m='821490'>zero,</span> <span m='822270'>this</span> <span m='822480'>analysis</span>
  <span m='823020'>wasn't</span> <span m='823260'>really</span> <span m='823590'>valid.</span>
  <span m='823970'>You</span> <span m='824030'>can't</span> <span m='824460'>divide</span>
  <span m='824880'>by</span> <span m='825750'>zero</span> <span m='826170'>in</span>
  <span m='826290'>various</span> <span m='826620'>places,</span> <span m='827220'>OK?</span>
  <span m='829260'>It</span> <span m='829350'>turns</span> <span m='829560'>out</span>
  <span m='829650'>the</span> <span m='829740'>same</span> <span m='829920'>thing</span>
  <span m='830070'>is</span> <span m='830190'>true</span> <span m='831330'>if</span>
  <span m='831510'>we</span> <span m='831630'>do</span> <span m='831840'>the</span>
  <span m='831960'>multidimensional</span> <span m='832710'>case.</span> </p><p><span
  m='832890'>I'll</span> <span m='833040'>leave</span> <span m='833190'>it</span>
  <span m='833250'>to</span> <span m='833370'>you</span> <span m='833550'>to</span>
  <span m='833730'>investigate</span> <span m='834300'>that</span> <span m='834480'>case.</span>
  <span m='834960'>I</span> <span m='834990'>think</span> <span m='835140'>it's</span>
  <span m='835260'>interesting</span> <span m='835770'>for</span> <span m='835890'>you</span>
  <span m='835950'>to</span> <span m='836040'>try</span> <span m='836200'>and</span>
  <span m='836280'>explore</span> <span m='836820'>that.</span> <span m='837060'>It</span>
  <span m='837150'>follows</span> <span m='837630'>the</span> <span m='837750'>1D</span>
  <span m='837960'>model</span> <span m='838380'>I showed</span> <span m='838800'>you</span>
  <span m='838920'>before.</span> <span m='839940'>But</span> <span m='840060'>the</span>
  <span m='840180'>absolute</span> <span m='840600'>error</span> <span m='841230'>in</span>
  <span m='841350'>iterate</span> <span m='841670'>i</span> <span m='841850'>plus</span>
  <span m='842140'>1,</span> <span m='842930'>divided</span> <span m='843270'>by</span>
  <span m='843360'>the</span> <span m='843480'>absolute</span> <span m='843840'>error</span>
  <span m='843960'>in</span> <span m='844060'>iterate</span> <span m='844440'>i--</span>
  <span m='845070'>here's</span> <span m='845250'>a</span> <span m='845310'>small</span>
  <span m='845550'>typo</span> <span m='845940'>here.</span> <span m='846150'>Cross
  out</span> <span m='846510'>that</span> <span m='846660'>plus</span> <span m='846930'>1,</span>
  <span m='847340'>right?</span> <span m='847590'>The</span> <span m='847710'>absolute</span>
  <span m='848080'>error</span> <span m='848210'>in</span> <span m='848330'>iterate</span>
  <span m='848620'>i</span> <span m='849150'>squared</span> <span m='851070'>is</span>
  <span m='851190'>going</span> <span m='851310'>to</span> <span m='851400'>be</span>
  <span m='851520'>bound</span> <span m='851850'>by</span> <span m='852060'>a</span>
  <span m='852090'>constant.</span> </p><p><span m='854980'>And</span> <span m='855070'>this</span>
  <span m='855190'>will</span> <span m='855280'>be</span> <span m='855400'>true</span>
  <span m='856460'>so</span> <span m='856570'>long</span> <span m='856930'>as</span>
  <span m='857200'>the</span> <span m='857320'>determinant</span> <span m='857670'>at</span>
  <span m='857770'>the</span> <span m='857860'>Jacobian</span> <span m='858520'>at</span>
  <span m='858610'>the</span> <span m='858700'>root</span> <span m='859270'>is</span>
  <span m='859420'>not</span> <span m='859600'>equal</span> <span m='859840'>to</span>
  <span m='859960'>zero.</span> <span m='860770'>We</span> <span m='860860'>know</span>
  <span m='861010'>the</span> <span m='861130'>determinant</span> <span m='861550'>of
  the</span> <span m='861640'>Jacobian</span> <span m='862140'>plays</span> <span
  m='862420'>the</span> <span m='862510'>role</span> <span m='862750'>of</span> <span
  m='862840'>the</span> <span m='862960'>derivative</span> <span m='863800'>in</span>
  <span m='863890'>the</span> <span m='863980'>1D</span> <span m='864180'>case.</span>
  <span m='866260'>When</span> <span m='866380'>the Jacobian</span> <span m='866820'>is</span>
  <span m='866920'>singular,</span> <span m='867480'>you</span> <span m='867610'>can</span>
  <span m='867760'>show</span> <span m='867970'>that</span> <span m='868150'>linear</span>
  <span m='868570'>convergence</span> <span m='869230'>is</span> <span m='869320'>going</span>
  <span m='869500'>to</span> <span m='869590'>occur</span> <span m='869950'>instead.</span>
  <span m='871150'>So</span> <span m='871270'>it will</span> <span m='871390'>still</span>
  <span m='871630'>converge.</span> <span m='872540'>It's</span> <span m='872590'>not</span>
  <span m='872700'>necessarily</span> <span m='873340'>a</span> <span m='873400'>problem</span>
  <span m='873655'>that</span> <span m='873910'>the</span> <span m='874000'>Jacobian</span>
  <span m='874570'>becomes</span> <span m='874820'>singular</span> <span m='875290'>at</span>
  <span m='875410'>the</span> <span m='875500'>root.</span> <span m='876190'>But</span>
  <span m='876280'>you're</span> <span m='876400'>going</span> <span m='876520'>to</span>
  <span m='876580'>lose</span> <span m='877240'>your</span> <span m='877420'>rate</span>
  <span m='877660'>of</span> <span m='877750'>quadratic</span> <span m='878320'>convergence.</span>
  </p><p><span m='882590'>And</span> <span m='882710'>this</span> <span m='882890'>rate</span>
  <span m='883040'>of</span> <span m='883100'>convergence</span> <span m='883580'>is</span>
  <span m='883670'>only</span> <span m='883880'>guaranteed</span> <span m='884300'>if</span>
  <span m='884420'>we</span> <span m='884510'>start</span> <span m='884870'>sufficiently</span>
  <span m='885470'>close</span> <span m='885830'>to</span> <span m='885950'>the</span>
  <span m='886070'>root.</span> <span m='886390'>So</span> <span m='886640'>good</span>
  <span m='887150'>initial</span> <span m='887420'>guesses,</span> <span m='888830'>that's</span>
  <span m='888980'>important.</span> <span m='889610'>We</span> <span m='889700'>have</span>
  <span m='889820'>a</span> <span m='889850'>locally</span> <span m='890330'>convergent</span>
  <span m='890870'>method.</span> <span m='891230'>Bad</span> <span m='891590'>initial</span>
  <span m='892020'>guesses?</span> <span m='892490'>Well,</span> <span m='892610'>who</span>
  <span m='892760'>knows</span> <span m='894140'>where</span> <span m='894590'>this</span>
  <span m='894800'>iterative</span> <span m='895160'>method</span> <span m='895490'>is</span>
  <span m='895610'>going</span> <span m='895760'>to</span> <span m='895820'>go.</span>
  <span m='896000'>There's</span> <span m='896180'>nothing</span> <span m='896480'>to</span>
  <span m='896540'>guarantee</span> <span m='897170'>that</span> <span m='897320'>it's</span>
  <span m='897470'>going</span> <span m='897620'>to</span> <span m='897680'>converge</span>
  <span m='898160'>even.</span> <span m='898430'>Right</span> <span m='898600'>It</span>
  <span m='898670'>may</span> <span m='898900'>run away</span> <span m='899500'>someplace.</span>
  </p><p><span m='900500'>Here</span> <span m='900620'>are</span> <span m='900650'>a</span>
  <span m='900680'>few</span> <span m='900860'>examples</span> <span m='901490'>of</span>
  <span m='901610'>where</span> <span m='901790'>things</span> <span m='902090'>can</span>
  <span m='902240'>go</span> <span m='902390'>wrong.</span> <span m='903540'>So</span>
  <span m='903560'>if</span> <span m='903650'>I</span> <span m='903680'>have</span>
  <span m='903830'>a</span> <span m='903890'>local</span> <span m='904220'>minima</span>
  <span m='905150'>or</span> <span m='905300'>maxima,</span> <span m='907010'>I</span>
  <span m='907130'>might</span> <span m='907280'>have</span> <span m='907430'>an</span>
  <span m='907550'>iterate</span> <span m='908690'>where</span> <span m='908870'>I</span>
  <span m='908960'>evaluate</span> <span m='909620'>the</span> <span m='909830'>linearization,</span>
  <span m='910940'>and</span> <span m='911060'>it</span> <span m='911150'>tells</span>
  <span m='911360'>me</span> <span m='911480'>my</span> <span m='911630'>next</span>
  <span m='911870'>best</span> <span m='912080'>approximation</span> <span m='912770'>is</span>
  <span m='912890'>on</span> <span m='913010'>the</span> <span m='913250'>other</span>
  <span m='913520'>side</span> <span m='913850'>of</span> <span m='913970'>this</span>
  <span m='914150'>minima</span> <span m='914600'>or</span> <span m='914720'>maxima.</span>
  </p><p><span m='916140'>And</span> <span m='916260'>then</span> <span m='916380'>I</span>
  <span m='916440'>go</span> <span m='916650'>up,</span> <span m='916860'>and</span>
  <span m='917010'>I</span> <span m='917190'>get</span> <span m='917460'>the</span>
  <span m='917550'>linearization</span> <span m='918270'>here.</span> <span m='918630'>And</span>
  <span m='918750'>it</span> <span m='918810'>tells</span> <span m='919050'>me,</span>
  <span m='919390'>oh,</span> <span m='919470'>my</span> <span m='919620'>next</span>
  <span m='919830'>best</span> <span m='920010'>approximation</span> <span m='920670'>is</span>
  <span m='920790'>on</span> <span m='920910'>the</span> <span m='921000'>other</span>
  <span m='921150'>side.</span> <span m='921390'>And</span> <span m='921480'>this</span>
  <span m='921600'>method</span> <span m='921960'>could</span> <span m='922890'>bounce</span>
  <span m='923220'>back</span> <span m='923460'>and</span> <span m='923610'>forth</span>
  <span m='924000'>in</span> <span m='924180'>here</span> <span m='924510'>for</span>
  <span m='925800'>as</span> <span m='925860'>long</span> <span m='926070'>as</span>
  <span m='926160'>we</span> <span m='926370'>sit and</span> <span m='926670'>wait.</span>
  <span m='928020'>It's locally</span> <span m='928390'>convergent,</span> <span m='928740'>not</span>
  <span m='929070'>globally</span> <span m='929520'>convergent.</span> <span m='929880'>It</span>
  <span m='930030'>can</span> <span m='930180'>get</span> <span m='930330'>hung</span>
  <span m='930540'>up</span> <span m='930930'>in</span> <span m='931050'>situations</span>
  <span m='931710'>like</span> <span m='931920'>this.</span> </p><p><span m='933330'>Asymptotes</span>
  <span m='933930'>are</span> <span m='934020'>a</span> <span m='934080'>problem.</span>
  <span m='935250'>I</span> <span m='935290'>have</span> <span m='935430'>an</span>
  <span m='935520'>asymptote,</span> <span m='936960'>which</span> <span m='937230'>presumably</span>
  <span m='937980'>has</span> <span m='938280'>an</span> <span m='938370'>effective</span>
  <span m='938880'>root</span> <span m='939120'>somewhere</span> <span m='939480'>out</span>
  <span m='939600'>here</span> <span m='939810'>at</span> <span m='939900'>infinity.</span>
  <span m='940800'>Well,</span> <span m='940890'>my</span> <span m='941010'>solution</span>
  <span m='941520'>would</span> <span m='941640'>like</span> <span m='941790'>to</span>
  <span m='941940'>follow</span> <span m='942540'>the</span> <span m='942690'>linearization,</span>
  <span m='943740'>the</span> <span m='943860'>successive</span> <span m='944430'>linearizations</span>
  <span m='945210'>all</span> <span m='945450'>the</span> <span m='945540'>way</span>
  <span m='945690'>out</span> <span m='945840'>along</span> <span m='946140'>this</span>
  <span m='946290'>asymptote,</span> <span m='947230'>right?</span> <span m='947580'>So</span>
  <span m='947730'>my</span> <span m='947890'>iterates</span> <span m='948300'>may</span>
  <span m='949110'>blow</span> <span m='949400'>up</span> <span m='949800'>in</span>
  <span m='949920'>an</span> <span m='950010'>uncontrolled</span> <span m='950550'>fashion.</span>
  </p><p><span m='952470'>You</span> <span m='952930'>can</span> <span m='953050'>also</span>
  <span m='953310'>end</span> <span m='953410'>up</span> <span m='953500'>with</span>
  <span m='953620'>funny</span> <span m='953860'>cases</span> <span m='954400'>where</span>
  <span m='956030'>our</span> <span m='956170'>Newton-Raphson</span> <span m='956890'>steps</span>
  <span m='957760'>continually</span> <span m='958590'>overshoot</span> <span m='959620'>the</span>
  <span m='959770'>roots.</span> <span m='960090'>So</span> <span m='960220'>they</span>
  <span m='960310'>can</span> <span m='960400'>be</span> <span m='960520'>functions</span>
  <span m='963130'>who</span> <span m='963430'>have</span> <span m='963670'>a</span>
  <span m='963790'>power</span> <span m='964180'>loss</span> <span m='964440'>scaling</span>
  <span m='965490'>right</span> <span m='965830'>near</span> <span m='966100'>the</span>
  <span m='966280'>root,</span> <span m='967390'>such</span> <span m='967750'>that</span>
  <span m='967960'>the</span> <span m='968110'>derivative</span> <span m='970390'>doesn't</span>
  <span m='970720'>exist.</span> <span m='971640'>OK?</span> </p><p><span m='972820'>So</span>
  <span m='973000'>here</span> <span m='973360'>the</span> <span m='973480'>derivative</span>
  <span m='973930'>of</span> <span m='974050'>this</span> <span m='974290'>thing,</span>
  <span m='974560'>if</span> <span m='974710'>s</span> <span m='975010'>is</span>
  <span m='975100'>smaller</span> <span m='975460'>than</span> <span m='975900'>1,</span>
  <span m='977080'>and</span> <span m='977230'>x</span> <span m='977440'>equals</span>
  <span m='977710'>zero,</span> <span m='978640'>it</span> <span m='978760'>won't</span>
  <span m='979000'>exist,</span> <span m='979480'>right?</span> <span m='979720'>There</span>
  <span m='979870'>isn't</span> <span m='980100'>a</span> <span m='980200'>derivative</span>
  <span m='980650'>that's</span> <span m='980890'>defined</span> <span m='981340'>there.</span>
  <span m='982580'>And</span> <span m='982720'>in</span> <span m='982930'>those</span>
  <span m='983140'>cases,</span> <span m='983660'>you</span> <span m='983760'>can</span>
  <span m='983860'>often</span> <span m='984000'>wind</span> <span m='984220'>up</span>
  <span m='984310'>with</span> <span m='984490'>overshoot.</span> <span m='985090'>So</span>
  <span m='985390'>I'll</span> <span m='985630'>take</span> <span m='985900'>a</span>
  <span m='986200'>linearization,</span> <span m='987010'>and</span> <span m='987160'>I'll</span>
  <span m='987360'>shoot</span> <span m='987700'>over</span> <span m='988150'>the</span>
  <span m='988320'>root.</span> <span m='989320'>And</span> <span m='989500'>I'll</span>
  <span m='989590'>go</span> <span m='989770'>up</span> <span m='989890'>and</span>
  <span m='989990'>I'll</span> <span m='990070'>take</span> <span m='990250'>my</span>
  <span m='990400'>next</span> <span m='990670'>linearization,</span> <span m='991450'>I'll</span>
  <span m='991540'>shoot</span> <span m='991740'>back</span> <span m='992050'>on</span>
  <span m='992140'>the</span> <span m='992260'>other</span> <span m='992410'>side</span>
  <span m='992680'>of</span> <span m='992770'>the</span> <span m='992860'>root.</span>
  </p><p><span m='993330'>And</span> <span m='993430'>depending</span> <span m='993730'>on</span>
  <span m='993820'>the</span> <span m='993880'>power</span> <span m='994270'>of</span>
  <span m='994420'>s</span> <span m='994810'>associated</span> <span m='995290'>with</span>
  <span m='995380'>this</span> <span m='995530'>function,</span> <span m='996530'>it</span>
  <span m='996580'>may</span> <span m='997070'>diverge,</span> <span m='997990'>right?</span>
  <span m='998440'>I</span> <span m='998500'>may</span> <span m='998650'>get</span>
  <span m='998860'>further</span> <span m='999340'>and</span> <span m='999490'>further</span>
  <span m='1000120'>away</span> <span m='1000360'>from</span> <span m='1000570'>the</span>
  <span m='1000660'>root,</span> <span m='1000830'>or it</span> <span m='1000960'>may</span>
  <span m='1001230'>slowly</span> <span m='1001980'>converge</span> <span m='1002760'>towards</span>
  <span m='1003120'>that</span> <span m='1003300'>root.</span> <span m='1004140'>But</span>
  <span m='1004230'>it</span> <span m='1004290'>can</span> <span m='1004380'>be</span>
  <span m='1004470'>problematic.</span> </p><p></p><p><span m='1008205'>Here's</span>
  <span m='1008310'>another</span> <span m='1008550'>problem</span> <span m='1008820'>that</span>
  <span m='1008940'>crops</span> <span m='1009270'>up.</span> <span m='1011910'>Sometimes</span>
  <span m='1012330'>people</span> <span m='1012600'>talk</span> <span m='1012810'>about</span>
  <span m='1013020'>basins</span> <span m='1013560'>of</span> <span m='1013650'>attraction.</span>
  <span m='1014620'>So</span> <span m='1014670'>here's</span> <span m='1015000'>a</span>
  <span m='1015720'>two-dimensional,</span> <span m='1017070'>non-linear</span> <span
  m='1017730'>equation</span> <span m='1018180'>I</span> <span m='1018240'>want</span>
  <span m='1018360'>to</span> <span m='1018420'>find</span> <span m='1018630'>the</span>
  <span m='1018720'>roots</span> <span m='1019080'>for.</span> <span m='1019850'>It's</span>
  <span m='1020040'>cubic</span> <span m='1020550'>in</span> <span m='1020700'>nature,</span>
  <span m='1021090'>so</span> <span m='1021210'>it's</span> <span m='1021300'>got</span>
  <span m='1021420'>three</span> <span m='1021660'>roots,</span> <span m='1022210'>which</span>
  <span m='1022290'>are</span> <span m='1022350'>indicated</span> <span m='1022740'>by</span>
  <span m='1022890'>the</span> <span m='1023040'>stars</span> <span m='1023640'>in</span>
  <span m='1023730'>the</span> <span m='1023870'>x1</span> <span m='1024130'>x</span>
  <span m='1024230'>2</span> <span m='1024730'>plane.</span> <span m='1026839'>And</span>
  <span m='1027069'>I've</span> <span m='1027550'>taken</span> <span m='1027849'>a</span>
  <span m='1027910'>number</span> <span m='1028240'>of</span> <span m='1028329'>different</span>
  <span m='1028660'>initial</span> <span m='1029099'>guesses</span> <span m='1029589'>from</span>
  <span m='1029829'>all</span> <span m='1030069'>over</span> <span m='1030280'>the</span>
  <span m='1030520'>plane</span> <span m='1031300'>and</span> <span m='1031690'>I've</span>
  <span m='1032109'>asked--</span> <span m='1033160'>given</span> <span m='1033460'>that</span>
  <span m='1033609'>initial</span> <span m='1033970'>guess,</span> <span m='1034420'>using</span>
  <span m='1034869'>the</span> <span m='1034960'>Newton-Raphson</span> <span m='1035619'>method,</span>
  <span m='1035980'>which</span> <span m='1036550'>root</span> <span m='1037900'>do</span>
  <span m='1038020'>I</span> <span m='1038140'>find?</span> </p><p><span m='1040000'>So</span>
  <span m='1040359'>if</span> <span m='1040540'>you</span> <span m='1040599'>see</span>
  <span m='1040750'>a</span> <span m='1040810'>dark</span> <span m='1041050'>blue</span>
  <span m='1041230'>color</span> <span m='1041530'>like</span> <span m='1041740'>this,</span>
  <span m='1042190'>that</span> <span m='1042339'>means</span> <span m='1042670'>initial</span>
  <span m='1043000'>guesses</span> <span m='1043470'>there</span> <span m='1043750'>found</span>
  <span m='1044790'>this</span> <span m='1045000'>root.</span> <span m='1045230'>If</span>
  <span m='1045480'>you</span> <span m='1045550'>see</span> <span m='1045700'>a</span>
  <span m='1045760'>medium</span> <span m='1046089'>blue</span> <span m='1046270'>color,</span>
  <span m='1046569'>that</span> <span m='1046690'>means</span> <span m='1046869'>they</span>
  <span m='1046960'>found</span> <span m='1047170'>this</span> <span m='1047410'>root.</span>
  <span m='1048099'>See</span> <span m='1048280'>a</span> <span m='1048339'>light</span>
  <span m='1048580'>blue</span> <span m='1048820'>color,</span> <span m='1049060'>that</span>
  <span m='1049150'>means</span> <span m='1049360'>they</span> <span m='1049480'>found</span>
  <span m='1049780'>this</span> <span m='1050080'>root.</span> <span m='1051110'>And</span>
  <span m='1053140'>this</span> <span m='1053320'>is</span> <span m='1053710'>a</span>
  <span m='1053840'>relatively</span> <span m='1054460'>simple</span> <span m='1054790'>function,</span>
  <span m='1055300'>relatively</span> <span m='1055900'>low</span> <span m='1056140'>dimension,</span>
  <span m='1056920'>but</span> <span m='1057310'>the</span> <span m='1057430'>plane</span>
  <span m='1057970'>here</span> <span m='1058420'>is</span> <span m='1058720'>tilled</span>
  <span m='1059200'>by--</span> <span m='1060010'>it's not</span> <span m='1060610'>tiled.
  It's filled</span> <span m='1060970'>with</span> <span m='1061130'>a</span> <span
  m='1061210'>fractal.</span> <span m='1061960'>These</span> <span m='1062110'>basins</span>
  <span m='1062560'>of</span> <span m='1062650'>attraction</span> <span m='1063100'>are</span>
  <span m='1063160'>fractal</span> <span m='1063670'>in</span> <span m='1063730'>nature.</span>
  </p><p><span m='1064160'>Which</span> <span m='1064180'>means</span> <span m='1064550'>that</span>
  <span m='1065410'>I</span> <span m='1066130'>could</span> <span m='1066430'>think</span>
  <span m='1066850'>that</span> <span m='1067000'>I'm</span> <span m='1067120'>starting</span>
  <span m='1067570'>with</span> <span m='1067710'>a</span> <span m='1067810'>solution</span>
  <span m='1068410'>rate</span> <span m='1068710'>here</span> <span m='1069310'>that</span>
  <span m='1069490'>should</span> <span m='1069700'>converge</span> <span m='1070180'>to</span>
  <span m='1070330'>this</span> <span m='1070510'>green</span> <span m='1070900'>root</span>
  <span m='1071150'>because</span> <span m='1071380'>it's</span> <span m='1071530'>close.</span>
  <span m='1072070'>But</span> <span m='1072220'>it actually</span> <span m='1072610'>goes</span>
  <span m='1072820'>over</span> <span m='1073000'>here.</span> <span m='1073970'>And</span>
  <span m='1074070'>if</span> <span m='1074170'>I</span> <span m='1074270'>change</span>
  <span m='1074440'>that</span> <span m='1074590'>initial</span> <span m='1074950'>guess</span>
  <span m='1075160'>by</span> <span m='1075370'>a</span> <span m='1075400'>little</span>
  <span m='1075700'>bit,</span> <span m='1076000'>it</span> <span m='1076120'>actually</span>
  <span m='1076480'>pops</span> <span m='1076780'>up</span> <span m='1076900'>to</span>
  <span m='1077020'>this</span> <span m='1077260'>root</span> <span m='1077470'>over</span>
  <span m='1077680'>here</span> <span m='1077950'>instead.</span> </p><p><span m='1079870'>It's</span>
  <span m='1080170'>quite</span> <span m='1080500'>difficult</span> <span m='1081250'>to</span>
  <span m='1081370'>predict</span> <span m='1082210'>which</span> <span m='1082480'>solution</span>
  <span m='1083170'>you're</span> <span m='1083320'>going</span> <span m='1083470'>to</span>
  <span m='1083530'>converge</span> <span m='1084130'>to.</span> </p><p><span m='1087060'>Yes?</span>
  </p><p><span m='1087910'>AUDIENCE:</span> <span m='1088390'>And in this case, you</span>
  <span m='1088870'>knew how many</span> <span m='1089350'>roots there are.</span>
  </p><p><span m='1089830'>JAMES SWAN:</span> <span m='1090020'>Yes.</span> </p><p><span
  m='1090210'>AUDIENCE:</span> <span m='1090668'>Often you</span> <span m='1091126'>wouldn't</span>
  <span m='1091584'>know.</span> <span m='1092042'>So you</span> <span m='1092500'>find
  one, and</span> <span m='1092958'>you're</span> <span m='1093416'>happy.</span>
  <span m='1094880'>Right?</span> <span m='1095130'>You're happy</span> <span m='1095617'>because</span>
  <span m='1096104'>[INAUDIBLE]</span> <span m='1098052'>physical.</span> <span m='1098539'>Might
  be</span> <span m='1099026'>the wrong one.</span> </p><p><span m='1100000'>JAMES
  SWAN:</span> <span m='1100490'>So</span> <span m='1101980'>this</span> <span m='1102130'>the</span>
  <span m='1102280'>problem.</span> <span m='1107980'>I</span> <span m='1108040'>think</span>
  <span m='1108280'>this</span> <span m='1108970'>is</span> <span m='1109060'>about</span>
  <span m='1109300'>the</span> <span m='1109390'>minimum</span> <span m='1109810'>level</span>
  <span m='1110110'>of</span> <span m='1110200'>complexity</span> <span m='1110770'>you</span>
  <span m='1110890'>need.</span> <span m='1111500'>Which</span> <span m='1111550'>is</span>
  <span m='1111640'>not</span> <span m='1111790'>very</span> <span m='1112030'>complex</span>
  <span m='1112510'>at</span> <span m='1112600'>all</span> <span m='1112780'>in</span>
  <span m='1112870'>a</span> <span m='1112930'>function</span> <span m='1113320'>to</span>
  <span m='1113440'>get</span> <span m='1113620'>these</span> <span m='1113770'>sorts</span>
  <span m='1114070'>of</span> <span m='1114130'>basins</span> <span m='1114610'>of</span>
  <span m='1114700'>attraction.</span> <span m='1116740'>Polynomial</span> <span m='1117280'>equations</span>
  <span m='1117730'>are</span> <span m='1117790'>ones</span> <span m='1118060'>that</span>
  <span m='1118210'>really</span> <span m='1118510'>suffer</span> <span m='1119020'>from</span>
  <span m='1119290'>this</span> <span m='1119500'>especially,</span> <span m='1120060'>but</span>
  <span m='1120790'>it's</span> <span m='1121300'>a</span> <span m='1121360'>problem</span>
  <span m='1121720'>in</span> <span m='1121840'>general.</span> <span m='1122170'>You</span>
  <span m='1122290'>often</span> <span m='1122620'>don't</span> <span m='1122830'>know.</span>
  </p><p><span m='1124300'>I'll</span> <span m='1124570'>show</span> <span m='1124800'>you</span>
  <span m='1124960'>quasi</span> <span m='1125320'>Newton-Raphson</span> <span m='1125920'>methods</span>
  <span m='1126250'>that</span> <span m='1126370'>help</span> <span m='1126550'>fix</span>
  <span m='1127090'>some</span> <span m='1127330'>of</span> <span m='1127390'>these</span>
  <span m='1127570'>problems.</span> <span m='1128460'>How</span> <span m='1128870'>about</span>
  <span m='1129280'>other</span> <span m='1129640'>problems?</span> <span m='1130270'>It's</span>
  <span m='1130360'>good</span> <span m='1130510'>to</span> <span m='1130600'>know</span>
  <span m='1130930'>where</span> <span m='1131440'>the</span> <span m='1131530'>weaknesses</span>
  <span m='1132070'>are.</span> <span m='1132240'>Newton-Raphson</span> <span m='1132730'>sounds</span>
  <span m='1132970'>great,</span> <span m='1133150'>but</span> <span m='1133240'>where</span>
  <span m='1133390'>are</span> <span m='1133450'>the</span> <span m='1133540'>weaknesses?</span>
  </p><p><span m='1135140'>Let's</span> <span m='1135190'>see.</span> <span m='1135370'>The</span>
  <span m='1135460'>Jacobian--</span> <span m='1137540'>might</span> <span m='1137640'>not</span>
  <span m='1137760'>be</span> <span m='1137850'>easy</span> <span m='1138090'>to</span>
  <span m='1138210'>calculate</span> <span m='1139050'>analytically,</span> <span
  m='1139890'>right?</span> <span m='1140430'>So</span> <span m='1140610'>far</span>
  <span m='1140850'>we've</span> <span m='1141060'>written</span> <span m='1141270'>down</span>
  <span m='1141510'>analytical</span> <span m='1142020'>forms</span> <span m='1142440'>for</span>
  <span m='1142620'>the</span> <span m='1142710'>Jacobian.</span> <span m='1143460'>We've</span>
  <span m='1144180'>had</span> <span m='1144540'>simple functions.</span> <span m='1146070'>But</span>
  <span m='1146160'>maybe</span> <span m='1146370'>it's</span> <span m='1146520'>not</span>
  <span m='1146650'>easy</span> <span m='1146850'>to</span> <span m='1146970'>calculate</span>
  <span m='1147450'>analytically.</span> <span m='1148320'>You</span> <span m='1148530'>should</span>
  <span m='1148680'>think</span> <span m='1148890'>about</span> <span m='1149100'>what</span>
  <span m='1149250'>are</span> <span m='1149340'>the</span> <span m='1149460'>sources</span>
  <span m='1150090'>for</span> <span m='1150240'>this</span> <span m='1150960'>function,</span>
  <span m='1151620'>f</span> <span m='1151830'>of</span> <span m='1151950'>x,</span>
  <span m='1152220'>that</span> <span m='1152310'>we're</span> <span m='1152400'>trying</span>
  <span m='1152670'>to</span> <span m='1152760'>find</span> <span m='1153000'>the</span>
  <span m='1153120'>roots</span> <span m='1153450'>for.</span> </p><p><span m='1154470'>Also</span>
  <span m='1155040'>we</span> <span m='1155120'>got</span> <span m='1155220'>to</span>
  <span m='1155280'>invert</span> <span m='1155670'>the</span> <span m='1155790'>Jacobian,</span>
  <span m='1156210'>and</span> <span m='1156300'>we</span> <span m='1156390'>know</span>
  <span m='1156510'>that's</span> <span m='1156720'>a</span> <span m='1156780'>matrix.</span>
  <span m='1157380'>And</span> <span m='1157470'>matrices</span> <span m='1158070'>which</span>
  <span m='1158220'>have</span> <span m='1158370'>a</span> <span m='1158430'>lot</span>
  <span m='1158670'>of</span> <span m='1158760'>dimensions</span> <span m='1159270'>in</span>
  <span m='1159390'>them</span> <span m='1159570'>are</span> <span m='1159720'>complicated</span>
  <span m='1160440'>to</span> <span m='1160620'>invert.</span> <span m='1161160'>There's</span>
  <span m='1161310'>a</span> <span m='1161370'>huge</span> <span m='1161760'>amount</span>
  <span m='1162120'>of</span> <span m='1162720'>complexity,</span> <span m='1163530'>computational</span>
  <span m='1164160'>complexity,</span> <span m='1164760'>in</span> <span m='1164850'>doing</span>
  <span m='1165120'>those</span> <span m='1165330'>inversions.</span> <span m='1165675'>It</span>
  <span m='1166020'>can</span> <span m='1166140'>take</span> <span m='1166320'>a</span>
  <span m='1166350'>long</span> <span m='1166560'>time</span> <span m='1166890'>to</span>
  <span m='1167040'>do</span> <span m='1167250'>them.</span> </p><p><span m='1168970'>It</span>
  <span m='1169070'>may</span> <span m='1169170'>undesirable</span> <span m='1169920'>to</span>
  <span m='1170160'>have</span> <span m='1170430'>to</span> <span m='1170910'>constantly</span>
  <span m='1171600'>be</span> <span m='1171750'>solving</span> <span m='1172350'>a</span>
  <span m='1172410'>system</span> <span m='1172770'>of</span> <span m='1172860'>linear</span>
  <span m='1173250'>equations.</span> <span m='1174770'>So</span> <span m='1174840'>might</span>
  <span m='1174960'>think</span> <span m='1175140'>about</span> <span m='1175320'>some</span>
  <span m='1175500'>options</span> <span m='1175890'>for</span> <span m='1176010'>mitigating</span>
  <span m='1176610'>this.</span> <span m='1179500'>Sometimes</span> <span m='1179850'>it</span>
  <span m='1179940'>won't</span> <span m='1180730'>converge</span> <span m='1181540'>at</span>
  <span m='1181660'>all?</span> <span m='1182020'>Or</span> <span m='1182170'>to</span>
  <span m='1182290'>the</span> <span m='1182390'>nearest</span> <span m='1182680'>root.</span>
  <span m='1182930'>This</span> <span m='1183040'>is</span> <span m='1183160'>this</span>
  <span m='1183310'>overshoot,</span> <span m='1183790'>or</span> <span m='1183860'>basin</span>
  <span m='1184750'>of</span> <span m='1184840'>attraction</span> <span m='1185350'>problem.</span>
  </p><p><span m='1186130'>And</span> <span m='1186250'>we'll</span> <span m='1186340'>talk</span>
  <span m='1186490'>about</span> <span m='1186640'>these</span> <span m='1186790'>modifications</span>
  <span m='1187570'>to</span> <span m='1187660'>correct</span> <span m='1188020'>these</span>
  <span m='1188260'>issues.</span> <span m='1188770'>They</span> <span m='1188890'>come</span>
  <span m='1189010'>with</span> <span m='1189130'>a</span> <span m='1189190'>penalty</span>
  <span m='1189610'>though.</span> <span m='1190190'>OK?</span> <span m='1191230'>So</span>
  <span m='1191480'>Newton-Raphson</span> <span m='1191910'>was</span> <span m='1192010'>based</span>
  <span m='1192250'>around</span> <span m='1192430'>the</span> <span m='1192550'>idea</span>
  <span m='1192760'>of</span> <span m='1192880'>linearization.</span> <span m='1193870'>If</span>
  <span m='1194050'>we</span> <span m='1194230'>modify</span> <span m='1194950'>that</span>
  <span m='1195130'>linearization,</span> <span m='1196630'>we're</span> <span m='1197010'>going</span>
  <span m='1197270'>to</span> <span m='1197620'>lose</span> <span m='1198190'>some</span>
  <span m='1198460'>of</span> <span m='1198610'>these</span> <span m='1199090'>great</span>
  <span m='1199690'>benefits</span> <span m='1200150'>of</span> <span m='1200230'>the</span>
  <span m='1200320'>Newton-Raphson</span> <span m='1200830'>method,</span> <span m='1201100'>namely</span>
  <span m='1201580'>that</span> <span m='1201730'>it's</span> <span m='1201850'>quadratically</span>
  <span m='1202570'>convergent,</span> <span m='1203060'>right?</span> </p><p><span
  m='1203260'>We're</span> <span m='1203320'>going</span> <span m='1203440'>to</span>
  <span m='1203500'>make</span> <span m='1203650'>some</span> <span m='1203830'>changes</span>
  <span m='1204280'>to</span> <span m='1204400'>the</span> <span m='1204490'>method,</span>
  <span m='1205632'>and</span> <span m='1205970'>it's</span> <span m='1206110'>not</span>
  <span m='1206230'>going</span> <span m='1206350'>to</span> <span m='1206410'>converge</span>
  <span m='1206770'>quadratically</span> <span m='1207520'>anymore.</span> <span m='1208150'>It's</span>
  <span m='1208360'>going</span> <span m='1208480'>to</span> <span m='1208540'>slow</span>
  <span m='1208900'>down,</span> <span m='1209650'>but</span> <span m='1209740'>maybe</span>
  <span m='1210130'>we'll</span> <span m='1210280'>be</span> <span m='1210400'>able</span>
  <span m='1210580'>to</span> <span m='1210850'>rein</span> <span m='1211240'>in</span>
  <span m='1211390'>the</span> <span m='1211480'>method</span> <span m='1211780'>and</span>
  <span m='1211860'>make</span> <span m='1212080'>it</span> <span m='1212140'>converge</span>
  <span m='1213060'>either</span> <span m='1213280'>to</span> <span m='1213430'>the</span>
  <span m='1213520'>roots</span> <span m='1213790'>we</span> <span m='1213940'>want</span>
  <span m='1214180'>it</span> <span m='1214270'>to</span> <span m='1214390'>converge</span>
  <span m='1214900'>to</span> <span m='1215260'>or</span> <span m='1215350'>converge</span>
  <span m='1215770'>more</span> <span m='1215980'>reliably</span> <span m='1216790'>than</span>
  <span m='1216940'>it</span> <span m='1217000'>would</span> <span m='1217210'>before.</span>
  <span m='1219250'>Maybe</span> <span m='1219450'>we'll</span> <span m='1219580'>be</span>
  <span m='1219700'>able</span> <span m='1219880'>to</span> <span m='1220750'>actually</span>
  <span m='1221230'>do</span> <span m='1221530'>the</span> <span m='1221680'>calculation</span>
  <span m='1222430'>faster,</span> <span m='1223150'>even</span> <span m='1223600'>though</span>
  <span m='1224690'>it</span> <span m='1224770'>may</span> <span m='1224920'>require</span>
  <span m='1225220'>more</span> <span m='1225460'>iterations.</span> <span m='1226180'>Maybe</span>
  <span m='1226420'>we</span> <span m='1226480'>can</span> <span m='1226600'>make</span>
  <span m='1226720'>each</span> <span m='1226900'>iteration</span> <span m='1227350'>much</span>
  <span m='1227620'>faster</span> <span m='1228070'>using</span> <span m='1228370'>some</span>
  <span m='1228520'>of</span> <span m='1228580'>these</span> <span m='1228730'>methods.</span>
  <span m='1231560'>OK</span> <span m='1231770'>so</span> <span m='1231960'>here are</span>
  <span m='1232040'>the</span> <span m='1232160'>three</span> <span m='1232370'>things</span>
  <span m='1232560'>that</span> <span m='1232640'>we're</span> <span m='1232730'>going
  to</span> <span m='1232840'>talk</span> <span m='1233040'>about.</span> <span m='1233190'>We're</span>
  <span m='1233330'>going to talk</span> <span m='1233510'>about</span> <span m='1234410'>approximating</span>
  <span m='1235070'>the</span> <span m='1235160'>Jacobian</span> <span m='1235730'>with</span>
  <span m='1235910'>finite</span> <span m='1236300'>differences.</span> <span m='1237290'>We're</span>
  <span m='1237410'>talking</span> <span m='1237590'>about</span> <span m='1237740'>Broyden's</span>
  <span m='1238220'>method</span> <span m='1238730'>for</span> <span m='1238910'>approximating</span>
  <span m='1239600'>the</span> <span m='1239750'>inverse</span> <span m='1240230'>of</span>
  <span m='1240320'>the</span> <span m='1240410'>Jacobian.</span> <span m='1241250'>And</span>
  <span m='1241340'>we're</span> <span m='1241460'>going to talk</span> <span m='1241640'>about</span>
  <span m='1241790'>something</span> <span m='1242060'>called</span> <span m='1242240'>damped</span>
  <span m='1242660'>Newton-Raphson</span> <span m='1243350'>methods.</span> <span
  m='1244130'>Those</span> <span m='1244310'>will</span> <span m='1244400'>be</span>
  <span m='1244520'>the</span> <span m='1244640'>three</span> <span m='1244850'>topics</span>
  <span m='1245240'>of</span> <span m='1245330'>the</span> <span m='1245420'>day.</span>
  </p><p><span m='1248960'>So</span> <span m='1249200'>here's</span> <span m='1249440'>what</span>
  <span m='1249530'>I</span> <span m='1249590'>said</span> <span m='1249740'>before.</span>
  <span m='1249980'>Analytical</span> <span m='1250510'>calculations</span> <span
  m='1250790'>of</span> <span m='1251070'>Jacobian</span> <span m='1251480'>requires</span>
  <span m='1252140'>analytical</span> <span m='1252620'>formulas</span> <span m='1253070'>for</span>
  <span m='1253250'>f.</span> <span m='1253620'>And</span> <span m='1254360'>for</span>
  <span m='1254480'>functions</span> <span m='1254930'>of</span> <span m='1255020'>a</span>
  <span m='1255080'>few</span> <span m='1255290'>dimensions,</span> <span m='1255890'>right?</span>
  <span m='1256070'>These</span> <span m='1256220'>calculations</span> <span m='1256820'>are</span>
  <span m='1256910'>not</span> <span m='1257090'>too</span> <span m='1257270'>tough.</span>
  <span m='1258620'>For</span> <span m='1258740'>functions</span> <span m='1259100'>of</span>
  <span m='1259160'>many</span> <span m='1259580'>dimensions,</span> <span m='1260780'>this</span>
  <span m='1261050'>is</span> <span m='1262280'>tedious</span> <span m='1262730'>at</span>
  <span m='1262850'>best.</span> <span m='1263710'>Error</span> <span m='1263990'>prone,</span>
  <span m='1264650'>at</span> <span m='1264800'>worst.</span> </p><p><span m='1265880'>Think</span>
  <span m='1266060'>about</span> <span m='1266690'>even</span> <span m='1266930'>something</span>
  <span m='1267260'>like</span> <span m='1267410'>10</span> <span m='1267620'>equations</span>
  <span m='1268190'>for</span> <span m='1268340'>10</span> <span m='1268580'>unknowns.</span>
  <span m='1269190'>If</span> <span m='1269240'>your</span> <span m='1269510'>error</span>
  <span m='1269750'>rate</span> <span m='1270050'>is</span> <span m='1270200'>1%,</span>
  <span m='1271370'>well,</span> <span m='1271510'>you're</span> <span m='1271840'>shot.</span>
  <span m='1273050'>There's</span> <span m='1273140'>a</span> <span m='1273200'>pretty</span>
  <span m='1273380'>good</span> <span m='1273500'>chance</span> <span m='1273980'>that</span>
  <span m='1274100'>you</span> <span m='1274220'>missed</span> <span m='1274550'>one</span>
  <span m='1274760'>element</span> <span m='1275170'>of</span> <span m='1275270'>the</span>
  <span m='1275360'>Jacobian.</span> <span m='1275900'>You</span> <span m='1275990'>made</span>
  <span m='1276200'>a</span> <span m='1276230'>mistake</span> <span m='1276650'>somewhere</span>
  <span m='1276950'>in</span> <span m='1277130'>there.</span> <span m='1278000'>And</span>
  <span m='1278120'>now</span> <span m='1278270'>you're</span> <span m='1278420'>not</span>
  <span m='1278600'>doing</span> <span m='1278870'>Newton-Raphson</span> <span m='1279530'>You're</span>
  <span m='1279620'>doing</span> <span m='1279920'>some</span> <span m='1280190'>other</span>
  <span m='1280490'>iterative</span> <span m='1280910'>method</span> <span m='1281240'>that</span>
  <span m='1281390'>isn't</span> <span m='1281630'>the</span> <span m='1281720'>one</span>
  <span m='1281930'>that</span> <span m='1282080'>you</span> <span m='1282200'>intended.</span>
  </p><p><span m='1284540'>There</span> <span m='1284660'>are</span> <span m='1284690'>a</span>
  <span m='1284720'>lot</span> <span m='1284870'>of</span> <span m='1284930'>times</span>
  <span m='1285350'>where</span> <span m='1286140'>you--</span> <span m='1286430'>maybe</span>
  <span m='1286700'>you have</span> <span m='1286790'>an</span> <span m='1286880'>analytical</span>
  <span m='1287360'>formula</span> <span m='1287780'>for</span> <span m='1287930'>some</span>
  <span m='1288230'>of</span> <span m='1288350'>these</span> <span m='1288760'>f's,</span>
  <span m='1289310'>but</span> <span m='1289520'>not</span> <span m='1290330'>all</span>
  <span m='1290570'>of</span> <span m='1290690'>them.</span> <span m='1291980'>So</span>
  <span m='1292430'>where</span> <span m='1292670'>can</span> <span m='1292820'>these</span>
  <span m='1292940'>functionalities</span> <span m='1293570'>come</span> <span m='1293780'>from?</span>
  <span m='1294710'>We've</span> <span m='1294810'>seen</span> <span m='1295100'>some</span>
  <span m='1295340'>cases,</span> <span m='1296150'>where</span> <span m='1297020'>you</span>
  <span m='1297080'>have</span> <span m='1297170'>physical</span> <span m='1297530'>models.</span>
  <span m='1297950'>Thermodynamic</span> <span m='1298610'>models</span> <span m='1299150'>that</span>
  <span m='1299330'>you</span> <span m='1299690'>can</span> <span m='1299900'>write</span>
  <span m='1300110'>down</span> <span m='1300410'>by</span> <span m='1300620'>hand.</span>
  <span m='1300920'>But</span> <span m='1301060'>where</span> <span m='1301130'>are</span>
  <span m='1301250'>other</span> <span m='1301460'>places</span> <span m='1301970'>that</span>
  <span m='1302120'>these</span> <span m='1302300'>functions</span> <span m='1302810'>come</span>
  <span m='1302990'>from?</span> <span m='1306560'>Ideas?</span> </p><p><span m='1307498'>AUDIENCE:</span>
  <span m='1307986'>[INAUDIBLE]</span> </p><p><span m='1310426'>JAMES SWAN:</span>
  <span m='1310914'>Oh, good.</span> </p><p><span m='1311890'>AUDIENCE:</span> <span
  m='1312378'>[INAUDIBLE]</span> </p><p><span m='1314330'>JAMES SWAN:</span> <span
  m='1314480'>Beautiful.</span> <span m='1314630'>So</span> <span m='1314750'>this</span>
  <span m='1314930'>is</span> <span m='1314990'>going</span> <span m='1315110'>to</span>
  <span m='1315170'>be</span> <span m='1315230'>the</span> <span m='1315290'>most</span>
  <span m='1315440'>common</span> <span m='1315770'>case,</span> <span m='1316130'>right?</span>
  <span m='1316710'>Maybe</span> <span m='1318530'>you</span> <span m='1318590'>want</span>
  <span m='1318710'>to</span> <span m='1318770'>use</span> <span m='1318920'>some</span>
  <span m='1319100'>sort</span> <span m='1319280'>of</span> <span m='1319370'>simulation</span>
  <span m='1319970'>code,</span> <span m='1320450'>right?</span> <span m='1320720'>To</span>
  <span m='1320840'>model</span> <span m='1321200'>something.</span> <span m='1321860'>It's</span>
  <span m='1321980'>somebody</span> <span m='1322250'>else's</span> <span m='1322550'>simulation</span>
  <span m='1322905'>code.</span> <span m='1323260'>They're</span> <span m='1323450'>an</span>
  <span m='1323540'>expert</span> <span m='1323960'>at</span> <span m='1324620'>doing</span>
  <span m='1325070'>finite</span> <span m='1325460'>element</span> <span m='1325790'>modeling.</span>
  <span m='1326240'>But</span> <span m='1326360'>the</span> <span m='1326540'>output</span>
  <span m='1328400'>is</span> <span m='1328550'>this</span> <span m='1328790'>f</span>
  <span m='1329090'>that</span> <span m='1329240'>you're</span> <span m='1329390'>interested,</span>
  <span m='1329900'>and</span> <span m='1329960'>the</span> <span m='1330140'>input</span>
  <span m='1330530'>to</span> <span m='1330650'>the</span> <span m='1330740'>simulation</span>
  <span m='1331350'>are</span> <span m='1331520'>these</span> <span m='1331790'>x's.</span>
  <span m='1332930'>And</span> <span m='1333020'>you</span> <span m='1333080'>want</span>
  <span m='1333200'>to</span> <span m='1333260'>find</span> <span m='1333500'>the</span>
  <span m='1333590'>roots</span> <span m='1334550'>associated</span> <span m='1335210'>with</span>
  <span m='1335360'>this</span> <span m='1335570'>problem</span> <span m='1335960'>that</span>
  <span m='1336110'>you're</span> <span m='1336230'>solving</span> <span m='1336740'>via</span>
  <span m='1336950'>the</span> <span m='1337070'>simulation</span> <span m='1337670'>code,</span>
  <span m='1338030'>right?</span> </p><p><span m='1338840'>This</span> <span m='1338990'>is</span>
  <span m='1339080'>pretty</span> <span m='1339290'>important</span> <span m='1339710'>being</span>
  <span m='1339890'>able</span> <span m='1340070'>to</span> <span m='1340130'>connect</span>
  <span m='1340490'>different</span> <span m='1340820'>pieces</span> <span m='1341300'>of</span>
  <span m='1341420'>software</span> <span m='1341990'>together.</span> <span m='1343420'>Well,</span>
  <span m='1345400'>there's</span> <span m='1345520'>no</span> <span m='1345700'>analytical</span>
  <span m='1346180'>formula</span> <span m='1346540'>for</span> <span m='1346760'>f</span>
  <span m='1347060'>there.</span> <span m='1347910'>OK?</span> <span m='1348600'>You're</span>
  <span m='1348730'>shot.</span> <span m='1349990'>So</span> <span m='1350180'>it</span>
  <span m='1350240'>may</span> <span m='1350350'>come</span> <span m='1350560'>from</span>
  <span m='1350950'>results</span> <span m='1351490'>of</span> <span m='1351580'>simulations.</span>
  <span m='1352180'>This</span> <span m='1352360'>is</span> <span m='1352610'>extremely</span>
  <span m='1353230'>common.</span> <span m='1353710'>It could</span> <span m='1354020'>come</span>
  <span m='1354280'>from</span> <span m='1354670'>interpretation</span> <span m='1355330'>of</span>
  <span m='1355420'>data.</span> <span m='1356550'>So you</span> <span m='1356710'>may</span>
  <span m='1356860'>have</span> <span m='1357040'>a</span> <span m='1357100'>bunch</span>
  <span m='1357340'>of</span> <span m='1357910'>data</span> <span m='1358450'>that's</span>
  <span m='1358630'>being</span> <span m='1358840'>generated</span> <span m='1359350'>by</span>
  <span m='1359620'>some</span> <span m='1360040'>physical</span> <span m='1360430'>measurement</span>
  <span m='1361090'>or</span> <span m='1361180'>a</span> <span m='1361210'>process,</span>
  <span m='1361780'>either</span> <span m='1361990'>continuously</span> <span m='1362860'>or</span>
  <span m='1363000'>you</span> <span m='1363430'>just</span> <span m='1363580'>have</span>
  <span m='1363730'>a</span> <span m='1363760'>data</span> <span m='1364030'>set</span>
  <span m='1364240'>that's</span> <span m='1364420'>available</span> <span m='1364930'>to</span>
  <span m='1365050'>you.</span> </p><p><span m='1367030'>But</span> <span m='1367150'>these</span>
  <span m='1367300'>function</span> <span m='1367630'>values</span> <span m='1367990'>are</span>
  <span m='1368080'>often</span> <span m='1368500'>not,</span> <span m='1370060'>they're</span>
  <span m='1370180'>not</span> <span m='1370360'>things</span> <span m='1370690'>that</span>
  <span m='1370840'>you</span> <span m='1370930'>know</span> <span m='1371170'>analytically.</span>
  <span m='1372250'>It</span> <span m='1372340'>may</span> <span m='1372520'>also</span>
  <span m='1372820'>be</span> <span m='1372940'>the</span> <span m='1373060'>case</span>
  <span m='1373420'>that,</span> <span m='1375370'>oh,</span> <span m='1375550'>man,</span>
  <span m='1375830'>even</span> <span m='1376100'>Aspen,</span> <span m='1376520'>you're</span>
  <span m='1376730'>going</span> <span m='1376850'>to</span> <span m='1376910'>wind</span>
  <span m='1377120'>up</span> <span m='1377210'>solving</span> <span m='1377810'>systems</span>
  <span m='1378320'>of</span> <span m='1378410'>nonlinear</span> <span m='1378860'>equations.</span>
  <span m='1379340'>It's</span> <span m='1379460'>going</span> <span m='1379580'>to</span>
  <span m='1379640'>use</span> <span m='1379790'>the</span> <span m='1379910'>Newton-Raphson</span>
  <span m='1380600'>method.</span> <span m='1380990'>Aspen's</span> <span m='1381470'>going</span>
  <span m='1381590'>to</span> <span m='1381650'>have</span> <span m='1382220'>lots</span>
  <span m='1382460'>of</span> <span m='1382550'>these</span> <span m='1382850'>formulas</span>
  <span m='1383510'>in</span> <span m='1383630'>it</span> <span m='1383750'>for</span>
  <span m='1383990'>functions.</span> </p><p><span m='1385250'>Whose</span> <span
  m='1385730'>going</span> <span m='1386060'>in</span> <span m='1386240'>by</span>
  <span m='1386450'>hand</span> <span m='1386870'>and</span> <span m='1386990'>computing</span>
  <span m='1387440'>the</span> <span m='1387560'>derivatives</span> <span m='1388100'>of</span>
  <span m='1388190'>all</span> <span m='1388340'>these</span> <span m='1388490'>functions</span>
  <span m='1388970'>for</span> <span m='1389150'>aspen?</span> <span m='1391010'>MATLAB</span>
  <span m='1391790'>has</span> <span m='1392240'>a</span> <span m='1392330'>nonlinear</span>
  <span m='1392930'>equation</span> <span m='1393350'>solver</span> <span m='1393740'>in</span>
  <span m='1393850'>it.</span> <span m='1393920'>You</span> <span m='1394070'>give</span>
  <span m='1394220'>it</span> <span m='1394340'>the</span> <span m='1394430'>function,</span>
  <span m='1395180'>and</span> <span m='1395350'>it'll</span> <span m='1395900'>find</span>
  <span m='1396260'>the</span> <span m='1396350'>root</span> <span m='1396560'>of</span>
  <span m='1396650'>the</span> <span m='1396770'>equation,</span> <span m='1397340'>given</span>
  <span m='1397610'>a</span> <span m='1397640'>guess.</span> <span m='1398000'>It's</span>
  <span m='1398090'>going</span> <span m='1398210'>to</span> <span m='1398270'>use</span>
  <span m='1398450'>the</span> <span m='1398570'>Newton-Raphson</span> <span m='1399230'>method.</span>
  </p><p><span m='1399490'>Whose</span> <span m='1399890'>computing</span> <span m='1400340'>the</span>
  <span m='1400430'>Jacobian</span> <span m='1401090'>for</span> <span m='1402410'>MATLAB?</span>
  <span m='1403850'>You</span> <span m='1403970'>can.</span> <span m='1404120'>You
  can</span> <span m='1404420'>compute it</span> <span m='1404480'>by</span> <span
  m='1404660'>hand,</span> <span m='1404990'>and</span> <span m='1405080'>give</span>
  <span m='1405220'>it</span> <span m='1405300'>an</span> <span m='1405410'>input.</span>
  <span m='1405870'>Sometimes</span> <span m='1406130'>that's</span> <span m='1406280'>a</span>
  <span m='1406340'>really</span> <span m='1406580'>good</span> <span m='1406760'>thing</span>
  <span m='1407030'>to</span> <span m='1407180'>do.</span> <span m='1409100'>But</span>
  <span m='1409280'>sometimes,</span> <span m='1409850'>we</span> <span m='1409970'>don't</span>
  <span m='1410120'>have</span> <span m='1410270'>that</span> <span m='1410390'>available</span>
  <span m='1410780'>to</span> <span m='1410900'>us.</span> <span m='1411070'>So</span>
  <span m='1411170'>we</span> <span m='1411270'>need</span> <span m='1411290'>alternative</span>
  <span m='1411860'>ways</span> <span m='1412160'>of</span> <span m='1412220'>computing</span>
  <span m='1412640'>the</span> <span m='1412790'>Jacobian.</span> <span m='1413300'>The</span>
  <span m='1413390'>simplest</span> <span m='1413960'>one</span> <span m='1415090'>is</span>
  <span m='1415220'>a</span> <span m='1415310'>finite</span> <span m='1415640'>difference</span>
  <span m='1415970'>approximation.</span> </p><p><span m='1417410'>So</span> <span
  m='1417500'>you</span> <span m='1417650'>recall</span> <span m='1418070'>the</span>
  <span m='1418190'>definition</span> <span m='1419060'>of</span> <span m='1419210'>the</span>
  <span m='1419360'>derivative.</span> <span m='1420200'>It's</span> <span m='1420590'>the</span>
  <span m='1420710'>limit</span> <span m='1421970'>of</span> <span m='1422150'>this</span>
  <span m='1422420'>difference,</span> <span m='1423890'>f</span> <span m='1424170'>of</span>
  <span m='1424340'>x</span> <span m='1424580'>plus</span> <span m='1424790'>epsilon</span>
  <span m='1425570'>minus</span> <span m='1425930'>f</span> <span m='1426080'>of</span>
  <span m='1426200'>x</span> <span m='1426440'>divided by</span> <span m='1426520'>epsilon,</span>
  <span m='1427040'>as</span> <span m='1427170'>epsilon</span> <span m='1427700'>goes</span>
  <span m='1427940'>to</span> <span m='1428090'>zero.</span> <span m='1429680'>There's</span>
  <span m='1429860'>an</span> <span m='1430040'>error</span> <span m='1430730'>in</span>
  <span m='1430880'>this</span> <span m='1431360'>approximation</span> <span m='1432260'>for</span>
  <span m='1432410'>the</span> <span m='1432530'>derivative</span> <span m='1433040'>with</span>
  <span m='1433180'>a</span> <span m='1433250'>finite</span> <span m='1433730'>value</span>
  <span m='1434090'>for</span> <span m='1434300'>epsilon,</span> <span m='1435210'>which</span>
  <span m='1435290'>is</span> <span m='1435380'>proportional</span> <span m='1436100'>to</span>
  <span m='1436250'>epsilon.</span> </p><p><span m='1438320'>So</span> <span m='1438470'>choose</span>
  <span m='1438800'>a</span> <span m='1438860'>small</span> <span m='1439130'>value</span>
  <span m='1439460'>of</span> <span m='1439550'>epsilon.</span> <span m='1439970'>You'll</span>
  <span m='1440120'>get</span> <span m='1440270'>a</span> <span m='1440330'>good</span>
  <span m='1440480'>approximation</span> <span m='1441320'>for</span> <span m='1441710'>the</span>
  <span m='1441830'>derivative.</span> <span m='1444080'>It</span> <span m='1444170'>turns</span>
  <span m='1444440'>out</span> <span m='1444590'>the</span> <span m='1444740'>accuracy</span>
  <span m='1445460'>depends</span> <span m='1445790'>on</span> <span m='1445910'>epsilon,</span>
  <span m='1446270'>but kind of</span> <span m='1446500'>in</span> <span m='1446660'>a</span>
  <span m='1446720'>non-intuitive</span> <span m='1447440'>way.</span> <span m='1447620'>And</span>
  <span m='1447710'>here's</span> <span m='1447890'>a</span> <span m='1447980'>simple</span>
  <span m='1448250'>example.</span> <span m='1448770'>So</span> <span m='1449180'>let's</span>
  <span m='1449360'>compute</span> <span m='1449690'>the</span> <span m='1449780'>derivative</span>
  <span m='1450380'>of</span> <span m='1451160'>f</span> <span m='1451370'>of</span>
  <span m='1451490'>x</span> <span m='1451670'>equals</span> <span m='1451970'>e</span>
  <span m='1452270'>the</span> <span m='1452420'>x,</span> <span m='1453600'>which</span>
  <span m='1453650'>is</span> <span m='1453770'>e</span> <span m='1453860'>to</span>
  <span m='1454010'>the</span> <span m='1454160'>x.</span> <span m='1454520'>Let's
  evaluate</span> <span m='1454865'>it</span> <span m='1455210'>at</span> <span m='1455330'>x</span>
  <span m='1455510'>equals</span> <span m='1455840'>1.</span> </p><p><span m='1457980'>So</span>
  </p><p><span m='1458170'>F prime</span> <span m='1458480'>of</span> <span m='1458600'>1</span>
  <span m='1458930'>is</span> <span m='1459050'>e</span> <span m='1459320'>the</span>
  <span m='1459440'>1,</span> <span m='1459980'>which</span> <span m='1460130'>should</span>
  <span m='1460430'>approximately</span> <span m='1461240'>be</span> <span m='1461990'>e</span>
  <span m='1462230'>to</span> <span m='1462290'>the</span> <span m='1462380'>1</span>
  <span m='1462560'>plus</span> <span m='1462830'>epsilon</span> <span m='1463460'>minus</span>
  <span m='1463770'>e</span> <span m='1463920'>to</span> <span m='1464030'>the</span>
  <span m='1464150'>1</span> <span m='1464480'>over</span> <span m='1464780'>epsilon.</span>
  <span m='1466740'>And</span> <span m='1466850'>here</span> <span m='1467030'>I've</span>
  <span m='1467450'>done</span> <span m='1467780'>this</span> <span m='1467960'>calculation.</span>
  <span m='1469930'>And</span> <span m='1470050'>I've</span> <span m='1470170'>asked,</span>
  <span m='1470510'>what's</span> <span m='1470890'>the</span> <span m='1471160'>absolute</span>
  <span m='1471760'>error</span> <span m='1472600'>in</span> <span m='1472750'>this</span>
  <span m='1472900'>calculation</span> <span m='1473500'>by</span> <span m='1473590'>taking</span>
  <span m='1473860'>the</span> <span m='1473950'>difference</span> <span m='1474340'>between</span>
  <span m='1474760'>this</span> <span m='1475810'>and</span> <span m='1476050'>this,</span>
  <span m='1478030'>for</span> <span m='1478150'>different</span> <span m='1478420'>values</span>
  <span m='1478810'>of</span> <span m='1478900'>epsilon.</span> </p><p><span m='1479290'>You</span>
  <span m='1479350'>can</span> <span m='1479470'>see</span> <span m='1480070'>initially,</span>
  <span m='1480790'>as</span> <span m='1480910'>epsilon</span> <span m='1481270'>gets</span>
  <span m='1481450'>smaller,</span> <span m='1482180'>the</span> <span m='1482230'>absolute</span>
  <span m='1482650'>error</span> <span m='1482890'>goes</span> <span m='1483190'>down</span>
  <span m='1483670'>in</span> <span m='1483850'>proportion</span> <span m='1484340'>to</span>
  <span m='1484390'>epsilon.</span> <span m='1484980'>10</span> <span m='1485150'>to</span>
  <span m='1485230'>the</span> <span m='1485320'>minus</span> <span m='1485640'>3,</span>
  <span m='1485950'>10 to</span> <span m='1486070'>the</span> <span m='1486130'>minus</span>
  <span m='1486490'>3.</span> <span m='1487000'>10</span> <span m='1487150'>to the</span>
  <span m='1487240'>minus</span> <span m='1487570'>4,</span> <span m='1487890'>10</span>
  <span m='1488190'>to the minus</span> <span m='1488500'>4.</span> <span m='1489190'>10</span>
  <span m='1489340'>to</span> <span m='1489430'>the</span> <span m='1489520'>minus</span>
  <span m='1489820'>8,</span> <span m='1490120'>10</span> <span m='1490330'>to the</span>
  <span m='1490390'>minus</span> <span m='1490510'>8.</span> <span m='1491380'>10</span>
  <span m='1491650'>to</span> <span m='1491740'>the</span> <span m='1491830'>minus</span>
  <span m='1492280'>9.</span> <span m='1492660'>10 to the</span> <span m='1492940'>minus</span>
  <span m='1493320'>7.</span> <span m='1493960'>10 to</span> <span m='1494290'>the</span>
  <span m='1494620'>minus</span> <span m='1495080'>10.</span> <span m='1495390'>And</span>
  <span m='1495700'>10 to the minus</span> <span m='1495940'>6.</span> <span m='1496380'>So</span>
  <span m='1496400'>it went</span> <span m='1496600'>down,</span> <span m='1497680'>and</span>
  <span m='1497780'>it</span> <span m='1497830'>came</span> <span m='1498070'>back</span>
  <span m='1498340'>up.</span> <span m='1498860'>But</span> <span m='1498880'>that's</span>
  <span m='1499030'>not</span> <span m='1499120'>what</span> <span m='1499210'>this</span>
  <span m='1499360'>formula</span> <span m='1499750'>told</span> <span m='1500050'>us</span>
  <span m='1500120'>should</span> <span m='1500320'>happen,</span> <span m='1501040'>right?</span>
  <span m='1502060'>Yes?</span> </p><p><span m='1502849'>AUDIENCE:</span> <span m='1503012'>So
  just</span> <span m='1503175'>to</span> <span m='1503338'>be</span> <span m='1503827'>sure.</span>
  <span m='1504316'>That term</span> <span m='1504805'>in that</span> <span m='1505294'>column</span>
  <span m='1505783'>on</span> <span m='1506272'>the right?</span> </p><p><span m='1507250'>JAMES
  SWAN:</span> <span m='1507430'>Yes?</span> </p><p><span m='1508028'>AUDIENCE:</span>
  <span m='1508446'>It says</span> <span m='1508864'>exponential</span> <span m='1509700'>1,</span>
  <span m='1510055'>but it represents</span> <span m='1510410'>the</span> <span m='1510903'>approximation?</span>
  </p><p><span m='1511890'>JAMES SWAN:</span> <span m='1512260'>Exponential</span>
  <span m='1512830'>1</span> <span m='1513070'>is</span> <span m='1513190'>exponential</span>
  <span m='1513700'>1.</span> <span m='1514170'>f</span> <span m='1514340'>prime</span>
  <span m='1514660'>of</span> <span m='1514810'>1</span> <span m='1515050'>is</span>
  <span m='1515200'>our</span> <span m='1515290'>approximation</span> <span m='1516040'>here.</span>
  </p><p><span m='1516310'>AUDIENCE:</span> <span m='1516565'>Oh, OK.</span> </p><p><span
  m='1516820'>JAMES SWAN:</span> <span m='1516940'>Sorry</span> <span m='1517060'>that</span>
  <span m='1517210'>that's</span> <span m='1517420'>unclear.</span> <span m='1517870'>Yes,</span>
  <span m='1518170'>so</span> <span m='1518320'>this</span> <span m='1518530'>is</span>
  <span m='1518650'>the</span> <span m='1518770'>absolute</span> <span m='1519220'>error</span>
  <span m='1519580'>in</span> <span m='1519820'>this</span> <span m='1520090'>approximation.</span>
  <span m='1523370'>So</span> <span m='1523390'>it</span> <span m='1523450'>goes</span>
  <span m='1523660'>down,</span> <span m='1524590'>and</span> <span m='1524680'>then</span>
  <span m='1524800'>it</span> <span m='1524860'>goes</span> <span m='1525100'>up.</span>
  <span m='1525660'>Is that</span> <span m='1526010'>clear</span> <span m='1526440'>now?</span>
  <span m='1526590'>Good.</span> <span m='1527210'>OK,</span> <span m='1527770'>why</span>
  <span m='1527920'>does</span> <span m='1528040'>it</span> <span m='1528100'>go</span>
  <span m='1528250'>down?</span> <span m='1528730'>It goes</span> <span m='1528940'>down</span>
  <span m='1529270'>because</span> <span m='1529810'>our</span> <span m='1530020'>definition</span>
  <span m='1530650'>of</span> <span m='1530740'>the</span> <span m='1530830'>derivative</span>
  <span m='1531280'>says</span> <span m='1531580'>it</span> <span m='1531700'>should</span>
  <span m='1531820'>go</span> <span m='1532000'>down.</span> </p><p><span m='1533140'>At</span>
  <span m='1533260'>some</span> <span m='1533530'>point,</span> <span m='1534460'>I've</span>
  <span m='1534560'>actually</span> <span m='1534880'>got</span> <span m='1535030'>to</span>
  <span m='1535120'>do</span> <span m='1535510'>these</span> <span m='1535750'>calculations</span>
  <span m='1537610'>with</span> <span m='1537790'>high</span> <span m='1538000'>enough</span>
  <span m='1538240'>accuracy</span> <span m='1539440'>to</span> <span m='1539560'>be</span>
  <span m='1539650'>able</span> <span m='1539770'>to</span> <span m='1539860'>perceive</span>
  <span m='1540370'>the</span> <span m='1540460'>difference</span> <span m='1540910'>between</span>
  <span m='1541270'>e</span> <span m='1541570'>to</span> <span m='1541630'>the</span>
  <span m='1541750'>1</span> <span m='1542050'>plus,</span> <span m='1543040'>10</span>
  <span m='1543280'>to</span> <span m='1543400'>the</span> <span m='1543490'>minus</span>
  <span m='1543850'>9,</span> <span m='1544450'>and</span> <span m='1544630'>e</span>
  <span m='1544810'>to</span> <span m='1544960'>the</span> <span m='1545080'>1.</span>
  <span m='1547030'>So</span> <span m='1547240'>there</span> <span m='1547490'>is</span>
  <span m='1547570'>a</span> <span m='1547660'>truncation</span> <span m='1548350'>error</span>
  <span m='1548830'>in</span> <span m='1548950'>the</span> <span m='1549040'>calculation</span>
  <span m='1549640'>of</span> <span m='1549730'>this</span> <span m='1550000'>difference</span>
  <span m='1551710'>that</span> <span m='1551830'>reduces</span> <span m='1552340'>my</span>
  <span m='1552490'>accuracy</span> <span m='1553090'>at</span> <span m='1553180'>a</span>
  <span m='1553240'>certain</span> <span m='1553540'>level.</span> </p><p><span m='1554810'>There's</span>
  <span m='1555050'>a</span> <span m='1555150'>heuristic</span> <span m='1555550'>you</span>
  <span m='1555640'>can</span> <span m='1555790'>use</span> <span m='1556000'>here,</span>
  <span m='1556480'>OK?</span> <span m='1557650'>You</span> <span m='1557740'>want</span>
  <span m='1557860'>to</span> <span m='1557920'>set</span> <span m='1558130'>this</span>
  <span m='1558340'>epsilon</span> <span m='1559030'>when</span> <span m='1559150'>you</span>
  <span m='1559210'>do</span> <span m='1559330'>this</span> <span m='1559510'>finite</span>
  <span m='1559800'>difference</span> <span m='1560100'>approximation,</span> <span
  m='1560920'>to</span> <span m='1561040'>be</span> <span m='1561310'>the</span> <span
  m='1561430'>square</span> <span m='1561730'>root</span> <span m='1562000'>of</span>
  <span m='1562060'>the</span> <span m='1562150'>machine</span> <span m='1562510'>precision</span>
  <span m='1563740'>times</span> <span m='1564010'>the</span> <span m='1564070'>magnitude</span>
  <span m='1564760'>of</span> <span m='1565810'>x,</span> <span m='1566200'>the</span>
  <span m='1566320'>point</span> <span m='1566530'>at</span> <span m='1566590'>which</span>
  <span m='1566740'>you're</span> <span m='1566830'>trying</span> <span m='1567010'>to</span>
  <span m='1567100'>calculate</span> <span m='1567580'>this</span> <span m='1567740'>derivative.</span>
  <span m='1568340'>So that's,</span> <span m='1569020'>usually</span> <span m='1569320'>we're</span>
  <span m='1569440'>double</span> <span m='1569710'>precision.</span> <span m='1570220'>So</span>
  <span m='1570330'>this</span> <span m='1570430'>is</span> <span m='1570490'>something</span>
  <span m='1570820'>like</span> <span m='1570970'>10</span> <span m='1571210'>to</span>
  <span m='1571330'>the</span> <span m='1571450'>minus</span> <span m='1571690'>8</span>
  <span m='1572200'>times</span> <span m='1572470'>the</span> <span m='1572560'>magnitude</span>
  <span m='1573040'>of</span> <span m='1573130'>x.</span> <span m='1573940'>That's</span>
  <span m='1574060'>pretty</span> <span m='1574270'>good.</span> <span m='1574690'>That</span>
  <span m='1574780'>holds</span> <span m='1575050'>true</span> <span m='1575260'>here.</span>
  <span m='1576070'>OK?</span> <span m='1576310'>You</span> <span m='1576400'>can</span>
  <span m='1576550'>test</span> <span m='1576830'>it</span> <span m='1576940'>out</span>
  <span m='1577090'>on</span> <span m='1577210'>some</span> <span m='1577360'>other</span>
  <span m='1577510'>functions.</span> </p><p><span m='1580140'>If</span> <span m='1580290'>x</span>
  <span m='1580490'>is</span> <span m='1580560'>0,</span> <span m='1581130'>or</span>
  <span m='1581310'>very</span> <span m='1581580'>small.</span> <span m='1582210'>We</span>
  <span m='1582300'>don't</span> <span m='1582390'>want</span> <span m='1582510'>a</span>
  <span m='1582570'>relative</span> <span m='1583020'>tolerance.</span> <span m='1583410'>We've</span>
  <span m='1583470'>got to</span> <span m='1583610'>choose</span> <span m='1583800'>an</span>
  <span m='1583890'>absolute</span> <span m='1584280'>tolerance</span> <span m='1584760'>instead.</span>
  <span m='1586110'>Just</span> <span m='1586320'>like</span> <span m='1586440'>we</span>
  <span m='1586740'>talked</span> <span m='1586980'>about</span> <span m='1587250'>with
  the</span> <span m='1587340'>step</span> <span m='1587640'>norm</span> <span m='1587940'>criteria.</span>
  <span m='1589080'>So</span> <span m='1589200'>one</span> <span m='1589290'>has</span>
  <span m='1589410'>to</span> <span m='1589530'>be</span> <span m='1589620'>a</span>
  <span m='1589680'>little</span> <span m='1590070'>bit</span> <span m='1590250'>careful</span>
  <span m='1590670'>in</span> <span m='1590790'>how</span> <span m='1590880'>you</span>
  <span m='1591060'>implement</span> <span m='1591540'>this.</span> <span m='1591850'>But</span>
  <span m='1591870'>this</span> <span m='1592050'>is</span> <span m='1592170'>a</span>
  <span m='1593340'>good</span> <span m='1593550'>guide,</span> <span m='1594210'>OK?</span>
  <span m='1594570'>A</span> <span m='1594630'>good</span> <span m='1594840'>way</span>
  <span m='1595080'>to</span> <span m='1595350'>think</span> <span m='1595590'>about</span>
  <span m='1596250'>how</span> <span m='1596400'>the</span> <span m='1596550'>error</span>
  <span m='1596700'>is</span> <span m='1596790'>going</span> <span m='1596910'>to</span>
  <span m='1596970'>go</span> <span m='1597120'>down,</span> <span m='1597690'>and</span>
  <span m='1597840'>where</span> <span m='1598080'>it's</span> <span m='1598170'>going</span>
  <span m='1598290'>to</span> <span m='1598350'>start</span> <span m='1598590'>to</span>
  <span m='1598710'>come</span> <span m='1598890'>back</span> <span m='1599160'>up.</span>
  <span m='1600180'>Make</span> <span m='1600350'>sense?</span> <span m='1601350'>Good.</span>
  </p><p><span m='1603880'>OK,</span> <span m='1604070'>so</span> <span m='1604210'>how</span>
  <span m='1604270'>do</span> <span m='1604360'>you</span> <span m='1604430'>compute</span>
  <span m='1604760'>elements</span> <span m='1605090'>of</span> <span m='1605150'>the</span>
  <span m='1605270'>Jacobian</span> <span m='1605870'>then?</span> <span m='1606590'>Well,</span>
  <span m='1606680'>those</span> <span m='1606890'>are</span> <span m='1606950'>all</span>
  <span m='1607070'>just</span> <span m='1607250'>partial</span> <span m='1607730'>derivatives</span>
  <span m='1608360'>of</span> <span m='1608490'>the</span> <span m='1608600'>function</span>
  <span m='1609710'>with</span> <span m='1609890'>respect</span> <span m='1610250'>to</span>
  <span m='1610370'>one</span> <span m='1610520'>of</span> <span m='1610580'>the</span>
  <span m='1610700'>unknown</span> <span m='1611060'>variables.</span> <span m='1613100'>So</span>
  <span m='1613570'>partial</span> <span m='1614000'>f i</span> <span m='1614420'>with</span>
  <span m='1614570'>respect</span> <span m='1614900'>to</span> <span m='1614990'>x
  j</span> <span m='1615550'>is</span> <span m='1615710'>just</span> <span m='1616430'>f</span>
  <span m='1616805'>i</span> <span m='1617470'>at</span> <span m='1617740'>x</span>
  <span m='1618140'>plus</span> <span m='1619400'>some</span> <span m='1619730'>epsilon</span>
  <span m='1621660'>deviation</span> <span m='1622470'>of</span> <span m='1622620'>x</span>
  <span m='1623310'>in</span> <span m='1623500'>its</span> <span m='1623720'>j-th</span>
  <span m='1624090'>component</span> <span m='1624540'>only.</span> </p><p><span m='1624830'>So</span>
  <span m='1624960'>this</span> <span m='1625170'>is</span> <span m='1625290'>like</span>
  <span m='1625470'>a</span> <span m='1625560'>unit</span> <span m='1625920'>vector</span>
  <span m='1627270'>in</span> <span m='1627480'>the</span> <span m='1627600'>j</span>
  <span m='1628020'>direction,</span> <span m='1628710'>or</span> <span m='1629220'>associated</span>
  <span m='1629730'>with</span> <span m='1629880'>the</span> <span m='1630030'>j-th</span>
  <span m='1630450'>element</span> <span m='1631560'>of</span> <span m='1631740'>this</span>
  <span m='1631950'>vector.</span> <span m='1633090'>Minus</span> <span m='1633360'>f
  i</span> <span m='1633630'>of x</span> <span m='1634440'>divided</span> <span m='1634830'>by</span>
  <span m='1635010'>this</span> <span m='1635220'>epsilon.</span> <span m='1638200'>Equivalently,</span>
  <span m='1640120'>you'd</span> <span m='1640220'>have</span> <span m='1640330'>to</span>
  <span m='1640450'>do</span> <span m='1640570'>this</span> <span m='1640750'>for</span>
  <span m='1641050'>f i.</span> <span m='1641590'>You</span> <span m='1641680'>can</span>
  <span m='1641980'>compute</span> <span m='1642370'>all</span> <span m='1642520'>the</span>
  <span m='1642610'>columns</span> <span m='1643060'>of</span> <span m='1643150'>the</span>
  <span m='1643270'>Jacobian</span> <span m='1643780'>very</span> <span m='1643990'>quickly</span>
  <span m='1644380'>by</span> <span m='1644560'>calling</span> <span m='1645100'>f</span>
  <span m='1646080'>of</span> <span m='1646270'>x</span> <span m='1646540'>plus</span>
  <span m='1646840'>epsilon</span> <span m='1648220'>minus</span> <span m='1648620'>f</span>
  <span m='1648790'>of</span> <span m='1648940'>x</span> <span m='1649330'>over</span>
  <span m='1649600'>epsilon.</span> </p><p><span m='1650260'>Just</span> <span m='1650410'>evaluate</span>
  <span m='1650890'>your</span> <span m='1650980'>vector-valued</span> <span m='1651610'>function</span>
  <span m='1652990'>at</span> <span m='1653140'>these</span> <span m='1653380'>different</span>
  <span m='1653710'>x's.</span> <span m='1654790'>Take</span> <span m='1654970'>the</span>
  <span m='1655090'>difference,</span> <span m='1655540'>and</span> <span m='1655630'>that</span>
  <span m='1655740'>will</span> <span m='1655840'>give</span> <span m='1656020'>you</span>
  <span m='1656140'>column</span> <span m='1656590'>j</span> <span m='1657890'>of</span>
  <span m='1658030'>your</span> <span m='1658120'>Jacobian.</span> <span m='1660940'>So</span>
  <span m='1661120'>how</span> <span m='1661270'>many</span> <span m='1661480'>function</span>
  <span m='1661930'>evaluations</span> <span m='1662770'>does</span> <span m='1662950'>it</span>
  <span m='1663010'>take</span> <span m='1663370'>to</span> <span m='1663490'>calculate</span>
  <span m='1663970'>the</span> <span m='1664090'>Jacobian</span> <span m='1664720'>at</span>
  <span m='1664840'>a</span> <span m='1664870'>single</span> <span m='1665200'>point?</span>
  <span m='1667610'>How</span> <span m='1667670'>many</span> <span m='1667880'>times</span>
  <span m='1668240'>do</span> <span m='1668320'>I</span> <span m='1668360'>have</span>
  <span m='1668450'>to</span> <span m='1668540'>evaluate</span> <span m='1669050'>my</span>
  <span m='1669170'>function?</span> <span m='1676492'>Yeah?</span> </p><p><span m='1678960'>AUDIENCE:</span>
  <span m='1679095'>2</span> <span m='1679230'>n.</span> </p><p><span m='1679860'>JAMES
  SWAN:</span> <span m='1680085'>2n,</span> <span m='1680310'>right.</span> <span
  m='1680550'>So</span> <span m='1680730'>if</span> <span m='1680850'>I</span> <span
  m='1680940'>have</span> <span m='1681420'>n,</span> <span m='1682890'>if</span>
  <span m='1683040'>I</span> <span m='1683160'>have</span> <span m='1683430'>n</span>
  <span m='1683970'>elements</span> <span m='1684540'>to</span> <span m='1684660'>x,</span>
  <span m='1685530'>I've</span> <span m='1685650'>got</span> <span m='1685740'>to</span>
  <span m='1685830'>make</span> <span m='1686040'>two</span> <span m='1686400'>function</span>
  <span m='1686970'>calls</span> <span m='1688260'>per</span> <span m='1688590'>column</span>
  <span m='1688690'>of</span> <span m='1689010'>j.</span> <span m='1689740'>There's</span>
  <span m='1689880'>going</span> <span m='1690000'>to</span> <span m='1690060'>be
  n</span> <span m='1690300'>columns</span> <span m='1690750'>in</span> <span m='1690840'>j.</span>
  <span m='1691986'>So</span> <span m='1692370'>2n</span> <span m='1693060'>function</span>
  <span m='1693480'>evaluations</span> <span m='1694860'>to</span> <span m='1694980'>compute</span>
  <span m='1695310'>the</span> <span m='1695400'>Jacobian</span> <span m='1695910'>at</span>
  <span m='1696000'>a</span> <span m='1696060'>single</span> <span m='1696360'>point.</span>
  <span m='1697290'>Is</span> <span m='1697380'>that</span> <span m='1697470'>really</span>
  <span m='1697710'>true</span> <span m='1697920'>though?</span> </p><p><span m='1698520'>Not</span>
  <span m='1698670'>quite.</span> <span m='1699510'>f</span> <span m='1699720'>of</span>
  <span m='1699840'>x</span> <span m='1700170'>is</span> <span m='1700440'>f</span>
  <span m='1700650'>of</span> <span m='1700770'>x.</span> <span m='1701560'>I</span>
  <span m='1701590'>don't</span> <span m='1701670'>have</span> <span m='1701760'>to</span>
  <span m='1701850'>compute</span> <span m='1702180'>it</span> <span m='1702270'>every</span>
  <span m='1702510'>time.</span> <span m='1702790'>I just</span> <span m='1702930'>compute</span>
  <span m='1703230'>f</span> <span m='1703410'>of</span> <span m='1703530'>x</span>
  <span m='1703740'>once.</span> <span m='1705090'>So</span> <span m='1705210'>it's</span>
  <span m='1705300'>really</span> <span m='1705540'>like</span> <span m='1705780'>n</span>
  <span m='1705990'>plus</span> <span m='1706290'>1</span> <span m='1707340'>that</span>
  <span m='1707460'>I</span> <span m='1707520'>have</span> <span m='1707700'>to</span>
  <span m='1707820'>do,</span> <span m='1708180'>right?</span> <span m='1708460'>N</span>
  <span m='1708660'>plus</span> <span m='1708930'>a</span> <span m='1709140'>function</span>
  <span m='1709470'>evaluations</span> <span m='1710160'>to</span> <span m='1710250'>compute</span>
  <span m='1710630'>this</span> <span m='1710840'>thing.</span> <span m='1711942'>I</span>
  <span m='1712340'>actually</span> <span m='1712690'>got</span> <span m='1712780'>to</span>
  <span m='1712900'>compute</span> <span m='1713290'>them</span> <span m='1713500'>though.</span>
  <span m='1713710'>Function</span> <span m='1714070'>evaluations</span> <span m='1715200'>may</span>
  <span m='1715330'>be</span> <span m='1715450'>really</span> <span m='1715720'>expensive.</span>
  </p><p><span m='1717070'>Suppose</span> <span m='1717340'>you're</span> <span m='1717460'>doing</span>
  <span m='1717730'>some</span> <span m='1718030'>sort</span> <span m='1718240'>of</span>
  <span m='1719200'>complicated</span> <span m='1719830'>simulation,</span> <span
  m='1720250'>like</span> <span m='1720370'>a</span> <span m='1720430'>finite</span>
  <span m='1720790'>element</span> <span m='1721100'>simulation.</span> <span m='1721510'>Maybe</span>
  <span m='1721720'>it takes</span> <span m='1721990'>minutes</span> <span m='1722710'>to</span>
  <span m='1722830'>generate</span> <span m='1723190'>a</span> <span m='1723250'>function</span>
  <span m='1723610'>evaluation.</span> <span m='1724980'>So</span> <span m='1725140'>it
  can</span> <span m='1725220'>be</span> <span m='1725320'>expensive</span> <span
  m='1725890'>to</span> <span m='1726010'>compute</span> <span m='1726340'>the</span>
  <span m='1726400'>Jacobian</span> <span m='1727020'>in</span> <span m='1727150'>this</span>
  <span m='1727330'>way.</span> <span m='1728110'>Just</span> <span m='1728290'>be</span>
  <span m='1728440'>expensive</span> <span m='1728830'>to</span> <span m='1728920'>compute</span>
  <span m='1729220'>the</span> <span m='1729310'>Jacobian.</span> <span m='1731500'>How</span>
  <span m='1732250'>is</span> <span m='1732520'>approximation</span> <span m='1733120'>of</span>
  <span m='1733180'>Jacobian</span> <span m='1733660'>going</span> <span m='1733780'>to</span>
  <span m='1733850'>affect</span> <span m='1734140'>the</span> <span m='1734260'>convergence?</span>
  </p><p><span m='1738560'>What's</span> <span m='1738710'>going</span> <span m='1738830'>to</span>
  <span m='1738890'>happen</span> <span m='1739130'>to</span> <span m='1739220'>the</span>
  <span m='1739310'>rate</span> <span m='1739550'>of</span> <span m='1739640'>convergence</span>
  <span m='1740330'>of</span> <span m='1740480'>our</span> <span m='1740600'>method?</span>
  <span m='1742160'>It's</span> <span m='1742250'>going</span> <span m='1742430'>to</span>
  <span m='1743480'>go</span> <span m='1743600'>down,</span> <span m='1744380'>right?</span>
  <span m='1744890'>It's</span> <span m='1745100'>probably not</span> <span m='1745220'>going</span>
  <span m='1745340'>to</span> <span m='1745400'>be</span> <span m='1745730'>linear.</span>
  <span m='1747200'>It's</span> <span m='1747300'>not</span> <span m='1747320'>going</span>
  <span m='1747440'>to</span> <span m='1747500'>be</span> <span m='1747560'>quadratic.</span>
  <span m='1748250'>It's</span> <span m='1748340'>going</span> <span m='1748460'>to</span>
  <span m='1748520'>be</span> <span m='1748610'>some</span> <span m='1748790'>super</span>
  <span m='1749120'>linear</span> <span m='1749540'>factor.</span> </p><p><span m='1750230'>It's</span>
  <span m='1750320'>going</span> <span m='1750440'>to</span> <span m='1750500'>depend</span>
  <span m='1750800'>on</span> <span m='1750920'>how</span> <span m='1751160'>accurate</span>
  <span m='1751580'>the</span> <span m='1751670'>Jacobian</span> <span m='1752150'>is.</span>
  <span m='1752450'>How</span> <span m='1752630'>sensitive</span> <span m='1753530'>the</span>
  <span m='1753650'>function</span> <span m='1754190'>is</span> <span m='1755630'>near</span>
  <span m='1756140'>the</span> <span m='1756290'>root.</span> <span m='1757960'>But</span>
  <span m='1758090'>it's</span> <span m='1758210'>going</span> <span m='1758330'>to</span>
  <span m='1758390'>reduce</span> <span m='1759440'>the</span> <span m='1759980'>accuracy</span>
  <span m='1760530'>of</span> <span m='1760580'>the</span> <span m='1760670'>method,</span>
  <span m='1760940'>or</span> <span m='1761060'>the</span> <span m='1761180'>convergence</span>
  <span m='1761690'>rate</span> <span m='1761870'>of</span> <span m='1761930'>the</span>
  <span m='1762020'>method</span> <span m='1762320'>by</span> <span m='1762500'>a</span>
  <span m='1762530'>little</span> <span m='1762770'>bit.</span> <span m='1763880'>That's</span>
  <span m='1764090'>OK.</span> </p><p><span m='1765230'>So</span> <span m='1765290'>this</span>
  <span m='1765440'>is</span> <span m='1765530'>what</span> <span m='1765650'>MATLAB</span>
  <span m='1766040'>does.</span> <span m='1767330'>It</span> <span m='1767420'>uses</span>
  <span m='1767720'>a</span> <span m='1767780'>finite</span> <span m='1768110'>difference</span>
  <span m='1768410'>approximation</span> <span m='1769460'>for</span> <span m='1769650'>your</span>
  <span m='1769730'>Jacobian.</span> <span m='1770270'>When</span> <span m='1770390'>you</span>
  <span m='1770480'>give</span> <span m='1770660'>it</span> <span m='1770720'>a</span>
  <span m='1770780'>function,</span> <span m='1771290'>and</span> <span m='1771380'>you</span>
  <span m='1771470'>don't</span> <span m='1771650'>tell</span> <span m='1771880'>it</span>
  <span m='1771950'>the</span> <span m='1772040'>Jacobian</span> <span m='1772550'>explicitly.</span>
  <span m='1775990'>Here's</span> <span m='1776170'>an</span> <span m='1776260'>example</span>
  <span m='1776800'>of</span> <span m='1776920'>how</span> <span m='1777010'>to</span>
  <span m='1777190'>implement</span> <span m='1777640'>this</span> <span m='1777820'>yourself.</span>
  <span m='1779530'>So</span> <span m='1779650'>I've</span> <span m='1779710'>got</span>
  <span m='1779800'>to</span> <span m='1779860'>have</span> <span m='1779950'>some</span>
  <span m='1780130'>function</span> <span m='1780670'>that</span> <span m='1780820'>does</span>
  <span m='1781330'>whatever</span> <span m='1781630'>this</span> <span m='1781750'>function</span>
  <span m='1782110'>is</span> <span m='1782170'>supposed</span> <span m='1782440'>to</span>
  <span m='1782500'>do.</span> </p><p><span m='1782650'>It takes</span> <span m='1782890'>as</span>
  <span m='1783010'>input</span> <span m='1783340'>x</span> <span m='1783670'>and</span>
  <span m='1783760'>it</span> <span m='1783820'>gives</span> <span m='1784030'>an</span>
  <span m='1784120'>output</span> <span m='1784550'>f.</span> <span m='1785402'>And</span>
  <span m='1785830'>then</span> <span m='1785980'>the</span> <span m='1786070'>Jacobian,</span>
  <span m='1787180'>right?</span> <span m='1787480'>It's</span> <span m='1787970'>a</span>
  <span m='1788020'>matrix.</span> <span m='1788740'>So</span> <span m='1789120'>we</span>
  <span m='1789270'>initialize</span> <span m='1789790'>this</span> <span m='1789940'>matrix.</span>
  <span m='1790990'>We</span> <span m='1791140'>loop</span> <span m='1791440'>over</span>
  <span m='1791710'>each</span> <span m='1791890'>of</span> <span m='1791950'>the</span>
  <span m='1792040'>columns.</span> <span m='1793990'>We</span> <span m='1794080'>compute</span>
  <span m='1794560'>the</span> <span m='1794740'>displacement</span> <span m='1796600'>right?</span>
  <span m='1797350'>The</span> <span m='1797470'>deviation</span> <span m='1798670'>from</span>
  <span m='1798940'>x</span> <span m='1799330'>for</span> <span m='1799480'>each</span>
  <span m='1799690'>of</span> <span m='1799750'>these.</span> <span m='1800870'>And</span>
  <span m='1800970'>then</span> <span m='1801070'>we</span> <span m='1801100'>compute</span>
  <span m='1801470'>this</span> <span m='1801610'>difference</span> <span m='1801970'>and</span>
  <span m='1802090'>divide</span> <span m='1802350'>it</span> <span m='1802420'>by</span>
  <span m='1802990'>epsilon.</span> </p><p><span m='1805150'>I</span> <span m='1805230'>haven't</span>
  <span m='1805520'>done</span> <span m='1805630'>everything</span> <span m='1805960'>perfect</span>
  <span m='1806370'>here, right?</span> <span m='1806590'>Here's</span> <span m='1806800'>an</span>
  <span m='1806890'>extra</span> <span m='1807190'>function</span> <span m='1807580'>evaluation.</span>
  <span m='1808150'>I</span> <span m='1808210'>could</span> <span m='1808300'>just</span>
  <span m='1808420'>calculate</span> <span m='1809410'>the</span> <span m='1809500'>value</span>
  <span m='1809830'>of</span> <span m='1809890'>the</span> <span m='1810010'>function</span>
  <span m='1810400'>at</span> <span m='1810500'>x</span> <span m='1810700'>before</span>
  <span m='1811030'>doing</span> <span m='1811300'>the</span> <span m='1811390'>loop.</span>
  <span m='1812486'>I've</span> <span m='1812870'>also</span> <span m='1813070'>only</span>
  <span m='1813310'>used</span> <span m='1813460'>a</span> <span m='1813550'>relative</span>
  <span m='1813970'>tolerance</span> <span m='1814420'>here.</span> <span m='1814570'>I'm</span>
  <span m='1814630'>going</span> <span m='1814750'>to</span> <span m='1814810'>be</span>
  <span m='1814900'>in</span> <span m='1814990'>trouble</span> <span m='1815440'>if</span>
  <span m='1815580'>xi</span> <span m='1815710'>is</span> <span m='1816070'>0.</span>
  <span m='1816640'>It's</span> <span m='1817060'>going</span> <span m='1817180'>to</span>
  <span m='1817240'>be</span> <span m='1817300'>a</span> <span m='1817360'>problem</span>
  <span m='1817600'>with</span> <span m='1817750'>this</span> <span m='1817900'>algorithm.</span>
  </p><p><span m='1818350'>These</span> <span m='1818530'>are</span> <span m='1818590'>the</span>
  <span m='1818710'>little</span> <span m='1819400'>details</span> <span m='1820060'>one</span>
  <span m='1820270'>has</span> <span m='1820480'>to</span> <span m='1820600'>pay</span>
  <span m='1820750'>attention</span> <span m='1821260'>to.</span> <span m='1822620'>But</span>
  <span m='1823030'>it's</span> <span m='1823150'>a</span> <span m='1823180'>simple</span>
  <span m='1823480'>enough</span> <span m='1823660'>calculation</span> <span m='1824230'>to</span>
  <span m='1824360'>do.</span> <span m='1824560'>Loop</span> <span m='1824830'>over</span>
  <span m='1824980'>the</span> <span m='1825070'>columns,</span> <span m='1825510'>right?</span>
  <span m='1825850'>Compute</span> <span m='1826180'>these</span> <span m='1826360'>differences.</span>
  <span m='1827290'>Divide</span> <span m='1827620'>by</span> <span m='1827770'>epsilon.</span>
  <span m='1828130'>You</span> <span m='1828220'>have</span> <span m='1828370'>your</span>
  <span m='1828460'>approximation</span> <span m='1829120'>for the</span> <span m='1829300'>Jacobian.</span>
  <span m='1830980'>I've</span> <span m='1831040'>got</span> <span m='1831130'>to</span>
  <span m='1831220'>do</span> <span m='1831370'>that</span> <span m='1831580'>at</span>
  <span m='1832090'>every</span> <span m='1832630'>iteration,</span> <span m='1833530'>right?</span>
  <span m='1833890'>Every</span> <span m='1834100'>time</span> <span m='1834400'>x</span>
  <span m='1834660'>is</span> <span m='1834820'>updated,</span> <span m='1835330'>I've</span>
  <span m='1835420'>got</span> <span m='1835540'>to</span> <span m='1835600'>recompute</span>
  <span m='1836200'>my</span> <span m='1836350'>Jacobian.</span> <span m='1840830'>That's</span>
  <span m='1840980'>it</span> <span m='1841070'>though.</span> </p><p><span m='1841470'>All</span>
  <span m='1841540'>right,</span> <span m='1841700'>that's</span> <span m='1841880'>one</span>
  <span m='1842060'>way</span> <span m='1842210'>of</span> <span m='1842330'>approximating</span>
  <span m='1842900'>a</span> <span m='1842990'>Jacobian.</span> <span m='1844310'>There</span>
  <span m='1844760'>s</span> <span m='1844880'>a</span> <span m='1844940'>method</span>
  <span m='1845180'>that's</span> <span m='1845330'>used</span> <span m='1845570'>in</span>
  <span m='1845690'>one</span> <span m='1845870'>dimension</span> <span m='1846680'>called</span>
  <span m='1846830'>the</span> <span m='1846920'>Secant</span> <span m='1847370'>method.</span>
  <span m='1849380'>It's</span> <span m='1849620'>a</span> <span m='1849800'>special</span>
  <span m='1850190'>case</span> <span m='1850430'>of</span> <span m='1850490'>the</span>
  <span m='1850610'>Newton-Raphson</span> <span m='1851180'>method</span> <span m='1851570'>and
  uses</span> <span m='1851900'>a</span> <span m='1852060'>coarser</span> <span m='1852590'>approximation</span>
  <span m='1853370'>for</span> <span m='1853520'>the</span> <span m='1853640'>derivative.</span>
  <span m='1854090'>It</span> <span m='1854150'>says,</span> <span m='1855140'>I</span>
  <span m='1855210'>was</span> <span m='1855360'>taking</span> <span m='1855650'>these</span>
  <span m='1855770'>steps</span> <span m='1856880'>from</span> <span m='1857150'>xi</span>
  <span m='1857600'>minus</span> <span m='1858020'>1</span> <span m='1858440'>to</span>
  <span m='1858840'>xi.</span> <span m='1859600'>And</span> <span m='1859730'>I</span>
  <span m='1859790'>knew</span> <span m='1859940'>the</span> <span m='1860060'>function</span>
  <span m='1860510'>values</span> <span m='1860990'>there.</span> </p><p><span m='1861200'>Maybe</span>
  <span m='1861860'>I</span> <span m='1861980'>should</span> <span m='1862130'>just</span>
  <span m='1862790'>compute</span> <span m='1863090'>the</span> <span m='1863180'>slope</span>
  <span m='1863510'>of</span> <span m='1863570'>the</span> <span m='1863660'>line</span>
  <span m='1864050'>that</span> <span m='1864140'>goes</span> <span m='1864350'>through</span>
  <span m='1864500'>those</span> <span m='1864710'>points,</span> <span m='1865130'>and</span>
  <span m='1865220'>say,</span> <span m='1865400'>that's</span> <span m='1866420'>my</span>
  <span m='1866570'>approximation</span> <span m='1867260'>for</span> <span m='1867380'>the</span>
  <span m='1867500'>derivative.</span> <span m='1868050'>Why not?</span> <span m='1868190'>I</span>
  <span m='1868370'>have</span> <span m='1868550'>the</span> <span m='1868640'>data</span>
  <span m='1868970'>available</span> <span m='1869420'>to</span> <span m='1869570'>me.</span>
  <span m='1870020'>It</span> <span m='1870230'>seems</span> <span m='1870470'>like</span>
  <span m='1870620'>a</span> <span m='1870680'>sensible</span> <span m='1871070'>thing</span>
  <span m='1871280'>to</span> <span m='1871400'>do.</span> <span m='1872420'>So</span>
  <span m='1872550'>we</span> <span m='1872750'>replace</span> <span m='1874040'>f
  prime</span> <span m='1874460'>at</span> <span m='1874550'>x1</span> <span m='1875090'>with</span>
  <span m='1875420'>f</span> <span m='1875630'>of</span> <span m='1875750'>xi</span>
  <span m='1876260'>minus</span> <span m='1877100'>f of</span> <span m='1877220'>x</span>
  <span m='1877380'>i</span> <span m='1877610'>minus</span> <span m='1877910'>1.</span>
  </p><p><span m='1880590'>Down</span> <span m='1880880'>here</span> <span m='1881260'>we</span>
  <span m='1881380'>put</span> <span m='1881570'>xi</span> <span m='1881885'>minus</span>
  <span m='1882200'>xi</span> <span m='1882730'>minus</span> <span m='1883060'>1</span>
  <span m='1883465'>up</span> <span m='1883870'>here.</span> <span m='1884140'>That's</span>
  <span m='1884350'>our</span> <span m='1884440'>approximation</span> <span m='1885130'>for</span>
  <span m='1885280'>the</span> <span m='1885400'>derivative,</span> <span m='1885910'>or</span>
  <span m='1886030'>the</span> <span m='1886240'>inverse</span> <span m='1886630'>of</span>
  <span m='1886750'>the</span> <span m='1886840'>derivative.</span> <span m='1888010'>This</span>
  <span m='1888160'>can</span> <span m='1888340'>work,</span> <span m='1888790'>it</span>
  <span m='1888950'>can</span> <span m='1889090'>work</span> <span m='1889210'>just</span>
  <span m='1889390'>fine.</span> <span m='1891460'>Can</span> <span m='1891550'>it</span>
  <span m='1891600'>be</span> <span m='1891700'>extended</span> <span m='1892150'>to</span>
  <span m='1892240'>many</span> <span m='1892450'>dimensions?</span> <span m='1893050'>That's</span>
  <span m='1893230'>an</span> <span m='1893350'>interesting</span> <span m='1893950'>question,</span>
  <span m='1894620'>though?</span> <span m='1894700'>This</span> <span m='1894910'>is</span>
  <span m='1895000'>simple.</span> <span m='1895870'>In</span> <span m='1895960'>many</span>
  <span m='1896200'>dimensions,</span> <span m='1896750'>not</span> <span m='1896770'>so</span>
  <span m='1896950'>obvious</span> <span m='1897490'>right?</span> </p><p><span m='1897880'>If</span>
  <span m='1898030'>I</span> <span m='1898090'>know</span> <span m='1898555'>xi,</span>
  <span m='1899140'>xi</span> <span m='1899470'>minus</span> <span m='1899830'>1.</span>
  <span m='1900130'>f</span> <span m='1900430'>of</span> <span m='1900580'>xi,</span>
  <span m='1900820'>f</span> <span m='1901600'>of</span> <span m='1901720'>si</span>
  <span m='1902050'>minus</span> <span m='1902380'>1. Can</span> <span m='1902770'>I</span>
  <span m='1902890'>approximate</span> <span m='1905160'>the</span> <span m='1905250'>Jacobian?</span>
  <span m='1906930'>What</span> <span m='1907020'>do</span> <span m='1907110'>you</span>
  <span m='1907170'>think?</span> <span m='1915190'>Does</span> <span m='1915310'>it</span>
  <span m='1915450'>strike</span> <span m='1915730'>you</span> <span m='1916060'>as</span>
  <span m='1916230'>though</span> <span m='1916360'>there</span> <span m='1916450'>might</span>
  <span m='1916600'>be</span> <span m='1916720'>some</span> <span m='1916900'>fundamental</span>
  <span m='1917500'>difficulty</span> <span m='1918050'>to</span> <span m='1918220'>doing</span>
  <span m='1918911'>that?</span> <span m='1929713'>Yeah?</span> </p><p><span m='1930204'>AUDIENCE:</span>
  <span m='1930530'>Could you</span> <span m='1930695'>approximate</span> <span m='1931186'>the</span>
  <span m='1931677'>gradient?</span> <span m='1932659'>[INAUDIBLE]</span> <span m='1934623'>gradient</span>
  <span m='1935114'>of</span> <span m='1935605'>f</span> <span m='1936096'>at</span>
  <span m='1936587'>x.</span> </p><p><span m='1939533'>JAMES SWAN:</span> <span m='1940040'>OK.</span>
  </p><p><span m='1940855'>AUDIENCE:</span> <span m='1941320'>But</span> <span m='1941785'>I'm</span>
  <span m='1942250'>sure</span> <span m='1942715'>if you</span> <span m='1943650'>whether
  you</span> <span m='1944015'>can</span> <span m='1944380'>go</span> <span m='1944750'>backwards</span>
  <span m='1945020'>from</span> <span m='1945290'>the</span> <span m='1945560'>gradient</span>
  <span m='1945950'>in the</span> <span m='1946446'>Jacobian.</span> </p><p><span
  m='1947440'>JAMES SWAN:</span> <span m='1947585'>OK.</span> <span m='1949160'>So,</span>
  <span m='1949670'>let's--</span> <span m='1950380'>go</span> <span m='1950940'>ahead.</span>
  </p><p><span m='1951656'>AUDIENCE:</span> <span m='1952112'>Perhaps</span> <span
  m='1952570'>the</span> <span m='1953060'>difficulty is,</span> <span m='1953550'>I
  mean</span> <span m='1953820'>when</span> <span m='1953970'>they're</span> <span
  m='1954210'>just</span> <span m='1954430'>single</span> <span m='1954815'>values--</span>
  </p><p><span m='1955200'>JAMES SWAN:</span> <span m='1955305'>Yeah.</span> </p><p><span
  m='1955410'>AUDIENCE:</span> <span m='1955557'>You</span> <span m='1955704'>can</span>
  <span m='1955852'>think</span> <span m='1956294'>of</span> <span m='1956736'>[INAUDIBLE]</span>
  <span m='1957620'>derivative, right?</span> </p><p><span m='1958062'>JAMES SWAN:</span>
  <span m='1958504'>Yeah.</span> </p><p><span m='1959190'>AUDIENCE:</span> <span m='1959575'>[INAUDIBLE]</span>
  <span m='1960620'>get</span> <span m='1961020'>really</span> <span m='1961240'>big,</span>
  <span m='1961550'>you get</span> <span m='1961860'>a</span> <span m='1962115'>vector</span>
  <span m='1962370'>of</span> <span m='1962840'>a function</span> <span m='1963310'>at</span>
  <span m='1963730'>xi,</span> <span m='1964190'>a</span> <span m='1964600'>vector</span>
  <span m='1965048'>of a</span> <span m='1965496'>function of</span> <span m='1965944'>xi
  minus</span> <span m='1966392'>1</span> <span m='1966840'>or whatever.</span> <span
  m='1967290'>Vectors</span> <span m='1967580'>of</span> <span m='1967870'>these</span>
  <span m='1968490'>x's.</span> <span m='1969343'>And</span> <span m='1969706'>so
  if</span> <span m='1970070'>you're</span> <span m='1970856'>[INAUDIBLE]</span> </p><p><span
  m='1973040'>JAMES SWAN:</span> <span m='1973115'>Yeah,</span> <span m='1973190'>so
  how</span> <span m='1973590'>do</span> <span m='1973710'>I</span> <span m='1973770'>divide</span>
  <span m='1974100'>these</span> <span m='1974280'>things?</span> <span m='1974460'>That's</span>
  <span m='1974610'>a</span> <span m='1974640'>good</span> <span m='1974760'>question.</span>
  <span m='1975430'>The</span> <span m='1975530'>Jacobian--</span> <span m='1976260'>how</span>
  <span m='1976800'>much</span> <span m='1977040'>information</span> <span m='1977670'>content</span>
  <span m='1978210'>is</span> <span m='1978510'>in</span> <span m='1978750'>the</span>
  <span m='1978840'>Jacobian?</span> <span m='1979470'>Or</span> <span m='1980130'>how</span>
  <span m='1980250'>many</span> <span m='1980520'>independent</span> <span m='1980940'>quantities</span>
  <span m='1981690'>are</span> <span m='1982960'>built</span> <span m='1983200'>into</span>
  <span m='1983380'>the</span> <span m='1983470'>Jacobian?</span> </p><p><span m='1984010'>AUDIENCE:</span>
  <span m='1984460'>[INAUDIBLE]</span> </p><p><span m='1985360'>JAMES SWAN:</span>
  <span m='1985450'>And</span> <span m='1985810'>squared.</span> <span m='1986440'>And</span>
  <span m='1986710'>how</span> <span m='1986860'>much</span> <span m='1987400'>data</span>
  <span m='1987820'>do</span> <span m='1988030'>I</span> <span m='1988090'>have</span>
  <span m='1988360'>to</span> <span m='1988540'>work</span> <span m='1988810'>with</span>
  <span m='1989080'>here?</span> <span m='1990160'>You</span> <span m='1990310'>know,</span>
  <span m='1990570'>order</span> <span m='1990910'>n</span> <span m='1991150'>data.</span>
  <span m='1991870'>To</span> <span m='1991990'>figure</span> <span m='1992230'>out</span>
  <span m='1992350'>order</span> <span m='1992680'>n</span> <span m='1992890'>squared</span>
  <span m='1994000'>quantities.</span> <span m='1994540'>This</span> <span m='1994720'>is</span>
  <span m='1994840'>the</span> <span m='1994960'>division</span> <span m='1995350'>problem</span>
  <span m='1995670'>you're</span> <span m='1995770'>describing,</span> <span m='1996340'>right?</span>
  <span m='1996490'>So</span> <span m='1996580'>it</span> <span m='1996630'>seems</span>
  <span m='1996910'>like</span> <span m='1997120'>this</span> <span m='1997360'>is</span>
  <span m='1997720'>an</span> <span m='1997960'>underdetermined</span> <span m='1999130'>sort</span>
  <span m='1999400'>of</span> <span m='1999580'>problem.</span> <span m='2000040'>And</span>
  <span m='2000170'>it</span> <span m='2000300'>is.</span> <span m='2000910'>OK?</span>
  </p><p><span m='2001740'>So</span> <span m='2001860'>there</span> <span m='2002010'>isn't</span>
  <span m='2002280'>a</span> <span m='2002370'>direct</span> <span m='2003570'>analog</span>
  <span m='2004230'>to</span> <span m='2004350'>the</span> <span m='2004470'>Secant</span>
  <span m='2004830'>method</span> <span m='2005830'>in</span> <span m='2006330'>dimensions.</span>
  <span m='2007110'>We</span> <span m='2007260'>can</span> <span m='2007470'>write</span>
  <span m='2007860'>down</span> <span m='2009630'>something</span> <span m='2010170'>that</span>
  <span m='2010530'>makes</span> <span m='2010740'>sense.</span> <span m='2011090'>So</span>
  <span m='2011130'>this</span> <span m='2011310'>is</span> <span m='2011400'>the</span>
  <span m='2011520'>1D</span> <span m='2011700'>Secant</span> <span m='2012180'>approximation.</span>
  <span m='2012990'>That</span> <span m='2013200'>the</span> <span m='2013320'>value</span>
  <span m='2013740'>of</span> <span m='2013830'>the</span> <span m='2013950'>derivative</span>
  <span m='2015030'>multiplied</span> <span m='2015810'>by</span> <span m='2016060'>the</span>
  <span m='2016200'>step</span> <span m='2016950'>between</span> <span m='2017250'>i</span>
  <span m='2017550'>minus</span> <span m='2017940'>1</span> <span m='2018150'>and</span>
  <span m='2018300'>i</span> <span m='2018750'>is</span> <span m='2018900'>approximated</span>
  <span m='2019590'>by</span> <span m='2020430'>the</span> <span m='2020490'>difference</span>
  <span m='2020820'>in</span> <span m='2020910'>the</span> <span m='2020970'>values</span>
  <span m='2021330'>of</span> <span m='2021390'>the</span> <span m='2021480'>function.</span>
  </p><p><span m='2023840'>The</span> <span m='2023960'>equivalent</span> <span m='2024560'>is</span>
  <span m='2024890'>the</span> <span m='2024980'>value</span> <span m='2025340'>of</span>
  <span m='2025460'>the</span> <span m='2025550'>Jacobian</span> <span m='2026510'>multiplied</span>
  <span m='2027110'>by</span> <span m='2027260'>the</span> <span m='2027350'>step</span>
  <span m='2027770'>between</span> <span m='2028250'>i minus</span> <span m='2028550'>1</span>
  <span m='2028730'>and</span> <span m='2028760'>i</span> <span m='2029120'>is</span>
  <span m='2029240'>equal</span> <span m='2029570'>to</span> <span m='2030470'>the</span>
  <span m='2030590'>difference</span> <span m='2031220'>between</span> <span m='2031550'>the</span>
  <span m='2031640'>values</span> <span m='2031970'>of</span> <span m='2032030'>the</span>
  <span m='2032120'>functions.</span> <span m='2034220'>But</span> <span m='2034320'>now</span>
  <span m='2034430'>this</span> <span m='2034670'>is</span> <span m='2034850'>an</span>
  <span m='2034940'>equation</span> <span m='2035540'>for</span> <span m='2036620'>n</span>
  <span m='2037000'>squared</span> <span m='2037610'>elements</span> <span m='2038060'>of</span>
  <span m='2038180'>the</span> <span m='2038270'>Jacobian,</span> <span m='2040260'>in</span>
  <span m='2040490'>terms</span> <span m='2040910'>of</span> <span m='2041220'>n</span>
  <span m='2041420'>elements</span> <span m='2041840'>of</span> <span m='2041900'>the</span>
  <span m='2041990'>function,</span> <span m='2043150'>right?</span> <span m='2043700'>So</span>
  <span m='2043880'>it's</span> <span m='2044420'>massively,</span> <span m='2046080'>massively</span>
  <span m='2046580'>underdetermined.</span> <span m='2047690'>OK?</span> </p><p><span
  m='2050469'>Here</span> <span m='2050710'>we</span> <span m='2050770'>have</span>
  <span m='2050860'>an</span> <span m='2050949'>equation</span> <span m='2051400'>for--</span>
  <span m='2052120'>we</span> <span m='2052210'>have</span> <span m='2052330'>one</span>
  <span m='2052510'>equation</span> <span m='2053199'>for</span> <span m='2053380'>one</span>
  <span m='2053630'>unknown.</span> <span m='2054280'>The</span> <span m='2054370'>derivative,</span>
  <span m='2055150'>right?</span> <span m='2055659'>Think</span> <span m='2055810'>about</span>
  <span m='2055989'>how</span> <span m='2056170'>it</span> <span m='2056250'>was</span>
  <span m='2056380'>moving</span> <span m='2056710'>through</span> <span m='2056920'>space</span>
  <span m='2057370'>before,</span> <span m='2057730'>right?</span> <span m='2058420'>The</span>
  <span m='2058510'>difference</span> <span m='2058870'>here,</span> <span m='2059090'>xi</span>
  <span m='2059860'>minus</span> <span m='2060159'>1,</span> <span m='2060519'>that's</span>
  <span m='2061600'>some</span> <span m='2061780'>sort</span> <span m='2061929'>of</span>
  <span m='2062199'>linear</span> <span m='2062650'>path</span> <span m='2064120'>that</span>
  <span m='2064260'>I'm</span> <span m='2064330'>moving</span> <span m='2064780'>along</span>
  <span m='2065170'>through</span> <span m='2065440'>space.</span> <span m='2066469'>How</span>
  <span m='2066730'>am</span> <span m='2066790'>I</span> <span m='2066850'>supposed</span>
  <span m='2067120'>to</span> <span m='2067210'>figure</span> <span m='2067570'>out</span>
  <span m='2068530'>what</span> <span m='2068889'>the</span> <span m='2069040'>tangent</span>
  <span m='2069580'>curves</span> <span m='2070150'>to</span> <span m='2070239'>all</span>
  <span m='2070420'>these</span> <span m='2070600'>functions</span> <span m='2071139'>are</span>
  <span m='2071320'>from</span> <span m='2071620'>this</span> <span m='2071830'>linear</span>
  <span m='2072250'>path</span> <span m='2072699'>through</span> <span m='2072920'>multidimensional</span>
  <span m='2073659'>space,</span> <span m='2073969'>right?</span> <span m='2074139'>That's</span>
  <span m='2074290'>not</span> <span m='2074380'>going</span> <span m='2074530'>to</span>
  <span m='2074590'>work.</span> </p><p><span m='2077260'>So</span> <span m='2077739'>there's</span>
  <span m='2077989'>underdetermined</span> <span m='2078560'>problems.</span> <span
  m='2078840'>It's</span> <span m='2078960'>not</span> <span m='2079110'>so--</span>
  <span m='2079409'>that's</span> <span m='2079590'>not</span> <span m='2079710'>so</span>
  <span m='2079830'>bad,</span> <span m='2080100'>actually.</span> <span m='2080929'>Right?</span>
  <span m='2081420'>Doesn't</span> <span m='2081600'>mean</span> <span m='2081719'>there's</span>
  <span m='2081870'>no</span> <span m='2082080'>solution.</span> <span m='2082719'>In</span>
  <span m='2082820'>fact,</span> <span m='2083020'>it</span> <span m='2083120'>means</span>
  <span m='2083250'>there's</span> <span m='2083429'>all</span> <span m='2083540'>a</span>
  <span m='2083600'>lot</span> <span m='2083909'>of</span> <span m='2084000'>solutions.</span>
  <span m='2084690'>So</span> <span m='2084750'>we</span> <span m='2084840'>can</span>
  <span m='2084989'>pick</span> <span m='2086370'>whichever</span> <span m='2086730'>one</span>
  <span m='2086880'>we</span> <span m='2086969'>think</span> <span m='2087150'>is</span>
  <span m='2087239'>suitable.</span> <span m='2087630'>And</span> <span m='2087870'>Broyden's</span>
  <span m='2088080'>method</span> <span m='2089219'>is</span> <span m='2089340'>a</span>
  <span m='2089400'>method</span> <span m='2089610'>for</span> <span m='2089760'>picking</span>
  <span m='2090179'>one</span> <span m='2090480'>of</span> <span m='2090600'>these</span>
  <span m='2090810'>potential</span> <span m='2091260'>solutions</span> <span m='2091860'>to</span>
  <span m='2091920'>this</span> <span m='2092100'>underdetermined</span> <span m='2092730'>problem.</span>
  </p><p><span m='2093540'>We</span> <span m='2093659'>don't</span> <span m='2093750'>have</span>
  <span m='2093840'>enough</span> <span m='2094050'>information</span> <span m='2094560'>to</span>
  <span m='2094620'>calculate</span> <span m='2095820'>the</span> <span m='2096210'>Jacobian</span>
  <span m='2096780'>exactly.</span> <span m='2097710'>But</span> <span m='2097830'>maybe</span>
  <span m='2098010'>we</span> <span m='2098130'>can</span> <span m='2098310'>construct</span>
  <span m='2098850'>a</span> <span m='2098880'>suitable</span> <span m='2099270'>approximation</span>
  <span m='2100020'>for</span> <span m='2100200'>it.</span> <span m='2101380'>And</span>
  <span m='2101430'>here's</span> <span m='2101790'>what's</span> <span m='2102060'>done.</span>
  <span m='2104200'>So</span> <span m='2104280'>here's</span> <span m='2104760'>the</span>
  <span m='2104880'>Secant</span> <span m='2105270'>approximation.</span> <span m='2106890'>It</span>
  <span m='2106980'>says</span> <span m='2107190'>the</span> <span m='2107280'>Jacobian</span>
  <span m='2107730'>times</span> <span m='2108240'>the</span> <span m='2108390'>step</span>
  <span m='2108750'>size,</span> <span m='2109290'>or</span> <span m='2109350'>the</span>
  <span m='2109470'>Newton-Raphson</span> <span m='2110100'>step,</span> <span m='2110480'>should</span>
  <span m='2110610'>be</span> <span m='2110700'>the</span> <span m='2110790'>difference</span>
  <span m='2111120'>in</span> <span m='2111210'>the</span> <span m='2111300'>functions.</span>
  </p><p><span m='2112980'>And</span> <span m='2113130'>Newton's</span> <span m='2113580'>method</span>
  <span m='2116040'>for</span> <span m='2117150'>x</span> <span m='2117480'>i,</span>
  <span m='2117940'>said</span> <span m='2118200'>xi</span> <span m='2119430'>minus</span>
  <span m='2119820'>xi</span> <span m='2120120'>minus</span> <span m='2120450'>1</span>
  <span m='2120660'>was</span> <span m='2120810'>equal--</span> <span m='2121200'>times</span>
  <span m='2121590'>the</span> <span m='2121710'>Jacobian,</span> <span m='2122370'>was</span>
  <span m='2122550'>equal</span> <span m='2122730'>to</span> <span m='2122820'>minus</span>
  <span m='2123180'>f</span> <span m='2123330'>of</span> <span m='2123450'>xi minus</span>
  <span m='2123910'>1.</span> <span m='2124010'>This</span> <span m='2124110'>is</span>
  <span m='2124260'>just</span> <span m='2124410'>Newton's</span> <span m='2124740'>method.</span>
  <span m='2125080'>Invert</span> <span m='2126350'>the</span> <span m='2126450'>Jacobian,</span>
  <span m='2126800'>and</span> <span m='2126900'>put</span> <span m='2127020'>it</span>
  <span m='2127140'>on</span> <span m='2127260'>the</span> <span m='2127350'>other</span>
  <span m='2127530'>side</span> <span m='2127710'>of</span> <span m='2127770'>the</span>
  <span m='2127890'>equation.</span> <span m='2128910'>Broyden's</span> <span m='2129330'>method</span>
  <span m='2129420'>said,</span> <span m='2129600'>i--</span> <span m='2130020'>there's</span>
  <span m='2130230'>a</span> <span m='2130290'>trick</span> <span m='2130560'>here.</span>
  <span m='2131300'>Take</span> <span m='2131550'>the</span> <span m='2131640'>difference</span>
  <span m='2131970'>between</span> <span m='2132330'>these</span> <span m='2132540'>things.</span>
  </p><p><span m='2133970'>I</span> <span m='2134040'>get</span> <span m='2134160'>the</span>
  <span m='2134250'>same</span> <span m='2134610'>left-hand</span> <span m='2135060'>side</span>
  <span m='2135540'>on</span> <span m='2135660'>both</span> <span m='2135870'>of</span>
  <span m='2135930'>these</span> <span m='2136140'>equations.</span> <span m='2136660'>So</span>
  <span m='2136680'>take</span> <span m='2136890'>the</span> <span m='2136980'>difference,</span>
  <span m='2138150'>and</span> <span m='2138240'>I</span> <span m='2138300'>can</span>
  <span m='2138390'>figure</span> <span m='2138630'>out</span> <span m='2138720'>how</span>
  <span m='2139020'>the</span> <span m='2139140'>Jacobian</span> <span m='2139740'>should</span>
  <span m='2139920'>change</span> <span m='2140550'>from</span> <span m='2140730'>one</span>
  <span m='2141000'>step</span> <span m='2141390'>to</span> <span m='2141510'>the</span>
  <span m='2141600'>next.</span> <span m='2142270'>So</span> <span m='2142290'>maybe</span>
  <span m='2142500'>I have</span> <span m='2142590'>a</span> <span m='2142620'>good</span>
  <span m='2142740'>approximation</span> <span m='2143370'>to</span> <span m='2143490'>the</span>
  <span m='2143580'>Jacobian</span> <span m='2144060'>at</span> <span m='2144720'>xi</span>
  <span m='2145020'>minus</span> <span m='2145440'>i,</span> <span m='2145890'>I</span>
  <span m='2146340'>might</span> <span m='2146490'>be</span> <span m='2146580'>able</span>
  <span m='2146730'>to</span> <span m='2146850'>use</span> <span m='2147300'>this</span>
  <span m='2147940'>still</span> <span m='2148380'>underdetermined</span> <span m='2149190'>problem</span>
  <span m='2150450'>to</span> <span m='2150570'>figure</span> <span m='2150900'>out</span>
  <span m='2151080'>how</span> <span m='2151230'>to</span> <span m='2151440'>update</span>
  <span m='2152100'>that</span> <span m='2152310'>Jacobian,</span> <span m='2153100'>right?</span>
  </p><p><span m='2153250'>So</span> <span m='2153410'>Broyden's</span> <span m='2153750'>method</span>
  <span m='2154050'>is</span> <span m='2154140'>what's</span> <span m='2154320'>referred</span>
  <span m='2154620'>to</span> <span m='2154800'>as</span> <span m='2155340'>the</span>
  <span m='2155490'>rank</span> <span m='2155830'>one</span> <span m='2156270'>update.</span>
  <span m='2156780'>You</span> <span m='2156900'>should</span> <span m='2157020'>convince</span>
  <span m='2157410'>yourself</span> <span m='2158730'>that</span> <span m='2158880'>letting</span>
  <span m='2159750'>the</span> <span m='2159810'>Jacobian</span> <span m='2160350'>at</span>
  <span m='2160550'>xi</span> <span m='2161220'>minus</span> <span m='2161820'>the</span>
  <span m='2161910'>Jacobian</span> <span m='2162300'>at</span> <span m='2162390'>xi</span>
  <span m='2162480'>minus</span> <span m='2162920'>1</span> <span m='2164500'>be</span>
  <span m='2164720'>equal</span> <span m='2164970'>to</span> <span m='2165140'>this</span>
  <span m='2165870'>is</span> <span m='2166050'>one</span> <span m='2166410'>possible</span>
  <span m='2166890'>solution</span> <span m='2167370'>of</span> <span m='2167460'>this</span>
  <span m='2167640'>underdetermined</span> <span m='2168270'>equation.</span> <span
  m='2170500'>There</span> <span m='2170620'>are</span> <span m='2170710'>others.</span>
  <span m='2172150'>This</span> <span m='2172330'>is</span> <span m='2172450'>one</span>
  <span m='2172780'>possible</span> <span m='2173260'>solution.</span> <span m='2173860'>It</span>
  <span m='2174310'>turns</span> <span m='2174490'>out</span> <span m='2174580'>to</span>
  <span m='2174670'>be</span> <span m='2174760'>a</span> <span m='2174790'>good</span>
  <span m='2174940'>one</span> <span m='2175090'>to</span> <span m='2175150'>choose.</span>
  </p><p><span m='2177820'>So</span> <span m='2177870'>there's</span> <span m='2178020'>an</span>
  <span m='2178170'>iterative</span> <span m='2178650'>approximation</span> <span
  m='2179500'>now</span> <span m='2179730'>for</span> <span m='2180120'>the</span>
  <span m='2180870'>Jacobian.</span> <span m='2184615'>Does</span> <span m='2185110'>this</span>
  <span m='2185270'>strategy</span> <span m='2185770'>make</span> <span m='2185930'>sense?</span>
  <span m='2187020'>It's</span> <span m='2187120'>a</span> <span m='2187620'>little
  weird, right?</span> <span m='2187870'>There's</span> <span m='2187990'>something</span>
  <span m='2188260'>tricky</span> <span m='2188560'>here.</span> <span m='2188750'>You</span>
  <span m='2188840'>got</span> <span m='2188950'>to</span> <span m='2189010'>know</span>
  <span m='2189310'>to</span> <span m='2189460'>do</span> <span m='2189640'>this.</span>
  <span m='2190600'>Right,</span> <span m='2190870'>so</span> <span m='2190990'>somebody</span>
  <span m='2191290'>has</span> <span m='2191500'>to</span> <span m='2191590'>have</span>
  <span m='2191770'>in</span> <span m='2191890'>mind</span> <span m='2192310'>already</span>
  <span m='2192760'>that</span> <span m='2192910'>they're</span> <span m='2193060'>looking</span>
  <span m='2193420'>for</span> <span m='2193600'>differences</span> <span m='2194230'>in</span>
  <span m='2194320'>the</span> <span m='2194410'>Jacobian</span> <span m='2194860'>that</span>
  <span m='2194950'>they're</span> <span m='2195060'>going to</span> <span m='2195400'>update</span>
  <span m='2195850'>over</span> <span m='2196090'>time.</span> </p><p><span m='2200330'>So</span>
  <span m='2200450'>this</span> <span m='2200600'>tells</span> <span m='2200810'>me</span>
  <span m='2200930'>the</span> <span m='2201050'>Jacobian,</span> <span m='2201670'>how</span>
  <span m='2201770'>the</span> <span m='2201860'>Jacobian</span> <span m='2202370'>is</span>
  <span m='2202490'>updated.</span> <span m='2206480'>Really</span> <span m='2206960'>we</span>
  <span m='2207050'>need</span> <span m='2207230'>the</span> <span m='2207320'>Jacobian</span>
  <span m='2207920'>inverse,</span> <span m='2209480'>and</span> <span m='2209570'>the</span>
  <span m='2209660'>reason</span> <span m='2210200'>for</span> <span m='2210380'>choosing</span>
  <span m='2210980'>this</span> <span m='2211310'>rank</span> <span m='2211640'>one</span>
  <span m='2211880'>update</span> <span m='2212240'>approximation</span> <span m='2213230'>is</span>
  <span m='2214340'>it's</span> <span m='2215600'>possible</span> <span m='2216800'>to</span>
  <span m='2216920'>write</span> <span m='2217100'>the</span> <span m='2217310'>inverse</span>
  <span m='2218870'>of</span> <span m='2218990'>j of</span> <span m='2219410'>xi</span>
  <span m='2219800'>in</span> <span m='2219890'>terms</span> <span m='2220160'>of</span>
  <span m='2220220'>the</span> <span m='2220340'>inverse</span> <span m='2220940'>of</span>
  <span m='2221090'>j</span> <span m='2221330'>at</span> <span m='2221420'>xi</span>
  <span m='2221720'>minus</span> <span m='2222180'>1</span> <span m='2223880'>when</span>
  <span m='2224150'>this</span> <span m='2224330'>update</span> <span m='2224660'>formula</span>
  <span m='2225040'>is</span> <span m='2225160'>true.</span> </p><p><span m='2225340'>So</span>
  <span m='2225460'>it's</span> <span m='2225500'>something</span> <span m='2225800'>called</span>
  <span m='2225950'>the</span> <span m='2226070'>Sherman</span> <span m='2226460'>Morrison</span>
  <span m='2226910'>Formula,</span> <span m='2227450'>which</span> <span m='2227600'>says</span>
  <span m='2228290'>the</span> <span m='2228440'>inverse</span> <span m='2228830'>of</span>
  <span m='2228920'>a</span> <span m='2229010'>matrix</span> <span m='2229910'>plus</span>
  <span m='2230240'>the</span> <span m='2230360'>dyadic</span> <span m='2230750'>product</span>
  <span m='2231140'>of</span> <span m='2231230'>two</span> <span m='2231440'>vectors</span>
  <span m='2232790'>can</span> <span m='2232910'>be</span> <span m='2233030'>written</span>
  <span m='2233300'>in</span> <span m='2233420'>this</span> <span m='2233600'>form.</span>
  <span m='2234440'>We</span> <span m='2234560'>don't</span> <span m='2234680'>need</span>
  <span m='2234830'>to</span> <span m='2234950'>derive</span> <span m='2235400'>this,</span>
  <span m='2235640'>but</span> <span m='2235790'>this</span> <span m='2235970'>is</span>
  <span m='2236120'>true.</span> <span m='2238120'>This</span> <span m='2238780'>matrix</span>
  <span m='2239200'>plus</span> <span m='2239330'>dyadic</span> <span m='2239770'>product</span>
  <span m='2240460'>is</span> <span m='2240610'>exactly</span> <span m='2241180'>this.</span>
  <span m='2242260'>We</span> <span m='2242350'>have</span> <span m='2242470'>dyadic</span>
  <span m='2242785'>product</span> <span m='2243100'>between</span> <span m='2243460'>f</span>
  <span m='2243865'>and</span> <span m='2244270'>the</span> <span m='2244360'>step</span>
  <span m='2244660'>from</span> <span m='2244900'>xi</span> <span m='2245200'>minus</span>
  <span m='2245560'>1</span> <span m='2245830'>to</span> <span m='2246010'>x.</span>
  </p><p><span m='2247940'>And</span> <span m='2248110'>so</span> <span m='2248200'>we</span>
  <span m='2248260'>can</span> <span m='2248350'>apply</span> <span m='2248650'>that</span>
  <span m='2248800'>Sherman</span> <span m='2249130'>Morrison</span> <span m='2249520'>Formula</span>
  <span m='2249910'>to</span> <span m='2250030'>the</span> <span m='2250120'>rank</span>
  <span m='2250330'>one</span> <span m='2250510'>update.</span> <span m='2251350'>And</span>
  <span m='2251440'>not</span> <span m='2251620'>only</span> <span m='2251860'>can</span>
  <span m='2252010'>we</span> <span m='2252190'>update</span> <span m='2253540'>the</span>
  <span m='2253630'>Jacobian</span> <span m='2254110'>iteratively,</span> <span m='2254740'>but</span>
  <span m='2254860'>we</span> <span m='2254950'>can</span> <span m='2255070'>update</span>
  <span m='2255340'>the</span> <span m='2255400'>Jacobian</span> <span m='2255850'>inverse.</span>
  <span m='2256280'>So</span> <span m='2256390'>if</span> <span m='2256480'>I</span>
  <span m='2256570'>know</span> <span m='2257940'>j</span> <span m='2258250'>inverse</span>
  <span m='2258790'>at</span> <span m='2258880'>some</span> <span m='2259090'>previous</span>
  <span m='2259570'>time,</span> <span m='2259900'>I</span> <span m='2259960'>know</span>
  <span m='2260140'>j</span> <span m='2260330'>inverse</span> <span m='2260680'>at</span>
  <span m='2260740'>some</span> <span m='2260920'>later</span> <span m='2261220'>time</span>
  <span m='2261490'>too.</span> <span m='2262460'>I</span> <span m='2262500'>don't
  have</span> <span m='2262660'>to</span> <span m='2262750'>compute</span> <span m='2263080'>these</span>
  <span m='2263260'>things.</span> <span m='2263440'>I don't have</span> <span m='2263650'>to</span>
  <span m='2263740'>solve</span> <span m='2264040'>these</span> <span m='2264170'>systems</span>
  <span m='2264610'>of</span> <span m='2264700'>equations,</span> <span m='2265750'>right?</span>
  </p><p><span m='2265990'>I</span> <span m='2266080'>just</span> <span m='2266290'>update</span>
  <span m='2266650'>this</span> <span m='2266830'>matrix.</span> <span m='2270020'>Update</span>
  <span m='2270290'>this</span> <span m='2270440'>matrix,</span> <span m='2270800'>and</span>
  <span m='2270890'>I</span> <span m='2270950'>can</span> <span m='2271070'>very</span>
  <span m='2271310'>rapidly</span> <span m='2271880'>do</span> <span m='2272030'>these</span>
  <span m='2272180'>computations.</span> <span m='2275020'>So</span> <span m='2275140'>not</span>
  <span m='2275290'>only</span> <span m='2275410'>do</span> <span m='2275520'>we</span>
  <span m='2275560'>have</span> <span m='2275650'>an</span> <span m='2275710'>iterative</span>
  <span m='2276040'>formula</span> <span m='2276430'>for</span> <span m='2276550'>the</span>
  <span m='2276640'>steps,</span> <span m='2277630'>right?</span> <span m='2277900'>From</span>
  <span m='2278110'>x</span> <span m='2278320'>0</span> <span m='2278830'>to</span>
  <span m='2278950'>x1</span> <span m='2279520'>to</span> <span m='2279640'>x</span>
  <span m='2279890'>2,</span> <span m='2280270'>all</span> <span m='2280420'>the</span>
  <span m='2280510'>way</span> <span m='2280630'>up</span> <span m='2280750'>to</span>
  <span m='2280930'>our</span> <span m='2281470'>converged</span> <span m='2281860'>solution,
  but</span> <span m='2282210'>we</span> <span m='2282330'>can</span> <span m='2282500'>have</span>
  <span m='2282840'>a</span> <span m='2282910'>formula</span> <span m='2283360'>for</span>
  <span m='2283480'>the</span> <span m='2283600'>inverse</span> <span m='2283990'>of</span>
  <span m='2284080'>the</span> <span m='2284230'>Jacobian.</span> </p><p><span m='2285460'>We</span>
  <span m='2285550'>give</span> <span m='2285730'>up</span> <span m='2285850'>accuracy.</span>
  <span m='2287170'>But</span> <span m='2287290'>that's</span> <span m='2287500'>paid</span>
  <span m='2287800'>for</span> <span m='2289090'>in</span> <span m='2289210'>terms</span>
  <span m='2289510'>of</span> <span m='2289570'>the</span> <span m='2289660'>amount</span>
  <span m='2289840'>of</span> <span m='2289900'>time</span> <span m='2290260'>we</span>
  <span m='2290320'>have</span> <span m='2290440'>to</span> <span m='2290530'>spend</span>
  <span m='2290800'>doing</span> <span m='2291040'>these</span> <span m='2291190'>calculations.</span>
  <span m='2292930'>Does</span> <span m='2293090'>it</span> <span m='2293220'>pay</span>
  <span m='2293430'>off?</span> <span m='2293710'>It</span> <span m='2293770'>depends</span>
  <span m='2294040'>on</span> <span m='2294130'>the</span> <span m='2294220'>problem,</span>
  <span m='2294640'>right?</span> <span m='2295570'>We</span> <span m='2295660'>try</span>
  <span m='2295840'>to</span> <span m='2295900'>solve</span> <span m='2296170'>problems</span>
  <span m='2296560'>in</span> <span m='2296620'>different</span> <span m='2296890'>ways.</span>
  <span m='2297890'>This</span> <span m='2297970'>is</span> <span m='2298030'>a</span>
  <span m='2298090'>pretty</span> <span m='2298270'>common</span> <span m='2298570'>way</span>
  <span m='2298780'>to</span> <span m='2299920'>approximate</span> <span m='2300460'>the</span>
  <span m='2300550'>Jacobian.</span> <span m='2302631'>Questions</span> <span m='2303108'>about
  this?</span> <span m='2307410'>No.</span> <span m='2308130'>OK.</span> </p><p><span
  m='2309120'>Broyden's</span> <span m='2309430'>method.</span> <span m='2312660'>All
  right,</span> <span m='2313160'>here's</span> <span m='2313310'>the</span> <span
  m='2313370'>last</span> <span m='2313640'>one.</span> <span m='2316460'>The</span>
  <span m='2316550'>Damped</span> <span m='2316820'>Newton-Raphson</span> <span m='2317450'>method.</span>
  <span m='2318190'>We'll</span> <span m='2318890'>do</span> <span m='2319070'>this</span>
  <span m='2319220'>in</span> <span m='2319310'>one</span> <span m='2319490'>dimension.</span>
  <span m='2320330'>So</span> <span m='2320480'>the</span> <span m='2320570'>Newton-Raphson</span>
  <span m='2321070'>method,</span> <span m='2321410'>Newton and</span> <span m='2321770'>Raphson</span>
  <span m='2322130'>told</span> <span m='2322400'>us,</span> <span m='2322740'>take</span>
  <span m='2322970'>a</span> <span m='2323030'>step</span> <span m='2323960'>from</span>
  <span m='2324140'>xi</span> <span m='2324740'>to</span> <span m='2324890'>xi</span>
  <span m='2325280'>plus</span> <span m='2325550'>1</span> <span m='2325850'>that</span>
  <span m='2326000'>is</span> <span m='2326150'>this</span> <span m='2326480'>big.</span>
  <span m='2329880'>xi</span> <span m='2330440'>to</span> <span m='2330600'>xi</span>
  <span m='2330930'>plus</span> <span m='2331230'>1,</span> <span m='2331500'>it's</span>
  <span m='2331770'>this</span> <span m='2332130'>big.</span> <span m='2333570'>Sometimes</span>
  <span m='2334080'>you'll</span> <span m='2334230'>take</span> <span m='2334470'>that</span>
  <span m='2334680'>step,</span> <span m='2336030'>and</span> <span m='2336150'>you'll</span>
  <span m='2336270'>find</span> <span m='2336600'>that</span> <span m='2336720'>the</span>
  <span m='2336810'>value</span> <span m='2337170'>of</span> <span m='2337260'>the</span>
  <span m='2337380'>function</span> <span m='2338130'>at</span> <span m='2338310'>xi</span>
  <span m='2338610'>plus</span> <span m='2338910'>1</span> <span m='2339360'>is</span>
  <span m='2339480'>even</span> <span m='2339900'>bigger</span> <span m='2340560'>than</span>
  <span m='2340710'>the</span> <span m='2340800'>value</span> <span m='2341130'>of</span>
  <span m='2341220'>the</span> <span m='2341310'>function</span> <span m='2341700'>at</span>
  <span m='2341810'>xi.</span> </p><p><span m='2342180'>There</span> <span m='2342260'>was</span>
  <span m='2342360'>nothing</span> <span m='2342630'>about</span> <span m='2342780'>the</span>
  <span m='2342870'>Newton-Raphson</span> <span m='2343380'>method</span> <span m='2343650'>that</span>
  <span m='2343770'>told</span> <span m='2344160'>us</span> <span m='2345000'>the</span>
  <span m='2345120'>function</span> <span m='2345480'>value</span> <span m='2345880'>was</span>
  <span m='2345990'>always</span> <span m='2346230'>going</span> <span m='2346350'>to</span>
  <span m='2346440'>be</span> <span m='2346560'>decreasing.</span> <span m='2347550'>But</span>
  <span m='2347640'>actually,</span> <span m='2347970'>our</span> <span m='2348060'>goal</span>
  <span m='2348320'>is</span> <span m='2348450'>to</span> <span m='2348540'>make</span>
  <span m='2348660'>the</span> <span m='2348750'>function</span> <span m='2349050'>value</span>
  <span m='2349320'>go</span> <span m='2349440'>to</span> <span m='2349530'>0</span>
  <span m='2350010'>in</span> <span m='2350100'>absolute</span> <span m='2350520'>value.</span>
  <span m='2351070'>So</span> <span m='2351120'>it</span> <span m='2351180'>seems</span>
  <span m='2351600'>like</span> <span m='2352590'>this</span> <span m='2352860'>step,</span>
  <span m='2354490'>not</span> <span m='2354670'>a</span> <span m='2354700'>very</span>
  <span m='2354880'>good</span> <span m='2355060'>one,</span> <span m='2355530'>right?</span>
  <span m='2356710'>What</span> <span m='2356830'>are</span> <span m='2356920'>Newton
  and</span> <span m='2357265'>Raphson</span> <span m='2357610'>thinking</span> <span
  m='2357970'>here.</span> <span m='2358120'>This is</span> <span m='2358300'>not</span>
  <span m='2358510'>a</span> <span m='2358570'>good</span> <span m='2358690'>idea.</span>
  <span m='2359440'>The</span> <span m='2359530'>function</span> <span m='2359830'>value</span>
  <span m='2360160'>went</span> <span m='2360340'>up.</span> </p><p><span m='2364830'>Far</span>
  <span m='2365160'>from</span> <span m='2365400'>a</span> <span m='2365460'>root,</span>
  <span m='2366180'>OK?</span> <span m='2366450'>The</span> <span m='2366570'>Newton-Raphson</span>
  <span m='2366920'>method</span> <span m='2367230'>is</span> <span m='2367290'>going</span>
  <span m='2367410'>to</span> <span m='2367470'>give</span> <span m='2367590'>these</span>
  <span m='2367740'>sorts</span> <span m='2368010'>of</span> <span m='2368170'>erratic</span>
  <span m='2368670'>responses.</span> <span m='2369750'>Who</span> <span m='2369900'>knows</span>
  <span m='2370260'>what</span> <span m='2370410'>direction</span> <span m='2370860'>it's</span>
  <span m='2370980'>going</span> <span m='2371100'>to</span> <span m='2371160'>go?</span>
  <span m='2371370'>And</span> <span m='2371460'>it's</span> <span m='2371580'>only</span>
  <span m='2371820'>locally</span> <span m='2372340'>convergent.</span> <span m='2375480'>It</span>
  <span m='2375540'>tells</span> <span m='2375810'>us</span> <span m='2375920'>a</span>
  <span m='2375990'>direction</span> <span m='2376710'>to</span> <span m='2376830'>move</span>
  <span m='2377100'>in,</span> <span m='2377220'>but</span> <span m='2377340'>it</span>
  <span m='2377430'>doesn't</span> <span m='2377640'>always</span> <span m='2377820'>give</span>
  <span m='2378000'>the</span> <span m='2378090'>right</span> <span m='2378300'>sort</span>
  <span m='2378450'>of</span> <span m='2378570'>magnitude</span> <span m='2379440'>associated</span>
  <span m='2380070'>with</span> <span m='2380220'>that</span> <span m='2380430'>step.</span>
  <span m='2381630'>And</span> <span m='2381750'>so</span> <span m='2381870'>you</span>
  <span m='2381930'>take</span> <span m='2382170'>these</span> <span m='2382320'>steps</span>
  <span m='2382710'>and</span> <span m='2382800'>you</span> <span m='2382860'>can</span>
  <span m='2382980'>find</span> <span m='2383220'>out</span> <span m='2383310'>the</span>
  <span m='2383430'>value</span> <span m='2383700'>of</span> <span m='2383790'>your</span>
  <span m='2383880'>function,</span> <span m='2384490'>the</span> <span m='2384510'>normed</span>
  <span m='2384820'>value</span> <span m='2385070'>of</span> <span m='2385200'>your</span>
  <span m='2385290'>functions.</span> <span m='2385650'>It's</span> <span m='2385680'>bigger</span>
  <span m='2386040'>than</span> <span m='2386190'>where</span> <span m='2386280'>you</span>
  <span m='2386400'>started.</span> <span m='2386790'>It</span> <span m='2386880'>seems</span>
  <span m='2387090'>like</span> <span m='2387210'>you're</span> <span m='2387300'>getting</span>
  <span m='2387570'>further</span> <span m='2387990'>away</span> <span m='2388200'>from</span>
  <span m='2388440'>the</span> <span m='2388560'>root.</span> </p><p><span m='2389670'>Our</span>
  <span m='2389790'>ultimate</span> <span m='2390090'>goal</span> <span m='2390260'>is</span>
  <span m='2390390'>to</span> <span m='2391100'>drive</span> <span m='2391620'>this</span>
  <span m='2391830'>norm</span> <span m='2392190'>to</span> <span m='2392340'>0.</span>
  <span m='2392880'>So</span> <span m='2393300'>steps</span> <span m='2393660'>like</span>
  <span m='2393840'>that</span> <span m='2394030'>you</span> <span m='2394140'>might</span>
  <span m='2394260'>even</span> <span m='2394380'>call</span> <span m='2394620'>unacceptable.</span>
  <span m='2395310'>Right?</span> <span m='2395520'>Why</span> <span m='2395700'>would</span>
  <span m='2395850'>I</span> <span m='2395910'>ever</span> <span m='2396090'>take</span>
  <span m='2396360'>a</span> <span m='2396420'>step</span> <span m='2396690'>in</span>
  <span m='2396780'>that</span> <span m='2396930'>direction?</span> <span m='2397270'>Maybe</span>
  <span m='2397350'>I</span> <span m='2397560'>should</span> <span m='2397650'>use</span>
  <span m='2397830'>a</span> <span m='2397860'>different</span> <span m='2398130'>method.</span>
  <span m='2398940'>When</span> <span m='2399070'>I</span> <span m='2399150'>take</span>
  <span m='2399360'>a</span> <span m='2399420'>step</span> <span m='2399750'>that's</span>
  <span m='2399900'>so</span> <span m='2400230'>big</span> <span m='2400560'>my</span>
  <span m='2400740'>function</span> <span m='2401190'>value</span> <span m='2401550'>grows</span>
  <span m='2402060'>in</span> <span m='2402130'>norm</span> <span m='2402540'>value.</span>
  </p><p><span m='2405690'>So</span> <span m='2405740'>what</span> <span m='2405860'>one</span>
  <span m='2406070'>does,</span> <span m='2406490'>oftentimes,</span> <span m='2407150'>is</span>
  <span m='2407270'>introduce</span> <span m='2407660'>a</span> <span m='2407720'>damping</span>
  <span m='2408140'>factor,</span> <span m='2408920'>right?</span> <span m='2409970'>We</span>
  <span m='2410090'>said</span> <span m='2410450'>that</span> <span m='2411290'>this</span>
  <span m='2411530'>ratio,</span> <span m='2412400'>or</span> <span m='2412550'>equivalently,</span>
  <span m='2413450'>the</span> <span m='2413540'>Jacobian</span> <span m='2414020'>inverse</span>
  <span m='2414440'>times</span> <span m='2414680'>the</span> <span m='2414770'>value</span>
  <span m='2415040'>of</span> <span m='2415130'>the</span> <span m='2415220'>function,</span>
  <span m='2415760'>gives</span> <span m='2416030'>us</span> <span m='2416150'>the</span>
  <span m='2416270'>right</span> <span m='2416480'>direction</span> <span m='2417110'>to</span>
  <span m='2417260'>step</span> <span m='2417620'>in.</span> <span m='2418320'>But</span>
  <span m='2418340'>how</span> <span m='2418460'>big</span> <span m='2418670'>a</span>
  <span m='2418730'>step</span> <span m='2419000'>should</span> <span m='2419150'>we</span>
  <span m='2419240'>take?</span> </p><p><span m='2421760'>It's</span> <span m='2421880'>clear</span>
  <span m='2422960'>a</span> <span m='2423020'>step</span> <span m='2423320'>like</span>
  <span m='2423530'>this</span> <span m='2424610'>is</span> <span m='2424730'>a</span>
  <span m='2424790'>good</span> <span m='2425000'>one.</span> <span m='2425750'>It</span>
  <span m='2425930'>reduced</span> <span m='2426380'>the</span> <span m='2426470'>value</span>
  <span m='2426800'>of</span> <span m='2426890'>the</span> <span m='2427010'>function.</span>
  <span m='2430790'>And</span> <span m='2430910'>it's</span> <span m='2431040'>better</span>
  <span m='2431340'>than</span> <span m='2431490'>the</span> <span m='2431580'>one</span>
  <span m='2431700'>we</span> <span m='2431820'>took</span> <span m='2431970'>before,</span>
  <span m='2432480'>which</span> <span m='2432720'>was</span> <span m='2433320'>given</span>
  <span m='2433590'>by</span> <span m='2433770'>the</span> <span m='2433950'>linear</span>
  <span m='2434520'>approximation.</span> <span m='2435240'>So</span> <span m='2435300'>if</span>
  <span m='2435390'>I</span> <span m='2435450'>draw</span> <span m='2435660'>the</span>
  <span m='2435780'>tangent</span> <span m='2436350'>line,</span> <span m='2436650'>it</span>
  <span m='2436770'>intercepts</span> <span m='2437340'>here.</span> <span m='2438150'>If</span>
  <span m='2438240'>I</span> <span m='2438330'>take</span> <span m='2438540'>a</span>
  <span m='2438600'>step</span> <span m='2438930'>in</span> <span m='2439020'>this</span>
  <span m='2439170'>direction,</span> <span m='2440290'>but</span> <span m='2440310'>I</span>
  <span m='2440400'>reduce</span> <span m='2440940'>the</span> <span m='2441090'>slope</span>
  <span m='2441930'>by</span> <span m='2442050'>having</span> <span m='2442290'>some</span>
  <span m='2442440'>damping</span> <span m='2442860'>factor</span> <span m='2443220'>that's</span>
  <span m='2443400'>smaller</span> <span m='2443730'>than</span> <span m='2443830'>1,</span>
  <span m='2443990'>I</span> <span m='2444050'>get</span> <span m='2444180'>closer</span>
  <span m='2444750'>to</span> <span m='2444900'>the</span> <span m='2445020'>root.</span>
  </p><p><span m='2446570'>Ideally</span> <span m='2447980'>we'd</span> <span m='2448100'>like</span>
  <span m='2448250'>to</span> <span m='2448370'>choose</span> <span m='2448880'>that</span>
  <span m='2449030'>damping</span> <span m='2449510'>factor</span> <span m='2450710'>to</span>
  <span m='2450830'>be</span> <span m='2450980'>the</span> <span m='2451100'>one</span>
  <span m='2451400'>that</span> <span m='2451670'>minimizes</span> <span m='2452900'>the</span>
  <span m='2453050'>value</span> <span m='2453440'>of</span> <span m='2453530'>the</span>
  <span m='2453650'>function</span> <span m='2454250'>at</span> <span m='2454370'>xi</span>
  <span m='2454760'>plus</span> <span m='2455230'>1.</span> <span m='2457280'>So</span>
  <span m='2457460'>it's</span> <span m='2457610'>the</span> <span m='2457850'>argument</span>
  <span m='2459290'>that</span> <span m='2459440'>minimizes</span> <span m='2461510'>the</span>
  <span m='2461600'>value</span> <span m='2461900'>of</span> <span m='2461990'>the</span>
  <span m='2462080'>function</span> <span m='2462470'>at</span> <span m='2462590'>xi</span>
  <span m='2462940'>plus</span> <span m='2463190'>1</span> <span m='2463480'>or</span>
  <span m='2463980'>at xi</span> <span m='2464260'>minus</span> <span m='2464540'>alpha,</span>
  <span m='2465230'>f</span> <span m='2465530'>over</span> <span m='2465770'>f</span>
  <span m='2465950'>prime.</span> </p><p><span m='2468060'>Solving</span> <span m='2468480'>that</span>
  <span m='2468630'>optimization</span> <span m='2469230'>problem,</span> <span m='2469500'>what's</span>
  <span m='2469620'>hard</span> <span m='2469840'>as</span> <span m='2469950'>finding</span>
  <span m='2470250'>the</span> <span m='2470340'>root</span> <span m='2470970'>itself.</span>
  <span m='2472150'>So</span> <span m='2472590'>ideally</span> <span m='2473070'>this</span>
  <span m='2473280'>is</span> <span m='2473430'>true.</span> <span m='2473760'>But</span>
  <span m='2474590'>practically</span> <span m='2475490'>you're</span> <span m='2475590'>not</span>
  <span m='2475710'>going</span> <span m='2475830'>to</span> <span m='2475920'>be</span>
  <span m='2475980'>able</span> <span m='2476130'>to</span> <span m='2476250'>do</span>
  <span m='2476490'>it.</span> <span m='2476730'>So</span> <span m='2476760'>we</span>
  <span m='2476820'>have</span> <span m='2476940'>to</span> <span m='2477030'>come</span>
  <span m='2477180'>up</span> <span m='2477270'>with</span> <span m='2477360'>some</span>
  <span m='2477630'>approximate</span> <span m='2478320'>methods</span> <span m='2479340'>of</span>
  <span m='2480000'>solving</span> <span m='2480540'>this</span> <span m='2480690'>optimization</span>
  <span m='2481410'>problem.</span> <span m='2481720'>Actually</span> <span m='2481960'>we
  don't</span> <span m='2481990'>even</span> <span m='2482280'>care</span> <span m='2482460'>about</span>
  <span m='2482640'>getting</span> <span m='2482880'>it</span> <span m='2482970'>exact.</span>
  <span m='2483320'>We</span> <span m='2483470'>know</span> <span m='2483600'>Newton-Raphson</span>
  <span m='2484200'>does</span> <span m='2484350'>a</span> <span m='2484380'>pretty</span>
  <span m='2484590'>good</span> <span m='2484710'>job.</span> <span m='2485670'>We</span>
  <span m='2485850'>want</span> <span m='2486490'>some</span> <span m='2486930'>sort</span>
  <span m='2487050'>of</span> <span m='2487160'>guess</span> <span m='2488110'>that's</span>
  <span m='2488400'>respectable</span> <span m='2489060'>for</span> <span m='2489300'>this</span>
  <span m='2489480'>alpha</span> <span m='2490920'>so</span> <span m='2491110'>that</span>
  <span m='2491220'>we</span> <span m='2491310'>get</span> <span m='2491460'>close</span>
  <span m='2491760'>to</span> <span m='2491850'>this</span> <span m='2492060'>root.</span>
  </p><p><span m='2492300'>Once</span> <span m='2492480'>we</span> <span m='2492570'>get</span>
  <span m='2492720'>close,</span> <span m='2493290'>we'll</span> <span m='2493410'>probably</span>
  <span m='2493590'>choose</span> <span m='2493790'>alpha</span> <span m='2494040'>equal</span>
  <span m='2494340'>to</span> <span m='2494490'>1.</span> <span m='2494800'>We'll</span>
  <span m='2494910'>just</span> <span m='2495030'>take</span> <span m='2495210'>the</span>
  <span m='2495300'>Newton-Raphson</span> <span m='2496020'>steps</span> <span m='2496440'>all</span>
  <span m='2496590'>the</span> <span m='2496710'>way</span> <span m='2496800'>down</span>
  <span m='2497070'>to</span> <span m='2497160'>the</span> <span m='2497270'>root.</span>
  <span m='2500100'>So</span> <span m='2500150'>here</span> <span m='2500300'>it</span>
  <span m='2500390'>is</span> <span m='2500480'>in</span> <span m='2500540'>many</span>
  <span m='2500780'>dimensions.</span> <span m='2501800'>Modify</span> <span m='2503090'>the</span>
  <span m='2503180'>Newton-Raphson</span> <span m='2503840'>step</span> <span m='2504140'>by</span>
  <span m='2504290'>some</span> <span m='2504530'>value</span> <span m='2504890'>alpha,</span>
  <span m='2505960'>choose</span> <span m='2506270'>alpha</span> <span m='2506960'>to</span>
  <span m='2507080'>be</span> <span m='2507170'>the</span> <span m='2507290'>argument</span>
  <span m='2507740'>that</span> <span m='2507890'>minimizes</span> <span m='2508880'>the</span>
  <span m='2509030'>norm</span> <span m='2509390'>value</span> <span m='2509780'>of</span>
  <span m='2509900'>the</span> <span m='2509990'>function</span> <span m='2510890'>at</span>
  <span m='2511040'>xi</span> <span m='2511460'>plus</span> <span m='2511900'>1.</span>
  </p><p><span m='2515510'>Here's</span> <span m='2515840'>one</span> <span m='2516230'>way</span>
  <span m='2516440'>of</span> <span m='2516530'>doing</span> <span m='2516800'>this.</span>
  <span m='2517340'>So</span> <span m='2517440'>this</span> <span m='2517460'>is</span>
  <span m='2517550'>called</span> <span m='2517730'>the</span> <span m='2517880'>Armijo</span>
  <span m='2518480'>line</span> <span m='2518970'>search.</span> <span m='2519470'>See?</span>
  <span m='2519830'>Line</span> <span m='2520070'>search.</span> <span m='2521180'>Start</span>
  <span m='2521510'>by</span> <span m='2521660'>letting</span> <span m='2521960'>alpha</span>
  <span m='2522140'>equal</span> <span m='2522440'>to</span> <span m='2522560'>1.</span>
  <span m='2523400'>Take</span> <span m='2523580'>the</span> <span m='2523700'>full</span>
  <span m='2523910'>Newton-Raphson</span> <span m='2524600'>step,</span> <span m='2524900'>and</span>
  <span m='2524990'>check.</span> <span m='2525960'>Was</span> <span m='2526190'>the</span>
  <span m='2526280'>value of my</span> <span m='2526750'>function</span> <span m='2527150'>smaller</span>
  <span m='2527720'>than</span> <span m='2527840'>where</span> <span m='2528020'>I</span>
  <span m='2528110'>started?</span> <span m='2529000'>If</span> <span m='2529250'>it</span>
  <span m='2529340'>is,</span> <span m='2529850'>let's</span> <span m='2530060'>take</span>
  <span m='2530270'>the</span> <span m='2530360'>step.</span> <span m='2531470'>It's</span>
  <span m='2531650'>getting</span> <span m='2531950'>us--</span> <span m='2532720'>we're</span>
  <span m='2532820'>accomplishing</span> <span m='2533300'>our</span> <span m='2533390'>goal.</span>
  <span m='2533630'>We</span> <span m='2534020'>re reducing</span> <span m='2534500'>the</span>
  <span m='2534560'>value</span> <span m='2534830'>of</span> <span m='2534890'>the</span>
  <span m='2534980'>function</span> <span m='2535640'>in norm.</span> <span m='2536180'>Maybe</span>
  <span m='2536450'>we're</span> <span m='2536570'>headed</span> <span m='2536780'>towards</span>
  <span m='2537070'>z.</span> <span m='2537410'>That's</span> <span m='2537650'>good.</span>
  <span m='2538370'>Accept</span> <span m='2538940'>it.</span> </p><p><span m='2540020'>If</span>
  <span m='2540230'>no,</span> <span m='2541400'>let's</span> <span m='2541580'>replace</span>
  <span m='2542060'>alpha</span> <span m='2542870'>with</span> <span m='2543050'>alpha</span>
  <span m='2543290'>over</span> <span m='2543530'>2.</span> <span m='2544440'>Let's</span>
  <span m='2544550'>take</span> <span m='2544730'>a</span> <span m='2544790'>shorter</span>
  <span m='2545240'>step.</span> <span m='2548330'>We</span> <span m='2548420'>take</span>
  <span m='2548600'>a</span> <span m='2548660'>shorter</span> <span m='2548930'>step,</span>
  <span m='2549320'>and</span> <span m='2549440'>we</span> <span m='2549560'>repeat.</span>
  <span m='2550190'>Right?</span> <span m='2550410'>Take</span> <span m='2550640'>the</span>
  <span m='2550730'>shorter</span> <span m='2551030'>step.</span> <span m='2552200'>Check</span>
  <span m='2552440'>whether</span> <span m='2552710'>the</span> <span m='2552800'>value</span>
  <span m='2553130'>of</span> <span m='2553250'>the</span> <span m='2553340'>function</span>
  <span m='2553730'>with</span> <span m='2553850'>the</span> <span m='2553910'>shorter</span>
  <span m='2554240'>step</span> <span m='2554570'>is</span> <span m='2554720'>acceptable.</span>
  <span m='2555740'>If</span> <span m='2555920'>yes,</span> <span m='2556370'>let's</span>
  <span m='2556580'>take</span> <span m='2556820'>it,</span> <span m='2557390'>and</span>
  <span m='2557510'>let's</span> <span m='2557660'>move</span> <span m='2557870'>on.</span>
  <span m='2558540'>And</span> <span m='2558560'>if</span> <span m='2558710'>no,</span>
  <span m='2560420'>replace</span> <span m='2560780'>alpha</span> <span m='2561080'>with</span>
  <span m='2561230'>alpha</span> <span m='2561470'>over</span> <span m='2561680'>2,</span>
  <span m='2561940'>and</span> <span m='2562070'>continue.</span> <span m='2562590'>So</span>
  <span m='2562640'>we</span> <span m='2562790'>have</span> <span m='2563210'>our</span>
  <span m='2563330'>step</span> <span m='2563660'>size</span> <span m='2564110'>every</span>
  <span m='2564320'>time.</span> </p><p><span m='2565580'>We</span> <span m='2566120'>don't</span>
  <span m='2566300'>just</span> <span m='2566480'>have</span> <span m='2566600'>to</span>
  <span m='2566720'>have</span> <span m='2566990'>it.</span> <span m='2567080'>We</span>
  <span m='2567200'>could</span> <span m='2567320'>choose</span> <span m='2567590'>different</span>
  <span m='2567830'>factors</span> <span m='2568340'>to</span> <span m='2568460'>reduce</span>
  <span m='2568850'>it</span> <span m='2568940'>by.</span> <span m='2569930'>But</span>
  <span m='2570630'>we</span> <span m='2570700'>try</span> <span m='2570860'>to</span>
  <span m='2570950'>take</span> <span m='2571130'>shorter</span> <span m='2571460'>and</span>
  <span m='2571550'>shorter</span> <span m='2571880'>steps</span> <span m='2572300'>until</span>
  <span m='2572570'>we</span> <span m='2572720'>accomplish</span> <span m='2573140'>our</span>
  <span m='2573230'>goal</span> <span m='2574160'>of</span> <span m='2574280'>having</span>
  <span m='2574520'>a</span> <span m='2574580'>function</span> <span m='2576530'>which</span>
  <span m='2576710'>is</span> <span m='2576770'>smaller</span> <span m='2577300'>in</span>
  <span m='2577410'>norm</span> <span m='2577730'>at</span> <span m='2577820'>our</span>
  <span m='2577910'>next</span> <span m='2578200'>iterate</span> <span m='2578900'>than</span>
  <span m='2579020'>where</span> <span m='2579170'>we</span> <span m='2579290'>were</span>
  <span m='2579470'>before.</span> </p><p><span m='2581580'>It's</span> <span m='2581670'>got--</span>
  <span m='2581960'>the</span> <span m='2582080'>function</span> <span m='2582350'>value</span>
  <span m='2582680'>will</span> <span m='2583070'>be</span> <span m='2583370'>reduced.</span>
  <span m='2583910'>The</span> <span m='2584030'>Newton-Raphson</span> <span m='2584750'>method</span>
  <span m='2585110'>picks</span> <span m='2585500'>a</span> <span m='2585560'>direction</span>
  <span m='2586430'>that</span> <span m='2586550'>wants</span> <span m='2586880'>to</span>
  <span m='2587000'>bring</span> <span m='2587390'>the</span> <span m='2587510'>function</span>
  <span m='2587870'>value</span> <span m='2588170'>closer</span> <span m='2588560'>to</span>
  <span m='2588680'>0.</span> <span m='2590170'>We</span> <span m='2590330'>linearize</span>
  <span m='2591050'>the</span> <span m='2591170'>function,</span> <span m='2591590'>and</span>
  <span m='2591680'>we</span> <span m='2591830'>found</span> <span m='2592400'>the</span>
  <span m='2592490'>direction</span> <span m='2592850'>we</span> <span m='2592910'>needed</span>
  <span m='2593180'>to</span> <span m='2593270'>go</span> <span m='2593420'>to</span>
  <span m='2593510'>make</span> <span m='2593660'>that</span> <span m='2593780'>linearization</span>
  <span m='2594380'>go</span> <span m='2594470'>to</span> <span m='2594560'>0.</span>
  <span m='2594740'>So</span> <span m='2594860'>there</span> <span m='2595010'>is</span>
  <span m='2595970'>a</span> <span m='2596030'>step</span> <span m='2596330'>size</span>
  <span m='2596840'>for</span> <span m='2597020'>which</span> <span m='2597860'>the</span>
  <span m='2597980'>function</span> <span m='2598310'>value</span> <span m='2598640'>will</span>
  <span m='2598820'>be</span> <span m='2598970'>reduced.</span> </p><p><span m='2601450'>And</span>
  <span m='2601550'>because</span> <span m='2601820'>of</span> <span m='2601940'>that,</span>
  <span m='2602420'>this</span> <span m='2602570'>Armijo</span> <span m='2602950'>line</span>
  <span m='2603290'>search</span> <span m='2603650'>of the</span> <span m='2603790'>Damped</span>
  <span m='2604070'>Newton-Raphson</span> <span m='2604700'>method</span> <span m='2605090'>is</span>
  <span m='2605390'>actually</span> <span m='2605690'>globally</span> <span m='2606320'>convergent,</span>
  <span m='2607190'>right?</span> <span m='2607690'>The</span> <span m='2607810'>iterative</span>
  <span m='2608120'>method</span> <span m='2608480'>will</span> <span m='2608840'>terminate.</span>
  <span m='2610370'>You</span> <span m='2610580'>can</span> <span m='2610730'>guarantee</span>
  <span m='2611150'>it.</span> <span m='2611570'>Here's</span> <span m='2611720'>what</span>
  <span m='2611810'>it</span> <span m='2611870'>looks</span> <span m='2612050'>like</span>
  <span m='2612200'>graphically.</span> </p><p><span m='2612930'>I</span> <span m='2612980'>take</span>
  <span m='2613190'>my</span> <span m='2613370'>big</span> <span m='2613580'>step,</span>
  <span m='2614090'>my</span> <span m='2614360'>alpha</span> <span m='2614750'>equals
  1</span> <span m='2614960'>step.</span> <span m='2615790'>I</span> <span m='2615920'>check</span>
  <span m='2616130'>the</span> <span m='2616190'>value</span> <span m='2616490'>of</span>
  <span m='2616580'>the</span> <span m='2616670'>function.</span> <span m='2617450'>It's</span>
  <span m='2617600'>bigger</span> <span m='2617930'>in</span> <span m='2618050'>absolute</span>
  <span m='2618380'>value</span> <span m='2618680'>than</span> <span m='2618800'>where</span>
  <span m='2618920'>I</span> <span m='2618980'>started.</span> <span m='2619500'>So</span>
  <span m='2619600'>I go</span> <span m='2619700'>back.</span> <span m='2620570'>I</span>
  <span m='2620690'>take</span> <span m='2621230'>half</span> <span m='2621500'>that</span>
  <span m='2621680'>step</span> <span m='2621980'>size.</span> <span m='2622830'>OK?</span>
  <span m='2623570'>I</span> <span m='2623660'>look</span> <span m='2623780'>at</span>
  <span m='2623840'>the</span> <span m='2623900'>value of the</span> <span m='2624140'>function.</span>
  <span m='2624480'>It's still</span> <span m='2624770'>bigger.</span> <span m='2625280'>Let's</span>
  <span m='2625460'>reject</span> <span m='2625910'>it,</span> <span m='2626030'>and</span>
  <span m='2626150'>go</span> <span m='2626270'>back.</span> </p><p><span m='2626890'>I</span>
  <span m='2626960'>take</span> <span m='2627170'>half</span> <span m='2627380'>that</span>
  <span m='2627530'>step</span> <span m='2627770'>size</span> <span m='2628070'>again.</span>
  <span m='2629010'>The</span> <span m='2629110'>value</span> <span m='2629220'>of</span>
  <span m='2629320'>the</span> <span m='2629330'>function</span> <span m='2629690'>here</span>
  <span m='2629990'>is</span> <span m='2630110'>now</span> <span m='2630260'>smaller</span>
  <span m='2630920'>in</span> <span m='2631070'>absolute</span> <span m='2631430'>value.</span>
  <span m='2631950'>So</span> <span m='2632030'>I</span> <span m='2632080'>accept</span>
  <span m='2632600'>it.</span> <span m='2633370'>And</span> <span m='2633540'>I</span>
  <span m='2633590'>put</span> <span m='2633770'>myself</span> <span m='2634070'>pretty</span>
  <span m='2634310'>close</span> <span m='2634610'>to</span> <span m='2634730'>the</span>
  <span m='2634820'>root.</span> <span m='2637200'>So</span> <span m='2637350'>it's</span>
  <span m='2637470'>convergent,</span> <span m='2638010'>globally</span> <span m='2638700'>convergent.</span>
  <span m='2640050'>That's</span> <span m='2640290'>nice.</span> <span m='2641850'>It's</span>
  <span m='2642000'>not</span> <span m='2642210'>globally</span> <span m='2642660'>convergent</span>
  <span m='2643080'>to</span> <span m='2643230'>roots,</span> <span m='2644040'>which</span>
  <span m='2644250'>is</span> <span m='2644820'>a</span> <span m='2644880'>pain.</span>
  <span m='2645870'>But</span> <span m='2645990'>it's</span> <span m='2646080'>globally</span>
  <span m='2646490'>convergent.</span> <span m='2646920'>It will</span> <span m='2647100'>terminate</span>
  <span m='2647580'>eventually.</span> <span m='2648220'>You'll</span> <span m='2648810'>get</span>
  <span m='2648960'>to</span> <span m='2649080'>a</span> <span m='2649140'>point</span>
  <span m='2649440'>where</span> <span m='2651480'>you</span> <span m='2651600'>won't</span>
  <span m='2651780'>be</span> <span m='2651870'>able</span> <span m='2652050'>to</span>
  <span m='2652260'>advance</span> <span m='2652890'>your</span> <span m='2653100'>steps</span>
  <span m='2653610'>any</span> <span m='2653850'>further.</span> </p><p><span m='2654500'>It</span>
  <span m='2654670'>may</span> <span m='2655050'>converge</span> <span m='2655500'>to</span>
  <span m='2655620'>minima</span> <span m='2656040'>or</span> <span m='2656160'>maxima</span>
  <span m='2656630'>of</span> <span m='2656750'>a</span> <span m='2656820'>function.</span>
  <span m='2658050'>Or it</span> <span m='2658200'>may</span> <span m='2658410'>converge</span>
  <span m='2658800'>to</span> <span m='2658930'>roots.</span> <span m='2659550'>But</span>
  <span m='2659700'>it</span> <span m='2659760'>will</span> <span m='2660030'>converge.</span>
  <span m='2663290'>I</span> <span m='2663350'>showed you</span> <span m='2663620'>this</span>
  <span m='2663830'>example</span> <span m='2664190'>before</span> <span m='2664580'>with</span>
  <span m='2664730'>basins</span> <span m='2665120'>of</span> <span m='2665240'>attraction.</span>
  </p><p><span m='2666890'>So</span> <span m='2667010'>here</span> <span m='2667160'>we</span>
  <span m='2667250'>have</span> <span m='2667340'>different</span> <span m='2667640'>basins</span>
  <span m='2668060'>of</span> <span m='2668150'>attraction.</span> <span m='2668690'>They're</span>
  <span m='2668810'>all</span> <span m='2668900'>colored</span> <span m='2669320'>in.</span>
  <span m='2669500'>They</span> <span m='2669620'>show</span> <span m='2669760'>you</span>
  <span m='2669880'>which</span> <span m='2670130'>roots</span> <span m='2670430'>you</span>
  <span m='2670550'>approach.</span> <span m='2671460'>Here</span> <span m='2671770'>I've</span>
  <span m='2671900'>applied</span> <span m='2672410'>the</span> <span m='2672500'>Damped</span>
  <span m='2672740'>Newton-Raphson</span> <span m='2673460'>method</span> <span m='2674680'>to</span>
  <span m='2674810'>the</span> <span m='2674940'>same</span> <span m='2675380'>system</span>
  <span m='2675770'>of</span> <span m='2675890'>equations.</span> <span m='2676860'>And</span>
  <span m='2676960'>you</span> <span m='2677060'>can</span> <span m='2677160'>see</span>
  <span m='2677260'>the</span> <span m='2677270'>basins</span> <span m='2677630'>of</span>
  <span m='2677720'>attraction</span> <span m='2678380'>are</span> <span m='2678620'>shrunk</span>
  <span m='2679910'>because</span> <span m='2680210'>of</span> <span m='2680270'>the</span>
  <span m='2680390'>damping.</span> <span m='2681380'>What</span> <span m='2681560'>happens</span>
  <span m='2682790'>when</span> <span m='2682910'>you're</span> <span m='2683000'>very</span>
  <span m='2683240'>close</span> <span m='2683570'>to</span> <span m='2683690'>places</span>
  <span m='2684200'>where</span> <span m='2684380'>the</span> <span m='2684500'>determinant</span>
  <span m='2684910'>of</span> <span m='2684980'>the</span> <span m='2685070'>Jacobian</span>
  <span m='2685310'>is</span> <span m='2685640'>singular,</span> <span m='2686640'>you</span>
  <span m='2686720'>take</span> <span m='2686930'>all</span> <span m='2687020'>sorts</span>
  <span m='2687290'>of</span> <span m='2687410'>wild</span> <span m='2687860'>steps.</span>
  </p><p><span m='2689690'>You</span> <span m='2689810'>go</span> <span m='2689990'>to</span>
  <span m='2690110'>places</span> <span m='2690560'>where</span> <span m='2690680'>the</span>
  <span m='2690770'>value</span> <span m='2691100'>of</span> <span m='2691150'>the</span>
  <span m='2691250'>function</span> <span m='2691700'>is</span> <span m='2692000'>bigger</span>
  <span m='2692570'>than</span> <span m='2692750'>where</span> <span m='2692900'>you</span>
  <span m='2693020'>started.</span> <span m='2694310'>And</span> <span m='2694340'>then</span>
  <span m='2694460'>you've</span> <span m='2694550'>got</span> <span m='2694640'>to</span>
  <span m='2694700'>step</span> <span m='2695030'>down</span> <span m='2695300'>from</span>
  <span m='2695510'>there</span> <span m='2695810'>to</span> <span m='2695960'>try</span>
  <span m='2696170'>to</span> <span m='2696260'>find</span> <span m='2696560'>the</span>
  <span m='2696650'>root.</span> <span m='2697430'>Who</span> <span m='2697550'>knows</span>
  <span m='2697940'>where</span> <span m='2698090'>those</span> <span m='2698300'>locations</span>
  <span m='2698930'>are?</span> <span m='2699320'>It's</span> <span m='2699500'>a</span>
  <span m='2699560'>very</span> <span m='2699800'>complicated,</span> <span m='2700550'>geometrically</span>
  <span m='2701180'>complicated</span> <span m='2701780'>space</span> <span m='2702650'>that</span>
  <span m='2702770'>you're</span> <span m='2702860'>moving</span> <span m='2703280'>through.</span>
  <span m='2704240'>And</span> <span m='2704360'>the</span> <span m='2704450'>Damped</span>
  <span m='2704870'>Newton-Raphson</span> <span m='2705200'>method</span> <span m='2705575'>is</span>
  <span m='2705950'>forcing</span> <span m='2708140'>the</span> <span m='2708380'>steps</span>
  <span m='2708890'>to</span> <span m='2709010'>always</span> <span m='2709430'>reduce</span>
  <span m='2709910'>the</span> <span m='2710000'>value</span> <span m='2710300'>of</span>
  <span m='2710390'>the</span> <span m='2710480'>function,</span> <span m='2710960'>so</span>
  <span m='2711110'>they</span> <span m='2711200'>reduce</span> <span m='2711710'>the</span>
  <span m='2711830'>size</span> <span m='2712250'>of</span> <span m='2712310'>these</span>
  <span m='2712520'>basins</span> <span m='2712940'>of</span> <span m='2713030'>attraction.</span>
  </p><p><span m='2715030'>So</span> <span m='2715130'>this is</span> <span m='2715240'>often</span>
  <span m='2715570'>a</span> <span m='2715630'>nice</span> <span m='2715900'>way</span>
  <span m='2716830'>to</span> <span m='2718330'>supplement</span> <span m='2718900'>the</span>
  <span m='2718990'>Newton-Raphson</span> <span m='2719470'>method</span> <span m='2719740'>when</span>
  <span m='2719830'>your</span> <span m='2719920'>guesses</span> <span m='2720310'>aren't</span>
  <span m='2720520'>very</span> <span m='2720760'>good</span> <span m='2721000'>to</span>
  <span m='2721120'>begin</span> <span m='2721390'>with.</span> <span m='2722110'>When</span>
  <span m='2722230'>you</span> <span m='2722290'>start</span> <span m='2722470'>to</span>
  <span m='2722530'>get</span> <span m='2722620'>close</span> <span m='2722920'>to</span>
  <span m='2723160'>root</span> <span m='2723370'>you're,</span> <span m='2723490'>always</span>
  <span m='2723730'>just</span> <span m='2723880'>going</span> <span m='2724000'>to
  accept</span> <span m='2724360'>alpha</span> <span m='2724550'>equals</span> <span
  m='2724930'>1.</span> <span m='2725650'>The</span> <span m='2725740'>first</span>
  <span m='2726010'>step</span> <span m='2726280'>will</span> <span m='2726400'>be</span>
  <span m='2726520'>the</span> <span m='2726610'>best</span> <span m='2726850'>step,</span>
  <span m='2727480'>and</span> <span m='2727600'>then</span> <span m='2727720'>you'll</span>
  <span m='2727840'>converge</span> <span m='2728290'>very</span> <span m='2728470'>rapidly</span>
  <span m='2728980'>to</span> <span m='2729100'>the</span> <span m='2729220'>solution.</span>
  <span m='2730825'>Do we</span> <span m='2731210'>have</span> <span m='2731490'>to</span>
  <span m='2731680'>do</span> <span m='2731800'>any</span> <span m='2731980'>extra</span>
  <span m='2732250'>work</span> <span m='2732670'>actually</span> <span m='2733150'>to</span>
  <span m='2734200'>do</span> <span m='2734410'>this</span> <span m='2734560'>Damped</span>
  <span m='2734770'>Newton-Raphson</span> <span m='2735100'>method.</span> <span m='2735460'>Does</span>
  <span m='2735610'>it</span> <span m='2735660'>require</span> <span m='2736000'>extra</span>
  <span m='2736390'>calculations?</span> </p><p><span m='2743010'>What</span> <span
  m='2743100'>do</span> <span m='2743160'>you</span> <span m='2743220'>think?</span>
  <span m='2744390'>A</span> <span m='2744450'>lot</span> <span m='2744600'>of</span>
  <span m='2744660'>extra--</span> <span m='2745020'>a</span> <span m='2745080'>lot</span>
  <span m='2745260'>of</span> <span m='2745350'>extra</span> <span m='2745590'>calculation?</span>
  <span m='2745890'>How</span> <span m='2746010'>many</span> <span m='2746190'>extra</span>
  <span m='2746430'>calculations</span> <span m='2747090'>does</span> <span m='2747240'>it</span>
  <span m='2747330'>require?</span> <span m='2747780'>Of</span> <span m='2747920'>course</span>
  <span m='2748140'>it requires</span> <span m='2748400'>extra.</span> <span m='2748990'>How</span>
  <span m='2749090'>many?</span> </p><p><span m='2750246'>AUDIENCE:</span> <span m='2750729'>[INAUDIBLE]</span>
  </p><p><span m='2755076'>JAMES SWAN:</span> <span m='2755560'>What do</span> <span
  m='2755620'>you</span> <span m='2755680'>think?</span> </p><p><span m='2756712'>AUDIENCE:</span>
  <span m='2757080'>[INAUDIBLE]</span> </p><p><span m='2767180'>JAMES SWAN:</span>
  <span m='2767310'>It's--</span> <span m='2768360'>that</span> <span m='2768540'>much
  is</span> <span m='2768700'>true.</span> <span m='2769060'>So</span> <span m='2769320'>let's</span>
  <span m='2769470'>talk</span> <span m='2769620'>about</span> <span m='2769770'>taking</span>
  <span m='2770130'>one</span> <span m='2770340'>step.</span> <span m='2773160'>How</span>
  <span m='2773370'>many</span> <span m='2773550'>more--</span> <span m='2774490'>how</span>
  <span m='2774690'>many</span> <span m='2774840'>more</span> <span m='2774960'>calculations</span>
  <span m='2775770'>do</span> <span m='2775860'>I</span> <span m='2775890'>have</span>
  <span m='2775980'>to</span> <span m='2776100'>pay</span> <span m='2776490'>to</span>
  <span m='2776670'>do</span> <span m='2776940'>this</span> <span m='2777150'>sort</span>
  <span m='2777390'>of</span> <span m='2777480'>a</span> <span m='2777540'>step?</span>
  <span m='2778110'>Or</span> <span m='2778260'>even</span> <span m='2780030'>write</span>
  <span m='2780240'>the</span> <span m='2780360'>multidimensional</span> <span m='2781200'>step?</span>
  </p><p><span m='2784160'>For</span> <span m='2784340'>each</span> <span m='2784610'>of</span>
  <span m='2784700'>these</span> <span m='2785180'>times</span> <span m='2785810'>around</span>
  <span m='2786230'>this</span> <span m='2786440'>loop,</span> <span m='2787185'>do</span>
  <span m='2787510'>I</span> <span m='2787630'>have</span> <span m='2787760'>to</span>
  <span m='2788030'>recompute?</span> <span m='2788810'>Do I</span> <span m='2788960'>have</span>
  <span m='2789080'>to</span> <span m='2789170'>solve</span> <span m='2789560'>the</span>
  <span m='2789680'>system</span> <span m='2790040'>of</span> <span m='2790160'>equations?</span>
  <span m='2792420'>No.</span> <span m='2792930'>Right?</span> <span m='2793170'>You</span>
  <span m='2793320'>precompute</span> <span m='2793860'>this,</span> <span m='2794310'>right?</span>
  <span m='2794970'>This</span> <span m='2795150'>is</span> <span m='2795270'>the</span>
  <span m='2795360'>basic</span> <span m='2795720'>Newton-Raphson</span> <span m='2796320'>step.</span>
  <span m='2796560'>You</span> <span m='2796650'>compute</span> <span m='2796950'>that</span>
  <span m='2797160'>first.</span> <span m='2797480'>You've</span> <span m='2797550'>got</span>
  <span m='2797640'>to</span> <span m='2797730'>do</span> <span m='2797850'>it</span>
  <span m='2797940'>once.</span> <span m='2799470'>And</span> <span m='2799590'>then</span>
  <span m='2799770'>it's</span> <span m='2799950'>pretty</span> <span m='2800190'>cheap</span>
  <span m='2800700'>after</span> <span m='2800970'>that.</span> <span m='2801570'>I've</span>
  <span m='2801630'>got</span> <span m='2801750'>to</span> <span m='2801840'>do</span>
  <span m='2801960'>some</span> <span m='2802110'>extra</span> <span m='2802350'>function</span>
  <span m='2802740'>evaluations,</span> <span m='2803430'>but</span> <span m='2803520'>I
  don't actually</span> <span m='2803790'>have</span> <span m='2803880'>to</span>
  <span m='2803970'>solve</span> <span m='2804240'>the</span> <span m='2804300'>system</span>
  <span m='2804630'>of</span> <span m='2804720'>equations.</span> </p><p><span m='2805320'>Remember</span>
  <span m='2806730'>this</span> <span m='2807150'>is</span> <span m='2807540'>order</span>
  <span m='2807900'>n</span> <span m='2808140'>cubed.</span> <span m='2809040'>If</span>
  <span m='2809130'>we</span> <span m='2809250'>solve</span> <span m='2809520'>it</span>
  <span m='2809610'>exactly,</span> <span m='2811050'>maybe</span> <span m='2812070'>order</span>
  <span m='2812550'>n</span> <span m='2812760'>squared</span> <span m='2813190'>or</span>
  <span m='2813410'>order</span> <span m='2813690'>n</span> <span m='2813960'>if</span>
  <span m='2814080'>we</span> <span m='2814140'>do</span> <span m='2814270'>it</span>
  <span m='2814350'>iteratively.</span> <span m='2815160'>And</span> <span m='2815580'>the</span>
  <span m='2816110'>Jacobian</span> <span m='2816660'>is</span> <span m='2816750'>sparse</span>
  <span m='2817160'>somehow,</span> <span m='2817620'>and we</span> <span m='2817770'>know</span>
  <span m='2817920'>about</span> <span m='2818160'>it</span> <span m='2818260'>sparsity</span>
  <span m='2818760'>pattern.</span> <span m='2819510'>This</span> <span m='2819690'>is</span>
  <span m='2819810'>expensive.</span> <span m='2820320'>Function</span> <span m='2820680'>evaluations,</span>
  <span m='2821430'>those</span> <span m='2821580'>are</span> <span m='2821670'>order</span>
  <span m='2821970'>n</span> <span m='2822330'>to</span> <span m='2822480'>compute.</span>
  <span m='2824040'>Relatively</span> <span m='2824520'>cheap</span> <span m='2824760'>by</span>
  <span m='2824880'>comparison.</span> </p><p><span m='2825490'>So</span> <span m='2825990'>you</span>
  <span m='2826080'>compute</span> <span m='2826410'>your</span> <span m='2826560'>initial</span>
  <span m='2826950'>step.</span> <span m='2828760'>That's</span> <span m='2828970'>expensive.</span>
  <span m='2829690'>But</span> <span m='2829930'>all</span> <span m='2830350'>of</span>
  <span m='2830530'>this</span> <span m='2831070'>down</span> <span m='2831340'>here</span>
  <span m='2832390'>is</span> <span m='2832480'>pretty</span> <span m='2832690'>cheap.</span>
  <span m='2833500'>Yeah?</span> </p><p><span m='2834211'>AUDIENCE:</span> <span m='2834692'>You're
  also</span> <span m='2835173'>assuming that your function</span> <span m='2835654'>evaluations
  are</span> <span m='2836135'>reasonably true.</span> </p><p><span m='2836620'>JAMES
  SWAN:</span> <span m='2836770'>This</span> <span m='2837220'>is</span> <span m='2837320'>true.</span>
  </p><p><span m='2837530'>AUDIENCE:</span> <span m='2838000'>[INAUDIBLE]</span> </p><p><span
  m='2839880'>JAMES SWAN:</span> <span m='2839940'>It's</span> <span m='2840000'>true.</span>
  <span m='2840390'>Well,</span> <span m='2840640'>Jacobian</span> <span m='2841040'>is</span>
  <span m='2841150'>also</span> <span m='2841360'>very</span> <span m='2841570'>expensive</span>
  <span m='2841960'>to</span> <span m='2842080'>compute</span> <span m='2842420'>then</span>
  <span m='2842630'>too.</span> <span m='2843250'>So,</span> <span m='2844450'>if--</span>
  </p><p><span m='2844830'>AUDIENCE:</span> <span m='2844920'>[INAUDIBLE]</span> </p><p><span
  m='2848830'>JAMES SWAN:</span> <span m='2848985'>Sure, sure,</span> <span m='2849140'>sure.</span>
  <span m='2849560'>No,</span> <span m='2849830'>I</span> <span m='2850430'>don't</span>
  <span m='2850580'>disagree.</span> <span m='2851210'>I</span> <span m='2851300'>think</span>
  <span m='2851450'>one</span> <span m='2851600'>has</span> <span m='2851780'>to</span>
  <span m='2851900'>pick</span> <span m='2852950'>the</span> <span m='2853040'>method</span>
  <span m='2853340'>you're</span> <span m='2853430'>going</span> <span m='2853550'>to</span>
  <span m='2853610'>use</span> <span m='2854510'>to</span> <span m='2854690'>suit</span>
  <span m='2854900'>the</span> <span m='2854990'>problem.</span> <span m='2855380'>But</span>
  <span m='2855470'>turns</span> <span m='2855680'>out</span> <span m='2855800'>this</span>
  <span m='2856430'>doesn't</span> <span m='2856670'>involve</span> <span m='2856910'>much</span>
  <span m='2857120'>extra</span> <span m='2857390'>calculation.</span> <span m='2857900'>So</span>
  <span m='2858020'>by</span> <span m='2858140'>default,</span> <span m='2858560'>for</span>
  <span m='2858680'>example,</span> <span m='2859260'>fsolve</span> <span m='2859520'>in</span>
  <span m='2859640'>MATLAB</span> <span m='2860060'>is going</span> <span m='2860180'>to</span>
  <span m='2860450'>do</span> <span m='2860600'>this</span> <span m='2860960'>for</span>
  <span m='2861140'>you.</span> <span m='2861560'>Or</span> <span m='2861680'>some</span>
  <span m='2861860'>version</span> <span m='2862250'>of</span> <span m='2862340'>this.</span>
  <span m='2863450'>it's</span> <span m='2863570'>going</span> <span m='2863690'>to</span>
  <span m='2863750'>try</span> <span m='2863900'>to</span> <span m='2863990'>take</span>
  <span m='2864200'>steps</span> <span m='2864650'>that</span> <span m='2865430'>aren't</span>
  <span m='2865670'>too</span> <span m='2865880'>big.</span> <span m='2866150'>It
  will</span> <span m='2866240'>limit</span> <span m='2866660'>the</span> <span m='2866780'>step</span>
  <span m='2867050'>size</span> <span m='2867380'>for</span> <span m='2867580'>you,</span>
  <span m='2867740'>so</span> <span m='2868010'>that</span> <span m='2868190'>it</span>
  <span m='2868250'>keeps</span> <span m='2868640'>the</span> <span m='2868910'>value</span>
  <span m='2869330'>of</span> <span m='2869390'>the</span> <span m='2869510'>function</span>
  <span m='2869990'>reducing</span> <span m='2870830'>in</span> <span m='2870980'>magnitude.</span>
  <span m='2872320'>It's</span> <span m='2872530'>a</span> <span m='2872600'>pretty</span>
  <span m='2872780'>good</span> <span m='2872930'>general</span> <span m='2873350'>strategy.</span>
  <span m='2875160'>Yes?</span> </p><p><span m='2875998'>AUDIENCE:</span> <span m='2876496'>[INAUDIBLE]</span>
  <span m='2879484'>so</span> <span m='2879982'>why</span> <span m='2880480'>do</span>
  <span m='2880978'>we</span> <span m='2881476'>just</span> <span m='2881974'>pick</span>
  <span m='2882472'>one value</span> <span m='2882970'>for</span> <span m='2883468'>[INAUDIBLE]</span>
  </p><p><span m='2888960'>JAMES SWAN:</span> <span m='2889000'>I</span> <span m='2889040'>see.</span>
  <span m='2889250'>So</span> <span m='2889370'>why--</span> <span m='2890080'>ask</span>
  <span m='2890500'>that</span> <span m='2890780'>one</span> <span m='2890900'>more</span>
  <span m='2890990'>time.</span> <span m='2891160'>This</span> <span m='2891650'>is</span>
  <span m='2891740'>a</span> <span m='2891800'>good</span> <span m='2891920'>question.</span>
  <span m='2892640'>Can</span> <span m='2892670'>you</span> <span m='2893180'>say</span>
  <span m='2893300'>it</span> <span m='2893360'>a</span> <span m='2893390'>little</span>
  <span m='2893640'>louder so</span> <span m='2894130'>everyone can</span> <span m='2894260'>hear?</span>
  </p><p><span m='2894410'>AUDIENCE:</span> <span m='2894893'>So</span> <span m='2895376'>why,
  instead of</span> <span m='2895859'>having</span> <span m='2896342'>just one</span>
  <span m='2896825'>value of</span> <span m='2897308'>alpha</span> <span m='2897791'>and
  not</span> <span m='2898274'>having</span> <span m='2898757'>several</span> <span
  m='2899240'>values of</span> <span m='2899723'>alpha</span> <span m='2900206'>[INAUDIBLE]</span>
  </p><p><span m='2902150'>JAMES SWAN:</span> <span m='2902210'>I</span> <span m='2902270'>see.</span>
  <span m='2902450'>So</span> <span m='2902690'>the</span> <span m='2902840'>question</span>
  <span m='2903260'>is,</span> <span m='2903980'>yeah,</span> <span m='2904190'>we</span>
  <span m='2904340'>used</span> <span m='2904550'>a</span> <span m='2904670'>scalar</span>
  <span m='2905360'>alpha</span> <span m='2905780'>here,</span> <span m='2906740'>right?</span>
  <span m='2907550'>If</span> <span m='2907670'>we</span> <span m='2907760'>wanted</span>
  <span m='2908150'>to,</span> <span m='2908840'>we</span> <span m='2908990'>could</span>
  <span m='2909140'>reduce</span> <span m='2909500'>the</span> <span m='2909620'>step</span>
  <span m='2909860'>size</span> <span m='2910130'>and</span> <span m='2910250'>also</span>
  <span m='2910520'>change</span> <span m='2911300'>direction.</span> <span m='2912260'>We</span>
  <span m='2912350'>would</span> <span m='2912440'>use</span> <span m='2912590'>a</span>
  <span m='2912620'>matrix</span> <span m='2913100'>to</span> <span m='2913220'>do</span>
  <span m='2913340'>that,</span> <span m='2913520'>instead,</span> <span m='2913970'>right?</span>
  <span m='2914960'>It</span> <span m='2915020'>would</span> <span m='2915110'>transform</span>
  <span m='2915740'>the</span> <span m='2915830'>step</span> <span m='2916160'>and</span>
  <span m='2916280'>change</span> <span m='2916610'>its</span> <span m='2916790'>direction.</span>
  <span m='2917180'>And</span> <span m='2917270'>maybe</span> <span m='2917510'>we</span>
  <span m='2917630'>would</span> <span m='2917780'>choose</span> <span m='2918200'>different</span>
  <span m='2918890'>alphas</span> <span m='2919340'>along</span> <span m='2919580'>different</span>
  <span m='2919850'>directions,</span> <span m='2920420'>for</span> <span m='2920570'>example.</span>
  <span m='2920850'>So</span> <span m='2921310'>diagonal</span> <span m='2921800'>matrix</span>
  <span m='2922160'>with</span> <span m='2922280'>different</span> <span m='2922490'>alphas.</span>
  </p><p><span m='2923300'>We</span> <span m='2923390'>could</span> <span m='2923660'>potentially</span>
  <span m='2924200'>do</span> <span m='2924410'>that.</span> <span m='2926150'>we're</span>
  <span m='2926270'>probably</span> <span m='2926720'>going</span> <span m='2926870'>to</span>
  <span m='2926960'>need</span> <span m='2927410'>some</span> <span m='2929690'>extra</span>
  <span m='2929990'>information</span> <span m='2930650'>to</span> <span m='2930770'>decide</span>
  <span m='2931250'>how</span> <span m='2931580'>to</span> <span m='2931970'>set</span>
  <span m='2932750'>the</span> <span m='2932870'>scaling</span> <span m='2933350'>in</span>
  <span m='2933470'>different</span> <span m='2933710'>directions.</span> <span m='2935400'>One</span>
  <span m='2935480'>thing</span> <span m='2935630'>we</span> <span m='2935780'>know</span>
  <span m='2936110'>for</span> <span m='2936320'>sure</span> <span m='2937610'>is</span>
  <span m='2937760'>that</span> <span m='2937910'>the</span> <span m='2938000'>Newton-Raphson</span>
  <span m='2938780'>step</span> <span m='2939770'>will</span> <span m='2940130'>reduce</span>
  <span m='2940520'>the</span> <span m='2940610'>value</span> <span m='2940910'>of</span>
  <span m='2941000'>the</span> <span m='2941090'>function.</span> <span m='2941550'>If</span>
  <span m='2941570'>we</span> <span m='2941660'>take</span> <span m='2941840'>a</span>
  <span m='2941900'>small</span> <span m='2942350'>enough</span> <span m='2942560'>step</span>
  <span m='2942890'>size,</span> <span m='2943490'>it</span> <span m='2943640'>will</span>
  <span m='2943970'>bring</span> <span m='2944390'>the</span> <span m='2944480'>value</span>
  <span m='2944750'>of</span> <span m='2944840'>the</span> <span m='2944960'>function</span>
  <span m='2945410'>down.</span> </p><p><span m='2945890'>We</span> <span m='2946010'>know</span>
  <span m='2946190'>that</span> <span m='2946370'>because</span> <span m='2947210'>we</span>
  <span m='2947300'>did</span> <span m='2947450'>the</span> <span m='2947510'>Taylor</span>
  <span m='2947870'>Expansion</span> <span m='2948350'>of</span> <span m='2948410'>the</span>
  <span m='2948500'>function</span> <span m='2949070'>to</span> <span m='2949220'>determine</span>
  <span m='2949730'>that</span> <span m='2949940'>step</span> <span m='2950240'>size.</span>
  <span m='2951710'>And</span> <span m='2951860'>that</span> <span m='2952010'>Taylor</span>
  <span m='2952310'>expansion</span> <span m='2952760'>was</span> <span m='2952880'>going</span>
  <span m='2953000'>to</span> <span m='2953060'>be--</span> <span m='2953950'>that</span>
  <span m='2954200'>Taylor</span> <span m='2954440'>expansion</span> <span m='2954980'>is</span>
  <span m='2955580'>nearly</span> <span m='2956060'>exact</span> <span m='2956810'>in</span>
  <span m='2956930'>the</span> <span m='2957020'>limit</span> <span m='2957170'>of</span>
  <span m='2957320'>very,</span> <span m='2957660'>very</span> <span m='2957770'>small</span>
  <span m='2958130'>step</span> <span m='2958430'>sizes.</span> <span m='2958820'>So</span>
  <span m='2959000'>there</span> <span m='2959090'>will</span> <span m='2959270'>always</span>
  <span m='2959660'>be</span> <span m='2959810'>some</span> <span m='2960170'>small</span>
  <span m='2960500'>step</span> <span m='2961220'>in</span> <span m='2961460'>this</span>
  <span m='2961880'>direction,</span> <span m='2964010'>which</span> <span m='2964090'>will</span>
  <span m='2964210'>reduce</span> <span m='2964570'>the</span> <span m='2964660'>value</span>
  <span m='2964930'>of</span> <span m='2965020'>the</span> <span m='2965140'>function.</span>
  </p><p><span m='2965720'>In</span> <span m='2965800'>other</span> <span m='2966010'>directions,</span>
  <span m='2966970'>we</span> <span m='2967120'>may</span> <span m='2967270'>reduce</span>
  <span m='2967540'>the</span> <span m='2967630'>value</span> <span m='2967840'>of</span>
  <span m='2967930'>the</span> <span m='2967990'>function</span> <span m='2968320'>faster.</span>
  <span m='2970090'>We</span> <span m='2970210'>don't</span> <span m='2970330'>know</span>
  <span m='2970450'>which</span> <span m='2970630'>directions</span> <span m='2971230'>to</span>
  <span m='2971350'>choose,</span> <span m='2972090'>OK?</span> <span m='2972810'>Actually</span>
  <span m='2973210'>I</span> <span m='2973270'>shouldn't</span> <span m='2973450'>say</span>
  <span m='2973630'>that.</span> <span m='2973810'>When</span> <span m='2973990'>we</span>
  <span m='2974050'>take</span> <span m='2974200'>very</span> <span m='2974350'>small</span>
  <span m='2974665'>step sizes</span> <span m='2974980'>in this</span> <span m='2975220'>direction,</span>
  <span m='2975610'>it's</span> <span m='2975760'>reducing</span> <span m='2976090'>the</span>
  <span m='2976180'>value</span> <span m='2976360'>of</span> <span m='2976420'>the</span>
  <span m='2976510'>function</span> <span m='2976910'>fastest.</span> <span m='2977200'>There</span>
  <span m='2977490'>isn't a</span> <span m='2977660'>faster</span> <span m='2978040'>direction</span>
  <span m='2978460'>to</span> <span m='2978580'>go</span> <span m='2978850'>in.</span>
  </p><p><span m='2979480'>When</span> <span m='2979600'>we</span> <span m='2979690'>take</span>
  <span m='2980800'>impossibly</span> <span m='2981430'>small,</span> <span m='2982060'>vanishingly</span>
  <span m='2982780'>small</span> <span m='2983140'>step</span> <span m='2983410'>sizes.</span>
  <span m='2984820'>But</span> <span m='2984910'>in</span> <span m='2985000'>principle,</span>
  <span m='2985300'>if</span> <span m='2985420'>I</span> <span m='2985480'>had</span>
  <span m='2985600'>some</span> <span m='2985750'>extra</span> <span m='2985990'>information</span>
  <span m='2986500'>on</span> <span m='2986560'>the</span> <span m='2986650'>problem,</span>
  <span m='2986860'>I</span> <span m='2986950'>might</span> <span m='2987100'>be</span>
  <span m='2987190'>able</span> <span m='2987310'>to</span> <span m='2987400'>choose</span>
  <span m='2987820'>step</span> <span m='2988030'>sizes</span> <span m='2988480'>along</span>
  <span m='2988780'>different</span> <span m='2989050'>directions.</span> <span m='2989440'>I</span>
  <span m='2989530'>may</span> <span m='2989680'>know</span> <span m='2990520'>that</span>
  <span m='2990640'>one</span> <span m='2990820'>of</span> <span m='2990910'>these</span>
  <span m='2991090'>directions</span> <span m='2991600'>is</span> <span m='2991750'>more</span>
  <span m='2992560'>ill-behaved</span> <span m='2993340'>than</span> <span m='2993520'>the</span>
  <span m='2993640'>other</span> <span m='2993850'>ones.</span> <span m='2995080'>And</span>
  <span m='2995290'>choose</span> <span m='2995800'>a</span> <span m='2995890'>different</span>
  <span m='2996160'>damping</span> <span m='2996550'>factor</span> <span m='2996940'>for</span>
  <span m='2997180'>it.</span> <span m='2997480'>That's</span> <span m='2997630'>a</span>
  <span m='2997690'>possibility.</span> </p><p><span m='2998290'>But</span> <span
  m='2998590'>we</span> <span m='2998680'>actually</span> <span m='2998860'>have</span>
  <span m='2998950'>to</span> <span m='2999040'>know</span> <span m='2999730'>something</span>
  <span m='3000030'>about</span> <span m='3000180'>the</span> <span m='3000270'>details</span>
  <span m='3000690'>of</span> <span m='3000750'>the</span> <span m='3000840'>problem</span>
  <span m='3001050'>we're</span> <span m='3001110'>trying</span> <span m='3001320'>to</span>
  <span m='3001410'>solve</span> <span m='3001760'>if we're going</span> <span m='3002030'>to
  do--</span> <span m='3002340'>it's</span> <span m='3002490'>a</span> <span m='3002550'>wonderful</span>
  <span m='3002910'>question.</span> <span m='3003820'>I</span> <span m='3003920'>mean,</span>
  <span m='3004800'>you</span> <span m='3004980'>could</span> <span m='3005100'>think</span>
  <span m='3005280'>about</span> <span m='3005460'>ways</span> <span m='3005880'>of</span>
  <span m='3006030'>making</span> <span m='3006420'>this</span> <span m='3006630'>more,</span>
  <span m='3007080'>potentially</span> <span m='3007590'>more</span> <span m='3007800'>robust.</span>
  <span m='3008310'>I'll</span> <span m='3008370'>show</span> <span m='3008510'>you</span>
  <span m='3008580'>an</span> <span m='3008670'>alternative</span> <span m='3009240'>way</span>
  <span m='3009450'>of</span> <span m='3009540'>doing</span> <span m='3009810'>this</span>
  <span m='3009990'>when</span> <span m='3010140'>we</span> <span m='3010200'>talk</span>
  <span m='3010410'>about</span> <span m='3010680'>optimization.</span> <span m='3012660'>In</span>
  <span m='3012810'>optimization</span> <span m='3013350'>we'll</span> <span m='3013470'>do--</span>
  <span m='3013890'>we'll</span> <span m='3014010'>solve</span> <span m='3014280'>systems</span>
  <span m='3014730'>of</span> <span m='3014850'>nonlinear</span> <span m='3015300'>equations</span>
  <span m='3015780'>to</span> <span m='3015840'>solve</span> <span m='3016080'>these</span>
  <span m='3016230'>optimization</span> <span m='3016890'>problems.</span> </p><p><span
  m='3017550'>There's</span> <span m='3017700'>another</span> <span m='3017970'>way</span>
  <span m='3018090'>of</span> <span m='3018180'>doing</span> <span m='3018420'>the</span>
  <span m='3018510'>same</span> <span m='3018780'>sort</span> <span m='3018960'>of</span>
  <span m='3019050'>strategy</span> <span m='3020220'>that's</span> <span m='3020520'>more</span>
  <span m='3020850'>along</span> <span m='3021150'>what</span> <span m='3021300'>you're</span>
  <span m='3021450'>describing.</span> <span m='3021870'>Maybe</span> <span m='3022080'>there's</span>
  <span m='3022230'>a</span> <span m='3022260'>different</span> <span m='3022500'>direction</span>
  <span m='3023040'>to</span> <span m='3023190'>choose</span> <span m='3023520'>instead</span>
  <span m='3024000'>that</span> <span m='3024120'>could</span> <span m='3024270'>be</span>
  <span m='3024420'>preferable.</span> <span m='3025130'>This</span> <span m='3025290'>is</span>
  <span m='3025350'>something</span> <span m='3025590'>called</span> <span m='3025740'>the</span>
  <span m='3025860'>dogleg</span> <span m='3026160'>method.</span> <span m='3027640'>Great</span>
  <span m='3028310'>question.</span> <span m='3030230'>Anything</span> <span m='3030500'>else?</span>
  <span m='3032280'>No.</span> </p><p><span m='3036120'>So</span> <span m='3036780'>globally</span>
  <span m='3037230'>convergent,</span> <span m='3038040'>right?</span> <span m='3039720'>Converges</span>
  <span m='3040320'>to</span> <span m='3040440'>roots,</span> <span m='3040860'>local</span>
  <span m='3041160'>minima or</span> <span m='3041500'>maxima.</span> <span m='3043200'>There</span>
  <span m='3043320'>are</span> <span m='3043380'>other</span> <span m='3043590'>modifications</span>
  <span m='3044250'>that</span> <span m='3044370'>are</span> <span m='3044430'>possible.</span>
  <span m='3044820'>We'll</span> <span m='3044910'>talk</span> <span m='3045120'>about</span>
  <span m='3045330'>them</span> <span m='3045480'>in</span> <span m='3045570'>optimization.</span>
  <span m='3046780'>There's</span> <span m='3046860'>always</span> <span m='3047070'>a</span>
  <span m='3047130'>penalty</span> <span m='3047520'>to</span> <span m='3047640'>doing</span>
  <span m='3047910'>this.</span> <span m='3048270'>The</span> <span m='3048360'>penalty</span>
  <span m='3048810'>is</span> <span m='3048960'>in</span> <span m='3049080'>the</span>
  <span m='3049170'>rate</span> <span m='3049350'>of</span> <span m='3049410'>convergence.</span>
  <span m='3050550'>So</span> <span m='3050680'>it will</span> <span m='3050760'>converge</span>
  <span m='3051150'>more</span> <span m='3051300'>slowly.</span> <span m='3051910'>But</span>
  <span m='3052010'>maybe you</span> <span m='3052170'>speed</span> <span m='3052410'>the</span>
  <span m='3052500'>calculations</span> <span m='3053130'>along</span> <span m='3053400'>anyways,</span>
  <span m='3053790'>right?</span> </p><p><span m='3054130'>Maybe it</span> <span m='3054270'>requires</span>
  <span m='3055080'>fewer</span> <span m='3055350'>iterations</span> <span m='3055950'>overall</span>
  <span m='3056370'>to</span> <span m='3056520'>get</span> <span m='3056730'>there</span>
  <span m='3056910'>because</span> <span m='3057210'>you</span> <span m='3057360'>tame</span>
  <span m='3058590'>the</span> <span m='3058770'>locally</span> <span m='3059280'>convergent</span>
  <span m='3059700'>properties</span> <span m='3060150'>of</span> <span m='3060210'>the</span>
  <span m='3060300'>Newton-Raphson</span> <span m='3060900'>method.</span> <span m='3061260'>Or</span>
  <span m='3062040'>you</span> <span m='3062340'>shortcut</span> <span m='3063300'>some</span>
  <span m='3063510'>of</span> <span m='3063570'>the</span> <span m='3063780'>expensive</span>
  <span m='3064350'>calculations,</span> <span m='3065160'>like</span> <span m='3065310'>getting</span>
  <span m='3065670'>your</span> <span m='3065850'>Jacobian</span> <span m='3066540'>or</span>
  <span m='3066600'>calculating</span> <span m='3066900'>your</span> <span m='3067200'>Jacobian</span>
  <span m='3067740'>inverse.</span> <span m='3069010'>All</span> <span m='3069090'>right?</span>
  </p><p><span m='3070280'>So</span> <span m='3070410'>Monday</span> <span m='3070740'>we're</span>
  <span m='3070830'>going</span> <span m='3070950'>to</span> <span m='3071190'>review</span>
  <span m='3071820'>sort</span> <span m='3072000'>of</span> <span m='3072120'>topics</span>
  <span m='3072570'>up</span> <span m='3072690'>til</span> <span m='3072820'>now.</span>
  <span m='3073050'>Professor</span> <span m='3073420'>Green</span> <span m='3073980'>will</span>
  <span m='3074550'>run</span> <span m='3074790'>the</span> <span m='3074880'>lecture</span>
  <span m='3075180'>on</span> <span m='3075270'>Monday.</span> <span m='3075600'>And</span>
  <span m='3075690'>then</span> <span m='3075780'>after</span> <span m='3076020'>that,</span>
  <span m='3076170'>we'll</span> <span m='3076290'>pick</span> <span m='3076500'>up</span>
  <span m='3076650'>with</span> <span m='3076950'>optimization,</span> <span m='3077800'>which</span>
  <span m='3077850'>will</span> <span m='3078000'>follow</span> <span m='3078430'>right
  on</span> <span m='3078810'>from what</span> <span m='3078900'>we've</span> <span
  m='3079020'>done</span> <span m='3079230'>so</span> <span m='3079380'>far.</span>
  <span m='3079680'>Thanks.</span> </p>
type: course
uid: 44db3d5653762ccc6b2e9efc295dfe51

---
None