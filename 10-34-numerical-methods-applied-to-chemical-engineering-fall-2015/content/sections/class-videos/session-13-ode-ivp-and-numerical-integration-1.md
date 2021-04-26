---
about_this_resource_text: <p><strong>Description:</strong> This lecture covered the
  topics on ordinary differential equation with initial value problem (ODE-IVP) and
  numerical integration.</p> <p><strong>Instructor:</strong> William Green</p>
course_id: 10-34-numerical-methods-applied-to-chemical-engineering-fall-2015
embedded_media:
- id: Video-YouTube-Stream
  media_location: KkN_Dk3E2yw
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: Video-YouTube-Stream
  type: Video
  uid: bbc7512d12191dcd150139eccb6cf6c1
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/KkN_Dk3E2yw/default.jpg
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 36e93f18f5e9d950a5e535568251d980
- id: 3Play-3PlayYouTubeid-MP4
  media_location: KkN_Dk3E2yw
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8b36943eaec16eb572e28ee8f16c3810
- id: KkN_Dk3E2yw.srt
  parent_uid: 025e160abba890f59d132d00a605bf33
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-13-ode-ivp-and-numerical-integration-1/KkN_Dk3E2yw.srt
  title: 3play caption file
  type: null
  uid: caa7c9692f49596df6c26dad24887b67
- id: KkN_Dk3E2yw.pdf
  parent_uid: 025e160abba890f59d132d00a605bf33
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-13-ode-ivp-and-numerical-integration-1/KkN_Dk3E2yw.pdf
  title: 3play pdf file
  type: null
  uid: 9a610a09d15162096fb294545cd58686
- id: Caption-3Play YouTube id-SRT
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 21294ac253e78a612bb1402c995dcad7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1968f74a9f3361e1cd87154907b5e49d
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id1271456481
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: Video-iTunes U-MP4
  type: Video
  uid: beaac6427e5719a7733723978fc02f8c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT10.34F15/MIT10_34F15_ses13_300k.mp4
  parent_uid: 025e160abba890f59d132d00a605bf33
  title: Video-Internet Archive-MP4
  type: Video
  uid: 5bc0a7c7a8042685a8525e1ed785589c
inline_embed_id: 98391627session13odeivpandnumericalintegration13047092
layout: video
order_index: null
parent_uid: afa0ff29750f6846eda04cb1a3d4b84a
related_resources_text: ''
short_url: session-13-ode-ivp-and-numerical-integration-1
technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-13-ode-ivp-and-numerical-integration-1
template_type: Tabbed
title: 'Session 13: ODE-IVP and Numerical Integration 1'
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
  <span m='18100'>at</span> <span m='18250'>ocw.mit.edu.</span> </p><p><span m='24250'>WILLIAM
  GREEN JR:</span> <span m='24290'>All</span> <span m='24330'>right,</span> <span
  m='24570'>so we're</span> <span m='24830'>going to</span> <span m='25170'>start
  a new</span> <span m='25330'>topic</span> <span m='25820'>today</span> <span m='31910'>about</span>
  <span m='32549'>ordinary</span> <span m='32900'>differential</span> <span m='33260'>equations</span>
  <span m='33966'>initial</span> <span m='34490'>value</span> <span m='34710'>problems.</span>
  <span m='35555'>But</span> <span m='35900'>before</span> <span m='37610'>I</span>
  <span m='37730'>start to</span> <span m='37970'>talk</span> <span m='38180'>about</span>
  <span m='38360'>that,</span> <span m='39020'>I want</span> <span m='39140'>to</span>
  <span m='39240'>remind</span> <span m='39620'>you</span> <span m='39710'>next</span>
  <span m='39920'>week's</span> <span m='40070'>schedule is</span> <span m='40560'>weird.</span>
  <span m='41840'>So</span> <span m='42230'>there's</span> <span m='42560'>no</span>
  <span m='43040'>classes</span> <span m='43460'>on</span> <span m='43580'>Monday,</span>
  <span m='45170'>but</span> <span m='45320'>instead</span> <span m='45710'>we'll</span>
  <span m='45830'>have</span> <span m='46400'>Monday</span> <span m='46640'>class</span>
  <span m='46970'>on</span> <span m='47060'>Tuesday.</span> <span m='48860'>So</span>
  <span m='49730'>I'll</span> <span m='49880'>see</span> <span m='50060'>you</span>
  <span m='50120'>next on</span> <span m='50510'>Tuesday</span> <span m='50900'>morning.</span>
  </p><p><span m='51950'>And</span> <span m='52100'>then</span> <span m='53000'>we're</span>
  <span m='53180'>not</span> <span m='53360'>going</span> <span m='53480'>to</span>
  <span m='53540'>have</span> <span m='53660'>a</span> <span m='53690'>class</span>
  <span m='54050'>on</span> <span m='54290'>Wednesday,</span> <span m='55980'>but</span>
  <span m='56030'>we</span> <span m='56210'>have</span> <span m='56360'>the</span>
  <span m='56600'>quiz</span> <span m='56990'>on</span> <span m='57050'>Wednesday</span>
  <span m='57350'>night.</span> <span m='59490'>And</span> <span m='59610'>then</span>
  <span m='59760'>we'll</span> <span m='59880'>get</span> <span m='59970'>back</span>
  <span m='60120'>to</span> <span m='60180'>normal</span> <span m='60420'>on</span>
  <span m='60510'>Friday.</span> <span m='62250'>And</span> <span m='62460'>I</span>
  <span m='62700'>would</span> <span m='63000'>expect</span> <span m='63330'>that</span>
  <span m='63480'>possibly</span> <span m='63990'>the</span> <span m='64120'>TAs</span>
  <span m='64500'>might</span> <span m='64709'>be</span> <span m='64890'>interested</span>
  <span m='65340'>in</span> <span m='66400'>giving a</span> <span m='66570'>help</span>
  <span m='66730'>session</span> <span m='66990'>or</span> <span m='67200'>review</span>
  <span m='67710'>on</span> <span m='68280'>Wednesday</span> <span m='68770'>the</span>
  <span m='68880'>class</span> <span m='69140'>period.</span> </p><p><span m='70330'>AUDIENCE:</span>
  <span m='70456'>We'll</span> <span m='70582'>be</span> <span m='70710'>here at</span>
  <span m='71090'>3:00.</span> </p><p><span m='71470'>WILLIAM GREEN JR:</span> <span
  m='71540'>They'll</span> <span m='71610'>be</span> <span m='71730'>here.</span>
  <span m='71910'>So</span> <span m='72240'>if</span> <span m='72390'>you</span> <span
  m='72450'>want</span> <span m='72570'>to</span> <span m='72630'>come</span> <span
  m='72790'>at</span> <span m='72870'>class</span> <span m='73110'>period,</span>
  <span m='73390'>and</span> <span m='73560'>just ask</span> <span m='73740'>questions</span>
  <span m='74180'>and stuff.</span> </p><p><span m='74310'>AUDIENCE:</span> <span
  m='74469'>And</span> <span m='74628'>I'll</span> <span m='74788'>have your</span>
  <span m='75266'>PSAT</span> <span m='75744'>graded</span> <span m='76222'>back,
  if</span> <span m='76700'>you like.</span> </p><p><span m='78140'>WILLIAM GREEN
  JR:</span> <span m='78170'>All</span> <span m='78200'>right,</span> <span m='78710'>got</span>
  <span m='78850'>that?</span> <span m='79750'>PSAT</span> <span m='80070'>be</span>
  <span m='80160'>ready</span> <span m='80900'>as</span> <span m='80990'>well.</span>
  <span m='82400'>OK,</span> <span m='82790'>so</span> <span m='83220'>I'll</span>
  <span m='83300'>talk</span> <span m='83480'>about</span> <span m='84170'>today</span>
  <span m='85180'>ODE-IVPs.</span> </p><p><span m='86850'>AUDIENCE:</span> <span m='87006'>Yeah,
  we'll</span> <span m='87162'>still have</span> <span m='87320'>office hours</span>
  <span m='87790'>Monday</span> <span m='88260'>[INAUDIBLE]</span> </p><p><span m='91080'>WILLIAM
  GREEN JR:</span> <span m='91125'>Can</span> <span m='91170'>you</span> <span m='91230'>guys</span>
  <span m='91350'>hear</span> <span m='91470'>this?</span> <span m='93170'>Yes,</span>
  <span m='93830'>office</span> <span m='94100'>hours</span> <span m='94400'>like</span>
  <span m='94550'>normal</span> <span m='94880'>Monday.</span> <span m='98770'>And
  for</span> <span m='98930'>those of</span> <span m='99340'>you who</span> <span
  m='99440'>want</span> <span m='99590'>to</span> <span m='99650'>get</span> <span
  m='99740'>your</span> <span m='99860'>homework</span> <span m='100130'>started</span>
  <span m='100430'>early,</span> <span m='100700'>we</span> <span m='100820'>might</span>
  <span m='100940'>even</span> <span m='101090'>post</span> <span m='101360'>homework.</span>
  <span m='114290'>And</span> <span m='116240'>I'm</span> <span m='116300'>going</span>
  <span m='117080'>to</span> <span m='117140'>focus</span> <span m='118280'>exclusively</span>
  <span m='119030'>on</span> <span m='120380'>ODE-IVPs</span> <span m='121760'>you</span>
  <span m='121910'>can</span> <span m='122030'>write</span> <span m='122180'>this</span>
  <span m='122360'>way.</span> </p><p><span m='131600'>All</span> <span m='131660'>right,</span>
  <span m='133190'>and</span> <span m='133490'>I</span> <span m='133550'>would</span>
  <span m='133640'>just</span> <span m='134030'>comment,</span> <span m='136850'>what</span>
  <span m='137000'>do</span> <span m='137060'>these</span> <span m='137270'>things</span>
  <span m='137510'>mean?</span> <span m='137890'>ODE</span> <span m='138240'>means</span>
  <span m='138490'>ordinary</span> <span m='138680'>differential</span> <span m='139100'>equation.</span>
  <span m='140060'>It</span> <span m='140180'>means</span> <span m='140450'>that</span>
  <span m='141350'>the</span> <span m='141440'>only</span> <span m='141620'>differentials</span>
  <span m='142130'>in</span> <span m='142220'>the</span> <span m='142340'>problem</span>
  <span m='142950'>are with</span> <span m='143050'>respect</span> <span m='143340'>to</span>
  <span m='143420'>one</span> <span m='143690'>variable,</span> <span m='144230'>so</span>
  <span m='144690'>I'm going</span> <span m='145150'>to</span> <span m='145400'>call</span>
  <span m='145580'>that</span> <span m='145800'>t.</span> <span m='147200'>It</span>
  <span m='147260'>can</span> <span m='147410'>be</span> <span m='147530'>z</span>
  <span m='147830'>or</span> <span m='147950'>x</span> <span m='148250'>or</span>
  <span m='148340'>whatever</span> <span m='148610'>you</span> <span m='148670'>want,</span>
  <span m='149070'>but</span> <span m='149090'>I'm going</span> <span m='149230'>to</span>
  <span m='149460'>call it</span> <span m='149820'>t</span> <span m='150020'>here.</span>
  </p><p><span m='151190'>And</span> <span m='152660'>so</span> <span m='152810'>this</span>
  <span m='152930'>is</span> <span m='153000'>not</span> <span m='153140'>partial</span>
  <span m='153440'>differential</span> <span m='153800'>equations</span> <span m='154220'>where</span>
  <span m='154300'>you</span> <span m='154360'>have</span> <span m='154480'>differentials</span>
  <span m='155090'>respect</span> <span m='155360'>to</span> <span m='155480'>many</span>
  <span m='155690'>variables.</span> <span m='158030'>Initial</span> <span m='158420'>value</span>
  <span m='158750'>problems</span> <span m='159800'>mean</span> <span m='160110'>that</span>
  <span m='160460'>all</span> <span m='160820'>the</span> <span m='161780'>initial</span>
  <span m='162080'>conditions</span> <span m='164460'>are</span> <span m='164820'>given</span>
  <span m='164990'>in</span> <span m='165140'>at a</span> <span m='165200'>single</span>
  <span m='165680'>t</span> <span m='165980'>point</span> <span m='166530'>where</span>
  <span m='166780'>t</span> <span m='167060'>is</span> <span m='167180'>that</span>
  <span m='167570'>the</span> <span m='168650'>variable that</span> <span m='168990'>appears</span>
  <span m='169280'>in</span> <span m='169340'>the</span> <span m='169400'>differential.</span>
  <span m='173360'>All</span> <span m='173810'>right</span> <span m='173960'>so</span>
  <span m='174080'>this</span> <span m='174260'>is</span> <span m='174350'>the</span>
  <span m='174470'>form</span> <span m='174740'>we're</span> <span m='174800'>going</span>
  <span m='174920'>to</span> <span m='174980'>do.</span> </p><p><span m='175100'>This</span>
  <span m='175280'>is</span> <span m='175500'>first</span> <span m='175820'>order</span>
  <span m='176060'>a</span> <span m='176090'>way</span> <span m='176270'>of</span>
  <span m='176410'>writing</span> <span m='176720'>the</span> <span m='177662'>ODEs.</span>
  <span m='179880'>If</span> <span m='180020'>you</span> <span m='180140'>recall</span>
  <span m='180680'>from</span> <span m='181040'>homework</span> <span m='181460'>zero</span>
  <span m='182060'>problem</span> <span m='182390'>number</span> <span m='182730'>one,</span>
  <span m='184020'>we</span> <span m='184160'>showed</span> <span m='184400'>you</span>
  <span m='184490'>there</span> <span m='184860'>how</span> <span m='185030'>you</span>
  <span m='185180'>can</span> <span m='185330'>write</span> <span m='185570'>higher</span>
  <span m='185910'>order</span> <span m='186080'>differential</span> <span m='186590'>equations--</span>
  <span m='190580'>convert</span> <span m='190880'>them</span> <span m='191000'>into</span>
  <span m='191180'>the</span> <span m='191270'>form</span> <span m='191780'>of</span>
  <span m='192050'>first</span> <span m='192350'>order.</span> <span m='196100'>And</span>
  <span m='198240'>I</span> <span m='198300'>guess</span> <span m='198540'>that's</span>
  <span m='198720'>worthwhile</span> <span m='199170'>to</span> <span m='199530'>point</span>
  <span m='199690'>down.</span> <span m='201370'>I</span> <span m='201540'>would</span>
  <span m='201690'>also</span> <span m='201930'>comment</span> <span m='202230'>that</span>
  <span m='202550'>I</span> <span m='202650'>going</span> <span m='202810'>to just</span>
  <span m='202940'>talk</span> <span m='203050'>about</span> <span m='203240'>f of
  y,</span> <span m='204870'>however</span> <span m='205320'>the</span> <span m='205530'>ODE</span>
  <span m='206010'>solvers</span> <span m='206970'>in</span> <span m='207120'>Matlab</span>
  <span m='208170'>expect</span> <span m='209030'>f</span> <span m='209380'>of</span>
  <span m='209700'>the</span> <span m='209910'>t</span> <span m='210210'>comma</span>
  <span m='210650'>y</span> <span m='212410'>as</span> <span m='212620'>their</span>
  <span m='212790'>from.</span> </p><p><span m='214600'>All</span> <span m='214690'>right,</span>
  <span m='214900'>so</span> <span m='215020'>let's</span> <span m='215620'>just</span>
  <span m='219100'>explain</span> <span m='219370'>all the</span> <span m='219580'>details</span>
  <span m='219880'>about</span> <span m='220090'>this.</span> <span m='222820'>So</span>
  <span m='223740'>suppose</span> <span m='224100'>I</span> <span m='224160'>had</span>
  <span m='224400'>a</span> <span m='224460'>differential</span> <span m='224910'>equation</span>
  <span m='227210'>like</span> <span m='227400'>this.</span> <span m='238887'>All
  right,</span> <span m='239386'>so this</span> <span m='239890'>is</span> <span m='239980'>like</span>
  <span m='240715'>a</span> <span m='241210'>differential</span> <span m='241540'>equation</span>
  <span m='241950'>you'd have</span> <span m='242210'>for</span> <span m='244460'>a</span>
  <span m='244540'>body</span> <span m='244930'>move</span> <span m='245340'>moving--</span>
  <span m='246260'>a</span> <span m='246400'>particle</span> <span m='246730'>moving</span>
  <span m='247630'>with</span> <span m='247750'>some</span> <span m='247960'>friction</span>
  <span m='248290'>force</span> <span m='248590'>on</span> <span m='248740'>it</span>
  <span m='249520'>and</span> <span m='249760'>some</span> <span m='249910'>time</span>
  <span m='250150'>varying</span> <span m='250730'>force.</span> <span m='251760'>Yeah?</span>
  </p><p><span m='252378'>AUDIENCE:</span> <span m='252490'>Are</span> <span m='252602'>you</span>
  <span m='252714'>going</span> <span m='252826'>to be posting</span> <span m='253274'>your
  notes</span> <span m='253722'>online?</span> </p><p><span m='254170'>WILLIAM GREEN
  JR:</span> <span m='254394'>No,</span> <span m='254618'>I don't have</span> <span
  m='255070'>any notes.</span> <span m='255310'>This is</span> <span m='255789'>it.</span>
  <span m='260579'>All</span> <span m='260640'>right,</span> <span m='262940'>so</span>
  <span m='263690'>this</span> <span m='263840'>is</span> <span m='263990'>a</span>
  <span m='264800'>differential</span> <span m='265100'>equation.</span> <span m='266180'>What</span>
  <span m='266300'>you</span> <span m='266390'>can</span> <span m='266480'>do</span>
  <span m='266600'>is</span> <span m='266660'>to</span> <span m='266780'>convert</span>
  <span m='267110'>it</span> <span m='267200'>into</span> <span m='267440'>the</span>
  <span m='267560'>form</span> <span m='267950'>I</span> <span m='268010'>have</span>
  <span m='268190'>above,</span> <span m='269420'>is</span> <span m='269810'>to</span>
  <span m='269960'>write</span> <span m='271760'>a</span> <span m='271820'>new</span>
  <span m='271970'>variable,</span> <span m='272460'>say</span> <span m='272660'>v,</span>
  <span m='273320'>that's</span> <span m='273590'>defined</span> <span m='273720'>to
  be</span> <span m='274120'>dx</span> <span m='274290'>dt.</span> <span m='275100'>That's</span>
  <span m='275220'>the</span> <span m='275330'>velocity.</span> <span m='278250'>And</span>
  <span m='279800'>has</span> <span m='280100'>a</span> <span m='280160'>time</span>
  <span m='280440'>dependence,</span> <span m='280870'>but</span> <span m='281300'>I</span>
  <span m='281360'>told</span> <span m='281530'>you</span> <span m='281580'>I</span>
  <span m='281630'>don't</span> <span m='281810'>like</span> <span m='281930'>time</span>
  <span m='282110'>dependence,</span> <span m='282570'>so</span> <span m='282790'>I'm
  not</span> <span m='283010'>going to</span> <span m='283220'>write it</span> <span
  m='283490'>that</span> <span m='283640'>way.</span> <span m='284640'>So</span> <span
  m='284810'>we</span> <span m='284900'>can</span> <span m='285050'>also</span> <span
  m='285290'>define</span> <span m='286430'>another</span> <span m='286730'>variable.</span>
  </p><p><span m='287340'>So</span> <span m='287390'>we</span> <span m='287480'>can</span>
  <span m='287570'>define</span> <span m='287870'>our</span> <span m='287930'>new</span>
  <span m='288170'>y</span> <span m='288410'>vector</span> <span m='291110'>to</span>
  <span m='291590'>be</span> <span m='294740'>x,</span> <span m='296144'>v,</span>
  <span m='297440'>and</span> <span m='297560'>t.</span> <span m='301110'>So</span>
  <span m='301350'>this</span> <span m='301530'>is</span> <span m='301650'>y--</span>
  <span m='301980'>the</span> <span m='302100'>first</span> <span m='302280'>component</span>
  <span m='302580'>of</span> <span m='302670'>y,</span> <span m='302850'>this is</span>
  <span m='303010'>the second</span> <span m='303100'>component of</span> <span m='303415'>y,</span>
  <span m='303730'>this is</span> <span m='304250'>the third</span> <span m='304510'>component</span>
  <span m='304770'>of</span> <span m='305050'>y.</span> <span m='306210'>And</span>
  <span m='306330'>then</span> <span m='306450'>I</span> <span m='306510'>can</span>
  <span m='306660'>write</span> <span m='306840'>down</span> <span m='308970'>what</span>
  <span m='309150'>f</span> <span m='309330'>of</span> <span m='309450'>y</span> <span
  m='309720'>is.</span> <span m='322000'>So</span> <span m='322240'>the</span> <span
  m='322300'>equation</span> <span m='322720'>for</span> <span m='322870'>dx</span>
  <span m='323185'>dt</span> <span m='326092'>is</span> <span m='326530'>y2.</span>
  <span m='327190'>It's</span> <span m='327460'>the</span> <span m='327580'>second</span>
  <span m='327880'>component</span> <span m='328150'>of y,</span> <span m='328470'>dx</span>
  <span m='328790'>dt</span> <span m='329110'>is</span> <span m='329260'>equal</span>
  <span m='329500'>to</span> <span m='329650'>v.</span> </p><p><span m='332260'>The</span>
  <span m='333820'>equation</span> <span m='334240'>for</span> <span m='334510'>the</span>
  <span m='334810'>dv</span> <span m='335140'>dt</span> <span m='336580'>is</span>
  <span m='336760'>given</span> <span m='337000'>by</span> <span m='337120'>this</span>
  <span m='337300'>equation.</span> <span m='338750'>So</span> <span m='338800'>that's</span>
  <span m='342480'>f</span> <span m='343292'>of</span> <span m='343704'>y3</span>
  <span m='346010'>over</span> <span m='346270'>m</span> <span m='347860'>minus</span>
  <span m='350140'>gamma</span> <span m='351790'>y2.</span> <span m='353442'>And</span>
  <span m='353910'>the</span> <span m='354300'>equation</span> <span m='355840'>dt</span>
  <span m='356180'>dt</span> <span m='357060'>is</span> <span m='357150'>just</span>
  <span m='357330'>one.</span> <span m='360390'>So</span> <span m='360600'>this</span>
  <span m='360840'>is</span> <span m='360960'>my</span> <span m='361200'>f</span>
  <span m='361330'>of</span> <span m='361440'>y.</span> </p><p><span m='363360'>So</span>
  <span m='363480'>this</span> <span m='363660'>is</span> <span m='363750'>f1,</span>
  <span m='364140'>f2,</span> <span m='364500'>f3.</span> <span m='365780'>Is that</span>
  <span m='366240'>all</span> <span m='366700'>right?</span> <span m='370400'>So</span>
  <span m='370610'>this</span> <span m='370790'>is</span> <span m='370850'>just</span>
  <span m='371060'>how</span> <span m='371180'>you</span> <span m='371270'>can</span>
  <span m='371390'>convert--</span> <span m='371655'>if</span> <span m='371920'>somebody</span>
  <span m='372170'>writes you an</span> <span m='372440'>equation</span> <span m='372860'>this</span>
  <span m='373010'>way,</span> <span m='373250'>and</span> <span m='373370'>you</span>
  <span m='373430'>want</span> <span m='373580'>to</span> <span m='373640'>get</span>
  <span m='373820'>it</span> <span m='373880'>into</span> <span m='374120'>the</span>
  <span m='374210'>standard</span> <span m='374660'>form</span> <span m='376130'>that</span>
  <span m='376250'>I'm</span> <span m='376400'>going</span> <span m='376520'>to</span>
  <span m='376700'>show</span> <span m='376940'>you</span> <span m='377120'>here--</span>
  <span m='379700'>dy</span> <span m='379830'>dt</span> <span m='380270'>equals</span>
  <span m='380390'>f</span> <span m='380600'>of</span> <span m='380720'>y--</span>
  <span m='382230'>this</span> <span m='382350'>is</span> <span m='382440'>how</span>
  <span m='382530'>you</span> <span m='382620'>convert.</span> </p><p><span m='385710'>And</span>
  <span m='388150'>a</span> <span m='388460'>skill</span> <span m='388760'>we</span>
  <span m='388840'>haven't</span> <span m='389000'>really</span> <span m='389160'>emphasized</span>
  <span m='389500'>so</span> <span m='389670'>far</span> <span m='389820'>in</span>
  <span m='389880'>the</span> <span m='389970'>course,</span> <span m='390310'>but
  I</span> <span m='390360'>think</span> <span m='390540'>a</span> <span m='390600'>very</span>
  <span m='390780'>important</span> <span m='391110'>skill,</span> <span m='391830'>is</span>
  <span m='392550'>to</span> <span m='392640'>be</span> <span m='392700'>able</span>
  <span m='392820'>to</span> <span m='392880'>get</span> <span m='393000'>like</span>
  <span m='393150'>a</span> <span m='393210'>chemical</span> <span m='393540'>engineering</span>
  <span m='393930'>problem</span> <span m='395310'>and</span> <span m='396300'>rearrange</span>
  <span m='397140'>it</span> <span m='397620'>so</span> <span m='397890'>it</span>
  <span m='397950'>becomes</span> <span m='398310'>a</span> <span m='398370'>standard</span>
  <span m='398850'>form</span> <span m='399630'>that</span> <span m='399750'>maps</span>
  <span m='400050'>up</span> <span m='400140'>to</span> <span m='400230'>one</span>
  <span m='400350'>of</span> <span m='400410'>the</span> <span m='400470'>solvers</span>
  <span m='400910'>you</span> <span m='400980'>know</span> <span m='401100'>how</span>
  <span m='401190'>to</span> <span m='401280'>use.</span> <span m='403930'>So</span>
  <span m='404060'>you've</span> <span m='404190'>got</span> <span m='404280'>a</span>
  <span m='404310'>problem</span> <span m='404670'>has</span> <span m='404820'>some</span>
  <span m='404940'>differential</span> <span m='405420'>in</span> <span m='405540'>it.</span>
  <span m='406260'>Right</span> <span m='406440'>away</span> <span m='406710'>you</span>
  <span m='406830'>actually,</span> <span m='406960'>can I</span> <span m='407170'>somehow</span>
  <span m='407520'>rewrite</span> <span m='408000'>it</span> <span m='408450'>so</span>
  <span m='408690'>it</span> <span m='408750'>looks</span> <span m='409050'>like</span>
  <span m='409620'>this</span> <span m='409710'>standard</span> <span m='410130'>form--</span>
  <span m='410490'>or</span> <span m='410610'>actually</span> <span m='410910'>for</span>
  <span m='411030'>Matlab,</span> <span m='411710'>this</span> <span m='411870'>form.</span>
  <span m='412480'>So</span> <span m='412690'>Matlab</span> <span m='412890'>will</span>
  <span m='413210'>say</span> <span m='416867'>f</span> <span m='417348'>of</span>
  <span m='417829'>t, y.</span> </p><p><span m='418800'>If</span> <span m='418920'>you</span>
  <span m='418980'>can</span> <span m='419100'>do</span> <span m='419250'>that,</span>
  <span m='420640'>then</span> <span m='420780'>you</span> <span m='420870'>can</span>
  <span m='421050'>go</span> <span m='421230'>ahead</span> <span m='421530'>and use</span>
  <span m='421650'>those</span> <span m='421860'>Matlab</span> <span m='422070'>solvers</span>
  <span m='422310'>to</span> <span m='422400'>solve</span> <span m='422700'>it.</span>
  <span m='424230'>But</span> <span m='425190'>your</span> <span m='425400'>variables</span>
  <span m='425880'>may</span> <span m='426000'>not</span> <span m='426180'>have</span>
  <span m='426350'>a</span> <span m='426410'>letter</span> <span m='426630'>y</span>
  <span m='427230'>appearing</span> <span m='427500'>anywhere,</span> <span m='428470'>right?</span>
  <span m='428640'>You</span> <span m='428730'>have</span> <span m='428820'>to</span>
  <span m='428910'>figure</span> <span m='429100'>out</span> <span m='429140'>how</span>
  <span m='429210'>to</span> <span m='429300'>write</span> <span m='429510'>it</span>
  <span m='429570'>into</span> <span m='429720'>the</span> <span m='429810'>standard</span>
  <span m='430170'>form.</span> <span m='430980'>And</span> <span m='431070'>then</span>
  <span m='431160'>once</span> <span m='431310'>you</span> <span m='431400'>can</span>
  <span m='431520'>do</span> <span m='431640'>that,</span> <span m='431760'>you</span>
  <span m='431880'>can</span> <span m='432000'>use</span> <span m='432800'>the</span>
  <span m='433110'>solvers.</span> </p><p><span m='434190'>And</span> <span m='434280'>the</span>
  <span m='434370'>same</span> <span m='434580'>thing</span> <span m='434820'>with</span>
  <span m='435130'>the</span> <span m='435270'>non-linear</span> <span m='436110'>equations</span>
  <span m='436470'>solvers,</span> <span m='437010'>with</span> <span m='437070'>the</span>
  <span m='437190'>optimization</span> <span m='437700'>software.</span> <span m='438700'>If</span>
  <span m='438830'>you</span> <span m='439050'>can</span> <span m='439230'>rewrite</span>
  <span m='439710'>it</span> <span m='439860'>into</span> <span m='440070'>the</span>
  <span m='440190'>form</span> <span m='440490'>that</span> <span m='440580'>matches</span>
  <span m='441020'>the</span> <span m='441130'>standard</span> <span m='441210'>form,</span>
  <span m='441510'>then</span> <span m='441720'>once</span> <span m='441930'>you're</span>
  <span m='442020'>done,</span> <span m='442600'>you're</span> <span m='442620'>done.</span>
  <span m='443310'>Then</span> <span m='444360'>you</span> <span m='444420'>can</span>
  <span m='444510'>just</span> <span m='444660'>go</span> <span m='444870'>and</span>
  <span m='445110'>call</span> <span m='445380'>the</span> <span m='445530'>canned</span>
  <span m='445800'>programs</span> <span m='446220'>that</span> <span m='446310'>work</span>
  <span m='446490'>well</span> <span m='447150'>for</span> <span m='447270'>those</span>
  <span m='447470'>forms.</span> </p><p><span m='452130'>All</span> <span m='452240'>right,</span>
  <span m='452510'>now what</span> <span m='452630'>do</span> <span m='452690'>we</span>
  <span m='452840'>want</span> <span m='453470'>as</span> <span m='453680'>the</span>
  <span m='453800'>output?</span> <span m='454160'>So this</span> <span m='454340'>is</span>
  <span m='454400'>the</span> <span m='454520'>problem.</span> <span m='456900'>This
  is</span> <span m='457010'>the</span> <span m='457130'>problem</span> <span m='457440'>as</span>
  <span m='457750'>proposed.</span> <span m='458840'>What</span> <span m='458960'>do</span>
  <span m='459050'>we</span> <span m='459140'>really</span> <span m='459410'>want</span>
  <span m='459590'>out</span> <span m='459740'>of</span> <span m='459800'>this?</span>
  </p><p><span m='461150'>What</span> <span m='461210'>we're</span> <span m='461300'>going</span>
  <span m='461420'>to</span> <span m='461480'>get</span> <span m='461630'>out</span>
  <span m='461810'>of</span> <span m='461930'>it</span> <span m='462820'>is</span>
  <span m='463070'>a</span> <span m='463100'>bunch</span> <span m='463370'>of</span>
  <span m='463430'>points</span> <span m='465270'>y--</span> <span m='467190'>actually</span>
  <span m='467570'>a</span> <span m='467660'>matrix,</span> <span m='467960'>right?</span>
  <span m='468260'>It would</span> <span m='468350'>be</span> <span m='468470'>a</span>
  <span m='468560'>vector</span> <span m='469640'>of</span> <span m='469760'>y-values.</span>
  <span m='470240'>Typically</span> <span m='470570'>y is</span> <span m='470790'>a</span>
  <span m='470870'>vector.</span> <span m='471710'>And</span> <span m='471800'>we</span>
  <span m='471920'>want</span> <span m='472100'>to</span> <span m='472160'>know</span>
  <span m='472340'>it</span> <span m='472440'>a</span> <span m='472580'>bunch</span>
  <span m='472790'>of</span> <span m='472850'>time</span> <span m='473060'>points.</span>
  <span m='475220'>And</span> <span m='475310'>we</span> <span m='475400'>would</span>
  <span m='475520'>a</span> <span m='475580'>lot</span> <span m='475730'>of</span>
  <span m='475790'>time</span> <span m='475970'>points</span> <span m='476700'>so</span>
  <span m='476800'>we're</span> <span m='476900'>getting</span> <span m='476960'>pretty</span>
  <span m='477170'>plots</span> <span m='477930'>of</span> <span m='478040'>how</span>
  <span m='478220'>the</span> <span m='478430'>components</span> <span m='478820'>of</span>
  <span m='478910'>y</span> <span m='479110'>vary</span> <span m='479320'>with</span>
  <span m='479420'>time.</span> </p><p><span m='481820'>That's</span> <span m='482000'>what</span>
  <span m='482090'>we</span> <span m='482150'>usually</span> <span m='482390'>want.</span>
  <span m='482570'>Sometimes</span> <span m='482930'>we</span> <span m='483020'>just</span>
  <span m='483140'>want</span> <span m='483480'>the</span> <span m='483560'>final</span>
  <span m='483830'>value,</span> <span m='485440'>y</span> <span m='485600'>time</span>
  <span m='485840'>value.</span> <span m='487480'>We</span> <span m='487720'>integrate</span>
  <span m='488160'>to</span> <span m='488310'>some</span> <span m='488480'>point and</span>
  <span m='488930'>then stop,</span> <span m='489530'>and</span> <span m='489620'>just</span>
  <span m='489770'>run</span> <span m='489920'>through</span> <span m='489980'>the</span>
  <span m='490070'>final</span> <span m='490280'>value.</span> <span m='490550'>But</span>
  <span m='490700'>a</span> <span m='490730'>lot</span> <span m='490820'>of</span>
  <span m='490880'>times,</span> <span m='491090'>we actually</span> <span m='491180'>want
  to make</span> <span m='491570'>pretty</span> <span m='491750'>plots,</span> <span
  m='492440'>so</span> <span m='492560'>we</span> <span m='492650'>really</span> <span
  m='492830'>want</span> <span m='492950'>a</span> <span m='493010'>lot</span> <span
  m='493160'>of</span> <span m='493220'>points</span> <span m='493520'>here</span>
  <span m='494300'>and</span> <span m='494530'>making</span> <span m='494900'>plots.</span>
  </p><p><span m='495250'>Now</span> <span m='495530'>how</span> <span m='495590'>many</span>
  <span m='495740'>points</span> <span m='496010'>do you</span> <span m='496070'>need</span>
  <span m='496220'>to</span> <span m='496280'>make</span> <span m='496430'>a</span>
  <span m='496460'>nice</span> <span m='496640'>plot?</span> <span m='496910'>Maybe,</span>
  <span m='497210'>I</span> <span m='497270'>don't</span> <span m='497360'>know,</span>
  <span m='497470'>100</span> <span m='497750'>points,</span> <span m='498110'>50</span>
  <span m='498320'>points,</span> <span m='498700'>you can make</span> <span m='498860'>a
  nice</span> <span m='499080'>plot.</span> <span m='500000'>So</span> <span m='500300'>that's</span>
  <span m='500480'>the</span> <span m='500540'>kind</span> <span m='500720'>numbers</span>
  <span m='500980'>you'd</span> <span m='501110'>like.</span> <span m='502520'>And</span>
  <span m='502820'>so</span> <span m='504050'>the</span> <span m='504230'>output</span>
  <span m='504560'>of</span> <span m='504620'>these</span> <span m='504800'>programs</span>
  <span m='506270'>is</span> <span m='506390'>going</span> <span m='506540'>to</span>
  <span m='506600'>be</span> <span m='506690'>something</span> <span m='506960'>like</span>
  <span m='508050'>a</span> <span m='508160'>vector</span> <span m='508550'>of</span>
  <span m='508640'>the</span> <span m='508760'>time</span> <span m='509060'>points,</span>
  <span m='510530'>and</span> <span m='510710'>then</span> <span m='510930'>a</span>
  <span m='511050'>matrix</span> <span m='515070'>of</span> <span m='518720'>the</span>
  <span m='518840'>y-values</span> <span m='520140'>corresponding</span> <span m='520380'>to</span>
  <span m='520590'>each</span> <span m='520789'>time</span> <span m='521000'>point.</span>
  </p><p><span m='521750'>And</span> <span m='521900'>the</span> <span m='522020'>way</span>
  <span m='522130'>it</span> <span m='522240'>does</span> <span m='522570'>in</span>
  <span m='522750'>that</span> <span m='522870'>lab,</span> <span m='523280'>it's</span>
  <span m='523520'>reasonable.</span> <span m='524510'>Each</span> <span m='524720'>row</span>
  <span m='525140'>of</span> <span m='525260'>y</span> <span m='526490'>are</span>
  <span m='526730'>the</span> <span m='526850'>y-values</span> <span m='527720'>that</span>
  <span m='527870'>correspond</span> <span m='529490'>to</span> <span m='529610'>the</span>
  <span m='530000'>same</span> <span m='530210'>time</span> <span m='530450'>point,</span>
  <span m='530660'>the</span> <span m='530750'>first</span> <span m='530930'>time</span>
  <span m='531110'>point.</span> <span m='532050'>So</span> <span m='532070'>the</span>
  <span m='532160'>first</span> <span m='532430'>row</span> <span m='532640'>of</span>
  <span m='532760'>y</span> <span m='533060'>corresponds</span> <span m='533600'>to</span>
  <span m='533660'>the</span> <span m='533750'>first</span> <span m='534200'>number</span>
  <span m='534470'>in</span> <span m='534540'>the</span> <span m='534620'>time</span>
  <span m='535100'>vector.</span> <span m='536000'>The</span> <span m='536060'>second</span>
  <span m='536330'>run</span> <span m='536590'>is</span> <span m='536700'>the</span>
  <span m='537020'>second.</span> <span m='537830'>Last</span> <span m='538220'>one</span>
  <span m='538370'>will</span> <span m='538450'>be at</span> <span m='538640'>time</span>
  <span m='538910'>final.</span> <span m='541400'>And</span> <span m='541490'>then</span>
  <span m='541610'>you</span> <span m='541700'>can</span> <span m='541860'>plot</span>
  <span m='542060'>them.</span> <span m='543692'>OK</span> <span m='544100'>so</span>
  <span m='544450'>far?</span> </p><p><span m='548940'>And</span> <span m='549090'>ideally,</span>
  <span m='552000'>we</span> <span m='552120'>would</span> <span m='552270'>like</span>
  <span m='555310'>these</span> <span m='555530'>y-values</span> <span m='556220'>that</span>
  <span m='556310'>we</span> <span m='556400'>compute,</span> <span m='556940'>these</span>
  <span m='557120'>y's</span> <span m='557420'>we</span> <span m='557510'>get</span>
  <span m='557690'>out,</span> <span m='558620'>ideally</span> <span m='559100'>one</span>
  <span m='559280'>that</span> <span m='559400'>really</span> <span m='559670'>close</span>
  <span m='560030'>to</span> <span m='560180'>what</span> <span m='560300'>the</span>
  <span m='560390'>true</span> <span m='561230'>solution</span> <span m='561740'>of</span>
  <span m='561830'>the</span> <span m='561950'>true</span> <span m='562100'>differential</span>
  <span m='562490'>equation</span> <span m='562880'>is.</span> <span m='564360'>But</span>
  <span m='564510'>we're</span> <span m='564600'>doing</span> <span m='564750'>numerical</span>
  <span m='565170'>stuff,</span> <span m='565440'>so</span> <span m='565530'>it's</span>
  <span m='565620'>never</span> <span m='565830'>going</span> <span m='565950'>to</span>
  <span m='566010'>be</span> <span m='566070'>exactly</span> <span m='566430'>the</span>
  <span m='566520'>same.</span> <span m='567810'>And</span> <span m='567960'>so</span>
  <span m='568560'>a</span> <span m='568620'>big</span> <span m='568860'>part</span>
  <span m='569100'>of</span> <span m='569160'>the</span> <span m='569310'>effort</span>
  <span m='569610'>is</span> <span m='569670'>trying</span> <span m='569850'>to</span>
  <span m='569910'>figure</span> <span m='570150'>out,</span> <span m='570340'>how</span>
  <span m='570450'>can</span> <span m='570630'>we</span> <span m='570720'>get</span>
  <span m='570870'>the</span> <span m='570960'>thing</span> <span m='571200'>to</span>
  <span m='571260'>compute</span> <span m='572230'>y</span> <span m='572670'>calculated</span>
  <span m='573300'>at</span> <span m='573390'>each</span> <span m='573570'>time</span>
  <span m='573820'>point</span> <span m='574020'>to</span> <span m='574110'>be</span>
  <span m='574200'>as</span> <span m='574290'>close</span> <span m='574530'>as</span>
  <span m='574620'>possible</span> <span m='575040'>to</span> <span m='575130'>the</span>
  <span m='575220'>truth,</span> <span m='575810'>of</span> <span m='576000'>what</span>
  <span m='576120'>the</span> <span m='576210'>true</span> <span m='576390'>solution</span>
  <span m='576750'>of</span> <span m='577320'>the</span> <span m='577410'>equations</span>
  <span m='577860'>are?</span> <span m='579390'>And</span> <span m='579540'>that</span>
  <span m='579840'>turns</span> <span m='580020'>out</span> <span m='580110'>to</span>
  <span m='580170'>be</span> <span m='580890'>difficult,</span> <span m='581580'>so</span>
  <span m='582780'>that's</span> <span m='582970'>a</span> <span m='583040'>very</span>
  <span m='583200'>important</span> <span m='583470'>thing</span> <span m='583560'>to</span>
  <span m='583650'>worry</span> <span m='583800'>about.</span> </p><p><span m='587560'>What</span>
  <span m='587740'>else</span> <span m='587860'>can</span> <span m='587950'>we</span>
  <span m='588010'>say</span> <span m='588130'>about</span> <span m='588280'>this?</span>
  <span m='592100'>We</span> <span m='593710'>specify</span> <span m='594280'>this</span>
  <span m='594880'>from</span> <span m='595060'>t naught,</span> <span m='595810'>and</span>
  <span m='595900'>you</span> <span m='595990'>typically</span> <span m='596500'>have</span>
  <span m='596650'>to</span> <span m='596770'>input</span> <span m='597280'>your</span>
  <span m='597580'>t final,</span> <span m='598060'>how</span> <span m='598180'>far</span>
  <span m='598390'>you</span> <span m='598480'>want</span> <span m='598600'>to</span>
  <span m='598690'>go</span> <span m='599560'>away</span> <span m='599740'>from</span>
  <span m='599830'>your</span> <span m='600010'>t naught</span> <span m='600610'>as</span>
  <span m='600850'>another</span> <span m='601090'>input.</span> <span m='604000'>Normally,</span>
  <span m='604600'>people</span> <span m='604870'>write</span> <span m='605080'>it</span>
  <span m='605140'>where</span> <span m='605300'>t</span> <span m='605560'>naught</span>
  <span m='605710'>is</span> <span m='605980'>less</span> <span m='606160'>than</span>
  <span m='606300'>t</span> <span m='606440'>final,</span> <span m='607870'>and</span>
  <span m='607990'>so</span> <span m='608110'>you're</span> <span m='608290'>like</span>
  <span m='608500'>integrating</span> <span m='608920'>from</span> <span m='609040'>left</span>
  <span m='609220'>to</span> <span m='609310'>right.</span> <span m='610540'>But</span>
  <span m='610750'>you</span> <span m='610840'>could</span> <span m='611020'>actually</span>
  <span m='611620'>write</span> <span m='611800'>them,</span> <span m='612250'>put</span>
  <span m='612370'>a</span> <span m='612430'>negative</span> <span m='612700'>sign</span>
  <span m='612970'>equation</span> <span m='613340'>which</span> <span m='613710'>corresponds</span>
  <span m='613900'>to a</span> <span m='614290'>negative</span> <span m='614590'>t,</span>
  <span m='614950'>change</span> <span m='615200'>your</span> <span m='615270'>variable</span>
  <span m='615850'>to</span> <span m='616390'>of</span> <span m='616450'>t</span>
  <span m='616630'>prime</span> <span m='617030'>that</span> <span m='617140'>was</span>
  <span m='617290'>equal</span> <span m='617500'>to</span> <span m='617860'>t</span>
  <span m='618070'>final</span> <span m='618460'>minus</span> <span m='618810'>t</span>
  <span m='619950'>if</span> <span m='620020'>you</span> <span m='620080'>wanted</span>
  <span m='620290'>to,</span> <span m='620740'>and</span> <span m='620880'>integrate</span>
  <span m='621130'>the</span> <span m='621190'>other</span> <span m='621340'>direction.</span>
  </p><p><span m='621820'>And</span> <span m='621940'>in</span> <span m='622030'>fact</span>
  <span m='622360'>in</span> <span m='622480'>homework</span> <span m='622780'>zero</span>
  <span m='623050'>problem</span> <span m='623350'>one,</span> <span m='624400'>we</span>
  <span m='624550'>did</span> <span m='624670'>that</span> <span m='624850'>too.</span>
  <span m='626230'>So</span> <span m='626580'>you</span> <span m='626970'>can</span>
  <span m='627090'>integrate</span> <span m='627320'>frontwards.</span> <span m='627580'>You
  can</span> <span m='627630'>integrate</span> <span m='627920'>backwards.</span>
  <span m='628920'>If</span> <span m='628980'>somebody</span> <span m='629250'>tells</span>
  <span m='629490'>you</span> <span m='629550'>the</span> <span m='629610'>initial</span>
  <span m='629880'>condition</span> <span m='630420'>or</span> <span m='630630'>condition</span>
  <span m='631200'>in</span> <span m='631320'>the</span> <span m='631380'>center</span>
  <span m='631680'>of</span> <span m='631770'>the</span> <span m='631860'>range,</span>
  <span m='632890'>you</span> <span m='633100'>integrate</span> <span m='633310'>forward</span>
  <span m='633810'>for</span> <span m='633960'>part</span> <span m='634110'>of</span>
  <span m='634170'>the</span> <span m='634230'>range,</span> <span m='634500'>and</span>
  <span m='634560'>backwards</span> <span m='634920'>the</span> <span m='635010'>other</span>
  <span m='635130'>way,</span> <span m='636270'>so</span> <span m='636570'>anything</span>
  <span m='636870'>like</span> <span m='636960'>this.</span> </p><p><span m='637510'>So</span>
  <span m='637530'>what's</span> <span m='637650'>important</span> <span m='638010'>for</span>
  <span m='638130'>this</span> <span m='638250'>to</span> <span m='638340'>be</span>
  <span m='638640'>what's</span> <span m='638790'>called</span> <span m='639000'>an</span>
  <span m='639060'>initial</span> <span m='639330'>value</span> <span m='639570'>problem</span>
  <span m='639900'>is</span> <span m='639990'>just</span> <span m='640140'>that</span>
  <span m='640290'>all</span> <span m='640590'>of</span> <span m='640740'>the</span>
  <span m='640830'>specifications</span> <span m='641640'>of</span> <span m='641730'>y</span>
  <span m='641940'>are</span> <span m='642030'>given</span> <span m='642240'>at</span>
  <span m='642330'>the</span> <span m='642390'>same</span> <span m='642630'>value</span>
  <span m='642960'>of t.</span> <span m='643780'>It</span> <span m='643880'>doesn't</span>
  <span m='643920'>matter</span> <span m='644070'>exactly</span> <span m='644400'>what</span>
  <span m='644630'>value of</span> <span m='644780'>t it</span> <span m='645260'>is.</span>
  <span m='646720'>Later,</span> <span m='647050'>we'll</span> <span m='647170'>talk</span>
  <span m='647380'>about</span> <span m='647560'>what</span> <span m='647680'>happens</span>
  <span m='647980'>if</span> <span m='648070'>you</span> <span m='648130'>don't</span>
  <span m='648280'>know</span> <span m='648460'>all</span> <span m='648550'>the</span>
  <span m='648640'>specifications</span> <span m='649300'>at</span> <span m='649360'>one</span>
  <span m='650005'>value of</span> <span m='650350'>time.</span> </p><p><span m='652470'>All</span>
  <span m='652530'>right,</span> <span m='654060'>now</span> <span m='656950'>how</span>
  <span m='657570'>would</span> <span m='657730'>you</span> <span m='657910'>approach</span>
  <span m='658330'>this?</span> <span m='661250'>Probably,</span> <span m='661480'>a</span>
  <span m='661510'>bunch</span> <span m='661690'>of</span> <span m='661780'>you've</span>
  <span m='661960'>done</span> <span m='662110'>this</span> <span m='662260'>already</span>
  <span m='663450'>as</span> <span m='663760'>undergraduates,</span> <span m='664240'>or</span>
  <span m='664300'>maybe</span> <span m='664510'>even</span> <span m='664600'>high</span>
  <span m='664720'>school.</span> <span m='665530'>You</span> <span m='665650'>can</span>
  <span m='665800'>write</span> <span m='665950'>like</span> <span m='666100'>a</span>
  <span m='666160'>Taylor</span> <span m='666490'>expansion,</span> <span m='668690'>y</span>
  <span m='669030'>of t</span> <span m='669280'>plus</span> <span m='669550'>delta
  t--</span> <span m='672070'>is</span> <span m='672190'>y</span> <span m='672420'>of
  t</span> <span m='674490'>plus</span> <span m='674860'>delta t--</span> <span m='676550'>times</span>
  <span m='679400'>dy</span> <span m='679790'>dt.</span> </p><p><span m='683560'>You</span>
  <span m='683760'>can</span> <span m='683960'>write</span> <span m='684590'>that.</span>
  <span m='685570'>And</span> <span m='685690'>then</span> <span m='685780'>I</span>
  <span m='685840'>say,</span> <span m='686020'>wow,</span> <span m='686260'>I</span>
  <span m='686320'>know</span> <span m='686570'>dy</span> <span m='686690'>dt.</span>
  <span m='687040'>That's</span> <span m='687220'>actually</span> <span m='687440'>f,</span>
  <span m='688230'>so</span> <span m='688360'>this</span> <span m='688510'>is</span>
  <span m='688630'>actually</span> <span m='689070'>equal</span> <span m='689650'>to--</span>
  <span m='707750'>right?</span> <span m='708910'>And</span> <span m='709000'>then</span>
  <span m='709150'>if</span> <span m='709240'>I</span> <span m='709300'>truncate</span>
  <span m='709660'>the</span> <span m='709780'>Taylor</span> <span m='710050'>expansion,</span>
  <span m='711140'>now</span> <span m='711220'>I</span> <span m='711310'>have</span>
  <span m='711460'>an update</span> <span m='711880'>formula.</span> </p><p><span
  m='712390'>So if I</span> <span m='712510'>just</span> <span m='712630'>forget</span>
  <span m='712900'>this</span> <span m='713070'>last</span> <span m='713310'>bit,</span>
  <span m='715600'>I</span> <span m='715690'>can</span> <span m='715840'>put</span>
  <span m='715990'>in</span> <span m='716490'>my</span> <span m='716680'>current</span>
  <span m='716950'>value</span> <span m='717180'>of y,</span> <span m='717550'>like
  the</span> <span m='717640'>initial</span> <span m='717910'>condition.</span> <span
  m='718880'>The</span> <span m='719140'>initial</span> <span m='719410'>condition</span>
  <span m='719770'>here,</span> <span m='720010'>evaluate</span> <span m='720460'>f,</span>
  <span m='721000'>multiply</span> <span m='721360'>by</span> <span m='721780'>delta</span>
  <span m='721970'>t,</span> <span m='722520'>add</span> <span m='722800'>them</span>
  <span m='722950'>together,</span> <span m='723800'>and</span> <span m='723910'>I'll</span>
  <span m='723980'>get</span> <span m='724640'>a</span> <span m='724870'>new</span>
  <span m='725080'>value</span> <span m='725320'>of</span> <span m='725440'>y.</span>
  </p><p><span m='726460'>And</span> <span m='726550'>then</span> <span m='726670'>I</span>
  <span m='726730'>can</span> <span m='726910'>repeat</span> <span m='727360'>over</span>
  <span m='727570'>and</span> <span m='727660'>over</span> <span m='727870'>again.</span>
  <span m='729300'>And</span> <span m='729410'>in</span> <span m='729460'>fact,</span>
  <span m='729840'>this</span> <span m='729950'>is</span> <span m='730100'>a</span>
  <span m='730280'>very</span> <span m='730520'>famous</span> <span m='730790'>method.</span>
  <span m='731120'>It's</span> <span m='731180'>called</span> <span m='731360'>the</span>
  <span m='731450'>Forward</span> <span m='731750'>Euler</span> <span m='732020'>method.</span>
  <span m='732410'>Euler</span> <span m='732780'>was</span> <span m='733060'>a</span>
  <span m='733220'>pretty</span> <span m='733400'>smart</span> <span m='733610'>guy,</span>
  <span m='733880'>so</span> <span m='734060'>it's</span> <span m='734150'>not</span>
  <span m='734360'>completely</span> <span m='734720'>ridiculous,</span> <span m='735330'>but</span>
  <span m='735380'>as</span> <span m='735500'>I'll</span> <span m='735620'>show</span>
  <span m='735800'>you,</span> <span m='735980'>it has</span> <span m='736130'>some</span>
  <span m='736280'>problems.</span> </p><p><span m='741000'>So</span> <span m='741020'>the</span>
  <span m='741110'>Forward</span> <span m='741380'>Euler,</span> <span m='741840'>another</span>
  <span m='742400'>way</span> <span m='742520'>to</span> <span m='742580'>write</span>
  <span m='742760'>it</span> <span m='742850'>is</span> <span m='743570'>y</span>
  <span m='743900'>new</span> <span m='745850'>is</span> <span m='746030'>equal</span>
  <span m='746300'>to</span> <span m='747700'>y</span> <span m='748040'>old</span>
  <span m='751430'>plus</span> <span m='751912'>delta t</span> <span m='753840'>times</span>
  <span m='754322'>f</span> <span m='756030'>of y</span> <span m='756528'>old.</span>
  <span m='762510'>It's</span> <span m='762790'>called</span> <span m='762970'>Forward</span>
  <span m='763520'>Euler.</span> <span m='773090'>And</span> <span m='774890'>we</span>
  <span m='774980'>can</span> <span m='775130'>write</span> <span m='775280'>a</span>
  <span m='775340'>little</span> <span m='776810'>implementation</span> <span m='777530'>of</span>
  <span m='777590'>this</span> <span m='781030'>pretty</span> <span m='781240'>easily.</span>
  <span m='781700'>So</span> <span m='781750'>you</span> <span m='781810'>can</span>
  <span m='781940'>write</span> <span m='783740'>y</span> <span m='784120'>is</span>
  <span m='784280'>equal</span> <span m='784470'>to</span> <span m='784560'>y</span>
  <span m='784895'>naught,</span> <span m='785707'>t is equal</span> <span m='786184'>to
  t</span> <span m='786661'>naught</span> <span m='790480'>for</span> <span m='791535'>i</span>
  <span m='791950'>equals</span> <span m='792660'>1</span> <span m='793625'>to the</span>
  <span m='794070'>number</span> <span m='794290'>of</span> <span m='794350'>steps,</span>
  <span m='799100'>y</span> <span m='799960'>is</span> <span m='800370'>equal</span>
  <span m='800810'>to</span> <span m='801060'>y</span> <span m='802540'>plus</span>
  <span m='802870'>delta</span> <span m='803220'>t</span> <span m='803770'>times</span>
  <span m='804704'>f of</span> <span m='805171'>y,</span> <span m='807506'>t is</span>
  <span m='807973'>equal to</span> <span m='808440'>t plus</span> <span m='808907'>delta
  t.</span> <span m='810320'>Somewhere</span> <span m='810520'>up</span> <span m='810640'>here,</span>
  <span m='810730'>I need to</span> <span m='811090'>write</span> <span m='811390'>delta
  t.</span> </p><p><span m='821540'>OK,</span> <span m='822130'>so</span> <span m='822250'>there's</span>
  <span m='822490'>your</span> <span m='822580'>code</span> <span m='822760'>for</span>
  <span m='823050'>doing</span> <span m='823370'>Forward</span> <span m='823760'>Euler.</span>
  <span m='824765'>How</span> <span m='825180'>many of</span> <span m='825390'>you</span>
  <span m='825460'>have done</span> <span m='825670'>this</span> <span m='825760'>before?</span>
  <span m='827700'>OK,</span> <span m='828250'>so</span> <span m='828310'>I</span>
  <span m='828370'>can</span> <span m='828460'>skip</span> <span m='828640'>over</span>
  <span m='828790'>this</span> <span m='828930'>very</span> <span m='829280'>fast.</span>
  <span m='832630'>How</span> <span m='832720'>many</span> <span m='833320'>did</span>
  <span m='833470'>this,</span> <span m='833650'>and</span> <span m='833770'>it</span>
  <span m='833830'>didn't</span> <span m='834040'>work</span> <span m='834280'>for
  a</span> <span m='834758'>problem?</span> <span m='838110'>OK,</span> <span m='838280'>so</span>
  <span m='838550'>you're</span> <span m='838640'>not</span> <span m='838820'>doing</span>
  <span m='838920'>hard enough</span> <span m='839140'>problems.</span> <span m='840170'>Well,</span>
  <span m='840480'>we'll</span> <span m='840920'>correct</span> <span m='841210'>that.</span>
  </p><p><span m='843710'>All</span> <span m='843830'>right,</span> <span m='844250'>so</span>
  <span m='844490'>I</span> <span m='844580'>noticed</span> <span m='844900'>that</span>
  <span m='845060'>this</span> <span m='846170'>closely</span> <span m='846800'>resembles</span>
  <span m='848600'>the</span> <span m='848660'>rectangle</span> <span m='849160'>rule.</span>
  <span m='851350'>So</span> <span m='851950'>the</span> <span m='852040'>rectangle</span>
  <span m='852580'>rule</span> <span m='854410'>would</span> <span m='854590'>look</span>
  <span m='854800'>a</span> <span m='854830'>lot</span> <span m='855040'>the</span>
  <span m='855130'>same.</span> <span m='856000'>However,</span> <span m='856810'>if</span>
  <span m='856900'>you're</span> <span m='857080'>integrating</span> <span m='858760'>a</span>
  <span m='859000'>function--</span> <span m='860830'>so</span> <span m='861010'>I</span>
  <span m='861070'>have</span> <span m='861230'>I</span> <span m='861590'>is</span>
  <span m='861950'>equal</span> <span m='862220'>to the</span> <span m='862560'>integral</span>
  <span m='864100'>of f of</span> <span m='864580'>t</span> <span m='864895'>dt,</span>
  <span m='869110'>then</span> <span m='869290'>I</span> <span m='869350'>can</span>
  <span m='869530'>notice</span> <span m='869980'>that</span> <span m='870190'>the</span>
  <span m='870280'>derivative</span> <span m='870730'>dI</span> <span m='871060'>dt</span>
  <span m='873580'>is</span> <span m='873760'>equal</span> <span m='874060'>to</span>
  <span m='875346'>f of</span> <span m='875690'>t.</span> </p><p><span m='879900'>And</span>
  <span m='880110'>so</span> <span m='881310'>if</span> <span m='881430'>I</span>
  <span m='881490'>was</span> <span m='881610'>going</span> <span m='881730'>to</span>
  <span m='881790'>do</span> <span m='881940'>the</span> <span m='882060'>rectangle</span>
  <span m='882540'>rule,</span> <span m='883410'>it</span> <span m='883470'>would</span>
  <span m='883560'>look</span> <span m='883680'>just</span> <span m='883860'>the</span>
  <span m='883920'>same</span> <span m='884220'>as</span> <span m='884340'>this,</span>
  <span m='884550'>except</span> <span m='884790'>this</span> <span m='884910'>would</span>
  <span m='885000'>be</span> <span m='885120'>a t.</span> <span m='888330'>Maybe</span>
  <span m='888570'>I would</span> <span m='888700'>pick</span> <span m='888870'>y0</span>
  <span m='889410'>to</span> <span m='889470'>be</span> <span m='889670'>0.</span>
  <span m='891410'>And</span> <span m='892970'>the</span> <span m='893210'>final</span>
  <span m='893570'>value</span> <span m='893870'>of</span> <span m='894020'>y</span>
  <span m='894680'>I</span> <span m='894770'>would</span> <span m='894890'>get</span>
  <span m='895040'>to</span> <span m='895250'>would</span> <span m='895370'>be</span>
  <span m='895490'>my</span> <span m='895640'>integral,</span> <span m='896060'>my</span>
  <span m='896260'>i value</span> <span m='896590'>that I</span> <span m='896996'>want.</span>
  <span m='899640'>So</span> <span m='899820'>how</span> <span m='900060'>many</span>
  <span m='900210'>of</span> <span m='900290'>you have</span> <span m='900400'>done</span>
  <span m='900630'>rectangle</span> <span m='901060'>rule?</span> <span m='902490'>Yes?</span>
  <span m='904020'>All</span> <span m='904080'>right,</span> <span m='904260'>so</span>
  <span m='904380'>you</span> <span m='904440'>did</span> <span m='904580'>this</span>
  <span m='904680'>already.</span> </p><p><span m='906600'>Now</span> <span m='906750'>you</span>
  <span m='906840'>remember</span> <span m='907440'>in</span> <span m='907590'>high</span>
  <span m='907740'>school,</span> <span m='908340'>when</span> <span m='908430'>they</span>
  <span m='908520'>took</span> <span m='908700'>the</span> <span m='908790'>rectangle</span>
  <span m='909180'>rule,</span> <span m='910680'>they</span> <span m='910800'>probably</span>
  <span m='911070'>mentioned</span> <span m='912550'>that</span> <span m='912740'>it's</span>
  <span m='912830'>not</span> <span m='912930'>very</span> <span m='913140'>accurate.</span>
  <span m='914910'>And</span> <span m='915150'>so</span> <span m='915360'>then</span>
  <span m='915510'>they</span> <span m='915600'>also</span> <span m='915840'>taught</span>
  <span m='915990'>you</span> <span m='916080'>some</span> <span m='916260'>other</span>
  <span m='916410'>ones.</span> <span m='916680'>You</span> <span m='916740'>guys,</span>
  <span m='917040'>how</span> <span m='917100'>many of</span> <span m='917220'>you</span>
  <span m='917370'>learned</span> <span m='917610'>the</span> <span m='917730'>trapezoid</span>
  <span m='918140'>rule?</span> </p><p><span m='919496'>How</span> <span m='919980'>about</span>
  <span m='920690'>the</span> <span m='920810'>midpoint</span> <span m='921250'>rule?</span>
  <span m='923040'>How</span> <span m='923190'>about</span> <span m='924120'>Simpson's</span>
  <span m='924480'>rule?</span> <span m='927050'>All</span> <span m='927110'>right,</span>
  <span m='928220'>so</span> <span m='928430'>at</span> <span m='928490'>least</span>
  <span m='928750'>a</span> <span m='928820'>high</span> <span m='928940'>school</span>
  <span m='929150'>math</span> <span m='929360'>teachers</span> <span m='930380'>thought</span>
  <span m='930980'>that</span> <span m='931280'>this</span> <span m='931430'>is</span>
  <span m='931550'>inadequate</span> <span m='935470'>for</span> <span m='935810'>doing</span>
  <span m='936080'>real</span> <span m='936260'>work,</span> <span m='937310'>so</span>
  <span m='937430'>they</span> <span m='937550'>tell</span> <span m='937670'>you</span>
  <span m='937730'>all</span> <span m='937850'>these</span> <span m='937970'>other</span>
  <span m='938090'>things</span> <span m='938290'>instead.</span> <span m='938660'>This</span>
  <span m='938810'>was</span> <span m='938900'>like</span> <span m='939050'>your</span>
  <span m='939140'>first</span> <span m='939380'>baby</span> <span m='939650'>thing.</span>
  </p><p><span m='942020'>So</span> <span m='942290'>let's</span> <span m='942530'>talk</span>
  <span m='942800'>about</span> <span m='943010'>why</span> <span m='943310'>was</span>
  <span m='943490'>that.</span> <span m='959780'>So</span> <span m='961850'>let's</span>
  <span m='962390'>do</span> <span m='962510'>the</span> <span m='962590'>Taylor</span>
  <span m='962770'>expansion</span> <span m='963110'>a</span> <span m='963170'>little</span>
  <span m='963320'>bit</span> <span m='963410'>further.</span> <span m='963870'>So</span>
  <span m='964040'>let's</span> <span m='964160'>do</span> <span m='964280'>it</span>
  <span m='964370'>for</span> <span m='966110'>the</span> <span m='966230'>numeric</span>
  <span m='966640'>[INAUDIBLE]</span> <span m='967070'>case.</span> <span m='968650'>So</span>
  <span m='969010'>y</span> <span m='971086'>t</span> <span m='971540'>plus</span>
  <span m='971890'>delta</span> <span m='972060'>t</span> <span m='972310'>is</span>
  <span m='972500'>equal to</span> <span m='972970'>y</span> <span m='973220'>of</span>
  <span m='973560'>t</span> <span m='974990'>plus</span> <span m='976100'>delta</span>
  <span m='976220'>t</span> <span m='977120'>times</span> <span m='977670'>f</span>
  <span m='978125'>of</span> <span m='978580'>t</span> <span m='979945'>plus</span>
  <span m='980400'>1/2</span> <span m='981890'>delta</span> <span m='982160'>t</span>
  <span m='982500'>squared</span> <span m='984470'>times</span> <span m='985600'>the</span>
  <span m='985750'>second</span> <span m='986080'>derivative.</span> </p><p><span
  m='992320'>And</span> <span m='992960'>so</span> <span m='993220'>when</span> <span
  m='993340'>we</span> <span m='993460'>made</span> <span m='993640'>the</span> <span
  m='993730'>approximation</span> <span m='994510'>to</span> <span m='994600'>do</span>
  <span m='994690'>the</span> <span m='994780'>rectangle</span> <span m='995210'>rule,</span>
  <span m='995330'>we</span> <span m='995410'>just</span> <span m='995560'>threw</span>
  <span m='995740'>this</span> <span m='995950'>term</span> <span m='996190'>away.</span>
  <span m='997000'>So</span> <span m='997450'>that's</span> <span m='997650'>a</span>
  <span m='997700'>leading</span> <span m='997960'>term</span> <span m='998200'>that</span>
  <span m='998290'>we</span> <span m='998380'>threw</span> <span m='998590'>away.</span>
  <span m='999400'>So</span> <span m='999520'>we</span> <span m='999610'>made</span>
  <span m='999780'>an</span> <span m='999910'>error</span> <span m='1000240'>order</span>
  <span m='1000570'>or</span> <span m='1001020'>delta</span> <span m='1001310'>t squared.</span>
  <span m='1003280'>Because</span> <span m='1003520'>normally</span> <span m='1003910'>the</span>
  <span m='1003970'>second</span> <span m='1004090'>derivative is</span> <span m='1004270'>not</span>
  <span m='1004390'>exactly</span> <span m='1004720'>zero.</span> </p><p><span m='1006330'>So</span>
  <span m='1009260'>we</span> <span m='1009380'>have</span> <span m='1009470'>an</span>
  <span m='1009560'>error</span> <span m='1012050'>in</span> <span m='1012200'>each</span>
  <span m='1012380'>step</span> <span m='1017170'>that's</span> <span m='1017330'>the</span>
  <span m='1017390'>order</span> <span m='1017630'>of</span> <span m='1017720'>delta</span>
  <span m='1018070'>t squared.</span> <span m='1021070'>But</span> <span m='1021220'>how</span>
  <span m='1021310'>many</span> <span m='1021460'>steps</span> <span m='1021700'>do</span>
  <span m='1021790'>we</span> <span m='1021880'>make?</span> <span m='1022190'>The</span>
  <span m='1022480'>number</span> <span m='1022720'>of</span> <span m='1022780'>steps</span>
  <span m='1024920'>is</span> <span m='1025089'>equal</span> <span m='1025300'>to</span>
  <span m='1025660'>t</span> <span m='1026160'>final</span> <span m='1026680'>minus</span>
  <span m='1026990'>t naught</span> <span m='1027800'>over</span> <span m='1028099'>delta
  t.</span> <span m='1031270'>So</span> <span m='1031900'>therefore,</span> <span
  m='1032380'>we're</span> <span m='1032560'>making</span> <span m='1032920'>one</span>
  <span m='1033130'>over</span> <span m='1033369'>delta t</span> <span m='1033920'>order</span>
  <span m='1035430'>steps.</span> </p><p><span m='1036660'>So</span> <span m='1036780'>the</span>
  <span m='1036900'>total</span> <span m='1037220'>error</span> <span m='1037530'>is
  going</span> <span m='1037680'>to be</span> <span m='1037920'>approximately</span>
  <span m='1038670'>the</span> <span m='1038819'>number</span> <span m='1039089'>of</span>
  <span m='1039180'>steps</span> <span m='1039530'>times</span> <span m='1039930'>how</span>
  <span m='1039990'>much</span> <span m='1040170'>error</span> <span m='1040290'>you</span>
  <span m='1040380'>making</span> <span m='1040619'>each</span> <span m='1040740'>step.</span>
  <span m='1041700'>So</span> <span m='1041819'>it's</span> <span m='1041910'>going</span>
  <span m='1042030'>to</span> <span m='1042089'>be</span> <span m='1042569'>something</span>
  <span m='1042849'>the</span> <span m='1042930'>second</span> <span m='1043200'>power</span>
  <span m='1043480'>in</span> <span m='1043680'>delta t</span> <span m='1044099'>divided</span>
  <span m='1044490'>by something</span> <span m='1044579'>to the</span> <span m='1044670'>first</span>
  <span m='1044880'>power</span> <span m='1045119'>of</span> <span m='1045170'>delta
  t.</span> <span m='1046150'>So</span> <span m='1047480'>the</span> <span m='1047670'>total</span>
  <span m='1048099'>error</span> <span m='1051220'>in</span> <span m='1051360'>the</span>
  <span m='1052340'>integral</span> <span m='1052740'>I</span> <span m='1053730'>is</span>
  <span m='1053930'>going</span> <span m='1054050'>to</span> <span m='1054140'>be</span>
  <span m='1054310'>older</span> <span m='1054630'>of</span> <span m='1054950'>delta</span>
  <span m='1055020'>t</span> <span m='1056150'>if</span> <span m='1056460'>you</span>
  <span m='1056590'>do</span> <span m='1056700'>the</span> <span m='1056760'>rectangle</span>
  <span m='1057025'>rule.</span> </p><p><span m='1059080'>And</span> <span m='1059270'>so</span>
  <span m='1059570'>order</span> <span m='1059860'>delta t</span> <span m='1060230'>is</span>
  <span m='1060290'>not</span> <span m='1060470'>very</span> <span m='1060680'>good.</span>
  <span m='1061730'>So</span> <span m='1061970'>you</span> <span m='1062090'>want</span>
  <span m='1062300'>to</span> <span m='1064310'>increase</span> <span m='1064670'>your</span>
  <span m='1064790'>accuracy--</span> <span m='1065870'>if</span> <span m='1065990'>you</span>
  <span m='1066050'>cut</span> <span m='1066200'>your</span> <span m='1066290'>step
  size</span> <span m='1066730'>in</span> <span m='1066830'>half,</span> <span m='1067670'>that</span>
  <span m='1067760'>means</span> <span m='1067880'>you</span> <span m='1067940'>double</span>
  <span m='1068240'>your</span> <span m='1068360'>CPU</span> <span m='1068720'>time,</span>
  <span m='1069050'>because you</span> <span m='1069160'>have to</span> <span m='1069230'>do</span>
  <span m='1069350'>twice</span> <span m='1069620'>as</span> <span m='1069680'>many</span>
  <span m='1069890'>function</span> <span m='1070160'>evaluations.</span> <span m='1071870'>But</span>
  <span m='1071960'>you</span> <span m='1072050'>only</span> <span m='1072350'>gain--</span>
  <span m='1072725'>you</span> <span m='1073100'>reduce</span> <span m='1073310'>your</span>
  <span m='1073670'>error</span> <span m='1073760'>by a</span> <span m='1073790'>factor</span>
  <span m='1074030'>of</span> <span m='1074090'>two.</span> <span m='1075710'>So if</span>
  <span m='1075950'>you</span> <span m='1076040'>want</span> <span m='1076190'>to,</span>
  <span m='1076670'>say,</span> <span m='1076890'>gain</span> <span m='1077720'>three</span>
  <span m='1078080'>significant</span> <span m='1078470'>figures</span> <span m='1079510'>of</span>
  <span m='1079610'>accuracy</span> <span m='1080030'>in</span> <span m='1080100'>your</span>
  <span m='1080190'>number,</span> <span m='1080990'>then</span> <span m='1081140'>you</span>
  <span m='1081200'>have</span> <span m='1081290'>to</span> <span m='1081380'>do</span>
  <span m='1082910'>1,000</span> <span m='1083540'>times</span> <span m='1083830'>much</span>
  <span m='1084000'>work</span> <span m='1085460'>as</span> <span m='1085550'>you</span>
  <span m='1085610'>did</span> <span m='1085750'>before.</span> </p><p><span m='1086770'>So</span>
  <span m='1087020'>I</span> <span m='1087080'>have</span> <span m='1087210'>some</span>
  <span m='1087420'>amount</span> <span m='1087670'>of</span> <span m='1087800'>some</span>
  <span m='1087980'>precision</span> <span m='1088640'>with</span> <span m='1088730'>some</span>
  <span m='1088880'>number</span> <span m='1089060'>of</span> <span m='1089120'>steps.</span>
  <span m='1090320'>I</span> <span m='1090380'>want</span> <span m='1090500'>to</span>
  <span m='1090590'>increase,</span> <span m='1091190'>get three</span> <span m='1091455'>more</span>
  <span m='1091720'>significant</span> <span m='1091920'>figures.</span> <span m='1092270'>I'll
  have to</span> <span m='1092410'>do 1,000</span> <span m='1092960'>times</span>
  <span m='1093170'>as</span> <span m='1093230'>much</span> <span m='1093410'>work.</span>
  <span m='1094520'>That's</span> <span m='1094640'>kind</span> <span m='1094780'>of</span>
  <span m='1094850'>bad</span> <span m='1095030'>scaling.</span> <span m='1097160'>If
  I</span> <span m='1097220'>want</span> <span m='1097370'>to</span> <span m='1097430'>get</span>
  <span m='1097580'>six</span> <span m='1097990'>more</span> <span m='1098060'>significant</span>
  <span m='1098150'>figures,</span> <span m='1098420'>I've</span> <span m='1098500'>got
  to</span> <span m='1098610'>do</span> <span m='1098810'>a</span> <span m='1098910'>million</span>
  <span m='1099020'>times</span> <span m='1099260'>more</span> <span m='1099410'>work.</span>
  <span m='1100630'>So</span> <span m='1100760'>at</span> <span m='1100820'>some</span>
  <span m='1100970'>point,</span> <span m='1101400'>this</span> <span m='1101510'>going</span>
  <span m='1101640'>to</span> <span m='1101750'>be</span> <span m='1101880'>kind of</span>
  <span m='1102100'>expensive.</span> </p><p><span m='1105000'>So</span> <span m='1105350'>if</span>
  <span m='1105530'>you</span> <span m='1105680'>contrast</span> <span m='1106400'>it,</span>
  <span m='1107180'>you</span> <span m='1107270'>can</span> <span m='1107420'>do</span>
  <span m='1108830'>things</span> <span m='1109070'>like</span> <span m='1109620'>trapezoid</span>
  <span m='1110200'>rule.</span> <span m='1111730'>And</span> <span m='1113000'>as</span>
  <span m='1113140'>you're</span> <span m='1113230'>probably--</span> <span m='1115580'>well</span>
  <span m='1116040'>let's</span> <span m='1116210'>talk about</span> <span m='1116330'>trapezoid</span>
  <span m='1116720'>rule</span> <span m='1117211'>for a</span> <span m='1117702'>bit.</span>
  <span m='1128030'>So</span> <span m='1128150'>the</span> <span m='1128270'>idea</span>
  <span m='1128630'>of this</span> <span m='1128840'>is</span> <span m='1128930'>you</span>
  <span m='1129020'>have</span> <span m='1129110'>your</span> <span m='1129200'>function,</span>
  <span m='1132140'>you</span> <span m='1132260'>have</span> <span m='1132470'>some</span>
  <span m='1133120'>point</span> <span m='1134400'>t,</span> <span m='1135280'>and</span>
  <span m='1135460'>t</span> <span m='1135650'>plus</span> <span m='1135860'>delta</span>
  <span m='1135950'>t.</span> <span m='1136340'>You're</span> <span m='1136450'>trying</span>
  <span m='1136610'>to</span> <span m='1136700'>integrate</span> <span m='1137030'>between</span>
  <span m='1137230'>them.</span> </p><p><span m='1139420'>Let's</span> <span m='1139700'>say</span>
  <span m='1139920'>t naught,</span> <span m='1140430'>t</span> <span m='1140690'>naught</span>
  <span m='1141090'>plus</span> <span m='1141385'>delta t.</span> <span m='1143384'>Try
  to</span> <span m='1143810'>integrate.</span> <span m='1144960'>Here's</span> <span
  m='1145170'>the</span> <span m='1145230'>value</span> <span m='1145580'>of</span>
  <span m='1145680'>the</span> <span m='1145780'>function</span> <span m='1145930'>at</span>
  <span m='1146110'>t.</span> <span m='1147510'>Here</span> <span m='1147640'>is</span>
  <span m='1147780'>the</span> <span m='1148500'>value</span> <span m='1148850'>of</span>
  <span m='1148950'>the</span> <span m='1149010'>function</span> <span m='1149610'>that</span>
  <span m='1150305'>t</span> <span m='1150720'>plus</span> <span m='1151080'>delta
  t.</span> </p><p><span m='1153430'>If</span> <span m='1153550'>you</span> <span
  m='1153610'>do</span> <span m='1153730'>the</span> <span m='1153820'>rectangle</span>
  <span m='1154270'>rule,</span> <span m='1154540'>what</span> <span m='1154660'>you</span>
  <span m='1154780'>say</span> <span m='1155050'>is</span> <span m='1155200'>I</span>
  <span m='1155290'>just</span> <span m='1156500'>draw</span> <span m='1156650'>a</span>
  <span m='1156700'>line</span> <span m='1156910'>here</span> <span m='1157080'>and</span>
  <span m='1157150'>integrate</span> <span m='1157650'>that</span> <span m='1158290'>rectangle.</span>
  <span m='1160125'>But</span> <span m='1160570'>say</span> <span m='1160690'>the</span>
  <span m='1160780'>real</span> <span m='1160960'>function</span> <span m='1161350'>really</span>
  <span m='1161590'>looks</span> <span m='1161830'>like</span> <span m='1162040'>this.</span>
  <span m='1164480'>Then</span> <span m='1164660'>I</span> <span m='1164720'>missing</span>
  <span m='1165770'>that</span> <span m='1165950'>area</span> <span m='1166220'>there,</span>
  <span m='1166460'>so</span> <span m='1166610'>that's</span> <span m='1166790'>the</span>
  <span m='1166910'>error.</span> </p><p><span m='1167560'>That's</span> <span m='1167720'>why
  the</span> <span m='1167820'>error's</span> <span m='1168030'>so big.</span> <span
  m='1170280'>If</span> <span m='1170460'>I</span> <span m='1170580'>do</span> <span
  m='1170820'>that</span> <span m='1171310'>trapezoid</span> <span m='1172030'>rule,</span>
  <span m='1174920'>then</span> <span m='1175740'>the</span> <span m='1176020'>error--</span>
  <span m='1177140'>I</span> <span m='1177330'>actually</span> <span m='1177600'>overestimate</span>
  <span m='1178650'>the</span> <span m='1179470'>value</span> <span m='1179730'>here,</span>
  <span m='1180570'>but</span> <span m='1180720'>the</span> <span m='1180840'>integral</span>
  <span m='1181470'>of</span> <span m='1181650'>the</span> <span m='1181770'>difference</span>
  <span m='1182130'>between</span> <span m='1182400'>this</span> <span m='1182470'>dotted</span>
  <span m='1182730'>line</span> <span m='1182940'>and the</span> <span m='1183030'>solid</span>
  <span m='1183330'>line</span> <span m='1183930'>is</span> <span m='1184140'>less</span>
  <span m='1184620'>than</span> <span m='1184770'>the</span> <span m='1184830'>integral</span>
  <span m='1185250'>between</span> <span m='1185460'>the</span> <span m='1185610'>solid</span>
  <span m='1185760'>line</span> <span m='1185990'>and that</span> <span m='1186300'>dotted</span>
  <span m='1186630'>line,</span> <span m='1187420'>so</span> <span m='1187530'>its</span>
  <span m='1187650'>more</span> <span m='1187800'>accurate.</span> <span m='1189280'>So</span>
  <span m='1189300'>that's</span> <span m='1189450'>why</span> <span m='1189540'>people
  like</span> <span m='1189840'>the</span> <span m='1189930'>trapezoid</span> <span
  m='1190180'>rule</span> <span m='1190470'>better</span> <span m='1191280'>than</span>
  <span m='1191400'>the</span> <span m='1191460'>rectangle</span> <span m='1191900'>rule.</span>
  </p><p><span m='1192886'>If you</span> <span m='1193380'>did the</span> <span m='1193500'>midpoint</span>
  <span m='1194070'>rule,</span> <span m='1195120'>you'd</span> <span m='1195270'>evaluate</span>
  <span m='1196560'>this</span> <span m='1196740'>function</span> <span m='1198330'>halfway</span>
  <span m='1198570'>between</span> <span m='1198870'>these</span> <span m='1198960'>two</span>
  <span m='1199110'>points</span> <span m='1200320'>and</span> <span m='1200420'>then</span>
  <span m='1200520'>draw</span> <span m='1200790'>a dotted</span> <span m='1200850'>line</span>
  <span m='1201090'>here</span> <span m='1201520'>and</span> <span m='1201785'>a dotted</span>
  <span m='1202050'>line</span> <span m='1202180'>there,</span> <span m='1202815'>and</span>
  <span m='1203080'>integrate</span> <span m='1203520'>that</span> <span m='1203730'>guy.</span>
  <span m='1205020'>And</span> <span m='1205880'>it</span> <span m='1205940'>would</span>
  <span m='1206080'>overestimate</span> <span m='1206400'>for</span> <span m='1206720'>part,</span>
  <span m='1207170'>and</span> <span m='1207360'>underestimate</span> <span m='1207715'>for</span>
  <span m='1208070'>part,</span> <span m='1208740'>and</span> <span m='1208830'>they</span>
  <span m='1208920'>would</span> <span m='1209010'>partially</span> <span m='1209310'>cancel</span>
  <span m='1209610'>each</span> <span m='1209730'>other</span> <span m='1209940'>out.</span>
  <span m='1210940'>And</span> <span m='1210960'>so</span> <span m='1211080'>that</span>
  <span m='1211290'>also</span> <span m='1211500'>would</span> <span m='1211590'>be</span>
  <span m='1211680'>more</span> <span m='1211860'>accurate</span> <span m='1212670'>than</span>
  <span m='1213510'>doing</span> <span m='1213750'>the</span> <span m='1213870'>rectangle</span>
  <span m='1214125'>rule.</span> </p><p><span m='1217770'>So</span> <span m='1217890'>you</span>
  <span m='1217980'>did</span> <span m='1218160'>it</span> <span m='1218220'>before.</span>
  <span m='1223740'>And</span> <span m='1224160'>so</span> <span m='1224520'>what</span>
  <span m='1224880'>we're</span> <span m='1224970'>going</span> <span m='1225090'>to</span>
  <span m='1225150'>try</span> <span m='1225390'>to</span> <span m='1225480'>do</span>
  <span m='1225660'>is,</span> <span m='1226050'>instead</span> <span m='1226350'>of</span>
  <span m='1226410'>using</span> <span m='1226740'>this</span> <span m='1227100'>formula</span>
  <span m='1227430'>we</span> <span m='1227760'>did</span> <span m='1228060'>before,</span>
  <span m='1229110'>we're</span> <span m='1229230'>going</span> <span m='1229380'>to</span>
  <span m='1229440'>replace</span> <span m='1229980'>this</span> <span m='1231450'>with</span>
  <span m='1231570'>something</span> <span m='1231870'>else</span> <span m='1232150'>that</span>
  <span m='1232250'>I'm</span> <span m='1232350'>going</span> <span m='1232450'>to</span>
  <span m='1232550'>call</span> <span m='1232650'>g.</span> <span m='1235300'>And</span>
  <span m='1235600'>g</span> <span m='1236200'>is</span> <span m='1236410'>something</span>
  <span m='1236660'>that's</span> <span m='1236770'>supposed</span> <span m='1237040'>to</span>
  <span m='1237160'>be</span> <span m='1237250'>the</span> <span m='1237400'>average</span>
  <span m='1237820'>value</span> <span m='1238150'>of</span> <span m='1238240'>f</span>
  <span m='1239650'>over</span> <span m='1239950'>the</span> <span m='1240280'>step.</span>
  <span m='1241510'>Instead</span> <span m='1241720'>of</span> <span m='1241780'>just</span>
  <span m='1241900'>taking</span> <span m='1242140'>the</span> <span m='1242230'>value</span>
  <span m='1243115'>f</span> <span m='1243490'>at</span> <span m='1243850'>the</span>
  <span m='1244300'>starting</span> <span m='1244630'>point,</span> <span m='1245410'>I</span>
  <span m='1245470'>want</span> <span m='1245590'>to</span> <span m='1245650'>get</span>
  <span m='1245770'>sort</span> <span m='1245920'>of</span> <span m='1246190'>the</span>
  <span m='1246400'>average.</span> <span m='1247600'>Right,</span> <span m='1247790'>because</span>
  <span m='1247990'>an</span> <span m='1248140'>integral</span> <span m='1248390'>is</span>
  <span m='1248550'>related</span> <span m='1248780'>to</span> <span m='1248860'>an</span>
  <span m='1248920'>average</span> <span m='1249760'>over</span> <span m='1250000'>the</span>
  <span m='1250150'>delta</span> <span m='1250300'>t.</span> </p><p><span m='1251170'>So</span>
  <span m='1251440'>g</span> <span m='1251680'>is</span> <span m='1251740'>going</span>
  <span m='1251860'>to</span> <span m='1251920'>be</span> <span m='1251980'>my</span>
  <span m='1252160'>way</span> <span m='1252340'>to</span> <span m='1252460'>estimate</span>
  <span m='1253570'>the</span> <span m='1253720'>average.</span> <span m='1254500'>And</span>
  <span m='1254620'>there's</span> <span m='1254740'>going</span> <span m='1254860'>to</span>
  <span m='1254920'>be</span> <span m='1255640'>a</span> <span m='1255700'>zillion</span>
  <span m='1256390'>update</span> <span m='1256630'>formulas</span> <span m='1257110'>that</span>
  <span m='1257200'>different</span> <span m='1257530'>mathematicians</span> <span
  m='1258130'>have</span> <span m='1258220'>proposed</span> <span m='1258610'>over</span>
  <span m='1258760'>the</span> <span m='1258880'>years.</span> <span m='1259630'>They</span>
  <span m='1259750'>give</span> <span m='1259900'>you</span> <span m='1259960'>different</span>
  <span m='1260260'>g's</span> <span m='1261190'>that</span> <span m='1261370'>tell</span>
  <span m='1261490'>you</span> <span m='1261580'>how</span> <span m='1261700'>to</span>
  <span m='1261760'>do</span> <span m='1261850'>the</span> <span m='1262050'>update.</span>
  <span m='1265240'>And</span> <span m='1265450'>the</span> <span m='1265570'>key</span>
  <span m='1265870'>is</span> <span m='1265960'>try</span> <span m='1266110'>to</span>
  <span m='1266200'>find</span> <span m='1266530'>a g that's</span> <span m='1266740'>really</span>
  <span m='1266980'>accurate.</span> </p><p><span m='1267500'>You</span> <span m='1267600'>want</span>
  <span m='1267610'>to</span> <span m='1267670'>have</span> <span m='1267760'>one</span>
  <span m='1267910'>that's</span> <span m='1268120'>the</span> <span m='1268480'>most</span>
  <span m='1268690'>accurate</span> <span m='1268930'>you</span> <span m='1269050'>can,</span>
  <span m='1269420'>because</span> <span m='1269540'>then</span> <span m='1269650'>your
  errors</span> <span m='1269820'>will be</span> <span m='1270130'>less.</span> <span
  m='1271060'>And</span> <span m='1271310'>if</span> <span m='1271420'>your</span>
  <span m='1271540'>errors</span> <span m='1271840'>are</span> <span m='1271930'>less,</span>
  <span m='1272860'>than</span> <span m='1273010'>your</span> <span m='1273100'>delta</span>
  <span m='1273400'>t</span> <span m='1273700'>can</span> <span m='1273910'>be</span>
  <span m='1274030'>bigger,</span> <span m='1275420'>which</span> <span m='1275470'>means</span>
  <span m='1275650'>your</span> <span m='1275810'>number</span> <span m='1276040'>of
  steps</span> <span m='1276280'>will</span> <span m='1276370'>be</span> <span m='1276460'>less,</span>
  <span m='1277250'>which</span> <span m='1277300'>means</span> <span m='1277460'>your</span>
  <span m='1277550'>CPU</span> <span m='1277830'>time</span> <span m='1278010'>will</span>
  <span m='1278100'>be</span> <span m='1278220'>less.</span> <span m='1279700'>So</span>
  <span m='1280540'>you</span> <span m='1280660'>might</span> <span m='1280780'>be</span>
  <span m='1280840'>able</span> <span m='1280960'>to</span> <span m='1281020'>get</span>
  <span m='1281140'>more</span> <span m='1281350'>accuracy</span> <span m='1281920'>and</span>
  <span m='1282280'>use</span> <span m='1282490'>less</span> <span m='1282670'>CPU</span>
  <span m='1282970'>time</span> <span m='1283180'>both</span> <span m='1284260'>if</span>
  <span m='1284380'>you</span> <span m='1284440'>can</span> <span m='1284560'>find</span>
  <span m='1284740'>a</span> <span m='1284800'>really</span> <span m='1285040'>good</span>
  <span m='1285170'>formula</span> <span m='1285500'>for</span> <span m='1285640'>g,</span>
  <span m='1285910'>for the</span> <span m='1286110'>update.</span> </p><p><span m='1289830'>So</span>
  <span m='1290790'>what's</span> <span m='1291000'>the</span> <span m='1291120'>g</span>
  <span m='1291540'>for</span> <span m='1291690'>the</span> <span m='1292150'>trapezoid</span>
  <span m='1292410'>rule?</span> <span m='1297300'>It's</span> <span m='1299410'>f</span>
  <span m='1299630'>of</span> <span m='1299750'>t</span> <span m='1300125'>plus</span>
  <span m='1301220'>f</span> <span m='1301535'>of</span> <span m='1301850'>t</span>
  <span m='1301970'>plus</span> <span m='1302300'>delta t</span> <span m='1304160'>over</span>
  <span m='1304460'>2.</span> <span m='1306800'>That</span> <span m='1307010'>was</span>
  <span m='1307130'>the</span> <span m='1307220'>g</span> <span m='1307520'>you used</span>
  <span m='1307820'>when</span> <span m='1307970'>you did</span> <span m='1308210'>the</span>
  <span m='1308270'>trapezoid</span> <span m='1308500'>rule</span> <span m='1308580'>when</span>
  <span m='1308690'>you</span> <span m='1308950'>were</span> <span m='1309080'>kids.</span>
  <span m='1311440'>What</span> <span m='1311580'>is</span> <span m='1311700'>the</span>
  <span m='1311780'>g</span> <span m='1311990'>for</span> <span m='1312140'>the</span>
  <span m='1312230'>midpoint</span> <span m='1312590'>rule?</span> <span m='1317280'>It's</span>
  <span m='1318790'>f</span> <span m='1319030'>of</span> <span m='1319393'>t</span>
  <span m='1320120'>plus</span> <span m='1320630'>delta</span> <span m='1320960'>t</span>
  <span m='1321434'>over</span> <span m='1321908'>2.</span> <span m='1326410'>And</span>
  <span m='1326600'>so</span> <span m='1326750'>the</span> <span m='1326870'>different</span>
  <span m='1327200'>g's</span> <span m='1327500'>are</span> <span m='1327900'>called</span>
  <span m='1328130'>different</span> <span m='1328370'>update</span> <span m='1328640'>formulas.</span>
  </p><p><span m='1330960'>And</span> <span m='1331350'>these</span> <span m='1331590'>particular</span>
  <span m='1332100'>ones</span> <span m='1332910'>reduce</span> <span m='1333450'>the</span>
  <span m='1334350'>error</span> <span m='1334740'>from</span> <span m='1335060'>delta
  t</span> <span m='1337240'>squared</span> <span m='1337770'>for</span> <span m='1338390'>[INAUDIBLE]</span>
  <span m='1338840'>step</span> <span m='1340140'>to,</span> <span m='1340455'>I think,</span>
  <span m='1340770'>delta t</span> <span m='1341100'>to the</span> <span m='1341430'>cubed</span>
  <span m='1342030'>power.</span> <span m='1343260'>And</span> <span m='1343410'>then</span>
  <span m='1344700'>when</span> <span m='1344910'>you</span> <span m='1345570'>multiply</span>
  <span m='1346110'>by</span> <span m='1346260'>this</span> <span m='1346410'>1</span>
  <span m='1346560'>every</span> <span m='1346740'>delta t,</span> <span m='1347670'>it</span>
  <span m='1347760'>turns</span> <span m='1348000'>out</span> <span m='1348120'>you</span>
  <span m='1348240'>go</span> <span m='1348450'>from</span> <span m='1348630'>being</span>
  <span m='1349480'>order</span> <span m='1349760'>of</span> <span m='1349860'>delta
  t</span> <span m='1350980'>to</span> <span m='1351090'>order</span> <span m='1351480'>of
  delta</span> <span m='1351760'>t squared,</span> <span m='1354000'>and</span> <span
  m='1354120'>that's</span> <span m='1354270'>a</span> <span m='1354360'>really</span>
  <span m='1354540'>big</span> <span m='1354690'>change.</span> <span m='1355840'>So</span>
  <span m='1355950'>now</span> <span m='1356340'>if</span> <span m='1356580'>I</span>
  <span m='1357720'>cut</span> <span m='1357930'>the step</span> <span m='1358050'>size</span>
  <span m='1358530'>by</span> <span m='1358710'>a</span> <span m='1358740'>factor</span>
  <span m='1359070'>of</span> <span m='1359130'>10,</span> <span m='1360280'>I</span>
  <span m='1360390'>gain</span> <span m='1360630'>a</span> <span m='1360690'>factor</span>
  <span m='1360900'>of</span> <span m='1360990'>100</span> <span m='1361830'>in</span>
  <span m='1362070'>the</span> <span m='1362310'>accuracy.</span> <span m='1363960'>If</span>
  <span m='1364230'>I</span> <span m='1364380'>want</span> <span m='1364500'>to</span>
  <span m='1364560'>get</span> <span m='1364770'>six</span> <span m='1364980'>more</span>
  <span m='1365160'>significant</span> <span m='1365430'>figures,</span> <span m='1365820'>I</span>
  <span m='1365890'>do</span> <span m='1366000'>1,000</span> <span m='1366360'>times</span>
  <span m='1366570'>more</span> <span m='1366690'>work,</span> <span m='1366960'>not</span>
  <span m='1367050'>a</span> <span m='1367110'>million</span> <span m='1367420'>times</span>
  <span m='1367580'>more</span> <span m='1368023'>work.</span> <span m='1368910'>So</span>
  <span m='1369840'>it's</span> <span m='1369960'>a</span> <span m='1370020'>pretty</span>
  <span m='1370230'>significant</span> <span m='1370590'>improvement.</span> </p><p><span
  m='1372220'>And then</span> <span m='1372340'>people</span> <span m='1372600'>have</span>
  <span m='1372720'>pushed</span> <span m='1373020'>this</span> <span m='1373170'>on</span>
  <span m='1373350'>further</span> <span m='1373650'>and</span> <span m='1373740'>further.</span>
  <span m='1374640'>And</span> <span m='1374760'>so</span> <span m='1374880'>actually</span>
  <span m='1375300'>very</span> <span m='1375540'>common</span> <span m='1375870'>integrators</span>
  <span m='1376320'>that</span> <span m='1376410'>you</span> <span m='1376500'>might</span>
  <span m='1376680'>use</span> <span m='1376860'>nowadays</span> <span m='1377695'>would</span>
  <span m='1377970'>go</span> <span m='1378140'>out</span> <span m='1378270'>to</span>
  <span m='1378360'>fourth</span> <span m='1378630'>and</span> <span m='1378720'>fifth</span>
  <span m='1378960'>order</span> <span m='1380220'>methods.</span> <span m='1382160'>And</span>
  <span m='1382320'>so</span> <span m='1382410'>they</span> <span m='1382500'>have</span>
  <span m='1382770'>complicated</span> <span m='1383280'>update</span> <span m='1383540'>formulas</span>
  <span m='1384510'>that</span> <span m='1384630'>are</span> <span m='1384690'>carefully</span>
  <span m='1385050'>designed</span> <span m='1385380'>to</span> <span m='1385470'>cancel</span>
  <span m='1385830'>out</span> <span m='1385950'>all</span> <span m='1386070'>the</span>
  <span m='1386160'>low</span> <span m='1386370'>order</span> <span m='1387150'>delta</span>
  <span m='1387495'>t</span> <span m='1387840'>errors</span> <span m='1388410'>and</span>
  <span m='1388500'>just</span> <span m='1388620'>leave</span> <span m='1388770'>very</span>
  <span m='1388920'>high</span> <span m='1389070'>order</span> <span m='1389280'>ones.</span>
  </p><p><span m='1390390'>And</span> <span m='1390480'>that's</span> <span m='1390930'>kind</span>
  <span m='1391050'>of</span> <span m='1391110'>the--</span> <span m='1392100'>typical</span>
  <span m='1392460'>ones</span> <span m='1392700'>are like</span> <span m='1392850'>that.</span>
  <span m='1393030'>And</span> <span m='1393130'>then</span> <span m='1393220'>some</span>
  <span m='1393420'>fancy</span> <span m='1393750'>ones</span> <span m='1393930'>might</span>
  <span m='1394080'>go</span> <span m='1394230'>even</span> <span m='1394380'>up</span>
  <span m='1394440'>to</span> <span m='1394500'>eighth</span> <span m='1394710'>order,</span>
  <span m='1394960'>I've seen,</span> <span m='1396970'>if</span> <span m='1397110'>you're</span>
  <span m='1397260'>really</span> <span m='1397680'>pushing</span> <span m='1397950'>it.</span>
  <span m='1398620'>You</span> <span m='1398730'>have</span> <span m='1398910'>really</span>
  <span m='1399060'>complicated</span> <span m='1399360'>g</span> <span m='1399660'>formulas</span>
  <span m='1399915'>then.</span> </p><p><span m='1407260'>Now,</span> <span m='1409460'>this</span>
  <span m='1409640'>is</span> <span m='1409730'>all for</span> <span m='1410210'>the</span>
  <span m='1410330'>integration,</span> <span m='1411980'>but</span> <span m='1412070'>really</span>
  <span m='1412340'>our</span> <span m='1412430'>problem</span> <span m='1413480'>was</span>
  <span m='1413750'>that</span> <span m='1414280'>the</span> <span m='1414440'>ODEs</span>
  <span m='1415040'>[INAUDIBLE].</span> <span m='1415950'>So</span> <span m='1419840'>we</span>
  <span m='1419930'>have</span> <span m='1420050'>to do</span> <span m='1420170'>f
  of</span> <span m='1420460'>y</span> <span m='1421010'>not</span> <span m='1421220'>f
  of</span> <span m='1421420'>t.</span> <span m='1421780'>Let's see if</span> <span
  m='1422250'>I can</span> <span m='1422720'>show you</span> <span m='1423190'>that.</span>
  </p><p><span m='1425070'>Yeah,</span> <span m='1425350'>so</span> <span m='1425470'>we</span>
  <span m='1425570'>did</span> <span m='1426320'>the</span> <span m='1428090'>rectangle</span>
  <span m='1428500'>rule,</span> <span m='1429560'>we</span> <span m='1429650'>had</span>
  <span m='1429850'>f of</span> <span m='1430000'>t.</span> <span m='1432140'>But</span>
  <span m='1432500'>the</span> <span m='1432620'>real</span> <span m='1432800'>problem</span>
  <span m='1433310'>is</span> <span m='1433670'>we</span> <span m='1433730'>have</span>
  <span m='1433820'>to</span> <span m='1433940'>do</span> <span m='1434120'>f</span>
  <span m='1434270'>of</span> <span m='1434420'>y.</span> <span m='1435320'>Now</span>
  <span m='1435440'>the</span> <span m='1435530'>problem</span> <span m='1436010'>is,</span>
  <span m='1437330'>we</span> <span m='1437420'>don't</span> <span m='1437570'>know</span>
  <span m='1437690'>what</span> <span m='1437810'>y is,</span> <span m='1438280'>y</span>
  <span m='1438750'>is</span> <span m='1438960'>our</span> <span m='1439110'>unknown.</span>
  <span m='1440710'>So</span> <span m='1440950'>we</span> <span m='1441400'>generally</span>
  <span m='1441700'>have</span> <span m='1441820'>a</span> <span m='1441880'>problem</span>
  <span m='1442300'>here.</span> </p><p><span m='1443880'>In</span> <span m='1444610'>Forward</span>
  <span m='1444850'>Euler,</span> <span m='1445180'>we</span> <span m='1445240'>can</span>
  <span m='1445330'>get</span> <span m='1445450'>away</span> <span m='1445690'>with</span>
  <span m='1445870'>it</span> <span m='1445990'>because</span> <span m='1446290'>we</span>
  <span m='1446380'>just</span> <span m='1446530'>put</span> <span m='1446680'>the</span>
  <span m='1446770'>y</span> <span m='1447070'>old</span> <span m='1447310'>value</span>
  <span m='1447700'>in.</span> <span m='1448930'>Like</span> <span m='1449080'>for</span>
  <span m='1449170'>example,</span> <span m='1449510'>if we</span> <span m='1449620'>wanted</span>
  <span m='1449860'>to</span> <span m='1449980'>do</span> <span m='1450190'>midpoint</span>
  <span m='1452800'>here,</span> <span m='1454450'>we'd</span> <span m='1454570'>have</span>
  <span m='1454660'>to</span> <span m='1454750'>know</span> <span m='1455600'>f</span>
  <span m='1456250'>at</span> <span m='1456430'>a</span> <span m='1456490'>different</span>
  <span m='1456850'>time</span> <span m='1457090'>point</span> <span m='1457690'>that</span>
  <span m='1457780'>we</span> <span m='1457870'>haven't</span> <span m='1458020'>computed</span>
  <span m='1458380'>yet,</span> <span m='1458650'>because</span> <span m='1459070'>it's</span>
  <span m='1459340'>forward</span> <span m='1459570'>in</span> <span m='1459660'>time.</span>
  <span m='1460260'>Same</span> <span m='1460360'>thing</span> <span m='1460670'>with</span>
  <span m='1460840'>trapezoidal</span> <span m='1461125'>rule.</span> </p><p><span
  m='1461410'>We</span> <span m='1461500'>have</span> <span m='1461590'>to</span>
  <span m='1461650'>know</span> <span m='1461810'>f at</span> <span m='1462070'>some</span>
  <span m='1462700'>future</span> <span m='1462970'>timepoint.</span> <span m='1464200'>So</span>
  <span m='1464950'>it's</span> <span m='1465070'>not</span> <span m='1465250'>so</span>
  <span m='1465430'>easy,</span> <span m='1465730'>actually,</span> <span m='1465970'>to</span>
  <span m='1466060'>go</span> <span m='1466180'>directly</span> <span m='1466540'>from</span>
  <span m='1466720'>these</span> <span m='1466900'>formulas</span> <span m='1468550'>to</span>
  <span m='1469370'>some</span> <span m='1469510'>explicit</span> <span m='1469610'>formula</span>
  <span m='1470070'>like</span> <span m='1470230'>this</span> <span m='1470860'>with</span>
  <span m='1471010'>a</span> <span m='1471070'>g</span> <span m='1471280'>in</span>
  <span m='1471400'>here,</span> <span m='1472330'>where</span> <span m='1472570'>the</span>
  <span m='1472720'>things</span> <span m='1473020'>inside</span> <span m='1473490'>g,</span>
  <span m='1473810'>the</span> <span m='1474130'>y's</span> <span m='1474460'>inside</span>
  <span m='1474580'>g,</span> <span m='1474880'>are all</span> <span m='1475000'>y-values</span>
  <span m='1475510'>we</span> <span m='1475570'>actually</span> <span m='1475850'>know.</span>
  <span m='1477810'>So</span> <span m='1477970'>this</span> <span m='1478150'>is</span>
  <span m='1478310'>a</span> <span m='1478940'>serious</span> <span m='1479240'>problem.</span>
  </p><p><span m='1485600'>But</span> <span m='1486030'>this</span> <span m='1486110'>didn't</span>
  <span m='1486320'>stop</span> <span m='1486500'>people</span> <span m='1486770'>from</span>
  <span m='1486920'>doing</span> <span m='1487150'>it.</span> <span m='1488570'>So</span>
  <span m='1488810'>one</span> <span m='1488990'>idea</span> <span m='1489740'>is</span>
  <span m='1489890'>you</span> <span m='1490010'>could</span> <span m='1490160'>go</span>
  <span m='1490550'>back</span> <span m='1490910'>to</span> <span m='1491060'>the</span>
  <span m='1491390'>Taylor</span> <span m='1491810'>expansion,</span> <span m='1494240'>and</span>
  <span m='1496070'>now</span> <span m='1496310'>do</span> <span m='1496460'>the</span>
  <span m='1496580'>Taylor</span> <span m='1496850'>expansion</span> <span m='1497450'>but</span>
  <span m='1497990'>in</span> <span m='1498050'>terms</span> <span m='1498290'>of</span>
  <span m='1498380'>f of</span> <span m='1498818'>y.</span> <span m='1501450'>So this</span>
  <span m='1501720'>is</span> <span m='1501930'>f</span> <span m='1502120'>of</span>
  <span m='1503140'>y</span> <span m='1503550'>of t.</span> <span m='1506240'>And</span>
  <span m='1506360'>then</span> <span m='1506510'>over</span> <span m='1506790'>here,</span>
  <span m='1508900'>this</span> <span m='1509110'>is</span> <span m='1510920'>d squared</span>
  <span m='1511380'>y dt</span> <span m='1511600'>squared,</span> <span m='1512140'>but</span>
  <span m='1512400'>dy</span> <span m='1512590'>dt</span> <span m='1512920'>is</span>
  <span m='1513040'>f,</span> <span m='1513370'>so</span> <span m='1513520'>this</span>
  <span m='1513670'>is</span> <span m='1513760'>really</span> <span m='1518540'>df</span>
  <span m='1518700'>dt.</span> <span m='1521080'>But</span> <span m='1521340'>f is</span>
  <span m='1521470'>actually</span> <span m='1521710'>not</span> <span m='1521850'>a
  function</span> <span m='1521940'>of t,</span> <span m='1522270'>it's</span> <span
  m='1522370'>a</span> <span m='1522430'>function</span> <span m='1522640'>of</span>
  <span m='1522730'>y,</span> <span m='1522970'>right?</span> </p><p><span m='1523540'>But</span>
  <span m='1523620'>we</span> <span m='1523700'>can</span> <span m='1523780'>do</span>
  <span m='1523900'>chain</span> <span m='1524400'>rule.</span> <span m='1524980'>So</span>
  <span m='1525250'>df</span> <span m='1525615'>dt</span> <span m='1532170'>is</span>
  <span m='1532350'>equal</span> <span m='1532620'>to</span> <span m='1532800'>the</span>
  <span m='1532890'>sum</span> <span m='1534950'>df</span> <span m='1537108'>dyn</span>
  <span m='1540315'>dyn</span> <span m='1541150'>dt.</span> <span m='1545630'>But</span>
  <span m='1545780'>dyn</span> <span m='1545940'>dt</span> <span m='1546810'>is</span>
  <span m='1547000'>f.</span> <span m='1548680'>And</span> <span m='1548800'>this</span>
  <span m='1549100'>is</span> <span m='1549220'>what</span> <span m='1549310'>we</span>
  <span m='1549370'>call</span> <span m='1549530'>the</span> <span m='1549630'>Jacobian</span>
  <span m='1550073'>[INAUDIBLE].</span> <span m='1550960'>So</span> <span m='1551110'>this</span>
  <span m='1551320'>is</span> <span m='1551440'>really</span> <span m='1551770'>saying</span>
  <span m='1553290'>that this</span> <span m='1553420'>is equal</span> <span m='1553840'>to</span>
  <span m='1554500'>J</span> <span m='1555400'>times</span> <span m='1556060'>f.</span>
  </p><p><span m='1559550'>So</span> <span m='1559700'>that</span> <span m='1559820'>would</span>
  <span m='1559910'>be</span> <span m='1560000'>one</span> <span m='1560210'>possibility,</span>
  <span m='1560930'>is</span> <span m='1561080'>you</span> <span m='1561200'>could</span>
  <span m='1561380'>go</span> <span m='1561650'>and</span> <span m='1561770'>write</span>
  <span m='1561950'>the</span> <span m='1562010'>Taylor</span> <span m='1562330'>expansion</span>
  <span m='1562670'>out</span> <span m='1562790'>to</span> <span m='1562880'>the</span>
  <span m='1562970'>next</span> <span m='1563240'>higher</span> <span m='1563450'>order</span>
  <span m='1563690'>explicitly,</span> <span m='1565190'>putting</span> <span m='1565490'>in</span>
  <span m='1565610'>J</span> <span m='1565820'>times</span> <span m='1566000'>f</span>
  <span m='1566240'>here,</span> <span m='1567380'>and</span> <span m='1567530'>then</span>
  <span m='1568400'>just</span> <span m='1568580'>being</span> <span m='1568820'>in</span>
  <span m='1569400'>the</span> <span m='1569500'>cubic</span> <span m='1569680'>terms.</span>
  <span m='1571920'>Now,</span> <span m='1572090'>people</span> <span m='1572360'>don't</span>
  <span m='1572540'>do</span> <span m='1572660'>this</span> <span m='1572840'>usually.</span>
  <span m='1573370'>Any</span> <span m='1573680'>idea</span> <span m='1573950'>why</span>
  <span m='1574580'>this</span> <span m='1574730'>is</span> <span m='1574790'>not</span>
  <span m='1574940'>a</span> <span m='1575000'>popular</span> <span m='1575330'>thing</span>
  <span m='1575480'>to</span> <span m='1575570'>do?</span> <span m='1579024'>Yeah?</span>
  </p><p><span m='1579496'>AUDIENCE:</span> <span m='1579732'>It's</span> <span m='1579968'>computationally</span>
  <span m='1580440'>expensive</span> <span m='1580912'>to</span> <span m='1581384'>[INAUDIBLE].</span>
  </p><p><span m='1582810'>WILLIAM GREEN JR:</span> <span m='1582885'>That's</span>
  <span m='1582960'>right.</span> <span m='1583350'>That's</span> <span m='1583470'>right.</span>
  <span m='1583630'>So</span> <span m='1583680'>how</span> <span m='1584100'>many</span>
  <span m='1584490'>function</span> <span m='1584790'>evaluations</span> <span m='1585330'>does</span>
  <span m='1585480'>it</span> <span m='1585570'>take</span> <span m='1585720'>to</span>
  <span m='1586080'>get</span> <span m='1586200'>the</span> <span m='1586290'>Jacobian?</span>
  <span m='1592270'>Right,</span> <span m='1592880'>so</span> <span m='1593090'>each</span>
  <span m='1593930'>function</span> <span m='1596430'>is</span> <span m='1596630'>n</span>
  <span m='1596820'>values,</span> <span m='1597170'>right,</span> <span m='1597390'>because
  it's</span> <span m='1597560'>a</span> <span m='1597590'>vector.</span> <span m='1598930'>And</span>
  <span m='1599060'>you</span> <span m='1599180'>have</span> <span m='1599300'>to</span>
  <span m='1599360'>do</span> <span m='1599510'>at</span> <span m='1599570'>least,</span>
  <span m='1600620'>say,</span> <span m='1601700'>forward</span> <span m='1601880'>differences</span>
  <span m='1603530'>would</span> <span m='1603650'>be</span> <span m='1604480'>n</span>
  <span m='1604640'>function</span> <span m='1604940'>evaluations.</span> <span m='1606750'>So</span>
  <span m='1606930'>instead</span> <span m='1607260'>of</span> <span m='1607320'>just</span>
  <span m='1607470'>doing</span> <span m='1607710'>one</span> <span m='1607890'>function</span>
  <span m='1608190'>evaluation</span> <span m='1608700'>like</span> <span m='1608850'>we</span>
  <span m='1608890'>were</span> <span m='1608970'>doing</span> <span m='1609180'>with</span>
  <span m='1609330'>the</span> <span m='1609420'>Forward</span> <span m='1609690'>Euler,</span>
  <span m='1610530'>now</span> <span m='1610710'>we</span> <span m='1610770'>have</span>
  <span m='1610860'>to</span> <span m='1610950'>do</span> <span m='1611170'>n plus</span>
  <span m='1611410'>1,</span> <span m='1611640'>or</span> <span m='1611700'>something</span>
  <span m='1611940'>like</span> <span m='1612060'>that,</span> <span m='1612540'>function</span>
  <span m='1612810'>evaluations.</span> </p><p><span m='1614190'>And</span> <span
  m='1614340'>actually,</span> <span m='1614580'>you</span> <span m='1614910'>probably</span>
  <span m='1615090'>want</span> <span m='1615210'>to use</span> <span m='1615270'>center</span>
  <span m='1615510'>differences,</span> <span m='1615835'>so you</span> <span m='1616160'>need</span>
  <span m='1616560'>2</span> <span m='1616740'>times</span> <span m='1617040'>n plus</span>
  <span m='1617310'>1.</span> <span m='1619260'>And</span> <span m='1619650'>if</span>
  <span m='1619770'>you</span> <span m='1619980'>do them</span> <span m='1620130'>analytically,</span>
  <span m='1621660'>unless</span> <span m='1621930'>it's</span> <span m='1622020'>sparse,</span>
  <span m='1622530'>it's</span> <span m='1622620'>still</span> <span m='1622770'>going</span>
  <span m='1622890'>to</span> <span m='1622950'>be</span> <span m='1623010'>really</span>
  <span m='1623400'>expensive</span> <span m='1623800'>to</span> <span m='1623900'>compute</span>
  <span m='1624110'>it.</span> <span m='1624670'>So</span> <span m='1624750'>it's</span>
  <span m='1625230'>a</span> <span m='1625290'>lot</span> <span m='1625470'>more</span>
  <span m='1625650'>effort</span> <span m='1626400'>to</span> <span m='1626520'>do</span>
  <span m='1626730'>it.</span> </p><p><span m='1626980'>So you</span> <span m='1627100'>need
  to</span> <span m='1627180'>think,</span> <span m='1627330'>well,</span> <span m='1627480'>is</span>
  <span m='1627600'>it</span> <span m='1627660'>really</span> <span m='1627870'>worth</span>
  <span m='1628170'>it?</span> <span m='1628750'>And</span> <span m='1628850'>so</span>
  <span m='1628920'>people</span> <span m='1629130'>have</span> <span m='1629220'>found</span>
  <span m='1629520'>other</span> <span m='1629730'>formulas</span> <span m='1630780'>that</span>
  <span m='1631050'>basically</span> <span m='1631410'>get</span> <span m='1631560'>rid</span>
  <span m='1631710'>of</span> <span m='1631830'>the</span> <span m='1631920'>delta</span>
  <span m='1632160'>t squared</span> <span m='1632550'>term</span> <span m='1633390'>that</span>
  <span m='1633510'>don't</span> <span m='1633690'>require</span> <span m='1633930'>so</span>
  <span m='1634050'>much</span> <span m='1634200'>effort,</span> <span m='1634800'>and</span>
  <span m='1634890'>so</span> <span m='1635200'>that's</span> <span m='1635710'>what</span>
  <span m='1635800'>people</span> <span m='1636000'>do</span> <span m='1636120'>instead.</span>
  <span m='1637370'>But</span> <span m='1637410'>this</span> <span m='1637560'>is</span>
  <span m='1637680'>an</span> <span m='1637770'>option.</span> <span m='1638140'>You</span>
  <span m='1638240'>could</span> <span m='1638340'>do</span> <span m='1638380'>it.</span>
  </p><p><span m='1645580'>All</span> <span m='1645640'>right,</span> <span m='1646570'>so</span>
  <span m='1646900'>instead,</span> <span m='1647260'>what</span> <span m='1647350'>people</span>
  <span m='1647620'>do</span> <span m='1648580'>is</span> <span m='1648730'>they've</span>
  <span m='1648820'>decided</span> <span m='1649210'>to</span> <span m='1649360'>generalize</span>
  <span m='1650350'>the</span> <span m='1650560'>midpoint</span> <span m='1651670'>rule</span>
  <span m='1652810'>and</span> <span m='1652990'>try</span> <span m='1653350'>to</span>
  <span m='1654040'>figure</span> <span m='1654310'>out,</span> <span m='1654530'>how</span>
  <span m='1654610'>can</span> <span m='1654700'>we</span> <span m='1654790'>get</span>
  <span m='1654910'>an</span> <span m='1655000'>estimate</span> <span m='1655390'>of</span>
  <span m='1655450'>the</span> <span m='1655540'>midpoint</span> <span m='1656830'>value</span>
  <span m='1657370'>that's</span> <span m='1657610'>cheap</span> <span m='1657820'>to</span>
  <span m='1657940'>evaluate?</span> <span m='1659380'>And</span> <span m='1659680'>so</span>
  <span m='1659830'>what</span> <span m='1659950'>they</span> <span m='1660040'>say</span>
  <span m='1660340'>is,</span> <span m='1660520'>well,</span> <span m='1660790'>this</span>
  <span m='1660970'>is</span> <span m='1661060'>g</span> <span m='1661460'>midpoint</span>
  <span m='1661960'>for</span> <span m='1662800'>numerical</span> <span m='1663160'>integration.</span>
  <span m='1664360'>Let's</span> <span m='1664540'>make</span> <span m='1664690'>an</span>
  <span m='1664810'>new g</span> <span m='1665230'>midpoint</span> <span m='1665500'>that</span>
  <span m='1665620'>works</span> <span m='1665980'>for</span> <span m='1666340'>when</span>
  <span m='1666660'>f is</span> <span m='1666810'>a function of</span> <span m='1667180'>y.</span>
  <span m='1668480'>So</span> <span m='1668500'>let's</span> <span m='1668680'>make</span>
  <span m='1668860'>it</span> <span m='1668950'>function</span> <span m='1670741'>of</span>
  <span m='1671150'>y</span> <span m='1672050'>evaluated</span> <span m='1672700'>at</span>
  <span m='1672820'>t</span> <span m='1673120'>plus</span> <span m='1673300'>delta</span>
  <span m='1673530'>t</span> <span m='1673620'>over</span> <span m='1673780'>2.</span>
  </p><p><span m='1679860'>So</span> <span m='1680170'>that's</span> <span m='1680370'>what</span>
  <span m='1680470'>the</span> <span m='1680560'>formula</span> <span m='1680770'>looks</span>
  <span m='1680950'>like.</span> <span m='1681370'>But</span> <span m='1681460'>then</span>
  <span m='1681610'>you</span> <span m='1681680'>say,</span> <span m='1681910'>well,</span>
  <span m='1682030'>I</span> <span m='1682070'>don't</span> <span m='1682170'>know</span>
  <span m='1682390'>y</span> <span m='1682660'>is</span> <span m='1682780'>at</span>
  <span m='1682900'>t</span> <span m='1683170'>plus</span> <span m='1683330'>delta</span>
  <span m='1683460'>t</span> <span m='1683590'>over</span> <span m='1683810'>2,</span>
  <span m='1685000'>because</span> <span m='1685210'>I</span> <span m='1685330'>only</span>
  <span m='1685510'>know</span> <span m='1685690'>it at</span> <span m='1686020'>y</span>
  <span m='1686260'>of</span> <span m='1686320'>t.</span> <span m='1687360'>So</span>
  <span m='1687830'>then</span> <span m='1688020'>they</span> <span m='1688120'>say,</span>
  <span m='1688330'>well,</span> <span m='1688480'>let's</span> <span m='1688610'>do</span>
  <span m='1688750'>Forward</span> <span m='1689250'>Euler</span> <span m='1689400'>for
  that.</span> <span m='1690140'>So</span> <span m='1690630'>then</span> <span m='1690830'>they</span>
  <span m='1690940'>say,</span> <span m='1691330'>well,</span> <span m='1691750'>let's</span>
  <span m='1691900'>say</span> <span m='1692170'>it's</span> <span m='1692290'>approximately</span>
  <span m='1694030'>f</span> <span m='1694410'>of--</span> <span m='1698580'>what's</span>
  <span m='1698820'>the</span> <span m='1699130'>Forward</span> <span m='1699500'>Euler</span>
  <span m='1699750'>formula?</span> </p><p><span m='1700380'>It's</span> <span m='1702330'>y</span>
  <span m='1702660'>of t</span> <span m='1703935'>plus</span> <span m='1704360'>delta</span>
  <span m='1704720'>t</span> <span m='1704860'>over</span> <span m='1705050'>2</span>
  <span m='1707260'>times</span> <span m='1707550'>f of</span> <span m='1707700'>y</span>
  <span m='1707990'>of t.</span> <span m='1711154'>How</span> <span m='1711606'>many</span>
  <span m='1712060'>parenthesis</span> <span m='1712520'>there?</span> <span m='1718410'>So</span>
  <span m='1721340'>this</span> <span m='1721550'>is</span> <span m='1721880'>the</span>
  <span m='1722320'>formula</span> <span m='1722610'>that's</span> <span m='1723410'>actually</span>
  <span m='1723680'>used</span> <span m='1723920'>in</span> <span m='1724010'>practice</span>
  <span m='1724340'>a</span> <span m='1724370'>lot.</span> <span m='1725360'>And</span>
  <span m='1725570'>this</span> <span m='1725720'>one</span> <span m='1725870'>is</span>
  <span m='1725990'>called</span> <span m='1726770'>Runge-Kutta</span> <span m='1727130'>two,</span>
  <span m='1727640'>second</span> <span m='1727910'>order</span> <span m='1728120'>Runge-Kutta</span>
  <span m='1728710'>formula.</span> <span m='1730030'>And</span> <span m='1730150'>it's</span>
  <span m='1730270'>just</span> <span m='1730540'>a--</span> <span m='1732080'>it's</span>
  <span m='1732280'>the</span> <span m='1732370'>midpoint</span> <span m='1732730'>rule</span>
  <span m='1733870'>where</span> <span m='1734110'>we</span> <span m='1734320'>estimate</span>
  <span m='1734770'>the</span> <span m='1734890'>value</span> <span m='1735340'>of</span>
  <span m='1736000'>y</span> <span m='1736280'>of t</span> <span m='1736400'>plus</span>
  <span m='1736740'>delta t</span> <span m='1737030'>using</span> <span m='1737350'>Forward</span>
  <span m='1737850'>Euler.</span> </p><p><span m='1739380'>And</span> <span m='1739750'>the
  advantage of</span> <span m='1740080'>this</span> <span m='1740230'>is</span> <span
  m='1740650'>it's</span> <span m='1740710'>very</span> <span m='1740880'>cheap,</span>
  <span m='1741130'>right?</span> <span m='1741240'>Just</span> <span m='1741470'>evaluate--</span>
  <span m='1742740'>I just</span> <span m='1743120'>have to</span> <span m='1743320'>evaluate</span>
  <span m='1744820'>one</span> <span m='1745000'>function</span> <span m='1745330'>here,</span>
  <span m='1745570'>one</span> <span m='1745810'>function</span> <span m='1745910'>here,</span>
  <span m='1746050'>so</span> <span m='1746110'>two</span> <span m='1746230'>function</span>
  <span m='1746530'>calls.</span> <span m='1750269'>[INAUDIBLE]</span> <span m='1753290'>and</span>
  <span m='1753490'>that</span> <span m='1753610'>way</span> <span m='1753730'>I can</span>
  <span m='1753790'>get</span> <span m='1753940'>an</span> <span m='1754000'>update</span>
  <span m='1754210'>formula.</span> <span m='1756860'>And</span> <span m='1757010'>this</span>
  <span m='1757160'>one,</span> <span m='1757790'>turns</span> <span m='1758030'>out</span>
  <span m='1758180'>that</span> <span m='1758270'>it</span> <span m='1758390'>has</span>
  <span m='1758640'>the</span> <span m='1758720'>nice</span> <span m='1759380'>delta
  t</span> <span m='1759810'>scaling</span> <span m='1760505'>that</span> <span m='1760830'>you</span>
  <span m='1760940'>might</span> <span m='1761090'>like.</span> </p><p><span m='1764640'>So</span>
  <span m='1765320'>that's</span> <span m='1765500'>the</span> <span m='1765560'>kind</span>
  <span m='1765680'>of</span> <span m='1765740'>thing</span> <span m='1765890'>people</span>
  <span m='1766100'>do.</span> <span m='1767950'>And</span> <span m='1768310'>the</span>
  <span m='1768400'>Runge-Kutta</span> <span m='1768895'>guys</span> <span m='1769150'>went</span>
  <span m='1769280'>crazy,</span> <span m='1770600'>and</span> <span m='1770830'>so</span>
  <span m='1771970'>one</span> <span m='1772190'>of</span> <span m='1772260'>the</span>
  <span m='1772330'>most</span> <span m='1772480'>popular</span> <span m='1772870'>solvers</span>
  <span m='1773260'>is</span> <span m='1773350'>called</span> <span m='1773560'>Runge-Kutta</span>
  <span m='1774080'>four</span> <span m='1774400'>five,</span> <span m='1775510'>and</span>
  <span m='1775690'>that's</span> <span m='1775930'>the</span> <span m='1776080'>ODE</span>
  <span m='1776410'>four</span> <span m='1776660'>five</span> <span m='1776920'>program</span>
  <span m='1777580'>in</span> <span m='1777700'>Matlab.</span> <span m='1778690'>And</span>
  <span m='1778780'>what</span> <span m='1778930'>that</span> <span m='1779050'>does</span>
  <span m='1779290'>is</span> <span m='1779360'>the</span> <span m='1779440'>fourth</span>
  <span m='1779740'>order</span> <span m='1780010'>extension</span> <span m='1780430'>of</span>
  <span m='1780490'>this,</span> <span m='1781330'>and</span> <span m='1781450'>the</span>
  <span m='1781510'>fifth</span> <span m='1781710'>order</span> <span m='1781900'>extension</span>
  <span m='1782200'>of</span> <span m='1782260'>this.</span> </p><p><span m='1782840'>And
  it</span> <span m='1782990'>uses</span> <span m='1783310'>them both,</span> <span
  m='1783700'>and</span> <span m='1783790'>it</span> <span m='1783850'>compares</span>
  <span m='1784270'>them,</span> <span m='1785050'>and</span> <span m='1785140'>uses</span>
  <span m='1785420'>the</span> <span m='1785500'>difference</span> <span m='1785800'>between</span>
  <span m='1786040'>an</span> <span m='1786190'>estimate</span> <span m='1786580'>the</span>
  <span m='1786730'>error</span> <span m='1787900'>in</span> <span m='1788050'>the</span>
  <span m='1788170'>calculation.</span> <span m='1788860'>And</span> <span m='1789010'>then</span>
  <span m='1790270'>uses</span> <span m='1790480'>that</span> <span m='1790660'>to</span>
  <span m='1790750'>decide</span> <span m='1791140'>what</span> <span m='1791720'>size</span>
  <span m='1791950'>delta t</span> <span m='1792340'>you</span> <span m='1792400'>need,</span>
  <span m='1792980'>depending</span> <span m='1793150'>on</span> <span m='1793240'>what</span>
  <span m='1793360'>tolerances</span> <span m='1793840'>you</span> <span m='1793930'>demand.</span>
  <span m='1798016'>And</span> <span m='1798490'>the</span> <span m='1798580'>formulas</span>
  <span m='1798970'>for</span> <span m='1799060'>all</span> <span m='1799210'>those--</span>
  <span m='1799710'>[INAUDIBLE]</span> <span m='1800170'>formulas</span> <span m='1800500'>are</span>
  <span m='1800590'>given</span> <span m='1800830'>in</span> <span m='1800890'>the</span>
  <span m='1800960'>textbook.</span> </p><p><span m='1806810'>Now,</span> <span m='1808440'>this</span>
  <span m='1808610'>starts</span> <span m='1809000'>to</span> <span m='1809080'>lead</span>
  <span m='1809310'>the</span> <span m='1809450'>problem.</span> <span m='1809960'>So</span>
  <span m='1810320'>we</span> <span m='1810530'>weren't</span> <span m='1810770'>able</span>
  <span m='1811010'>to</span> <span m='1811100'>actually</span> <span m='1811460'>evaluate</span>
  <span m='1812300'>the</span> <span m='1812390'>true g</span> <span m='1812880'>midpoint,</span>
  <span m='1814230'>which</span> <span m='1814310'>we'd</span> <span m='1814450'>like</span>
  <span m='1814610'>to</span> <span m='1814790'>be</span> <span m='1814970'>here.</span>
  <span m='1815400'>Instead,</span> <span m='1815600'>we</span> <span m='1815690'>have</span>
  <span m='1815780'>to</span> <span m='1815840'>use</span> <span m='1816010'>some</span>
  <span m='1816110'>approximation</span> <span m='1818390'>in</span> <span m='1818510'>order</span>
  <span m='1818690'>to</span> <span m='1818870'>extrapolate</span> <span m='1819440'>forwards</span>
  <span m='1819830'>to</span> <span m='1819950'>the</span> <span m='1820130'>y.</span>
  <span m='1821480'>So</span> <span m='1822410'>this</span> <span m='1822590'>is</span>
  <span m='1822770'>hinting</span> <span m='1823100'>at</span> <span m='1823160'>the</span>
  <span m='1823280'>whole</span> <span m='1823460'>problem.</span> </p><p><span m='1824230'>This</span>
  <span m='1824360'>whole</span> <span m='1824480'>problem</span> <span m='1824900'>is</span>
  <span m='1824990'>actually</span> <span m='1825230'>we're</span> <span m='1825320'>just</span>
  <span m='1825470'>extrapolating.</span> <span m='1826610'>We</span> <span m='1826730'>know</span>
  <span m='1827570'>the</span> <span m='1828140'>true</span> <span m='1828440'>value</span>
  <span m='1828770'>of</span> <span m='1828890'>y</span> <span m='1829250'>only</span>
  <span m='1829610'>at t</span> <span m='1830110'>naught,</span> <span m='1831260'>and</span>
  <span m='1832370'>all</span> <span m='1832580'>the</span> <span m='1832670'>rest</span>
  <span m='1832880'>we're</span> <span m='1833000'>doing</span> <span m='1833960'>is</span>
  <span m='1834170'>extrapolating</span> <span m='1834650'>forwards.</span> <span
  m='1835240'>And</span> <span m='1835330'>we're</span> <span m='1835400'>do</span>
  <span m='1835550'>it</span> <span m='1835670'>over</span> <span m='1835910'>and</span>
  <span m='1836000'>over</span> <span m='1836210'>again,</span> <span m='1836450'>so
  we're</span> <span m='1836530'>going to</span> <span m='1836730'>do it</span> <span
  m='1836850'>for</span> <span m='1836970'>n</span> <span m='1837170'>steps.</span>
  <span m='1837530'>Maybe</span> <span m='1837660'>we'll</span> <span m='1837740'>do</span>
  <span m='1837860'>1,000</span> <span m='1838340'>steps.</span> </p><p><span m='1840570'>So</span>
  <span m='1840860'>you're</span> <span m='1841000'>extrapolating.</span> <span m='1842120'>And</span>
  <span m='1842240'>then</span> <span m='1842330'>based</span> <span m='1842630'>on</span>
  <span m='1842820'>that</span> <span m='1843020'>extrapolation,</span> <span m='1843310'>you</span>
  <span m='1843600'>going</span> <span m='1843810'>to extrapolate</span> <span m='1844040'>again.</span>
  <span m='1844760'>And</span> <span m='1844850'>then</span> <span m='1844940'>based</span>
  <span m='1845200'>on</span> <span m='1845270'>extrapolation,</span> <span m='1845810'>you</span>
  <span m='1845870'>going to</span> <span m='1845990'>extrapolate</span> <span m='1846380'>again.</span>
  <span m='1847610'>And</span> <span m='1847790'>you</span> <span m='1847850'>can</span>
  <span m='1847970'>see</span> <span m='1848060'>that</span> <span m='1848180'>this</span>
  <span m='1848330'>is</span> <span m='1848450'>not</span> <span m='1848600'>really</span>
  <span m='1849710'>the</span> <span m='1849800'>most</span> <span m='1849980'>robust</span>
  <span m='1850370'>thing</span> <span m='1850520'>to</span> <span m='1850610'>do,</span>
  <span m='1851870'>right?</span> </p><p><span m='1852050'>Because</span> <span m='1852230'>if</span>
  <span m='1852650'>you</span> <span m='1853430'>have</span> <span m='1853550'>any</span>
  <span m='1853640'>experience,</span> <span m='1854090'>you're</span> <span m='1854570'>not</span>
  <span m='1854690'>that</span> <span m='1855080'>comfortable</span> <span m='1855560'>extrapolating</span>
  <span m='1856060'>at</span> <span m='1856160'>all.</span> <span m='1857480'>And</span>
  <span m='1857630'>then</span> <span m='1857770'>you</span> <span m='1857840'>have</span>
  <span m='1857930'>to</span> <span m='1857990'>extrapolate</span> <span m='1858770'>1,000</span>
  <span m='1859100'>times.</span> <span m='1860350'>You</span> <span m='1860650'>should</span>
  <span m='1860810'>be</span> <span m='1860950'>a</span> <span m='1860990'>little</span>
  <span m='1861090'>bit</span> <span m='1861200'>worried</span> <span m='1861560'>about</span>
  <span m='1861710'>what</span> <span m='1861800'>can</span> <span m='1861890'>happen.</span>
  </p><p><span m='1863220'>So</span> <span m='1863240'>let's</span> <span m='1863450'>think</span>
  <span m='1863630'>about</span> <span m='1863810'>how</span> <span m='1863930'>the</span>
  <span m='1864080'>error</span> <span m='1864330'>will</span> <span m='1864500'>propagate.</span>
  <span m='1865500'>So</span> <span m='1865550'>we're</span> <span m='1865670'>going</span>
  <span m='1865790'>to</span> <span m='1865850'>have</span> <span m='1865970'>some</span>
  <span m='1866110'>errors</span> <span m='1868830'>while</span> <span m='1869050'>we</span>
  <span m='1869180'>do</span> <span m='1869300'>these</span> <span m='1869390'>extrapolations.</span>
  <span m='1878780'>So</span> <span m='1880190'>we</span> <span m='1880280'>have</span>
  <span m='1880580'>here</span> <span m='1880870'>a t</span> <span m='1881120'>naught,</span>
  <span m='1881380'>t</span> <span m='1881590'>naught,</span> <span m='1882740'>we're</span>
  <span m='1882860'>happy.</span> <span m='1883520'>We</span> <span m='1883610'>know</span>
  <span m='1883790'>y</span> <span m='1883970'>naught.</span> <span m='1884810'>This</span>
  <span m='1884930'>is</span> <span m='1885540'>exact.</span> <span m='1886110'>We're</span>
  <span m='1886530'>like</span> <span m='1886950'>woohoo.</span> <span m='1887570'>We</span>
  <span m='1887700'>know</span> <span m='1887900'>one</span> <span m='1888090'>value</span>
  <span m='1888370'>of y,</span> <span m='1888620'>really</span> <span m='1888830'>good.</span>
  </p><p><span m='1889940'>All</span> <span m='1890000'>right,</span> <span m='1890150'>so</span>
  <span m='1890270'>now</span> <span m='1890420'>the</span> <span m='1890480'>question</span>
  <span m='1890660'>is</span> <span m='1890860'>the</span> <span m='1892760'>first</span>
  <span m='1893060'>step.</span> <span m='1894716'>Now</span> <span m='1895140'>we're</span>
  <span m='1895250'>going</span> <span m='1895370'>to</span> <span m='1895430'>get</span>
  <span m='1895520'>to</span> <span m='1895580'>value</span> <span m='1895970'>y1</span>
  <span m='1896360'>that</span> <span m='1896450'>we</span> <span m='1896540'>compute</span>
  <span m='1896810'>with</span> <span m='1896960'>one</span> <span m='1897050'>of</span>
  <span m='1897370'>the</span> <span m='1897500'>formulas,</span> <span m='1898630'>and</span>
  <span m='1898830'>it's</span> <span m='1898970'>going</span> <span m='1899090'>to</span>
  <span m='1899150'>be</span> <span m='1899270'>good</span> <span m='1899450'>to</span>
  <span m='1899530'>some</span> <span m='1899720'>accuracy</span> <span m='1900260'>depending</span>
  <span m='1900590'>on</span> <span m='1900680'>how</span> <span m='1900830'>good</span>
  <span m='1900980'>or</span> <span m='1901090'>g</span> <span m='1901540'>is,</span>
  <span m='1901805'>our</span> <span m='1902070'>update</span> <span m='1902330'>formula.</span>
  <span m='1903470'>And</span> <span m='1903920'>so it's</span> <span m='1904280'>going
  to</span> <span m='1904470'>have</span> <span m='1904600'>an</span> <span m='1904670'>error.</span>
  </p><p><span m='1907750'>I</span> <span m='1907860'>should</span> <span m='1908010'>comment</span>
  <span m='1908290'>that</span> <span m='1908570'>this</span> <span m='1908760'>y</span>
  <span m='1908940'>naught,</span> <span m='1910290'>although</span> <span m='1910520'>we
  treat</span> <span m='1910660'>it as</span> <span m='1910900'>exact,</span> <span
  m='1911690'>it</span> <span m='1911780'>could</span> <span m='1911890'>have</span>
  <span m='1912030'>an</span> <span m='1912110'>error</span> <span m='1912360'>too.</span>
  <span m='1912980'>But</span> <span m='1913130'>it</span> <span m='1913190'>will</span>
  <span m='1913320'>probably</span> <span m='1913590'>be</span> <span m='1913710'>more</span>
  <span m='1913890'>like</span> <span m='1914160'>a</span> <span m='1914250'>machine</span>
  <span m='1914550'>precision</span> <span m='1914910'>kind</span> <span m='1915060'>of</span>
  <span m='1915130'>error</span> <span m='1916320'>because</span> <span m='1916590'>we</span>
  <span m='1916680'>don't</span> <span m='1916860'>really</span> <span m='1917010'>know</span>
  <span m='1917160'>the</span> <span m='1917220'>initial</span> <span m='1917460'>conditions</span>
  <span m='1917850'>that well.</span> <span m='1918080'>Or</span> <span m='1918300'>might</span>
  <span m='1918450'>be</span> <span m='1918510'>an</span> <span m='1918600'>experimental</span>
  <span m='1919170'>error</span> <span m='1919290'>about</span> <span m='1919500'>how</span>
  <span m='1919630'>well</span> <span m='1919750'>we</span> <span m='1919890'>know</span>
  <span m='1920010'>what</span> <span m='1920100'>the</span> <span m='1920160'>initial</span>
  <span m='1920460'>conditions</span> <span m='1920850'>are.</span> </p><p><span m='1920940'>But
  I'm</span> <span m='1921140'>not going</span> <span m='1921270'>to</span> <span
  m='1921330'>worry</span> <span m='1921450'>about</span> <span m='1921600'>that one</span>
  <span m='1921760'>for now.</span> <span m='1922590'>But</span> <span m='1922720'>be</span>
  <span m='1923120'>aware,</span> <span m='1923450'>this</span> <span m='1923690'>is</span>
  <span m='1923880'>true,</span> <span m='1924240'>we</span> <span m='1924330'>don't</span>
  <span m='1924450'>really</span> <span m='1924600'>know</span> <span m='1924750'>initial</span>
  <span m='1924870'>conditions</span> <span m='1925350'>perfectly</span> <span m='1925620'>either.</span>
  <span m='1927700'>But</span> <span m='1927820'>certainly,</span> <span m='1928270'>even
  if</span> <span m='1928390'>we</span> <span m='1928510'>treat</span> <span m='1928730'>this</span>
  <span m='1928870'>as</span> <span m='1929020'>being</span> <span m='1929230'>known</span>
  <span m='1929440'>perfectly,</span> <span m='1931150'>we're</span> <span m='1931310'>going</span>
  <span m='1931540'>to</span> <span m='1931600'>have</span> <span m='1931690'>some</span>
  <span m='1931840'>error</span> <span m='1932260'>by</span> <span m='1932350'>the</span>
  <span m='1932440'>time</span> <span m='1932650'>we</span> <span m='1932710'>extrapolate</span>
  <span m='1933450'>to</span> <span m='1933630'>y1.</span> </p><p><span m='1935660'>So</span>
  <span m='1935960'>now</span> <span m='1936140'>what</span> <span m='1936260'>happens</span>
  <span m='1936670'>at</span> <span m='1936970'>y2?</span> <span m='1937660'>So</span>
  <span m='1937860'>now</span> <span m='1938000'>we've</span> <span m='1938610'>added</span>
  <span m='1938840'>some</span> <span m='1939070'>more,</span> <span m='1939400'>so
  now</span> <span m='1939510'>we're at</span> <span m='1939590'>t2.</span> <span
  m='1941780'>And</span> <span m='1943230'>we</span> <span m='1943440'>see</span>
  <span m='1943580'>started</span> <span m='1943910'>from</span> <span m='1945320'>y1</span>
  <span m='1945970'>true</span> <span m='1947820'>plus</span> <span m='1948080'>some
  error.</span> <span m='1948350'>This is</span> <span m='1948440'>y--</span> <span
  m='1948935'>y</span> <span m='1949250'>naught</span> <span m='1949430'>was</span>
  <span m='1949580'>true.</span> <span m='1952600'>Now</span> <span m='1952880'>we're</span>
  <span m='1952970'>starting</span> <span m='1953240'>from</span> <span m='1953390'>y1</span>
  <span m='1954080'>true</span> <span m='1954335'>with</span> <span m='1954590'>some
  error</span> <span m='1955040'>in</span> <span m='1955160'>it,</span> <span m='1955520'>because</span>
  <span m='1955820'>of</span> <span m='1955880'>a</span> <span m='1956210'>mistake</span>
  <span m='1956530'>we</span> <span m='1956640'>made</span> <span m='1956840'>the</span>
  <span m='1956930'>first</span> <span m='1957170'>step.</span> <span m='1958290'>And</span>
  <span m='1958310'>now</span> <span m='1958400'>we</span> <span m='1958490'>see</span>
  <span m='1958670'>how</span> <span m='1958790'>that</span> <span m='1958940'>step</span>
  <span m='1959420'>propagates</span> <span m='1959940'>further.</span> </p><p><span
  m='1962240'>So</span> <span m='1963782'>let's</span> <span m='1964270'>see</span>
  <span m='1964430'>what</span> <span m='1964550'>that's</span> <span m='1964760'>going</span>
  <span m='1964880'>to</span> <span m='1964940'>say.</span> <span m='1965170'>Well</span>
  <span m='1965330'>say</span> <span m='1965540'>y2</span> <span m='1966100'>is</span>
  <span m='1966190'>going</span> <span m='1966310'>to</span> <span m='1966380'>equal</span>
  <span m='1968290'>y1</span> <span m='1970820'>plus</span> <span m='1971460'>delta</span>
  <span m='1971630'>t</span> <span m='1972230'>times</span> <span m='1973400'>some</span>
  <span m='1973640'>update</span> <span m='1973850'>formula</span> <span m='1974930'>which</span>
  <span m='1975080'>would</span> <span m='1975170'>depend</span> <span m='1975410'>on</span>
  <span m='1975500'>y1.</span> <span m='1980770'>But</span> <span m='1980890'>y1</span>
  <span m='1981340'>was</span> <span m='1981490'>not</span> <span m='1982030'>true</span>
  <span m='1982300'>anymore,</span> <span m='1983240'>so</span> <span m='1983260'>this</span>
  <span m='1983410'>is</span> <span m='1983530'>actually</span> <span m='1983820'>equal
  to</span> <span m='1984250'>what</span> <span m='1984520'>should</span> <span m='1984730'>have</span>
  <span m='1984820'>been</span> <span m='1984970'>the</span> <span m='1985060'>true</span>
  <span m='1985230'>value</span> <span m='1985510'>of</span> <span m='1985630'>y1</span>
  <span m='1985990'>if</span> <span m='1986110'>we</span> <span m='1986230'>only</span>
  <span m='1986410'>knew</span> <span m='1986500'>what</span> <span m='1986590'>it</span>
  <span m='1986650'>was,</span> <span m='1987430'>but</span> <span m='1987730'>we</span>
  <span m='1987850'>don't</span> <span m='1988000'>know.</span> <span m='1989176'>And</span>
  <span m='1989570'>we have</span> <span m='1990060'>our</span> <span m='1990340'>error</span>
  <span m='1990620'>that</span> <span m='1990730'>we</span> <span m='1990790'>don't</span>
  <span m='1990910'>know</span> <span m='1991060'>exactly</span> <span m='1991390'>how</span>
  <span m='1991480'>big</span> <span m='1991690'>it</span> <span m='1991810'>is</span>
  <span m='1992380'>that</span> <span m='1992740'>we</span> <span m='1993050'>added</span>
  <span m='1993250'>on.</span> <span m='1994600'>And</span> <span m='1994930'>then</span>
  <span m='1995050'>we</span> <span m='1995140'>have</span> <span m='1995290'>another</span>
  <span m='1995500'>term</span> <span m='1996730'>from</span> <span m='1997270'>this</span>
  <span m='1997480'>guy,</span> <span m='1998980'>so</span> <span m='1999190'>it's</span>
  <span m='1999310'>going</span> <span m='1999430'>to</span> <span m='1999490'>be</span>
  <span m='1999670'>delta t</span> <span m='2001860'>times</span> <span m='2002370'>g</span>
  <span m='2004260'>of</span> <span m='2005100'>y1</span> <span m='2005760'>true</span>
  <span m='2007360'>plus</span> <span m='2007830'>delta</span> <span m='2008270'>1.</span>
  </p><p><span m='2011240'>And</span> <span m='2011360'>then</span> <span m='2011570'>we</span>
  <span m='2011690'>know</span> <span m='2011810'>our</span> <span m='2011990'>update</span>
  <span m='2012160'>formula's</span> <span m='2012440'>not</span> <span m='2012590'>right</span>
  <span m='2012770'>anyway,</span> <span m='2014240'>so</span> <span m='2014390'>there's</span>
  <span m='2014540'>actually</span> <span m='2014790'>another</span> <span m='2015290'>error,</span>
  <span m='2016190'>delta</span> <span m='2016400'>2,</span> <span m='2017870'>just</span>
  <span m='2018050'>because</span> <span m='2018440'>of the</span> <span m='2018570'>error
  in the</span> <span m='2018890'>update</span> <span m='2019130'>formula.</span>
  <span m='2025030'>Now</span> <span m='2025962'>if</span> <span m='2026430'>we</span>
  <span m='2026550'>had</span> <span m='2026670'>a</span> <span m='2026730'>great</span>
  <span m='2027270'>update</span> <span m='2027570'>formula,</span> <span m='2028350'>these</span>
  <span m='2028470'>deltas</span> <span m='2028770'>are</span> <span m='2028860'>kind</span>
  <span m='2029010'>of</span> <span m='2029070'>small.</span> <span m='2032240'>And</span>
  <span m='2032400'>if</span> <span m='2032520'>somehow,</span> <span m='2033090'>by</span>
  <span m='2033300'>luck,</span> <span m='2033630'>our</span> <span m='2033720'>delta</span>
  <span m='2035190'>1</span> <span m='2035430'>was</span> <span m='2035520'>0,</span>
  <span m='2038150'>and</span> <span m='2038300'>we</span> <span m='2038360'>had</span>
  <span m='2038450'>a</span> <span m='2038510'>great</span> <span m='2038690'>update</span>
  <span m='2038900'>formula,</span> <span m='2039260'>then</span> <span m='2039410'>we</span>
  <span m='2039500'>think</span> <span m='2039680'>that</span> <span m='2039800'>this</span>
  <span m='2039980'>error</span> <span m='2040240'>in</span> <span m='2040340'>y2</span>
  <span m='2040570'>is</span> <span m='2040700'>going</span> <span m='2040820'>to
  be</span> <span m='2040910'>pretty</span> <span m='2041210'>small.</span> </p><p><span
  m='2044440'>But</span> <span m='2044650'>it's</span> <span m='2044800'>not</span>
  <span m='2044950'>true.</span> <span m='2045920'>So</span> <span m='2046000'>really</span>
  <span m='2046240'>the</span> <span m='2046510'>errors are</span> <span m='2046570'>pretty</span>
  <span m='2046750'>big.</span> <span m='2050880'>So</span> <span m='2052770'>let's</span>
  <span m='2052889'>see</span> <span m='2052980'>if</span> <span m='2053040'>we</span>
  <span m='2053130'>can</span> <span m='2053370'>figure</span> <span m='2053610'>out--</span>
  <span m='2053790'>we're</span> <span m='2054050'>going to</span> <span m='2054350'>do
  a</span> <span m='2054530'>Taylor</span> <span m='2054929'>expansion</span> <span
  m='2055350'>here,</span> <span m='2057010'>so</span> <span m='2057130'>this'll</span>
  <span m='2057429'>be g</span> <span m='2059000'>of</span> <span m='2059210'>y1</span>
  <span m='2059530'>true</span> <span m='2063090'>plus</span> <span m='2063840'>d</span>
  <span m='2065679'>dgy--</span> <span m='2067139'>the</span> <span m='2067409'>Jacobian</span>
  <span m='2067870'>of g</span> <span m='2068110'>with</span> <span m='2068239'>respect</span>
  <span m='2068380'>to</span> <span m='2068489'>y--</span> <span m='2069800'>times</span>
  <span m='2070210'>the delta</span> <span m='2070681'>1.</span> <span m='2073199'>That's</span>
  <span m='2073340'>the</span> <span m='2073400'>first</span> <span m='2073580'>order</span>
  <span m='2073895'>Taylor</span> <span m='2074210'>extension.</span> </p><p><span
  m='2076960'>All</span> <span m='2077020'>right,</span> <span m='2077330'>so now</span>
  <span m='2077440'>let's</span> <span m='2077800'>group</span> <span m='2077980'>the</span>
  <span m='2078100'>terms.</span> <span m='2088679'>So</span> <span m='2090190'>y2</span>
  <span m='2091739'>is</span> <span m='2091889'>equal</span> <span m='2092159'>to</span>
  <span m='2092310'>y1</span> <span m='2092730'>true</span> <span m='2095219'>plus</span>
  <span m='2096360'>the</span> <span m='2096480'>update</span> <span m='2096750'>formula</span>
  <span m='2097960'>of</span> <span m='2098160'>y1</span> <span m='2098580'>true</span>
  <span m='2101130'>plus</span> <span m='2101490'>the</span> <span m='2101640'>error</span>
  <span m='2101925'>in our</span> <span m='2102210'>update</span> <span m='2102690'>formula</span>
  <span m='2103710'>if</span> <span m='2103830'>we</span> <span m='2103910'>had</span>
  <span m='2104040'>started</span> <span m='2106090'>at the</span> <span m='2106534'>true</span>
  <span m='2106978'>value.</span> <span m='2108310'>So</span> <span m='2108330'>this</span>
  <span m='2108510'>is</span> <span m='2108600'>what</span> <span m='2108750'>we--</span>
  <span m='2109780'>if</span> <span m='2110160'>somebody</span> <span m='2110430'>told</span>
  <span m='2110700'>us</span> <span m='2110850'>what</span> <span m='2110930'>the</span>
  <span m='2111020'>true</span> <span m='2111140'>value</span> <span m='2111440'>of</span>
  <span m='2111510'>y1,</span> <span m='2112170'>this</span> <span m='2112320'>is
  the</span> <span m='2112440'>size</span> <span m='2112740'>error</span> <span m='2113040'>we'd</span>
  <span m='2113130'>expect.</span> <span m='2114020'>It's</span> <span m='2114330'>to</span>
  <span m='2114430'>be</span> <span m='2114540'>that</span> <span m='2114650'>little</span>
  <span m='2114900'>error</span> <span m='2115340'>we</span> <span m='2115470'>calculated</span>
  <span m='2115890'>before.</span> </p><p><span m='2117390'>But</span> <span m='2117510'>then</span>
  <span m='2117660'>on</span> <span m='2117750'>top</span> <span m='2118020'>of</span>
  <span m='2118140'>it,</span> <span m='2118350'>we</span> <span m='2118500'>have</span>
  <span m='2119270'>these</span> <span m='2119650'>other</span> <span m='2119880'>terms.</span>
  <span m='2120600'>We</span> <span m='2120930'>have a</span> <span m='2121080'>delta</span>
  <span m='2121380'>1,</span> <span m='2122340'>because</span> <span m='2122550'>y1</span>
  <span m='2122910'>was</span> <span m='2123030'>not</span> <span m='2123270'>the</span>
  <span m='2123360'>true</span> <span m='2123540'>value.</span> <span m='2125490'>Sorry,</span>
  <span m='2125700'>I</span> <span m='2125810'>lost</span> <span m='2126370'>a</span>
  <span m='2126460'>delta t</span> <span m='2126580'>here.</span> <span m='2131490'>And</span>
  <span m='2131610'>then</span> <span m='2131700'>we</span> <span m='2131820'>have</span>
  <span m='2133000'>delta t</span> <span m='2134190'>times</span> <span m='2138100'>dg</span>
  <span m='2140590'>dy</span> <span m='2144120'>times</span> <span m='2144890'>delta</span>
  <span m='2145100'>1.</span> <span m='2146080'>And I'll</span> <span m='2146570'>emphasize</span>
  <span m='2147020'>these</span> <span m='2147170'>are</span> <span m='2147230'>all</span>
  <span m='2147380'>vectors.</span> <span m='2153283'>I</span> <span m='2153780'>think</span>
  <span m='2153880'>that's</span> <span m='2154100'>it</span> <span m='2155710'>if
  we</span> <span m='2155760'>only</span> <span m='2155890'>keep</span> <span m='2156050'>to</span>
  <span m='2156130'>first</span> <span m='2156360'>order.</span> </p><p><span m='2160140'>So</span>
  <span m='2160500'>what</span> <span m='2160650'>is</span> <span m='2160800'>this</span>
  <span m='2161010'>thing?</span> <span m='2161970'>This</span> <span m='2162120'>is</span>
  <span m='2162210'>a</span> <span m='2162270'>matrix,</span> <span m='2162750'>right,</span>
  <span m='2164400'>dg</span> <span m='2164830'>dy.</span> <span m='2166833'>I could</span>
  <span m='2167306'>write</span> <span m='2167780'>it</span> <span m='2168040'>this</span>
  <span m='2168220'>way.</span> <span m='2169600'>It's</span> <span m='2169760'>the</span>
  <span m='2169870'>identity</span> <span m='2170170'>matrix</span> <span m='2171730'>plus</span>
  <span m='2172110'>delta t</span> <span m='2172810'>times</span> <span m='2173290'>the</span>
  <span m='2173410'>Jacobian</span> <span m='2173850'>dg</span> <span m='2173980'>dy</span>
  <span m='2177160'>times</span> <span m='2177580'>the</span> <span m='2177640'>vector</span>
  <span m='2178180'>d1.</span> </p><p><span m='2181990'>And</span> <span m='2182170'>you</span>
  <span m='2182230'>can</span> <span m='2182350'>see,</span> <span m='2182660'>at</span>
  <span m='2182790'>every</span> <span m='2183280'>iteration</span> <span m='2183595'>when</span>
  <span m='2183910'>I</span> <span m='2184000'>do</span> <span m='2184150'>this,</span>
  <span m='2184430'>I'm</span> <span m='2184530'>going</span> <span m='2184630'>to</span>
  <span m='2184730'>get</span> <span m='2184830'>a</span> <span m='2184930'>similar</span>
  <span m='2185020'>factor</span> <span m='2185410'>like</span> <span m='2185530'>this.</span>
  <span m='2187500'>And</span> <span m='2187710'>it's</span> <span m='2187860'>going
  to</span> <span m='2188180'>again</span> <span m='2188650'>multiply</span> <span
  m='2189150'>delta</span> <span m='2189340'>1.</span> <span m='2190820'>I</span>
  <span m='2190900'>keep</span> <span m='2191140'>on</span> <span m='2191230'>multiplying</span>
  <span m='2191490'>the--</span> <span m='2192600'>errors</span> <span m='2192880'>from</span>
  <span m='2192970'>my</span> <span m='2193060'>previous</span> <span m='2193390'>step</span>
  <span m='2193630'>keep</span> <span m='2193760'>getting</span> <span m='2193990'>multiplied</span>
  <span m='2194260'>by</span> <span m='2194530'>this</span> <span m='2194680'>kind
  of</span> <span m='2195000'>factor.</span> </p><p><span m='2197330'>So</span> <span
  m='2197510'>it's</span> <span m='2197600'>going</span> <span m='2197690'>to</span>
  <span m='2197750'>be</span> <span m='2197810'>really</span> <span m='2198110'>important</span>
  <span m='2198470'>to</span> <span m='2198590'>us</span> <span m='2198840'>about</span>
  <span m='2198940'>what</span> <span m='2199070'>the</span> <span m='2199260'>norm</span>
  <span m='2199430'>of</span> <span m='2199550'>this</span> <span m='2199900'>matrix</span>
  <span m='2200220'>is.</span> <span m='2213320'>What's</span> <span m='2213470'>going</span>
  <span m='2213590'>to</span> <span m='2213650'>happen</span> <span m='2213860'>if</span>
  <span m='2213920'>the</span> <span m='2214010'>normal</span> <span m='2214220'>of
  this</span> <span m='2214320'>matrix</span> <span m='2214620'>is big?</span> <span
  m='2218452'>What's going</span> <span m='2218931'>to happen?</span> </p><p><span
  m='2219410'>AUDIENCE:</span> <span m='2219649'>[INAUDIBLE]</span> </p><p><span m='2221810'>WILLIAM
  GREEN JR:</span> <span m='2221885'>That's</span> <span m='2221960'>right,</span>
  <span m='2222200'>the</span> <span m='2222280'>error's</span> <span m='2222500'>going
  to</span> <span m='2222650'>get</span> <span m='2222800'>multiplied</span> <span
  m='2223340'>by</span> <span m='2223550'>some</span> <span m='2223760'>factor,</span>
  <span m='2224210'>say</span> <span m='2224390'>bigger</span> <span m='2224570'>than</span>
  <span m='2224690'>1,</span> <span m='2224900'>every</span> <span m='2225110'>iteration.</span>
  <span m='2226520'>And</span> <span m='2226790'>after</span> <span m='2226970'>we</span>
  <span m='2227090'>go</span> <span m='2227210'>1,000</span> <span m='2227600'>iterations,</span>
  <span m='2227880'>how big</span> <span m='2228160'>is the error</span> <span m='2228400'>going
  to be?</span> <span m='2231770'>Really</span> <span m='2232010'>big,</span> <span
  m='2232230'>right?</span> <span m='2232640'>Even</span> <span m='2232850'>if</span>
  <span m='2232970'>that</span> <span m='2233150'>thing</span> <span m='2233330'>is</span>
  <span m='2233450'>quite</span> <span m='2233660'>close</span> <span m='2233870'>to</span>
  <span m='2233990'>1,</span> <span m='2234700'>1</span> <span m='2234950'>plus</span>
  <span m='2235220'>something</span> <span m='2236060'>to</span> <span m='2236150'>the</span>
  <span m='2236240'>1,000</span> <span m='2236660'>power</span> <span m='2237560'>it's</span>
  <span m='2237710'>gigantic.</span> </p><p><span m='2238760'>So</span> <span m='2239030'>what</span>
  <span m='2239810'>was</span> <span m='2239930'>originally</span> <span m='2240290'>a</span>
  <span m='2240320'>pretty</span> <span m='2240530'>small</span> <span m='2240860'>error--</span>
  <span m='2241010'>because</span> <span m='2241280'>we</span> <span m='2241370'>chose</span>
  <span m='2241610'>a</span> <span m='2241670'>good g</span> <span m='2242000'>method--</span>
  <span m='2242880'>is</span> <span m='2243050'>going</span> <span m='2243170'>to</span>
  <span m='2243230'>get</span> <span m='2243350'>multiplied</span> <span m='2243800'>by</span>
  <span m='2243890'>this</span> <span m='2244040'>huge</span> <span m='2244220'>amplification</span>
  <span m='2244790'>factor.</span> <span m='2246020'>So</span> <span m='2246170'>the</span>
  <span m='2246260'>key</span> <span m='2246560'>thing</span> <span m='2246950'>for</span>
  <span m='2247310'>a</span> <span m='2247340'>method</span> <span m='2247640'>to</span>
  <span m='2247760'>be</span> <span m='2247850'>what</span> <span m='2247970'>is</span>
  <span m='2248060'>called</span> <span m='2248270'>numerically</span> <span m='2248840'>stable</span>
  <span m='2250190'>is</span> <span m='2250430'>that</span> <span m='2250670'>the</span>
  <span m='2250910'>norm</span> <span m='2251180'>of</span> <span m='2251270'>this</span>
  <span m='2251420'>matrix</span> <span m='2251750'>has</span> <span m='2252200'>got</span>
  <span m='2252440'>to</span> <span m='2252500'>be</span> <span m='2252620'>less</span>
  <span m='2252830'>than</span> <span m='2252950'>1.</span> <span m='2255280'>Or</span>
  <span m='2255500'>maybe</span> <span m='2255680'>even</span> <span m='2255920'>equal,</span>
  <span m='2256340'>equals</span> <span m='2256670'>1</span> <span m='2256790'>might
  be</span> <span m='2256910'>OK.</span> <span m='2257700'>If this</span> <span m='2258190'>is</span>
  <span m='2258620'>much</span> <span m='2258830'>bigger</span> <span m='2259040'>than</span>
  <span m='2259190'>1,</span> <span m='2259430'>you're</span> <span m='2259760'>doomed.</span>
  <span m='2260860'>Your</span> <span m='2261160'>numeric</span> <span m='2261490'>order
  is just</span> <span m='2261740'>going</span> <span m='2261860'>to</span> <span
  m='2262430'>blow</span> <span m='2262700'>up</span> <span m='2263390'>from</span>
  <span m='2263600'>step</span> <span m='2263780'>to</span> <span m='2263870'>step</span>
  <span m='2264080'>to</span> <span m='2264170'>step.</span> </p><p><span m='2266390'>And</span>
  <span m='2266570'>what's</span> <span m='2266750'>bad</span> <span m='2266990'>about</span>
  <span m='2267200'>it,</span> <span m='2267290'>is</span> <span m='2267410'>actually</span>
  <span m='2267620'>sometimes</span> <span m='2268010'>you</span> <span m='2268100'>might</span>
  <span m='2268220'>not</span> <span m='2268350'>even</span> <span m='2268440'>be</span>
  <span m='2268610'>aware</span> <span m='2268850'>of</span> <span m='2268910'>this.</span>
  <span m='2270510'>So</span> <span m='2270810'>you'll</span> <span m='2270960'>get</span>
  <span m='2271110'>some</span> <span m='2271260'>solution,</span> <span m='2271950'>because</span>
  <span m='2272150'>it</span> <span m='2272230'>still will</span> <span m='2272490'>calculate</span>
  <span m='2272860'>some</span> <span m='2272960'>numbers</span> <span m='2273270'>for</span>
  <span m='2273400'>the</span> <span m='2273520'>y's</span> <span m='2273860'>at</span>
  <span m='2273930'>each</span> <span m='2274130'>type--</span> <span m='2274490'>y1,</span>
  <span m='2275180'>y2,</span> <span m='2275380'>y3,</span> <span m='2275620'>y4--</span>
  <span m='2277070'>it's</span> <span m='2277190'>just</span> <span m='2277650'>running</span>
  <span m='2278310'>through</span> <span m='2278400'>the</span> <span m='2278490'>calculation.</span>
  <span m='2280740'>But</span> <span m='2281430'>the</span> <span m='2281550'>numbers</span>
  <span m='2281850'>may</span> <span m='2281970'>become</span> <span m='2282480'>increasingly</span>
  <span m='2283200'>meaningless</span> <span m='2284070'>further</span> <span m='2284370'>away</span>
  <span m='2284550'>from</span> <span m='2284700'>the</span> <span m='2284790'>y</span>
  <span m='2285030'>true</span> <span m='2285690'>as</span> <span m='2286330'>time</span>
  <span m='2286510'>goes on,</span> <span m='2287360'>as the</span> <span m='2287500'>steps</span>
  <span m='2287580'>go.</span> </p><p><span m='2294275'>AUDIENCE:</span> <span m='2294517'>[INAUDIBLE]</span>
  </p><p><span m='2300100'>WILLIAM GREEN JR:</span> <span m='2300235'>Yes,</span>
  <span m='2301200'>it</span> <span m='2301350'>can.</span> <span m='2301640'>Yeah,</span>
  <span m='2301900'>so</span> <span m='2302000'>that's</span> <span m='2302150'>what</span>
  <span m='2302240'>we</span> <span m='2302300'>call a</span> <span m='2302510'>stable</span>
  <span m='2302870'>numerical</span> <span m='2303270'>method</span> <span m='2303710'>is</span>
  <span m='2303860'>one</span> <span m='2304010'>that,</span> <span m='2304320'>if</span>
  <span m='2304490'>you</span> <span m='2304580'>make</span> <span m='2304730'>an</span>
  <span m='2304820'>error</span> <span m='2305150'>in an earlier</span> <span m='2305480'>step,</span>
  <span m='2306440'>its</span> <span m='2306920'>impact</span> <span m='2307700'>diminishes</span>
  <span m='2309170'>as</span> <span m='2309320'>the</span> <span m='2309410'>steps</span>
  <span m='2309700'>go</span> <span m='2309870'>on.</span> <span m='2309980'>That's</span>
  <span m='2310100'>what</span> <span m='2310190'>you</span> <span m='2310310'>want.</span>
  <span m='2311880'>You</span> <span m='2311980'>can't</span> <span m='2311990'>always</span>
  <span m='2312170'>achieve</span> <span m='2312410'>this.</span> </p><p><span m='2312580'>But</span>
  <span m='2312680'>if</span> <span m='2312770'>you</span> <span m='2312830'>can,</span>
  <span m='2313700'>that's</span> <span m='2313850'>really</span> <span m='2314000'>great.</span>
  <span m='2315490'>Then</span> <span m='2315770'>that's</span> <span m='2316050'>you
  would call</span> <span m='2316430'>a really</span> <span m='2316640'>stable,</span>
  <span m='2317420'>robust</span> <span m='2317780'>kind</span> <span m='2317930'>of</span>
  <span m='2317990'>method.</span> <span m='2319080'>Even though</span> <span m='2319160'>I
  give</span> <span m='2319280'>you</span> <span m='2319540'>some</span> <span m='2319970'>stupidity</span>
  <span m='2320690'>early</span> <span m='2320960'>on,</span> <span m='2322170'>my</span>
  <span m='2322310'>stupidity</span> <span m='2322800'>evaporates</span> <span m='2323270'>away,</span>
  <span m='2323420'>and</span> <span m='2323510'>it</span> <span m='2323570'>goes</span>
  <span m='2323780'>to the</span> <span m='2323900'>true</span> <span m='2324020'>solution.</span>
  <span m='2325730'>That's</span> <span m='2325940'>what</span> <span m='2326030'>you</span>
  <span m='2326120'>want.</span> </p><p><span m='2328880'>OK,</span> <span m='2329120'>so</span>
  <span m='2329210'>let's</span> <span m='2329360'>think</span> <span m='2329510'>of</span>
  <span m='2329570'>cases</span> <span m='2329900'>where</span> <span m='2330110'>it's</span>
  <span m='2330530'>going</span> <span m='2330680'>to</span> <span m='2330740'>be</span>
  <span m='2330830'>problematic</span> <span m='2331280'>for</span> <span m='2331400'>sure.</span>
  <span m='2332660'>So</span> <span m='2333940'>if</span> <span m='2334100'>dg</span>
  <span m='2334580'>dy--</span> <span m='2336680'>say</span> <span m='2337620'>if</span>
  <span m='2337760'>all</span> <span m='2337930'>it's</span> <span m='2338030'>eigenvalues</span>
  <span m='2338570'>are</span> <span m='2338660'>positive</span> <span m='2340860'>and</span>
  <span m='2340980'>you</span> <span m='2341070'>add</span> <span m='2341410'>it to</span>
  <span m='2342390'>identity</span> <span m='2342510'>matrix,</span> <span m='2343540'>the</span>
  <span m='2343620'>thing</span> <span m='2343790'>is</span> <span m='2343890'>still</span>
  <span m='2344100'>going</span> <span m='2344220'>to</span> <span m='2344280'>have</span>
  <span m='2345760'>eigenvalues</span> <span m='2346170'>bigger</span> <span m='2346380'>than</span>
  <span m='2346500'>1.</span> <span m='2346890'>Can you</span> <span m='2346980'>see</span>
  <span m='2347100'>that?</span> <span m='2349350'>And</span> <span m='2349460'>actually,</span>
  <span m='2349630'>what</span> <span m='2349720'>do</span> <span m='2349840'>we</span>
  <span m='2349960'>say</span> <span m='2350260'>when</span> <span m='2350430'>dg</span>
  <span m='2350580'>dy</span> <span m='2351010'>is</span> <span m='2351130'>positive,</span>
  <span m='2352420'>has</span> <span m='2352600'>a</span> <span m='2352660'>positive</span>
  <span m='2353120'>eigenvalue?</span> <span m='2353440'>You</span> <span m='2353620'>guys</span>
  <span m='2353770'>have</span> <span m='2353890'>a</span> <span m='2353950'>word</span>
  <span m='2354130'>for</span> <span m='2354220'>this</span> <span m='2354340'>already</span>
  <span m='2354600'>you</span> <span m='2354670'>learn</span> <span m='2354780'>in</span>
  <span m='2354880'>your</span> <span m='2355000'>differential</span> <span m='2355330'>equations</span>
  <span m='2355660'>class.</span> <span m='2356060'>What</span> <span m='2356080'>do
  you</span> <span m='2356220'>call these</span> <span m='2356500'>kind</span> <span
  m='2356620'>of</span> <span m='2356680'>differential</span> <span m='2357060'>equations?</span>
  </p><p><span m='2360030'>Maybe</span> <span m='2360080'>not</span> <span m='2360340'>dg</span>
  <span m='2360470'>dy.</span> <span m='2360870'>Back</span> <span m='2361050'>up,</span>
  <span m='2361200'>how</span> <span m='2361350'>about</span> <span m='2361380'>df</span>
  <span m='2361770'>dy?</span> <span m='2362940'>If</span> <span m='2363140'>df</span>
  <span m='2363540'>dy,</span> <span m='2363805'>if that</span> <span m='2364070'>Jacobian</span>
  <span m='2364570'>has</span> <span m='2364890'>a</span> <span m='2365460'>positive</span>
  <span m='2365850'>eigenvalue,</span> <span m='2366270'>what</span> <span m='2366580'>do
  you say?</span> <span m='2374230'>You guys</span> <span m='2374500'>remember this?</span>
  <span m='2375710'>So</span> <span m='2376160'>this is</span> <span m='2376660'>what
  we</span> <span m='2377030'>call</span> <span m='2377270'>unstable</span> <span
  m='2377780'>differential</span> <span m='2378110'>equations.</span> </p><p><span
  m='2379700'>So</span> <span m='2379850'>if</span> <span m='2380060'>it</span> <span
  m='2380630'>has</span> <span m='2380810'>any</span> <span m='2380960'>positive</span>
  <span m='2381380'>eigenvalues,</span> <span m='2382970'>then</span> <span m='2384680'>two</span>
  <span m='2385970'>initial</span> <span m='2386330'>conditions</span> <span m='2387350'>that</span>
  <span m='2387590'>differ</span> <span m='2387890'>by</span> <span m='2388100'>a</span>
  <span m='2388190'>little</span> <span m='2388400'>differential</span> <span m='2389900'>exponentially</span>
  <span m='2390410'>separate</span> <span m='2391700'>as</span> <span m='2391850'>time</span>
  <span m='2392060'>goes</span> <span m='2392270'>on</span> <span m='2393380'>as</span>
  <span m='2393500'>long</span> <span m='2393650'>as</span> <span m='2393770'>the</span>
  <span m='2393830'>difference</span> <span m='2394640'>as</span> <span m='2394820'>any</span>
  <span m='2395000'>projection</span> <span m='2395510'>in</span> <span m='2395630'>the</span>
  <span m='2395690'>direction</span> <span m='2396050'>of</span> <span m='2396170'>the</span>
  <span m='2396900'>bad</span> <span m='2397160'>eigenvector.</span> <span m='2399630'>So</span>
  <span m='2399750'>those</span> <span m='2399890'>are</span> <span m='2399950'>called</span>
  <span m='2400070'>numerically</span> <span m='2400500'>unstable.</span> <span m='2401970'>A</span>
  <span m='2402000'>lot</span> <span m='2402180'>of</span> <span m='2402240'>those</span>
  <span m='2402390'>actually</span> <span m='2402630'>exist</span> <span m='2403190'>in</span>
  <span m='2403320'>reality.</span> </p><p><span m='2404980'>So</span> <span m='2405860'>explosions,</span>
  <span m='2407470'>that's</span> <span m='2407790'>because</span> <span m='2407940'>you</span>
  <span m='2408030'>had</span> <span m='2408150'>some</span> <span m='2408450'>positive</span>
  <span m='2408810'>eigenvalue</span> <span m='2409410'>somewhere</span> <span m='2410740'>for</span>
  <span m='2410760'>example.</span> <span m='2412200'>Amplifiers,</span> <span m='2413160'>like</span>
  <span m='2413310'>you</span> <span m='2413400'>buy</span> <span m='2413580'>an</span>
  <span m='2413640'>amplifier</span> <span m='2414090'>to</span> <span m='2414390'>crank</span>
  <span m='2414630'>up</span> <span m='2414720'>the</span> <span m='2414780'>music,</span>
  <span m='2416080'>you</span> <span m='2416160'>get</span> <span m='2416280'>positive</span>
  <span m='2416550'>feedback</span> <span m='2417010'>when--</span> <span m='2417900'>remember</span>
  <span m='2418310'>Professor</span> <span m='2418650'>Swan</span> <span m='2419390'>walked</span>
  <span m='2419620'>to</span> <span m='2419700'>some</span> <span m='2419850'>strange</span>
  <span m='2420150'>place,</span> <span m='2420360'>and</span> <span m='2420450'>for</span>
  <span m='2420540'>some</span> <span m='2420690'>reason,</span> <span m='2421040'>he</span>
  <span m='2421110'>got</span> <span m='2421230'>the</span> <span m='2421320'>feedback</span>
  <span m='2421680'>from</span> <span m='2421860'>the</span> <span m='2422250'>speakers?</span>
  <span m='2423150'>So</span> <span m='2423330'>he</span> <span m='2423450'>had</span>
  <span m='2423570'>a</span> <span m='2423600'>positive</span> <span m='2423930'>eigenvalue</span>
  <span m='2424400'>going</span> <span m='2424630'>there.</span> <span m='2424800'>A</span>
  <span m='2424840'>little</span> <span m='2425040'>tiny</span> <span m='2425220'>noise</span>
  <span m='2425550'>and</span> <span m='2425640'>his</span> <span m='2425730'>microphone,</span>
  <span m='2425985'>and</span> <span m='2426240'>it</span> <span m='2426590'>amplified</span>
  <span m='2427070'>to a big</span> <span m='2427250'>squeak.</span> </p><p><span
  m='2428700'>So</span> <span m='2429180'>there</span> <span m='2429300'>are</span>
  <span m='2429420'>real</span> <span m='2429570'>systems</span> <span m='2429870'>like</span>
  <span m='2429990'>this</span> <span m='2430340'>that</span> <span m='2430660'>amplify.</span>
  <span m='2431790'>And</span> <span m='2431910'>sometimes</span> <span m='2432240'>we</span>
  <span m='2432330'>want</span> <span m='2432450'>to</span> <span m='2432510'>model</span>
  <span m='2432800'>them,</span> <span m='2433440'>like</span> <span m='2433560'>explosions</span>
  <span m='2434070'>for</span> <span m='2434140'>examples.</span> <span m='2434540'>That's
  a pretty</span> <span m='2434830'>important</span> <span m='2435270'>for</span>
  <span m='2435360'>chemical</span> <span m='2435630'>engineers.</span> </p><p><span
  m='2437820'>But</span> <span m='2438420'>it's</span> <span m='2438540'>going</span>
  <span m='2438660'>to</span> <span m='2438720'>be</span> <span m='2438780'>really</span>
  <span m='2438960'>tough,</span> <span m='2439890'>because</span> <span m='2440920'>if</span>
  <span m='2441230'>it's</span> <span m='2441810'>got</span> <span m='2442050'>positive</span>
  <span m='2442650'>eigenvalues,</span> <span m='2444180'>then</span> <span m='2444330'>this</span>
  <span m='2444480'>is</span> <span m='2444600'>probably</span> <span m='2444920'>going</span>
  <span m='2444990'>to</span> <span m='2445080'>have</span> <span m='2445170'>a</span>
  <span m='2445220'>norm</span> <span m='2445470'>bigger</span> <span m='2445600'>than</span>
  <span m='2445770'>1.</span> <span m='2446850'>And</span> <span m='2447060'>then</span>
  <span m='2447360'>whatever</span> <span m='2447720'>little</span> <span m='2447900'>errors</span>
  <span m='2448230'>we</span> <span m='2448320'>may get</span> <span m='2448710'>any</span>
  <span m='2448890'>step</span> <span m='2449190'>in</span> <span m='2449280'>the</span>
  <span m='2449340'>whole</span> <span m='2449460'>calculation,</span> <span m='2449990'>we're</span>
  <span m='2450060'>going</span> <span m='2450180'>to</span> <span m='2450270'>amplify</span>
  <span m='2450500'>and</span> <span m='2450730'>amplify</span> <span m='2450880'>and</span>
  <span m='2451160'>amplify.</span> <span m='2452370'>And</span> <span m='2452550'>who</span>
  <span m='2452670'>knows</span> <span m='2453210'>if</span> <span m='2453310'>we're</span>
  <span m='2453360'>going</span> <span m='2453480'>to</span> <span m='2453540'>have</span>
  <span m='2453630'>any</span> <span m='2454200'>reality</span> <span m='2454620'>left</span>
  <span m='2455120'>in</span> <span m='2455340'>our</span> <span m='2455400'>solution</span>
  <span m='2456300'>by</span> <span m='2456360'>the</span> <span m='2456420'>time</span>
  <span m='2456600'>we</span> <span m='2456660'>get</span> <span m='2456780'>to</span>
  <span m='2456840'>the</span> <span m='2456990'>end.</span> </p><p><span m='2462850'>All</span>
  <span m='2462910'>right,</span> <span m='2463060'>so</span> <span m='2463150'>that's</span>
  <span m='2463600'>one</span> <span m='2463750'>kind</span> <span m='2463900'>of</span>
  <span m='2463960'>problem.</span> <span m='2469520'>So</span> <span m='2470190'>how</span>
  <span m='2470370'>about</span> <span m='2470500'>we</span> <span m='2470620'>have</span>
  <span m='2471780'>a</span> <span m='2471910'>problem</span> <span m='2472330'>that's</span>
  <span m='2472990'>intrinsically</span> <span m='2473530'>stable.</span> <span m='2473980'>That</span>
  <span m='2474100'>means</span> <span m='2474370'>that</span> <span m='2475060'>all</span>
  <span m='2475270'>the</span> <span m='2475420'>eigenvalues</span> <span m='2476140'>of</span>
  <span m='2476230'>the</span> <span m='2476320'>Jacobian</span> <span m='2476770'>of</span>
  <span m='2476850'>the</span> <span m='2476920'>original</span> <span m='2477250'>problem</span>
  <span m='2477940'>are</span> <span m='2478030'>negative.</span> <span m='2479320'>So</span>
  <span m='2479530'>the thing</span> <span m='2479710'>should</span> <span m='2479860'>be</span>
  <span m='2479950'>perfectly</span> <span m='2480340'>stable.</span> </p><p><span
  m='2482770'>From</span> <span m='2482920'>whatever</span> <span m='2483190'>initial</span>
  <span m='2483440'>condition</span> <span m='2484030'>they</span> <span m='2484300'>started</span>
  <span m='2484630'>from,</span> <span m='2485530'>the</span> <span m='2485590'>whole</span>
  <span m='2485710'>thing</span> <span m='2485830'>should</span> <span m='2485930'>sort</span>
  <span m='2486190'>of</span> <span m='2486250'>come</span> <span m='2486520'>down</span>
  <span m='2486920'>to</span> <span m='2487040'>like</span> <span m='2487150'>an</span>
  <span m='2487240'>equilibrium</span> <span m='2487630'>point.</span> <span m='2488300'>So</span>
  <span m='2488320'>that's</span> <span m='2488500'>a</span> <span m='2488560'>pretty</span>
  <span m='2488740'>common</span> <span m='2488980'>situation</span> <span m='2489340'>in</span>
  <span m='2489400'>chemical</span> <span m='2489670'>engineering</span> <span m='2489970'>too.</span>
  <span m='2490130'>You</span> <span m='2490290'>start</span> <span m='2490510'>from</span>
  <span m='2490690'>some</span> <span m='2491870'>state,</span> <span m='2492400'>and</span>
  <span m='2492550'>it</span> <span m='2493360'>relaxes</span> <span m='2494080'>down</span>
  <span m='2494410'>to</span> <span m='2494610'>like</span> <span m='2494740'>an</span>
  <span m='2494830'>equilibrium</span> <span m='2495250'>state</span> <span m='2495550'>or</span>
  <span m='2495620'>a</span> <span m='2495640'>steady</span> <span m='2495910'>state.</span>
  <span m='2497040'>Well-behaved</span> <span m='2497460'>systems</span> <span m='2497860'>act</span>
  <span m='2498040'>like</span> <span m='2498160'>that.</span> </p><p><span m='2499490'>So</span>
  <span m='2501586'>what</span> <span m='2501990'>I'm</span> <span m='2502140'>going</span>
  <span m='2502260'>to</span> <span m='2502320'>show</span> <span m='2502530'>you</span>
  <span m='2502680'>is</span> <span m='2502830'>that,</span> <span m='2504180'>despite</span>
  <span m='2504540'>the</span> <span m='2504630'>fact</span> <span m='2504870'>that</span>
  <span m='2505020'>the</span> <span m='2505350'>df</span> <span m='2505680'>dy</span>
  <span m='2507450'>is</span> <span m='2507570'>well-behaved,</span> <span m='2508470'>it's</span>
  <span m='2508590'>possible</span> <span m='2509160'>that</span> <span m='2509390'>this</span>
  <span m='2510210'>sum</span> <span m='2510540'>matrix</span> <span m='2512070'>might</span>
  <span m='2512250'>still</span> <span m='2512460'>be</span> <span m='2512610'>poorly</span>
  <span m='2512970'>behaved</span> <span m='2514630'>and</span> <span m='2514780'>still</span>
  <span m='2515020'>have</span> <span m='2515170'>a</span> <span m='2515230'>norm
  bigger</span> <span m='2515600'>that</span> <span m='2515740'>one.</span> <span
  m='2517310'>And</span> <span m='2517460'>so</span> <span m='2517670'>that</span>
  <span m='2517760'>means</span> <span m='2517970'>you</span> <span m='2518090'>started</span>
  <span m='2518390'>for</span> <span m='2518540'>a</span> <span m='2518570'>problem</span>
  <span m='2518870'>that</span> <span m='2518960'>was</span> <span m='2519050'>pretty</span>
  <span m='2519290'>well-behaved,</span> <span m='2519920'>and</span> <span m='2520070'>you</span>
  <span m='2520190'>broke</span> <span m='2520490'>it</span> <span m='2521390'>by</span>
  <span m='2521540'>your</span> <span m='2521660'>choice</span> <span m='2521920'>in</span>
  <span m='2521990'>numerical</span> <span m='2522350'>method.</span> <span m='2524030'>So</span>
  <span m='2524270'>this</span> <span m='2524450'>is</span> <span m='2524570'>a</span>
  <span m='2524630'>very</span> <span m='2524870'>bad</span> <span m='2525080'>one.</span>
  <span m='2526550'>This</span> <span m='2526730'>is</span> <span m='2526790'>the</span>
  <span m='2526880'>kind</span> <span m='2527150'>that</span> <span m='2527270'>can</span>
  <span m='2527390'>make you</span> <span m='2527670'>really</span> <span m='2528170'>embarrassed</span>
  <span m='2529370'>if</span> <span m='2529580'>you're</span> <span m='2529820'>working</span>
  <span m='2530150'>in</span> <span m='2530210'>a</span> <span m='2530250'>company.</span>
  </p><p><span m='2531440'>Your</span> <span m='2531560'>boss</span> <span m='2531860'>gives</span>
  <span m='2532040'>you</span> <span m='2532130'>a</span> <span m='2532160'>problem.</span>
  <span m='2533000'>He</span> <span m='2533090'>says,</span> <span m='2533360'>please</span>
  <span m='2533540'>tell</span> <span m='2533720'>me</span> <span m='2533840'>the</span>
  <span m='2533960'>time</span> <span m='2534230'>is</span> <span m='2534290'>going</span>
  <span m='2534410'>to</span> <span m='2534470'>take</span> <span m='2535340'>our</span>
  <span m='2535660'>reactor</span> <span m='2536060'>to</span> <span m='2536150'>relax</span>
  <span m='2536630'>after</span> <span m='2536790'>a</span> <span m='2536810'>start</span>
  <span m='2537080'>up.</span> <span m='2538070'>the</span> <span m='2538430'>system</span>
  <span m='2538790'>is</span> <span m='2538880'>perfectly</span> <span m='2539250'>well-behaved.</span>
  <span m='2539920'>He</span> <span m='2539980'>gives</span> <span m='2540140'>these</span>
  <span m='2540260'>beautiful</span> <span m='2540560'>equations</span> <span m='2541190'>that</span>
  <span m='2541820'>your</span> <span m='2541910'>previous</span> <span m='2542210'>coworker</span>
  <span m='2542720'>worked</span> <span m='2542960'>out.</span> <span m='2543230'>Everything's</span>
  <span m='2543500'>fine.</span> </p><p><span m='2543870'>You</span> <span m='2543950'>put</span>
  <span m='2544100'>it</span> <span m='2544190'>in</span> <span m='2544310'>there.</span>
  <span m='2545000'>You</span> <span m='2545110'>use</span> <span m='2545300'>your</span>
  <span m='2545390'>stupid</span> <span m='2545660'>numerical</span> <span m='2546080'>solver,</span>
  <span m='2546800'>and</span> <span m='2546890'>you</span> <span m='2546980'>get</span>
  <span m='2547070'>a</span> <span m='2547130'>wild</span> <span m='2547430'>oscillation,</span>
  <span m='2548360'>and</span> <span m='2548450'>the</span> <span m='2548510'>thing</span>
  <span m='2548780'>blows</span> <span m='2549080'>up.</span> <span m='2550700'>OK,</span>
  <span m='2550940'>and</span> <span m='2551030'>that's</span> <span m='2551270'>going</span>
  <span m='2551390'>to</span> <span m='2551450'>be</span> <span m='2551780'>because</span>
  <span m='2552560'>of</span> <span m='2552710'>a</span> <span m='2552800'>poor</span>
  <span m='2553080'>choice</span> <span m='2553250'>of</span> <span m='2553340'>g</span>
  <span m='2553610'>so</span> <span m='2553820'>that</span> <span m='2554650'>it</span>
  <span m='2554750'>makes</span> <span m='2555140'>this</span> <span m='2556020'>norm
  of</span> <span m='2556270'>this</span> <span m='2556400'>matrix</span> <span m='2556770'>bigger</span>
  <span m='2557180'>than one.</span> <span m='2559700'>It's</span> <span m='2559940'>pretty</span>
  <span m='2560180'>easy</span> <span m='2560510'>for</span> <span m='2560630'>that</span>
  <span m='2560750'>to</span> <span m='2560840'>happen.</span> <span m='2561360'>So</span>
  <span m='2561380'>you</span> <span m='2561440'>don't</span> <span m='2561560'>need</span>
  <span m='2561680'>a</span> <span m='2561740'>very</span> <span m='2561890'>complicated</span>
  <span m='2562430'>case</span> <span m='2563836'>to show</span> <span m='2564314'>it.</span>
  </p><p><span m='2572930'>So</span> <span m='2573020'>let's</span> <span m='2573230'>just</span>
  <span m='2573410'>do</span> <span m='2573830'>a</span> <span m='2573890'>scalar</span>
  <span m='2574280'>case.</span> <span m='2578150'>Say</span> <span m='2578630'>dy</span>
  <span m='2578840'>dt</span> <span m='2579020'>is equal</span> <span m='2579430'>to</span>
  <span m='2579700'>negative</span> <span m='2580040'>2y.</span> <span m='2582750'>So</span>
  <span m='2582870'>this</span> <span m='2583050'>is</span> <span m='2583140'>a</span>
  <span m='2583260'>well-behaved</span> <span m='2584730'>differential</span> <span
  m='2585080'>equation.</span> <span m='2585370'>What's the</span> <span m='2585620'>solution?</span>
  <span m='2588120'>So</span> <span m='2588330'>with</span> <span m='2588825'>a</span>
  <span m='2589320'>y</span> <span m='2589530'>naught</span> <span m='2591365'>y</span>
  <span m='2591860'>at</span> <span m='2592355'>t equals</span> <span m='2592850'>0</span>
  <span m='2593345'>is equal</span> <span m='2593840'>to 1.</span> <span m='2597800'>What's
  the</span> <span m='2598295'>solution?</span> </p><p><span m='2599780'>AUDIENCE:</span>
  <span m='2600027'>[INAUDIBLE]</span> </p><p><span m='2601770'>WILLIAM GREEN JR:</span>
  <span m='2601855'>Yeah,</span> <span m='2604480'>OK,</span> <span m='2605520'>so</span>
  <span m='2605660'>it's</span> <span m='2605790'>perfectly</span> <span m='2606180'>well-behaved</span>
  <span m='2606510'>function.</span> <span m='2607460'>And</span> <span m='2607735'>the</span>
  <span m='2608010'>plot</span> <span m='2608100'>when you</span> <span m='2608330'>plot</span>
  <span m='2608580'>it,</span> <span m='2610010'>here's</span> <span m='2610110'>one.</span>
  <span m='2611460'>It</span> <span m='2611765'>goes</span> <span m='2612070'>[PLANE
  DIVING NOISE].</span> <span m='2616800'>So now let's</span> <span m='2617220'>solve</span>
  <span m='2617760'>this</span> <span m='2618000'>with</span> <span m='2618210'>the</span>
  <span m='2618270'>Forward</span> <span m='2618540'>Euler</span> <span m='2618810'>method.</span>
  </p><p><span m='2619890'>So</span> <span m='2622324'>I'm going to</span> <span m='2622940'>say</span>
  <span m='2623140'>that</span> <span m='2623310'>y</span> <span m='2623720'>new</span>
  <span m='2625680'>is</span> <span m='2625830'>equal</span> <span m='2626040'>to</span>
  <span m='2626130'>y</span> <span m='2626690'>plus</span> <span m='2627210'>delta
  t</span> <span m='2628493'>times f.</span> <span m='2632570'>So</span> <span m='2632750'>in</span>
  <span m='2632810'>this</span> <span m='2632930'>case,</span> <span m='2633680'>this</span>
  <span m='2633860'>is</span> <span m='2633970'>f,</span> <span m='2635522'>right
  there,</span> <span m='2635986'>negative</span> <span m='2636450'>2y.</span> <span
  m='2638360'>So</span> <span m='2638660'>for</span> <span m='2638950'>Forward</span>
  <span m='2639420'>Euler,</span> <span m='2639780'>this</span> <span m='2639960'>is</span>
  <span m='2640110'>just</span> <span m='2640200'>saying</span> <span m='2640520'>that</span>
  <span m='2640620'>this</span> <span m='2640830'>is</span> <span m='2640950'>negative</span>
  <span m='2641438'>2y.</span> <span m='2645350'>All</span> <span m='2645420'>right,</span>
  <span m='2645660'>so</span> <span m='2646920'>let's</span> <span m='2647150'>choose</span>
  <span m='2647500'>a</span> <span m='2647850'>delta t,</span> <span m='2648700'>say</span>
  <span m='2649080'>delta t equals</span> <span m='2649570'>1</span> <span m='2650040'>to
  start</span> <span m='2650320'>with.</span> </p><p><span m='2652350'>So</span> <span
  m='2654830'>we're</span> <span m='2654950'>going</span> <span m='2655070'>to</span>
  <span m='2655160'>compute.</span> <span m='2656480'>We</span> <span m='2656540'>start
  at</span> <span m='2656870'>t equals</span> <span m='2657200'>0.</span> <span m='2657540'>We're</span>
  <span m='2657710'>computing</span> <span m='2658000'>out to</span> <span m='2658130'>t
  equals</span> <span m='2658550'>1.</span> <span m='2658820'>so we're</span> <span
  m='2659273'>out here.</span> <span m='2661540'>So</span> <span m='2662110'>we</span>
  <span m='2662230'>put</span> <span m='2662380'>1</span> <span m='2662560'>in</span>
  <span m='2662650'>here.</span> <span m='2664400'>Our</span> <span m='2664480'>initial</span>
  <span m='2664780'>condition</span> <span m='2665230'>was</span> <span m='2665770'>y</span>
  <span m='2666040'>was</span> <span m='2666350'>1,</span> <span m='2667030'>so that's</span>
  <span m='2667300'>1.</span> <span m='2668590'>So</span> <span m='2668740'>as</span>
  <span m='2668860'>1</span> <span m='2669490'>times</span> <span m='2669850'>negative</span>
  <span m='2669980'>2</span> <span m='2670150'>times</span> <span m='2670390'>1</span>
  <span m='2670600'>is</span> <span m='2671760'>negative</span> <span m='2672290'>2.</span>
  <span m='2673840'>This</span> <span m='2673990'>is</span> <span m='2674080'>a</span>
  <span m='2674140'>1.</span> <span m='2675410'>1</span> <span m='2675610'>minus</span>
  <span m='2675970'>2</span> <span m='2676210'>is</span> <span m='2677950'>negative</span>
  <span m='2678290'>1.</span> </p><p><span m='2680770'>So</span> <span m='2681550'>at</span>
  <span m='2681640'>the</span> <span m='2681730'>first</span> <span m='2681970'>step,</span>
  <span m='2682360'>it</span> <span m='2682680'>goes</span> <span m='2682980'>from</span>
  <span m='2683080'>here</span> <span m='2683946'>down</span> <span m='2684422'>to
  there.</span> <span m='2689670'>This</span> <span m='2689790'>is</span> <span m='2689880'>not</span>
  <span m='2690000'>looking</span> <span m='2690240'>good.</span> <span m='2694200'>This</span>
  <span m='2694580'>physical</span> <span m='2694940'>variable</span> <span m='2695360'>is
  supposed</span> <span m='2695750'>to be</span> <span m='2696140'>gradually</span>
  <span m='2696500'>relaxing</span> <span m='2696800'>towards</span> <span m='2696960'>0.</span>
  <span m='2697770'>Going</span> <span m='2698060'>negative</span> <span m='2698390'>is</span>
  <span m='2698450'>not</span> <span m='2698630'>what</span> <span m='2698720'>you</span>
  <span m='2698810'>want.</span> <span m='2700580'>And</span> <span m='2700700'>then</span>
  <span m='2700850'>I</span> <span m='2701450'>think</span> <span m='2701570'>we</span>
  <span m='2701660'>could</span> <span m='2701780'>go</span> <span m='2701960'>the</span>
  <span m='2702080'>next</span> <span m='2702260'>step,</span> <span m='2702570'>if</span>
  <span m='2702670'>you</span> <span m='2702770'>want.</span> </p><p><span m='2702990'>So</span>
  <span m='2703070'>we</span> <span m='2703160'>can</span> <span m='2703310'>put</span>
  <span m='2703520'>in</span> <span m='2704390'>suppose</span> <span m='2704750'>y</span>
  <span m='2704990'>is</span> <span m='2705090'>negative</span> <span m='2705440'>1.</span>
  <span m='2707432'>And</span> <span m='2707930'>we're</span> <span m='2708020'>still</span>
  <span m='2708200'>doing</span> <span m='2708380'>a delta t of</span> <span m='2708820'>one</span>
  <span m='2708980'>step.</span> <span m='2709640'>So</span> <span m='2709860'>negative</span>
  <span m='2710120'>1</span> <span m='2710310'>times</span> <span m='2710600'>negative</span>
  <span m='2710870'>2</span> <span m='2711170'>is</span> <span m='2712550'>positive</span>
  <span m='2712910'>2.</span> <span m='2714610'>Plus</span> <span m='2714990'>negative</span>
  <span m='2715290'>1,</span> <span m='2716040'>so</span> <span m='2716160'>this</span>
  <span m='2716340'>goes</span> <span m='2716520'>back</span> <span m='2716790'>to</span>
  <span m='2716880'>the</span> <span m='2716970'>starting</span> <span m='2717240'>point.</span>
  <span m='2718731'>We'll</span> <span m='2719160'>get</span> <span m='2719320'>the</span>
  <span m='2719520'>sawtooth,</span> <span m='2722710'>is</span> <span m='2722900'>what</span>
  <span m='2723010'>you</span> <span m='2723110'>get.</span> </p><p><span m='2725050'>And</span>
  <span m='2725150'>it</span> <span m='2725250'>turns</span> <span m='2725310'>out,</span>
  <span m='2725430'>actually,</span> <span m='2725670'>if</span> <span m='2725730'>you</span>
  <span m='2725820'>make</span> <span m='2726030'>delta</span> <span m='2726270'>t</span>
  <span m='2726390'>any</span> <span m='2726570'>larger</span> <span m='2726900'>than</span>
  <span m='2727090'>1,</span> <span m='2728410'>then</span> <span m='2728930'>this</span>
  <span m='2729060'>sawtooth</span> <span m='2729670'>amplifies,</span> <span m='2730630'>so</span>
  <span m='2730760'>you</span> <span m='2730910'>have</span> <span m='2731330'>a</span>
  <span m='2731580'>oscillating</span> <span m='2731860'>solution</span> <span m='2732260'>that</span>
  <span m='2732350'>explodes.</span> <span m='2734320'>Which</span> <span m='2734470'>is</span>
  <span m='2734530'>a</span> <span m='2734560'>little</span> <span m='2734710'>bit</span>
  <span m='2734800'>different</span> <span m='2735130'>than</span> <span m='2735250'>the</span>
  <span m='2735310'>physical</span> <span m='2735610'>solution,</span> <span m='2737170'>which</span>
  <span m='2737320'>gently</span> <span m='2737620'>relaxes.</span> <span m='2742230'>And</span>
  <span m='2742410'>so</span> <span m='2742680'>this</span> <span m='2742860'>is</span>
  <span m='2742980'>just</span> <span m='2743820'>a</span> <span m='2743910'>scalar</span>
  <span m='2744960'>equation</span> <span m='2746220'>that</span> <span m='2746310'>you</span>
  <span m='2746430'>guys</span> <span m='2746640'>could</span> <span m='2746730'>have</span>
  <span m='2746810'>done</span> <span m='2746930'>in</span> <span m='2746970'>high</span>
  <span m='2747080'>school.</span> <span m='2748260'>If</span> <span m='2748360'>you</span>
  <span m='2748440'>high</span> <span m='2748530'>school</span> <span m='2748680'>math</span>
  <span m='2748860'>teacher</span> <span m='2749240'>had</span> <span m='2749370'>been</span>
  <span m='2749490'>brave,</span> <span m='2749710'>he would</span> <span m='2749880'>have</span>
  <span m='2749960'>showed it</span> <span m='2750140'>you.</span> <span m='2751160'>But</span>
  <span m='2751310'>he</span> <span m='2751380'>don't</span> <span m='2751470'>want</span>
  <span m='2751590'>to</span> <span m='2752360'>ruin</span> <span m='2752700'>your</span>
  <span m='2752820'>faith</span> <span m='2753480'>in</span> <span m='2753730'>the</span>
  <span m='2753970'>Forward</span> <span m='2754390'>Euler</span> <span m='2754720'>method,</span>
  <span m='2755040'>so</span> <span m='2755190'>he</span> <span m='2755250'>just</span>
  <span m='2755520'>showed</span> <span m='2755840'>you</span> <span m='2755960'>a</span>
  <span m='2756120'>simple</span> <span m='2756370'>one</span> <span m='2756660'>that</span>
  <span m='2756760'>worked</span> <span m='2756960'>out.</span> </p><p><span m='2760320'>Now</span>
  <span m='2760490'>you</span> <span m='2760640'>can</span> <span m='2760790'>make</span>
  <span m='2760970'>this</span> <span m='2761390'>work</span> <span m='2761630'>better</span>
  <span m='2761990'>by</span> <span m='2762140'>making</span> <span m='2762380'>the</span>
  <span m='2762470'>delta t</span> <span m='2762890'>smaller.</span> <span m='2764650'>If</span>
  <span m='2764770'>you</span> <span m='2764830'>made</span> <span m='2765010'>the</span>
  <span m='2765080'>delta t</span> <span m='2765610'>small</span> <span m='2765940'>enough--</span>
  <span m='2767950'>in</span> <span m='2768040'>this</span> <span m='2768160'>case,</span>
  <span m='2768430'>I</span> <span m='2768530'>think</span> <span m='2768700'>it's</span>
  <span m='2768820'>delta t</span> <span m='2769140'>is</span> <span m='2769270'>less</span>
  <span m='2769480'>than</span> <span m='2769900'>half--</span> <span m='2771550'>then</span>
  <span m='2771700'>this</span> <span m='2771850'>actually</span> <span m='2772790'>behaves</span>
  <span m='2773100'>somewhat</span> <span m='2773380'>reasonably.</span> <span m='2775250'>And</span>
  <span m='2775400'>so</span> <span m='2776480'>what's</span> <span m='2776690'>going</span>
  <span m='2776870'>on</span> <span m='2777050'>there</span> <span m='2777470'>is</span>
  <span m='2777680'>that</span> <span m='2780280'>the</span> <span m='2780490'>identity</span>
  <span m='2780940'>matrix</span> <span m='2781420'>is</span> <span m='2781730'>positive.</span>
  <span m='2783660'>My</span> <span m='2784370'>Jacobian</span> <span m='2787220'>is</span>
  <span m='2787500'>negative.</span> <span m='2787880'>And if</span> <span m='2788260'>I
  make</span> <span m='2788430'>delta</span> <span m='2788700'>t</span> <span m='2788970'>small</span>
  <span m='2789300'>enough,</span> <span m='2790260'>this</span> <span m='2790440'>big</span>
  <span m='2790770'>positive</span> <span m='2791130'>number is</span> <span m='2791460'>bigger</span>
  <span m='2791760'>than</span> <span m='2791970'>this</span> <span m='2792750'>smaller</span>
  <span m='2793110'>negative</span> <span m='2793440'>number,</span> <span m='2793780'>and</span>
  <span m='2793890'>the</span> <span m='2793950'>whole</span> <span m='2794040'>thing</span>
  <span m='2794230'>stays</span> <span m='2794430'>positive</span> <span m='2794880'>but</span>
  <span m='2795000'>less</span> <span m='2795210'>than</span> <span m='2795330'>1,</span>
  <span m='2796550'>and</span> <span m='2796680'>so</span> <span m='2796820'>then</span>
  <span m='2796950'>the</span> <span m='2797180'>normal</span> <span m='2797450'>is
  good.</span> </p><p><span m='2798910'>But</span> <span m='2799010'>if</span> <span
  m='2799100'>I</span> <span m='2799160'>make</span> <span m='2799360'>delta t</span>
  <span m='2799820'>too</span> <span m='2800060'>large,</span> <span m='2801020'>I</span>
  <span m='2801110'>make</span> <span m='2801320'>this</span> <span m='2802010'>second</span>
  <span m='2802310'>term</span> <span m='2802490'>much</span> <span m='2802700'>larger.</span>
  <span m='2803615'>If it</span> <span m='2803870'>gets</span> <span m='2804200'>much</span>
  <span m='2804380'>larger</span> <span m='2804650'>than</span> <span m='2804830'>1,</span>
  <span m='2805220'>it</span> <span m='2805340'>overwhelms</span> <span m='2805820'>the</span>
  <span m='2805880'>first</span> <span m='2806120'>term.</span> <span m='2806390'>The</span>
  <span m='2806780'>thing's</span> <span m='2807070'>negative,</span> <span m='2808050'>but</span>
  <span m='2808130'>I</span> <span m='2808150'>what</span> <span m='2808190'>do</span>
  <span m='2808310'>the</span> <span m='2808410'>norm</span> <span m='2809490'>it's</span>
  <span m='2809690'>positive.</span> <span m='2811480'>And</span> <span m='2811600'>so</span>
  <span m='2811750'>it</span> <span m='2812290'>has</span> <span m='2812530'>an</span>
  <span m='2812890'>expansion.</span> <span m='2813360'>Then</span> <span m='2813430'>the</span>
  <span m='2813520'>negative</span> <span m='2813850'>is</span> <span m='2814090'>why</span>
  <span m='2814270'>we</span> <span m='2814360'>get</span> <span m='2814480'>these</span>
  <span m='2814630'>oscillations.</span> </p><p><span m='2815870'>So</span> <span
  m='2815970'>if</span> <span m='2816070'>you</span> <span m='2816170'>ever</span>
  <span m='2816270'>do a</span> <span m='2816370'>numerical</span> <span m='2816730'>differential</span>
  <span m='2817060'>equation</span> <span m='2817390'>solution</span> <span m='2818290'>and</span>
  <span m='2818380'>you</span> <span m='2818440'>start</span> <span m='2818680'>seeing</span>
  <span m='2818880'>this</span> <span m='2818980'>kind</span> <span m='2819090'>of</span>
  <span m='2819190'>stuff,</span> <span m='2820330'>it's</span> <span m='2820510'>almost</span>
  <span m='2820780'>certainly</span> <span m='2821080'>related</span> <span m='2821320'>to</span>
  <span m='2821410'>this</span> <span m='2821590'>numerical</span> <span m='2824530'>instability</span>
  <span m='2826090'>of</span> <span m='2826210'>the</span> <span m='2826300'>method.</span>
  <span m='2827590'>and</span> <span m='2828010'>not</span> <span m='2828220'>really</span>
  <span m='2828400'>a</span> <span m='2828430'>physical</span> <span m='2828760'>thing.</span>
  <span m='2829420'>I</span> <span m='2829450'>mean,</span> <span m='2829570'>there
  are</span> <span m='2829690'>physical</span> <span m='2829960'>things</span> <span
  m='2830140'>that</span> <span m='2830230'>do</span> <span m='2830320'>this,</span>
  <span m='2830500'>but</span> <span m='2830830'>not</span> <span m='2830980'>too</span>
  <span m='2831130'>often</span> <span m='2831310'>in</span> <span m='2831370'>chemical</span>
  <span m='2831640'>engineering,</span> <span m='2831940'>fortunately.</span> <span
  m='2834355'>All right,</span> <span m='2834838'>questions?</span> <span m='2838230'>No</span>
  <span m='2838460'>questions,</span> <span m='2838640'>OK.</span> </p><p><span m='2839040'>So</span>
  <span m='2839130'>in</span> <span m='2839220'>the</span> <span m='2839280'>textbook,</span>
  <span m='2839730'>they</span> <span m='2839850'>have</span> <span m='2840000'>a</span>
  <span m='2840060'>big</span> <span m='2840230'>discussion</span> <span m='2840690'>about</span>
  <span m='2841590'>how</span> <span m='2841860'>to</span> <span m='2842400'>evaluate</span>
  <span m='2843030'>different</span> <span m='2843300'>g</span> <span m='2843540'>methods</span>
  <span m='2844890'>in</span> <span m='2845010'>order</span> <span m='2845190'>to</span>
  <span m='2845250'>figure</span> <span m='2845490'>out</span> <span m='2845840'>if</span>
  <span m='2846020'>they're</span> <span m='2846270'>guaranteed</span> <span m='2846660'>to</span>
  <span m='2846750'>be</span> <span m='2846840'>stable,</span> <span m='2847800'>or</span>
  <span m='2847930'>under</span> <span m='2848070'>what</span> <span m='2848220'>conditions</span>
  <span m='2848610'>they'll be</span> <span m='2848790'>stable.</span> <span m='2850410'>And</span>
  <span m='2850500'>so</span> <span m='2850710'>that's</span> <span m='2851250'>worth</span>
  <span m='2851490'>a</span> <span m='2851880'>look</span> <span m='2853566'>to</span>
  <span m='2854040'>see.</span> <span m='2854315'>And</span> <span m='2854590'>they
  have</span> <span m='2854750'>detailed</span> <span m='2855090'>derivations</span>
  <span m='2855600'>for</span> <span m='2855690'>several</span> <span m='2856050'>of
  them.</span> </p><p><span m='2860000'>Questions?</span> <span m='2862500'>All</span>
  <span m='2862560'>right,</span> <span m='2862710'>so</span> <span m='2862830'>for</span>
  <span m='2862980'>the</span> <span m='2863070'>homework,</span> <span m='2863580'>homework</span>
  <span m='2864030'>four,</span> <span m='2864360'>you're</span> <span m='2864560'>going</span>
  <span m='2864570'>to</span> <span m='2864630'>have</span> <span m='2864720'>to</span>
  <span m='2864840'>write</span> <span m='2865740'>your</span> <span m='2865900'>own</span>
  <span m='2866440'>ODE</span> <span m='2866820'>solver.</span> <span m='2867870'>So</span>
  <span m='2868170'>you'll</span> <span m='2868800'>do</span> <span m='2868950'>update</span>
  <span m='2869160'>formulas</span> <span m='2871050'>and</span> <span m='2871140'>compare</span>
  <span m='2871470'>them.</span> <span m='2872390'>When</span> <span m='2872890'>we</span>
  <span m='2873060'>come</span> <span m='2873210'>back</span> <span m='2874290'>on</span>
  <span m='2874650'>Tuesday,</span> <span m='2876030'>I'll</span> <span m='2876180'>show</span>
  <span m='2876420'>you</span> <span m='2876570'>how</span> <span m='2876840'>this</span>
  <span m='2877050'>is</span> <span m='2877200'>usually</span> <span m='2877560'>dealt</span>
  <span m='2877830'>with</span> <span m='2878760'>by</span> <span m='2878910'>switching</span>
  <span m='2879270'>to</span> <span m='2879480'>implicit</span> <span m='2880050'>solvers</span>
  <span m='2881910'>and</span> <span m='2882630'>talk</span> <span m='2882840'>about</span>
  <span m='2882990'>that.</span> <span m='2884530'>All</span> <span m='2884610'>right,</span>
  <span m='2885610'>have</span> <span m='2886020'>a good</span> <span m='2886430'>weekend.</span>
  <span m='2886980'>Enjoy</span> <span m='2887170'>the</span> <span m='2887330'>three</span>
  <span m='2887490'>days</span> <span m='2887920'>off.</span> </p>
type: course
uid: 025e160abba890f59d132d00a605bf33

---
None