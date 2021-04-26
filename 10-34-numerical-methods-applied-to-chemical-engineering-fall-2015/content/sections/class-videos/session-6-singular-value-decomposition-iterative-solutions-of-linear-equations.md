---
about_this_resource_text: <p><strong>Description:</strong> This is the last lecture
  on solving linear algebra. It began in recapping what students already learned in
  eigenvalues, eigenvectors, and eigen decomposition, then conitnued to learn how
  to find iterative solutions to solve linear equestions.</p> <p><strong>Instructor:</strong>
  James Swan</p>
course_id: 10-34-numerical-methods-applied-to-chemical-engineering-fall-2015
embedded_media:
- id: Video-YouTube-Stream
  media_location: w9GJyvkHbNM
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: Video-YouTube-Stream
  type: Video
  uid: cd6a4cfc6625e9f4c7b6553569ab2146
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/w9GJyvkHbNM/default.jpg
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 6a92cf48a8cdf654bc03f393631393aa
- id: 3Play-3PlayYouTubeid-MP4
  media_location: w9GJyvkHbNM
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 74a94437536e7ecb1d8706458538cfc8
- id: w9GJyvkHbNM.srt
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-6-singular-value-decomposition-iterative-solutions-of-linear-equations/w9GJyvkHbNM.srt
  title: 3play caption file
  type: null
  uid: c6e94e5835af89c3ab37c67169aeab76
- id: w9GJyvkHbNM.pdf
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-6-singular-value-decomposition-iterative-solutions-of-linear-equations/w9GJyvkHbNM.pdf
  title: 3play pdf file
  type: null
  uid: f49d2e85189c3c7d117071f3cba60ca4
- id: Caption-3Play YouTube id-SRT
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 97faf785b55061a6f72c4867855e56bc
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4308d1312b84ee0a48c9b63647fbdb4b
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id1271456481
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: Video-iTunes U-MP4
  type: Video
  uid: 42d1c4068569dba1d4fc41a284d6b92d
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT10.34F15/MIT10_34F15_ses06_300k.mp4
  parent_uid: 72e0947eabbb0ab24ae80b96b1b5bddb
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4bd5efb110583a0b8c439a25f5a77310
inline_embed_id: 83173356session6singularvaluedecompositioniterativesolutionsoflinearequations43178737
layout: video
order_index: null
parent_uid: afa0ff29750f6846eda04cb1a3d4b84a
related_resources_text: ''
short_url: session-6-singular-value-decomposition-iterative-solutions-of-linear-equations
technical_location: https://ocw.mit.edu/courses/chemical-engineering/10-34-numerical-methods-applied-to-chemical-engineering-fall-2015/class-videos/session-6-singular-value-decomposition-iterative-solutions-of-linear-equations
template_type: Tabbed
title: 'Session 6: Singular Value Decomposition; Iterative Solutions of Linear Equations'
transcript: <p><span m='1580'>The</span> <span m='1670'>following</span> <span m='2120'>content</span>
  <span m='2600'>is</span> <span m='2720'>provided</span> <span m='3170'>under</span>
  <span m='3380'>a</span> <span m='3470'>Creative</span> <span m='3920'>Commons</span>
  <span m='4310'>license.</span> <span m='5340'>Your</span> <span m='5420'>support</span>
  <span m='5900'>will</span> <span m='6050'>help</span> <span m='6320'>MIT</span>
  <span m='6800'>OpenCourseWare</span> <span m='7550'>continue</span> <span m='8029'>to</span>
  <span m='8180'>offer</span> <span m='8510'>high</span> <span m='8720'>quality</span>
  <span m='9200'>educational</span> <span m='9860'>resources</span> <span m='10430'>for</span>
  <span m='10580'>free.</span> <span m='11640'>To</span> <span m='11740'>make</span>
  <span m='11840'>a</span> <span m='11900'>donation</span> <span m='12650'>or</span>
  <span m='12830'>to</span> <span m='12950'>view</span> <span m='13160'>additional</span>
  <span m='13550'>materials</span> <span m='14180'>from</span> <span m='14360'>hundreds</span>
  <span m='14690'>of</span> <span m='14780'>MIT</span> <span m='15170'>courses,</span>
  <span m='16470'>visit</span> <span m='16670'>MIT</span> <span m='17180'>OpenCourseWare</span>
  <span m='18110'>at</span> <span m='18330'>ocw.mit.edu.</span> </p><p><span m='23390'>JAMES
  W. SWAN:</span> <span m='23570'>So</span> <span m='24910'>this</span> <span m='25070'>is</span>
  <span m='25160'>going</span> <span m='25280'>to</span> <span m='25340'>be</span>
  <span m='25400'>our</span> <span m='25460'>last</span> <span m='25730'>lecture</span>
  <span m='26150'>on</span> <span m='26270'>linear</span> <span m='26570'>algebra.</span>
  <span m='27960'>The</span> <span m='28010'>first</span> <span m='28190'>three</span>
  <span m='28370'>lectures</span> <span m='28820'>covered</span> <span m='29210'>basics.</span>
  <span m='30680'>The</span> <span m='30740'>next</span> <span m='30950'>three</span>
  <span m='31130'>lectures,</span> <span m='31770'>we</span> <span m='31790'>talked</span>
  <span m='32000'>about</span> <span m='32150'>different</span> <span m='32420'>sorts</span>
  <span m='32750'>of</span> <span m='32900'>transformations</span> <span m='33980'>of</span>
  <span m='34190'>matrices.</span> <span m='34730'>This</span> <span m='34850'>final</span>
  <span m='35180'>lecture</span> <span m='35535'>is</span> <span m='35890'>the</span>
  <span m='36060'>last</span> <span m='36380'>of</span> <span m='36420'>those</span>
  <span m='36640'>three.</span> <span m='36840'>We're</span> <span m='36930'>going</span>
  <span m='37030'>to</span> <span m='37100'>talk</span> <span m='37280'>about</span>
  <span m='37410'>in</span> <span m='37450'>another</span> <span m='37730'>sort</span>
  <span m='37910'>of</span> <span m='37970'>transformation</span> <span m='39200'>called</span>
  <span m='39410'>the</span> <span m='39470'>singular</span> <span m='39890'>value</span>
  <span m='40250'>decomposition.</span> </p><p><span m='42820'>OK,</span> <span m='43070'>before</span>
  <span m='43370'>we</span> <span m='43610'>jump</span> <span m='43910'>in,</span>
  <span m='44160'>I'd</span> <span m='44260'>like</span> <span m='44360'>to</span>
  <span m='44840'>do</span> <span m='44960'>the</span> <span m='45080'>usual</span>
  <span m='45620'>recap</span> <span m='46220'>business.</span> <span m='46610'>I
  think</span> <span m='46820'>it's</span> <span m='46980'>always</span> <span m='47130'>hopeful</span>
  <span m='47570'>to</span> <span m='47780'>recap</span> <span m='48360'>or</span>
  <span m='48470'>look</span> <span m='48650'>at</span> <span m='48740'>things</span>
  <span m='49010'>from</span> <span m='49160'>a</span> <span m='49190'>different</span>
  <span m='49430'>perspective.</span> <span m='51170'>Early</span> <span m='51500'>on,</span>
  <span m='51680'>I</span> <span m='51770'>told</span> <span m='52070'>you</span>
  <span m='52340'>that</span> <span m='53180'>the</span> <span m='53420'>infinite</span>
  <span m='53930'>dimensional</span> <span m='54500'>equivalent</span> <span m='55130'>of</span>
  <span m='55310'>vectors</span> <span m='55970'>would</span> <span m='56060'>be</span>
  <span m='56120'>something</span> <span m='56450'>like</span> <span m='56660'>a</span>
  <span m='56780'>function,</span> <span m='57500'>which</span> <span m='57740'>is</span>
  <span m='57890'>a</span> <span m='57980'>map,</span> <span m='58730'>a</span> <span
  m='58790'>unique</span> <span m='59210'>map</span> <span m='59610'>maybe</span>
  <span m='59900'>from</span> <span m='60620'>a</span> <span m='60680'>point</span>
  <span m='61100'>to</span> <span m='61190'>x</span> <span m='61580'>to</span> <span
  m='61730'>some</span> <span m='61970'>value</span> <span m='62510'>f</span> <span
  m='62780'>of</span> <span m='62930'>x.</span> <span m='64150'>And</span> <span m='64420'>there</span>
  <span m='64530'>is</span> <span m='64670'>an</span> <span m='64760'>equivalent</span>
  <span m='65269'>representation</span> <span m='66080'>of</span> <span m='66170'>the</span>
  <span m='66350'>eigenvalue</span> <span m='67070'>eigenvector</span> <span m='67670'>problem</span>
  <span m='68030'>in</span> <span m='68120'>function</span> <span m='68510'>space.</span>
  <span m='68780'>We</span> <span m='68860'>call</span> <span m='68970'>these</span>
  <span m='69140'>eigenvalues</span> <span m='70280'>and</span> <span m='70490'>eigenfunctions.</span>
  </p><p><span m='71330'>Here's</span> <span m='71480'>a</span> <span m='71540'>classic</span>
  <span m='72050'>one</span> <span m='72950'>where</span> <span m='73040'>the</span>
  <span m='73130'>function</span> <span m='73580'>is</span> <span m='73740'>y</span>
  <span m='74060'>of</span> <span m='74250'>x,</span> <span m='74970'>OK?</span> <span
  m='75230'>This</span> <span m='75410'>is</span> <span m='75530'>the</span> <span
  m='75650'>equivalent</span> <span m='76040'>of</span> <span m='76130'>the</span>
  <span m='76250'>vector,</span> <span m='76670'>and</span> <span m='76790'>equivalent</span>
  <span m='77240'>of</span> <span m='77330'>the</span> <span m='77420'>transformation</span>
  <span m='78260'>or</span> <span m='78350'>the</span> <span m='78440'>matrix</span>
  <span m='78890'>that's</span> <span m='79000'>this</span> <span m='79220'>differential</span>
  <span m='79790'>operator</span> <span m='80240'>this</span> <span m='80410'>time,</span>
  <span m='81230'>the</span> <span m='81290'>second</span> <span m='81590'>derivative.</span>
  <span m='82850'>So</span> <span m='82960'>I</span> <span m='83000'>take</span> <span
  m='83180'>the</span> <span m='83270'>second</span> <span m='83540'>derivative</span>
  <span m='83900'>of</span> <span m='85220'>this</span> <span m='85400'>particular</span>
  <span m='85820'>function,</span> <span m='86340'>and</span> <span m='86440'>the</span>
  <span m='86540'>function</span> <span m='86810'>is</span> <span m='87290'>stretched.</span>
  <span m='88040'>It's</span> <span m='88190'>multiplied</span> <span m='88790'>by</span>
  <span m='88970'>some</span> <span m='89180'>fixed</span> <span m='89510'>value</span>
  <span m='89930'>at</span> <span m='90020'>all</span> <span m='90170'>points.</span>
  <span m='90980'>And</span> <span m='91130'>it</span> <span m='91190'>becomes</span>
  <span m='91460'>lambda</span> <span m='92330'>times</span> <span m='92720'>y.</span>
  </p><p><span m='93830'>And</span> <span m='94130'>that</span> <span m='94310'>operator</span>
  <span m='94850'>has</span> <span m='95030'>to</span> <span m='95150'>be</span> <span
  m='95300'>closed</span> <span m='96080'>with</span> <span m='96350'>some</span>
  <span m='96710'>boundary</span> <span m='97100'>conditions</span> <span m='97610'>as</span>
  <span m='97760'>well.</span> <span m='97920'>We</span> <span m='98000'>have</span>
  <span m='98120'>to</span> <span m='98210'>say</span> <span m='98570'>what</span>
  <span m='98780'>the</span> <span m='98900'>value</span> <span m='99260'>of</span>
  <span m='99380'>y</span> <span m='99830'>is</span> <span m='100670'>at</span> <span
  m='100970'>the</span> <span m='101330'>edges</span> <span m='101840'>of</span> <span
  m='101960'>some</span> <span m='102260'>boundary.</span> <span m='103640'>So</span>
  <span m='103790'>there's</span> <span m='103970'>a</span> <span m='104060'>one-to-one</span>
  <span m='104690'>correspondence</span> <span m='105590'>between</span> <span m='106040'>these</span>
  <span m='106310'>things.</span> </p><p><span m='108470'>What</span> <span m='108650'>is</span>
  <span m='108860'>the</span> <span m='109340'>eigenfunction</span> <span m='111670'>here,</span>
  <span m='112570'>or</span> <span m='112690'>what</span> <span m='112870'>are</span>
  <span m='113080'>the</span> <span m='113260'>eigenfunctions?</span> <span m='114730'>And</span>
  <span m='114820'>what</span> <span m='115030'>are</span> <span m='115180'>the</span>
  <span m='115360'>eigenvalues</span> <span m='116320'>associated</span> <span m='117160'>with</span>
  <span m='117340'>this</span> <span m='117520'>transformation</span> <span m='117995'>or</span>
  <span m='118470'>this</span> <span m='118720'>operator?</span> <span m='119590'>Can</span>
  <span m='119680'>you</span> <span m='119770'>work</span> <span m='119920'>those</span>
  <span m='120100'>out</span> <span m='120250'>really</span> <span m='120490'>quickly?</span>
  <span m='121810'>You</span> <span m='121910'>learned</span> <span m='122110'>this</span>
  <span m='122320'>at</span> <span m='122410'>some</span> <span m='122620'>point,</span>
  <span m='122890'>right?</span> </p><p><span m='123250'>Somebody</span> <span m='123580'>taught</span>
  <span m='123850'>you</span> <span m='125230'>differential</span> <span m='125710'>equations</span>
  <span m='125995'>and</span> <span m='126280'>you</span> <span m='126430'>calculated</span>
  <span m='126970'>these</span> <span m='127150'>things.</span> <span m='127360'>Take</span>
  <span m='127510'>about</span> <span m='127690'>90</span> <span m='127960'>seconds.</span>
  <span m='128410'>Work</span> <span m='128560'>with</span> <span m='128650'>the</span>
  <span m='128710'>people</span> <span m='128979'>around</span> <span m='129280'>you.</span>
  <span m='129370'>See</span> <span m='129490'>if</span> <span m='129610'>you</span>
  <span m='129699'>can</span> <span m='129940'>come</span> <span m='130120'>to</span>
  <span m='130270'>a</span> <span m='130300'>conclusion</span> <span m='130840'>about</span>
  <span m='130990'>what</span> <span m='131170'>the</span> <span m='131590'>eigenfunction</span>
  <span m='133720'>and</span> <span m='133870'>eigenvalues</span> <span m='134680'>are.</span>
  </p><p></p><p><span m='146920'>That's</span> <span m='147110'>enough</span> <span
  m='147220'>time.</span> <span m='147490'>You</span> <span m='147550'>can</span>
  <span m='147670'>work</span> <span m='147820'>on</span> <span m='147910'>this</span>
  <span m='148120'>on</span> <span m='148240'>your</span> <span m='148360'>own</span>
  <span m='148540'>later</span> <span m='148870'>if</span> <span m='149020'>you've</span>
  <span m='149150'>run</span> <span m='149320'>out</span> <span m='149440'>of</span>
  <span m='149500'>time.</span> <span m='149830'>Don't</span> <span m='149980'>worry</span>
  <span m='150190'>about</span> <span m='150460'>it.</span> <span m='151030'>Does</span>
  <span m='151150'>somebody</span> <span m='151390'>want</span> <span m='151540'>to</span>
  <span m='151630'>volunteer</span> <span m='152080'>a</span> <span m='152200'>guess</span>
  <span m='152600'>for</span> <span m='152800'>what</span> <span m='152980'>the</span>
  <span m='153280'>eigenfunctions</span> <span m='154780'>are</span> <span m='155050'>in</span>
  <span m='155170'>this</span> <span m='155330'>case?</span> <span m='156340'>What</span>
  <span m='156490'>are</span> <span m='156580'>they?</span> <span m='158350'>Yeah?</span>
  </p><p><span m='159300'>AUDIENCE:</span> <span m='159537'>[INAUDIBLE]</span> </p><p><span
  m='163100'>JAMES W. SWAN:</span> <span m='163220'>OK,</span> <span m='163340'>so</span>
  <span m='163490'>you</span> <span m='163580'>chose</span> <span m='163920'>exponentials.</span>
  <span m='164720'>That's</span> <span m='164930'>an</span> <span m='165080'>interesting</span>
  <span m='165650'>choice.</span> <span m='165950'>That's</span> <span m='166100'>one</span>
  <span m='166340'>possible</span> <span m='166760'>choice</span> <span m='167060'>you</span>
  <span m='167150'>can</span> <span m='167270'>make.</span> <span m='167880'>OK,</span>
  <span m='168230'>so</span> <span m='168350'>we</span> <span m='168440'>could</span>
  <span m='168560'>say--</span> <span m='169310'>this</span> <span m='169460'>is</span>
  <span m='169520'>sort</span> <span m='169640'>of</span> <span m='169720'>a</span>
  <span m='169790'>classical</span> <span m='170210'>one</span> <span m='170420'>that</span>
  <span m='170540'>you</span> <span m='170660'>think</span> <span m='170870'>about</span>
  <span m='172250'>when</span> <span m='174110'>you</span> <span m='174170'>first</span>
  <span m='174410'>learn</span> <span m='174590'>differential</span> <span m='175010'>equation.</span>
  <span m='175350'>They</span> <span m='175440'>say, an</span> <span m='175760'>equation</span>
  <span m='176120'>of</span> <span m='176240'>this</span> <span m='176350'>sort</span>
  <span m='176690'>has</span> <span m='176960'>solutions</span> <span m='177680'>that</span>
  <span m='177800'>look</span> <span m='178040'>like</span> <span m='178310'>exponentials,</span>
  <span m='179760'>and</span> <span m='179930'>that's</span> <span m='180170'>true.</span>
  <span m='181640'>There's</span> <span m='181820'>another</span> <span m='182030'>representation</span>
  <span m='182720'>for</span> <span m='182870'>this,</span> <span m='183210'>which</span>
  <span m='183290'>is</span> <span m='183440'>as</span> <span m='183710'>trigonometric</span>
  <span m='184280'>functions</span> <span m='184730'>instead,</span> <span m='185360'>right?</span>
  </p><p><span m='189110'>Either</span> <span m='189270'>of</span> <span m='189570'>those</span>
  <span m='189880'>is</span> <span m='190050'>acceptable.</span> <span m='190470'>[INAUDIBLE]</span>
  <span m='191170'>the</span> <span m='191260'>trigonometric</span> <span m='191770'>functions,</span>
  <span m='192550'>that</span> <span m='192700'>representation</span> <span m='193360'>is</span>
  <span m='193480'>a</span> <span m='193510'>little</span> <span m='193660'>more</span>
  <span m='193810'>useful</span> <span m='194230'>for</span> <span m='194440'>us</span>
  <span m='194590'>here.</span> <span m='197440'>We</span> <span m='197560'>know</span>
  <span m='197740'>that</span> <span m='197890'>the</span> <span m='197980'>boundary</span>
  <span m='198250'>conditions</span> <span m='198850'>tell</span> <span m='199030'>us</span>
  <span m='199180'>that</span> <span m='199300'>y</span> <span m='199570'>of</span>
  <span m='199660'>0</span> <span m='199750'>is</span> <span m='199990'>supposed</span>
  <span m='200410'>to</span> <span m='200530'>be</span> <span m='200650'>0.</span>
  <span m='202430'>That</span> <span m='202450'>means</span> <span m='202690'>that</span>
  <span m='202810'>the</span> <span m='202960'>C1</span> <span m='203650'>has</span>
  <span m='203950'>to</span> <span m='204070'>be</span> <span m='204250'>0,</span>
  <span m='204760'>because</span> <span m='204970'>cosine</span> <span m='205070'>of</span>
  <span m='205720'>0</span> <span m='206080'>is</span> <span m='206200'>1.</span>
  <span m='206590'>So</span> <span m='206900'>C1</span> <span m='207160'>has</span>
  <span m='207730'>0</span> <span m='208130'>in</span> <span m='208270'>this</span>
  <span m='208420'>case.</span> <span m='209550'>So</span> <span m='209670'>that</span>
  <span m='209830'>fixes</span> <span m='210250'>one</span> <span m='210400'>of</span>
  <span m='210460'>these</span> <span m='210640'>coefficients.</span> </p><p><span
  m='213030'>And</span> <span m='213150'>now</span> <span m='213270'>we're</span>
  <span m='213360'>left</span> <span m='213600'>with</span> <span m='213750'>a</span>
  <span m='213810'>problem,</span> <span m='215040'>right?</span> <span m='215730'>Our</span>
  <span m='215910'>solutions,</span> <span m='217260'>our</span> <span m='217440'>eigenfunctions,</span>
  <span m='218310'>cannot</span> <span m='218550'>be</span> <span m='218670'>unique.</span>
  <span m='219220'>So</span> <span m='219300'>we</span> <span m='219360'>don't</span>
  <span m='219510'>get</span> <span m='219630'>to</span> <span m='219750'>specify</span>
  <span m='220440'>C2,</span> <span m='221340'>right?</span> <span m='221760'>Any</span>
  <span m='221940'>function</span> <span m='222510'>that's</span> <span m='222690'>a</span>
  <span m='222750'>multiple</span> <span m='223740'>of</span> <span m='223920'>this</span>
  <span m='224170'>sine</span> <span m='224580'>should</span> <span m='224730'>also</span>
  <span m='224970'>be</span> <span m='225060'>an</span> <span m='225150'>eigenfunction.</span>
  </p><p><span m='225870'>So</span> <span m='226030'>instead</span> <span m='226380'>the</span>
  <span m='226530'>other</span> <span m='226710'>boundary</span> <span m='227130'>condition,</span>
  <span m='227640'>this</span> <span m='227810'>y</span> <span m='228070'>of l</span>
  <span m='228335'>equals</span> <span m='228600'>0,</span> <span m='229020'>needs</span>
  <span m='229290'>to</span> <span m='229410'>be</span> <span m='229530'>used</span>
  <span m='230310'>to</span> <span m='230430'>pin</span> <span m='230700'>down</span>
  <span m='231030'>with</span> <span m='231210'>the</span> <span m='231360'>eigenvalue</span>
  <span m='232160'>is.</span> <span m='232920'>So</span> <span m='233100'>the</span>
  <span m='233230'>second</span> <span m='233610'>equation,</span> <span m='234060'>y</span>
  <span m='234300'>of</span> <span m='234450'>l</span> <span m='234600'>equals</span>
  <span m='234870'>0,</span> <span m='236920'>which</span> <span m='237130'>implies</span>
  <span m='237670'>that</span> <span m='237820'>the</span> <span m='237910'>square</span>
  <span m='238270'>root</span> <span m='238480'>of</span> <span m='238570'>minus</span>
  <span m='239110'>lambda</span> <span m='239560'>has</span> <span m='239830'>to</span>
  <span m='239920'>be</span> <span m='240110'>equal to</span> <span m='240310'>2</span>
  <span m='240490'>pi</span> <span m='240730'>over</span> <span m='241050'>l,</span>
  <span m='241590'>it</span> <span m='241660'>has</span> <span m='241840'>to</span>
  <span m='241960'>be</span> <span m='242110'>all</span> <span m='242260'>the</span>
  <span m='242410'>nodes</span> <span m='243490'>of</span> <span m='243610'>the</span>
  <span m='243730'>sine</span> <span m='244240'>where</span> <span m='244330'>the</span>
  <span m='244420'>sine</span> <span m='244720'>is</span> <span m='244810'>equal</span>
  <span m='244860'>to</span> <span m='245170'>0.</span> <span m='245440'>That's</span>
  <span m='245680'>the</span> <span m='245770'>equivalent</span> <span m='246190'>of</span>
  <span m='246280'>our</span> <span m='246370'>secular</span> <span m='246880'>characteristic</span>
  <span m='247450'>polynomial</span> <span m='248140'>that</span> <span m='248230'>prescribes</span>
  <span m='248770'>with</span> <span m='248920'>the</span> <span m='249070'>eigenvalues</span>
  <span m='249970'>are</span> <span m='250510'>associated</span> <span m='250990'>with</span>
  <span m='251140'>each</span> <span m='251290'>of</span> <span m='251350'>the</span>
  <span m='251470'>eigenfunctions.</span> </p><p><span m='253580'>So</span> <span
  m='253600'>now</span> <span m='253780'>we</span> <span m='253870'>know</span> <span
  m='253990'>what</span> <span m='254110'>the</span> <span m='254230'>eigenvalues</span>
  <span m='254860'>are.</span> <span m='255190'>The</span> <span m='255310'>eigenvalues</span>
  <span m='255910'>are</span> <span m='255970'>the</span> <span m='256060'>set</span>
  <span m='256300'>of</span> <span m='256420'>numbers</span> <span m='257320'>minus</span>
  <span m='257890'>2</span> <span m='258089'>pi</span> <span m='258339'>n</span> <span
  m='258779'>over</span> <span m='259204'>l</span> <span m='259630'>squared.</span>
  <span m='261700'>There's</span> <span m='261850'>an</span> <span m='261940'>infinite</span>
  <span m='262180'>number</span> <span m='262390'>of</span> <span m='262480'>eigenvalues.</span>
  <span m='263490'>It's</span> <span m='263620'>an</span> <span m='263740'>infinite</span>
  <span m='264130'>dimensional</span> <span m='265450'>space</span> <span m='266050'>that</span>
  <span m='266200'>we're</span> <span m='266350'>in,</span> <span m='266920'>so</span>
  <span m='267130'>it's</span> <span m='267220'>not</span> <span m='267340'>a</span>
  <span m='267400'>big</span> <span m='267520'>surprise</span> <span m='267940'>that</span>
  <span m='268030'>it</span> <span m='268090'>works</span> <span m='268330'>out</span>
  <span m='268480'>that</span> <span m='268630'>way.</span> <span m='269230'>And</span>
  <span m='269320'>the</span> <span m='269440'>eigenvectors</span> <span m='270190'>then</span>
  <span m='270850'>are</span> <span m='271900'>different</span> <span m='272200'>scalar</span>
  <span m='272530'>multiples</span> <span m='273100'>of</span> <span m='273250'>sine</span>
  <span m='274210'>of</span> <span m='274300'>the</span> <span m='274420'>eigenvalues,</span>
  <span m='274795'>square</span> <span m='275170'>root of</span> <span m='275560'>the</span>
  <span m='275680'>eigenvalues,</span> <span m='276220'>minus</span> <span m='276910'>x.</span>
  </p><p><span m='277900'>There's</span> <span m='278050'>a</span> <span m='278110'>one-to-one</span>
  <span m='278500'>correspondence</span> <span m='279130'>between</span> <span m='279430'>all</span>
  <span m='279550'>the</span> <span m='279670'>linear</span> <span m='279970'>algebra</span>
  <span m='280270'>we've</span> <span m='280450'>done</span> <span m='281110'>and</span>
  <span m='281260'>linear</span> <span m='281620'>differential</span> <span m='282070'>equations</span>
  <span m='282670'>or</span> <span m='282820'>linear</span> <span m='283120'>partial</span>
  <span m='283540'>differential</span> <span m='284050'>equations.</span> <span m='284560'>You</span>
  <span m='284680'>can</span> <span m='284800'>think</span> <span m='285010'>about</span>
  <span m='285280'>these</span> <span m='285490'>things</span> <span m='285780'>in</span>
  <span m='285880'>exactly</span> <span m='286280'>the</span> <span m='286360'>same</span>
  <span m='286570'>way.</span> <span m='287030'>I'm</span> <span m='287050'>sure</span>
  <span m='287350'>in</span> <span m='288320'>1050,</span> <span m='289270'>you</span>
  <span m='289750'>started</span> <span m='290320'>to</span> <span m='290500'>talk</span>
  <span m='290800'>about</span> <span m='291850'>orthogonal</span> <span m='292420'>functions</span>
  <span m='293080'>to</span> <span m='293170'>represent</span> <span m='293620'>solutions</span>
  <span m='294190'>of</span> <span m='294280'>differential</span> <span m='294760'>equations.</span>
  <span m='295270'>Or</span> <span m='295360'>if</span> <span m='295450'>you</span>
  <span m='295570'>haven't,</span> <span m='295930'>you're</span> <span m='296050'>going</span>
  <span m='296290'>to</span> <span m='296560'>very</span> <span m='296860'>soon.</span>
  </p><p><span m='297310'>This is</span> <span m='297520'>a</span> <span m='297580'>part</span>
  <span m='297790'>of</span> <span m='297850'>the</span> <span m='297940'>course</span>
  <span m='298500'>you</span> <span m='298570'>get</span> <span m='298690'>to</span>
  <span m='298750'>look</span> <span m='298900'>at</span> <span m='298960'>the</span>
  <span m='299050'>analytical</span> <span m='299560'>side</span> <span m='300280'>of</span>
  <span m='300370'>some</span> <span m='300550'>of</span> <span m='300610'>these</span>
  <span m='300790'>things</span> <span m='301060'>as</span> <span m='301180'>opposed</span>
  <span m='301450'>to</span> <span m='301510'>the</span> <span m='301600'>numerical</span>
  <span m='302050'>side.</span> <span m='302230'>But</span> <span m='302320'>there's</span>
  <span m='302470'>a</span> <span m='302530'>one-to-one</span> <span m='302950'>relationship</span>
  <span m='303550'>between</span> <span m='303880'>those</span> <span m='304120'>things.</span>
  <span m='304730'>So</span> <span m='304750'>if</span> <span m='304840'>you</span>
  <span m='304900'>understand</span> <span m='305260'>one,</span> <span m='305500'>you</span>
  <span m='305620'>understand</span> <span m='306010'>the</span> <span m='306130'>other,</span>
  <span m='306380'>and</span> <span m='306640'>you</span> <span m='306730'>can</span>
  <span m='306880'>come</span> <span m='307060'>at</span> <span m='307210'>them</span>
  <span m='307540'>from</span> <span m='307840'>either</span> <span m='308140'>perspective.</span>
  </p><p><span m='310770'>This</span> <span m='310870'>sort</span> <span m='311040'>of</span>
  <span m='311100'>stuff</span> <span m='311340'>is</span> <span m='311550'>useful.</span>
  <span m='312340'>Actually,</span> <span m='312390'>the</span> <span m='312520'>classical</span>
  <span m='312870'>chemical</span> <span m='313170'>engineering</span> <span m='313530'>example</span>
  <span m='313890'>comes</span> <span m='314100'>from</span> <span m='315030'>quantum</span>
  <span m='315330'>mechanics</span> <span m='315625'>where</span> <span m='315920'>you</span>
  <span m='316170'>think</span> <span m='316380'>about</span> <span m='316710'>wave</span>
  <span m='317010'>functions</span> <span m='317640'>and</span> <span m='317730'>different</span>
  <span m='317970'>energy</span> <span m='318360'>levels</span> <span m='318780'>corresponding</span>
  <span m='319110'>to</span> <span m='319440'>eigenvalues.</span> <span m='321870'>That's</span>
  <span m='322590'>cool.</span> <span m='323220'>Sometimes,</span> <span m='323910'>I</span>
  <span m='323970'>like</span> <span m='324090'>to</span> <span m='324180'>think</span>
  <span m='324330'>about</span> <span m='324480'>a</span> <span m='324540'>mechanical</span>
  <span m='325050'>analog</span> <span m='325460'>to</span> <span m='325590'>that,</span>
  <span m='325860'>which</span> <span m='326100'>is</span> <span m='326790'>the</span>
  <span m='326910'>buckling</span> <span m='327480'>of</span> <span m='327570'>an</span>
  <span m='327620'>elastic</span> <span m='328120'>column.</span> </p><p><span m='328660'>So</span>
  <span m='328770'>you</span> <span m='328860'>should</span> <span m='329040'>do</span>
  <span m='329190'>this</span> <span m='329400'>at</span> <span m='329490'>home.</span>
  <span m='329670'>You</span> <span m='329730'>should</span> <span m='329880'>go</span>
  <span m='330000'>get</span> <span m='330120'>a</span> <span m='330180'>piece</span>
  <span m='330450'>of</span> <span m='330540'>spaghetti</span> <span m='331800'>and</span>
  <span m='332010'>push</span> <span m='332280'>on</span> <span m='332400'>the</span>
  <span m='332550'>ends</span> <span m='332880'>of</span> <span m='332940'>the</span>
  <span m='333030'>piece</span> <span m='333270'>of</span> <span m='333330'>the</span>
  <span m='333430'>spaghetti.</span> <span m='334620'>And</span> <span m='334800'>the</span>
  <span m='334890'>spaghetti</span> <span m='335280'>will</span> <span m='335460'>buckle.</span>
  <span m='336000'>Eventually</span> <span m='336420'>it'll</span> <span m='336600'>break,</span>
  <span m='337020'>but</span> <span m='337160'>it'll</span> <span m='337390'>buckle</span>
  <span m='337800'>first.</span> <span m='338300'>It'll</span> <span m='338500'>bend.</span>
  </p><p><span m='339520'>And</span> <span m='339630'>how</span> <span m='339810'>does</span>
  <span m='339990'>it</span> <span m='340110'>bend?</span> <span m='341070'>Well,</span>
  <span m='341610'>a</span> <span m='341850'>balance</span> <span m='342510'>of</span>
  <span m='342630'>linear</span> <span m='343020'>momentum</span> <span m='344280'>on</span>
  <span m='344610'>this</span> <span m='344880'>bar</span> <span m='345330'>would</span>
  <span m='345450'>tell</span> <span m='345690'>you</span> <span m='345930'>that</span>
  <span m='347310'>the</span> <span m='347400'>deflection</span> <span m='348780'>in</span>
  <span m='348900'>the</span> <span m='348990'>bar</span> <span m='349620'>at</span>
  <span m='350040'>different</span> <span m='350280'>points</span> <span m='350700'>x</span>
  <span m='351220'>along</span> <span m='351390'>the</span> <span m='351480'>bar</span>
  <span m='352420'>multiplied</span> <span m='353310'>by</span> <span m='353460'>the</span>
  <span m='353550'>pressure</span> <span m='354860'>has</span> <span m='355130'>to</span>
  <span m='355260'>balance</span> <span m='355740'>the</span> <span m='355890'>bending</span>
  <span m='356490'>moment</span> <span m='357600'>in</span> <span m='357780'>the</span>
  <span m='357900'>bar</span> <span m='358140'>itself.</span> <span m='358690'>So</span>
  <span m='358860'>this</span> <span m='359160'>e</span> <span m='359460'>is</span>
  <span m='359550'>some</span> <span m='359760'>elastic</span> <span m='360300'>constant.</span>
  <span m='360840'>I</span> <span m='361140'>has</span> <span m='361290'>a</span>
  <span m='361350'>moment</span> <span m='361680'>of</span> <span m='361770'>inertia.</span>
  </p><p><span m='362640'>And</span> <span m='362900'>D</span> <span m='363180'>squared</span>
  <span m='363500'>y</span> <span m='363780'>dx</span> <span m='364020'>squared</span>
  <span m='364270'>is</span> <span m='364350'>something</span> <span m='364650'>like</span>
  <span m='364800'>the</span> <span m='364890'>curvature</span> <span m='365370'>of</span>
  <span m='365460'>the</span> <span m='365580'>bar.</span> <span m='365980'>So</span>
  <span m='366000'>it's</span> <span m='366150'>the</span> <span m='366270'>bending</span>
  <span m='366690'>moments</span> <span m='367050'>of</span> <span m='367110'>the</span>
  <span m='367230'>bar</span> <span m='367590'>that</span> <span m='367800'>balances</span>
  <span m='368820'>the</span> <span m='368910'>pressure</span> <span m='369330'>that's</span>
  <span m='369510'>being</span> <span m='369750'>exerted</span> <span m='370170'>on</span>
  <span m='370290'>the</span> <span m='370380'>bar.</span> <span m='371250'>And</span>
  <span m='371340'>sure</span> <span m='371610'>enough,</span> <span m='371880'>this</span>
  <span m='372060'>bar</span> <span m='372330'>will</span> <span m='372510'>buckle</span>
  <span m='373800'>when</span> <span m='373950'>the</span> <span m='374040'>pressure</span>
  <span m='374460'>applied</span> <span m='375360'>exceeds</span> <span m='376860'>the</span>
  <span m='376980'>first</span> <span m='377550'>eigenvalue</span> <span m='378900'>associated</span>
  <span m='379590'>with</span> <span m='379740'>this</span> <span m='379950'>differential</span>
  <span m='380460'>equation.</span> </p><p><span m='380830'>We</span> <span m='380930'>just</span>
  <span m='381040'>worked</span> <span m='381240'>that</span> <span m='381390'>eigenvalue</span>
  <span m='381990'>out.</span> <span m='384390'>We</span> <span m='384510'>said</span>
  <span m='384720'>that</span> <span m='384870'>that</span> <span m='385050'>eigenvalue</span>
  <span m='388230'>had</span> <span m='388500'>to</span> <span m='388650'>be</span>
  <span m='389160'>the</span> <span m='389250'>square root</span> <span m='389610'>of</span>
  <span m='389730'>2</span> <span m='389950'>pi</span> <span m='390180'>over</span>
  <span m='390450'>l squared.</span> <span m='391680'>And</span> <span m='391800'>so</span>
  <span m='391920'>when</span> <span m='392040'>the</span> <span m='392100'>pressure</span>
  <span m='392460'>exceeds</span> <span m='392950'>square root</span> <span m='393240'>of
  2</span> <span m='393410'>pi</span> <span m='393660'>over</span> <span m='393930'>l
  squared</span> <span m='394980'>times</span> <span m='395310'>the</span> <span m='395400'>elastic</span>
  <span m='395850'>modulus,</span> <span m='396810'>this</span> <span m='396960'>column</span>
  <span m='397860'>will</span> <span m='397980'>bend</span> <span m='399030'>and</span>
  <span m='399170'>deform</span> <span m='399660'>continuously</span> <span m='400650'>until</span>
  <span m='400950'>it</span> <span m='401040'>eventually</span> <span m='401460'>breaks,</span>
  <span m='401740'>right?</span> <span m='401880'>It</span> <span m='401940'>will</span>
  <span m='402060'>undergo</span> <span m='402750'>this</span> <span m='403320'>linear</span>
  <span m='403740'>elastic</span> <span m='404190'>deformation,</span> <span m='404710'>then</span>
  <span m='404820'>plastic</span> <span m='405270'>deformation</span> <span m='405750'>later,</span>
  <span m='406020'>and it will</span> <span m='406290'>break.</span> </p><p><span
  m='408560'>The</span> <span m='408680'>Eiffel</span> <span m='409010'>Tower,</span>
  <span m='410030'>actually,</span> <span m='410480'>is</span> <span m='410600'>one</span>
  <span m='410690'>of</span> <span m='410750'>the</span> <span m='410840'>first</span>
  <span m='411050'>structures</span> <span m='411440'>in</span> <span m='411530'>the</span>
  <span m='411620'>world</span> <span m='411860'>to</span> <span m='411950'>utilize</span>
  <span m='412370'>this</span> <span m='412520'>principle,</span> <span m='413600'>right?</span>
  <span m='414270'>It's</span> <span m='414350'>got</span> <span m='414500'>very</span>
  <span m='414770'>narrow</span> <span m='415160'>beams</span> <span m='415610'>in</span>
  <span m='415730'>it.</span> <span m='416000'>The</span> <span m='416090'>beams</span>
  <span m='416360'>are</span> <span m='416450'>engineered</span> <span m='417710'>so</span>
  <span m='417890'>that</span> <span m='418010'>their</span> <span m='418580'>elastic</span>
  <span m='419150'>modulus</span> <span m='419720'>is</span> <span m='419780'>strong</span>
  <span m='420110'>enough</span> <span m='420290'>that</span> <span m='420410'>they</span>
  <span m='420530'>won't</span> <span m='420680'>buckle.</span> <span m='421280'>Gustave</span>
  <span m='421730'>Eiffel</span> <span m='422090'>is one</span> <span m='422180'>of</span>
  <span m='422270'>the</span> <span m='422360'>first</span> <span m='423020'>applied</span>
  <span m='423500'>physicists,</span> <span m='424060'>somebody</span> <span m='424230'>who</span>
  <span m='424280'>took</span> <span m='425030'>the</span> <span m='425150'>physics</span>
  <span m='425600'>of</span> <span m='426600'>elastic</span> <span m='427190'>bars</span>
  <span m='427700'>and</span> <span m='427820'>applied</span> <span m='428210'>them</span>
  <span m='428480'>to</span> <span m='429500'>building</span> <span m='429860'>structures</span>
  <span m='430370'>that</span> <span m='430460'>weren't</span> <span m='430610'>big</span>
  <span m='430760'>and</span> <span m='430880'>blocky,</span> <span m='431390'>but</span>
  <span m='431570'>used</span> <span m='431930'>a</span> <span m='432020'>minimal</span>
  <span m='432440'>amount</span> <span m='432860'>of</span> <span m='433040'>material.</span>
  <span m='434570'>Cool,</span> <span m='434840'>right?</span> </p><p><span m='436880'>OK,</span>
  <span m='437830'>so</span> <span m='437950'>that's</span> <span m='438160'>recap.</span>
  <span m='441580'>Any</span> <span m='441700'>questions</span> <span m='442060'>about</span>
  <span m='442240'>that?</span> <span m='443980'>You've</span> <span m='444070'>seen</span>
  <span m='444250'>these</span> <span m='444340'>things</span> <span m='444580'>before.</span>
  <span m='446410'>You</span> <span m='446500'>understood</span> <span m='446860'>them</span>
  <span m='446920'>well</span> <span m='447130'>before</span> <span m='447490'>too</span>
  <span m='448090'>maybe?</span> <span m='449530'>Give</span> <span m='449650'>some</span>
  <span m='449770'>thought to</span> <span m='450250'>this,</span> <span m='450440'>OK?</span>
  </p><p><span m='453430'>We</span> <span m='453520'>talked</span> <span m='453760'>about</span>
  <span m='454450'>eigendecomposition</span> <span m='455710'>last</span> <span m='456100'>time</span>
  <span m='457090'>that,</span> <span m='457300'>associated</span> <span m='457870'>with</span>
  <span m='458020'>the</span> <span m='458110'>square</span> <span m='458560'>matrix,</span>
  <span m='460050'>was</span> <span m='460210'>a</span> <span m='460270'>particular</span>
  <span m='460860'>eigenvalue</span> <span m='462160'>or</span> <span m='462310'>particular</span>
  <span m='462730'>set</span> <span m='462940'>of</span> <span m='463030'>eigenvalues,</span>
  <span m='464050'>stretches</span> <span m='465310'>and</span> <span m='465460'>corresponding</span>
  <span m='466180'>eigenvectors</span> <span m='467140'>directions.</span> <span m='468250'>These</span>
  <span m='468400'>were</span> <span m='468490'>special</span> <span m='468970'>solutions</span>
  <span m='470080'>to</span> <span m='470170'>the</span> <span m='470260'>system</span>
  <span m='470590'>of</span> <span m='470710'>linear</span> <span m='471010'>equations</span>
  <span m='471490'>based</span> <span m='471760'>on</span> <span m='471850'>a</span>
  <span m='471940'>matrix.</span> <span m='472540'>It</span> <span m='472920'>was</span>
  <span m='473050'>a</span> <span m='473110'>square</span> <span m='473440'>matrix.</span>
  </p><p><span m='473815'>And</span> <span m='474190'>you</span> <span m='474310'>might</span>
  <span m='474520'>ask,</span> <span m='474830'>well,</span> <span m='474950'>what</span>
  <span m='475030'>happens</span> <span m='475540'>if</span> <span m='475660'>the</span>
  <span m='475750'>matrix</span> <span m='476160'>isn't</span> <span m='476650'>square?</span>
  <span m='477850'>What</span> <span m='478000'>if</span> <span m='478120'>A</span>
  <span m='478420'>is</span> <span m='478570'>in</span> <span m='479710'>the</span>
  <span m='479830'>space</span> <span m='480190'>of</span> <span m='480760'>real</span>
  <span m='481270'>matrices</span> <span m='481990'>that</span> <span m='482140'>are</span>
  <span m='482260'>n</span> <span m='482470'>by</span> <span m='482740'>m,</span>
  <span m='483010'>where</span> <span m='483240'>n and</span> <span m='483400'>m</span>
  <span m='483670'>maybe</span> <span m='484000'>aren't</span> <span m='484180'>the</span>
  <span m='484300'>same?</span> <span m='484630'>Maybe</span> <span m='484810'>they</span>
  <span m='484900'>are</span> <span m='485020'>the</span> <span m='485140'>same,</span>
  <span m='485410'>but</span> <span m='485500'>maybe</span> <span m='485710'>they're</span>
  <span m='485830'>not.</span> <span m='486910'>And</span> <span m='487060'>there</span>
  <span m='487110'>is</span> <span m='487240'>an</span> <span m='487330'>equivalent</span>
  <span m='488170'>decomposition.</span> <span m='490060'>It's</span> <span m='490210'>called</span>
  <span m='490360'>the</span> <span m='490420'>singular</span> <span m='490810'>value</span>
  <span m='491110'>decomposition.</span> <span m='491920'>It's</span> <span m='492070'>like</span>
  <span m='492400'>an</span> <span m='492520'>eigendecomposition</span> <span m='494110'>for</span>
  <span m='494260'>non-square</span> <span m='494710'>matrices.</span> </p><p><span
  m='496850'>So</span> <span m='496970'>rather</span> <span m='497240'>than</span>
  <span m='497360'>writing</span> <span m='497660'>our</span> <span m='497780'>matrix</span>
  <span m='498320'>as</span> <span m='498620'>some</span> <span m='499370'>w</span>
  <span m='500120'>lambda</span> <span m='500660'>w</span> <span m='501150'>inverse,</span>
  <span m='502690'>we're</span> <span m='502790'>going</span> <span m='502910'>to</span>
  <span m='502970'>write</span> <span m='503240'>it</span> <span m='503390'>as</span>
  <span m='503720'>some</span> <span m='504020'>product</span> <span m='504720'>U</span>
  <span m='505660'>times</span> <span m='505910'>sigma</span> <span m='506780'>times</span>
  <span m='507140'>V</span> <span m='507890'>with</span> <span m='508010'>this</span>
  <span m='508220'>dagger.</span> <span m='509490'>The</span> <span m='509590'>dagger</span>
  <span m='509870'>here</span> <span m='510230'>is</span> <span m='510440'>conjugate</span>
  <span m='511250'>transpose.</span> <span m='511940'>Transpose</span> <span m='512450'>the</span>
  <span m='512510'>matrix,</span> <span m='513260'>and</span> <span m='513350'>take</span>
  <span m='513530'>the</span> <span m='513620'>complex</span> <span m='514010'>conjugate</span>
  <span m='514400'>of</span> <span m='514520'>all</span> <span m='514640'>the</span>
  <span m='514789'>elements,</span> <span m='515210'>OK?</span> <span m='516382'>I</span>
  <span m='516820'>mentioned</span> <span m='517140'>last</span> <span m='517380'>time</span>
  <span m='517650'>that</span> <span m='517799'>eigenvalues</span> <span m='518700'>and</span>
  <span m='518940'>eigenvectors</span> <span m='519630'>could</span> <span m='519809'>be</span>
  <span m='520080'>complex,</span> <span m='520919'>potentially,</span> <span m='521760'>right?</span>
  <span m='522820'>So</span> <span m='523110'>whenever</span> <span m='523409'>we</span>
  <span m='523530'>have</span> <span m='523679'>that</span> <span m='523830'>case</span>
  <span m='524100'>where</span> <span m='524220'>things</span> <span m='524580'>can</span>
  <span m='524700'>be</span> <span m='524820'>complex,</span> <span m='525960'>usually</span>
  <span m='526440'>the</span> <span m='526560'>transposition</span> <span m='527220'>operation</span>
  <span m='527510'>is</span> <span m='527800'>replaced</span> <span m='528270'>with</span>
  <span m='528420'>the</span> <span m='528510'>conjugate</span> <span m='528880'>transpose.</span>
  </p><p><span m='532350'>What</span> <span m='532530'>are</span> <span m='532770'>these</span>
  <span m='533100'>different</span> <span m='533370'>matrices.</span> <span m='533640'>Well,</span>
  <span m='533910'>let</span> <span m='534060'>me</span> <span m='534150'>tell</span>
  <span m='534360'>you.</span> <span m='535620'>U</span> <span m='536440'>is</span>
  <span m='536580'>a</span> <span m='536640'>complex</span> <span m='537060'>matrix.</span>
  <span m='538140'>It</span> <span m='538370'>maps</span> <span m='538760'>from</span>
  <span m='538950'>the</span> <span m='539040'>space</span> <span m='539790'>N</span>
  <span m='540050'>to</span> <span m='540140'>R</span> <span m='540330'>N</span> <span
  m='540800'>to</span> <span m='541050'>R</span> <span m='541290'>N,</span> <span
  m='541530'>so</span> <span m='541710'>it's</span> <span m='541830'>an</span> <span
  m='541950'>n</span> <span m='542130'>by</span> <span m='542400'>n</span> <span m='542620'>square</span>
  <span m='543060'>matrix.</span> <span m='544350'>Sigma</span> <span m='545350'>is</span>
  <span m='545490'>a</span> <span m='545550'>real</span> <span m='545850'>valued</span>
  <span m='546180'>matrix,</span> <span m='547860'>and</span> <span m='547970'>it</span>
  <span m='548040'>lives</span> <span m='548310'>in</span> <span m='548400'>the</span>
  <span m='548490'>space</span> <span m='548820'>of</span> <span m='549030'>n</span>
  <span m='549240'>by</span> <span m='549450'>n</span> <span m='549600'>matrices.</span>
  </p><p><span m='550830'>V</span> <span m='552030'>is</span> <span m='552180'>a</span>
  <span m='552240'>square</span> <span m='552510'>matrix</span> <span m='552870'>again,</span>
  <span m='553940'>but</span> <span m='554070'>it</span> <span m='554130'>has</span>
  <span m='554310'>dimensions</span> <span m='554790'>m</span> <span m='554970'>by</span>
  <span m='555220'>m.</span> <span m='556520'>Remember,</span> <span m='557100'>A</span>
  <span m='557400'>maps</span> <span m='557790'>from</span> <span m='558350'>R</span>
  <span m='558680'>M</span> <span m='558990'>to</span> <span m='559140'>R</span> <span
  m='559440'>N,</span> <span m='559770'>so</span> <span m='559920'>that's</span> <span
  m='560160'>what</span> <span m='560340'>the</span> <span m='560460'>sequence</span>
  <span m='560970'>of</span> <span m='561060'>products</span> <span m='561420'>says.</span>
  <span m='562110'>B</span> <span m='562350'>maps</span> <span m='562650'>from</span>
  <span m='562800'>m</span> <span m='563010'>to</span> <span m='563160'>m.</span>
  <span m='563820'>Sigma</span> <span m='565500'>maps</span> <span m='565800'>from</span>
  <span m='565980'>m</span> <span m='566250'>to</span> <span m='566400'>n.</span>
  <span m='567320'>U maps</span> <span m='567750'>from</span> <span m='567930'>n</span>
  <span m='568200'>to</span> <span m='568350'>n.</span> <span m='568720'>So</span>
  <span m='568770'>this</span> <span m='568950'>match</span> <span m='569220'>from</span>
  <span m='570120'>m</span> <span m='570210'>to</span> <span m='570360'>n</span> <span
  m='570840'>as</span> <span m='571020'>well.</span> </p><p><span m='574060'>Sigma</span>
  <span m='574570'>is</span> <span m='574840'>like</span> <span m='575060'>lambda</span>
  <span m='575760'>from</span> <span m='575950'>before.</span> <span m='576760'>It's</span>
  <span m='576940'>a</span> <span m='577000'>diagonal</span> <span m='577390'>matrix.</span>
  <span m='578660'>It</span> <span m='578890'>only</span> <span m='579160'>has</span>
  <span m='579370'>diagonal</span> <span m='579675'>elements.</span> <span m='580040'>It's</span>
  <span m='580210'>just</span> <span m='580290'>not</span> <span m='580450'>square,</span>
  <span m='580840'>but</span> <span m='580930'>it</span> <span m='581020'>only</span>
  <span m='581260'>has</span> <span m='581490'>diagonal</span> <span m='581960'>elements,</span>
  <span m='584190'>all</span> <span m='584400'>of</span> <span m='584490'>which</span>
  <span m='584670'>will</span> <span m='584790'>be</span> <span m='584910'>positive.</span>
  <span m='588100'>And</span> <span m='588190'>then</span> <span m='588430'>U</span>
  <span m='588670'>and</span> <span m='588880'>V</span> <span m='589750'>are</span>
  <span m='589840'>called</span> <span m='590080'>the</span> <span m='590230'>left</span>
  <span m='590740'>and</span> <span m='590950'>right</span> <span m='591220'>singular</span>
  <span m='591730'>vectors.</span> <span m='592310'>And</span> <span m='592420'>they</span>
  <span m='592480'>have</span> <span m='592570'>special</span> <span m='592960'>properties</span>
  <span m='593410'>associated</span> <span m='593980'>with</span> <span m='594160'>them,</span>
  <span m='594310'>which</span> <span m='594460'>I'll show</span> <span m='594550'>you
  right</span> <span m='594985'>now.</span> </p><p><span m='596290'>Any</span> <span
  m='596550'>questions</span> <span m='596930'>about</span> <span m='597110'>how</span>
  <span m='598280'>this</span> <span m='598760'>decomposition</span> <span m='599600'>is</span>
  <span m='600650'>composed</span> <span m='601250'>or</span> <span m='601340'>made</span>
  <span m='601610'>up?</span> <span m='602690'>It</span> <span m='602780'>looks</span>
  <span m='603170'>just</span> <span m='603440'>like the</span> <span m='603680'>eigendecomposition,</span>
  <span m='604790'>but</span> <span m='604910'>it</span> <span m='604970'>can</span>
  <span m='605060'>be</span> <span m='605150'>applied</span> <span m='605450'>to</span>
  <span m='605540'>any</span> <span m='605750'>matrix.</span> <span m='606360'>Yes?</span>
  </p><p><span m='606660'>AUDIENCE:</span> <span m='606868'>Quick</span> <span m='607076'>question.</span>
  </p><p><span m='607910'>JAMES W. SWAN:</span> <span m='608040'>Sure.</span> </p><p><span
  m='608170'>AUDIENCE:</span> <span m='608328'>Do</span> <span m='608486'>all matrices</span>
  <span m='608644'>have this</span> <span m='609118'>thing, or</span> <span m='609592'>is
  it</span> <span m='610066'>like the</span> <span m='610540'>eigenvalues</span> <span
  m='611014'>where</span> <span m='611488'>some do</span> <span m='611962'>and some
  don't.</span> </p><p><span m='612440'>JAMES W. SWAN:</span> <span m='612483'>This</span>
  <span m='612526'>is</span> <span m='612570'>a</span> <span m='612620'>great</span>
  <span m='612800'>question.</span> <span m='613170'>So</span> <span m='613190'>all</span>
  <span m='613340'>matrices</span> <span m='613880'>are</span> <span m='613940'>going</span>
  <span m='614060'>to</span> <span m='614120'>have</span> <span m='614210'>a</span>
  <span m='614240'>singular</span> <span m='614600'>value</span> <span m='614840'>decomposition.</span>
  <span m='616710'>We</span> <span m='616870'>saw</span> <span m='617010'>with</span>
  <span m='617070'>the</span> <span m='617180'>eigenvalue</span> <span m='617690'>decomposition</span>
  <span m='618410'>that</span> <span m='619240'>there</span> <span m='619400'>could</span>
  <span m='619550'>be</span> <span m='619670'>a</span> <span m='619730'>case</span>
  <span m='620330'>where</span> <span m='621170'>the</span> <span m='621440'>eigenvectors</span>
  <span m='622340'>are</span> <span m='622520'>degenerate,</span> <span m='623390'>and</span>
  <span m='623510'>we</span> <span m='623570'>can't</span> <span m='623810'>write</span>
  <span m='624050'>that</span> <span m='624230'>full</span> <span m='624480'>decomposition.</span>
  <span m='625190'>All</span> <span m='625370'>matrices</span> <span m='625970'>are</span>
  <span m='626060'>going</span> <span m='626240'>to</span> <span m='626330'>have</span>
  <span m='626510'>this</span> <span m='627020'>decomposition.</span> </p><p><span
  m='634380'>So</span> <span m='634540'>for</span> <span m='634720'>some</span> <span
  m='634880'>properties</span> <span m='636530'>of</span> <span m='636650'>this</span>
  <span m='636800'>decomposition,</span> <span m='641690'>U and</span> <span m='642020'>V</span>
  <span m='642470'>are</span> <span m='642560'>what</span> <span m='642680'>we</span>
  <span m='642770'>call</span> <span m='643020'>unitary</span> <span m='643670'>matrices.</span>
  <span m='644330'>I</span> <span m='644450'>talked</span> <span m='644660'>about</span>
  <span m='644810'>these</span> <span m='645020'>before.</span> <span m='645850'>Unitary</span>
  <span m='646340'>matrices</span> <span m='646850'>are</span> <span m='646940'>ones</span>
  <span m='647330'>for</span> <span m='647480'>whom,</span> <span m='648350'>if</span>
  <span m='648500'>they're</span> <span m='648620'>real</span> <span m='648950'>valued,</span>
  <span m='649430'>their</span> <span m='649580'>transpose</span> <span m='650480'>is</span>
  <span m='650660'>also</span> <span m='650930'>their</span> <span m='651080'>inverse.</span>
  </p><p><span m='651830'>If</span> <span m='651950'>they're</span> <span m='652040'>complex</span>
  <span m='652550'>valued,</span> <span m='653450'>and</span> <span m='653570'>they're</span>
  <span m='654490'>conjugate</span> <span m='654830'>transpose</span> <span m='655940'>is</span>
  <span m='656480'>the</span> <span m='656630'>equivalent</span> <span m='657080'>of
  their</span> <span m='657170'>inverse.</span> <span m='657620'>So</span> <span m='657920'>U</span>
  <span m='658760'>times</span> <span m='659000'>U</span> <span m='659270'>conjugate</span>
  <span m='659720'>transpose</span> <span m='660500'>will</span> <span m='660650'>be</span>
  <span m='660800'>identity.</span> <span m='661930'>V</span> <span m='662580'>times</span>
  <span m='662965'>V</span> <span m='663350'>conjugate</span> <span m='663740'>transpose</span>
  <span m='664370'>will</span> <span m='664490'>be</span> <span m='664640'>identity.</span>
  </p><p><span m='665800'>Unitary</span> <span m='666290'>matrices</span> <span m='666830'>also</span>
  <span m='667250'>have</span> <span m='667760'>the</span> <span m='667940'>property</span>
  <span m='668510'>that</span> <span m='668660'>they</span> <span m='668810'>impart</span>
  <span m='669260'>no</span> <span m='669980'>stretch</span> <span m='670790'>to</span>
  <span m='670940'>a</span> <span m='671000'>matrix--</span> <span m='672400'>or</span>
  <span m='672980'>to</span> <span m='673130'>vectors.</span> <span m='673820'>So</span>
  <span m='673880'>their</span> <span m='674060'>maps</span> <span m='674990'>don't</span>
  <span m='675290'>stretch.</span> <span m='676460'>They're</span> <span m='676580'>kind</span>
  <span m='676760'>of</span> <span m='676850'>like</span> <span m='677030'>rotational</span>
  <span m='677960'>matrices,</span> <span m='678670'>right?</span> <span m='679250'>They</span>
  <span m='679340'>change</span> <span m='679640'>directions,</span> <span m='680240'>but</span>
  <span m='680360'>they</span> <span m='680450'>don't</span> <span m='680630'>stretch</span>
  <span m='681050'>things</span> <span m='681350'>out.</span> </p><p><span m='685190'>If</span>
  <span m='685370'>I</span> <span m='685460'>were</span> <span m='685550'>to</span>
  <span m='685670'>take</span> <span m='687260'>A</span> <span m='687860'>conjugate</span>
  <span m='688220'>transpose</span> <span m='688730'>and</span> <span m='688820'>multiply</span>
  <span m='689310'>it</span> <span m='689350'>by</span> <span m='689630'>A,</span>
  <span m='690890'>that</span> <span m='690980'>would</span> <span m='691070'>be</span>
  <span m='691190'>the</span> <span m='691310'>same</span> <span m='691720'>as</span>
  <span m='691930'>taking</span> <span m='693140'>U</span> <span m='693770'>sigma</span>
  <span m='694670'>V</span> <span m='695600'>conjugate</span> <span m='695960'>transpose,</span>
  <span m='696680'>and</span> <span m='696800'>multiplying</span> <span m='697230'>it</span>
  <span m='697310'>by</span> <span m='697460'>U</span> <span m='697640'>sigma</span>
  <span m='698000'>V.</span> <span m='698350'>If I</span> <span m='698780'>use</span>
  <span m='699020'>the</span> <span m='699110'>properties</span> <span m='700550'>of</span>
  <span m='701690'>matrix</span> <span m='702120'>multiplications</span> <span m='703010'>and</span>
  <span m='703250'>complex</span> <span m='703910'>conjugate</span> <span m='704450'>transposes,</span>
  <span m='706340'>and</span> <span m='706520'>work</span> <span m='706820'>out</span>
  <span m='707600'>what</span> <span m='707750'>this</span> <span m='707930'>expression</span>
  <span m='708380'>is,</span> <span m='708500'>I'll</span> <span m='708590'>find</span>
  <span m='708830'>out</span> <span m='708950'>that</span> <span m='709070'>it's</span>
  <span m='709250'>equivalent</span> <span m='709550'>to</span> <span m='709970'>V</span>
  <span m='711050'>sigma</span> <span m='711920'>conjugate</span> <span m='712280'>transpose</span>
  <span m='712970'>sigma</span> <span m='714230'>V</span> <span m='714650'>conjugate</span>
  <span m='715070'>transpose.</span> </p><p><span m='716660'>Well</span> <span m='716810'>this</span>
  <span m='718220'>has</span> <span m='718400'>exactly</span> <span m='718970'>the</span>
  <span m='719120'>same</span> <span m='719390'>form</span> <span m='720850'>as</span>
  <span m='721070'>an</span> <span m='721190'>eigendecomposition.</span> <span m='723050'>An</span>
  <span m='723170'>eigendecomposition</span> <span m='724400'>of</span> <span m='725210'>A</span>
  <span m='725370'>times</span> <span m='725820'>A</span> <span m='727100'>instead</span>
  <span m='727400'>of</span> <span m='727460'>an</span> <span m='727540'>eigendecomposition</span>
  <span m='728540'>of</span> <span m='728660'>A.</span> <span m='729710'>So</span>
  <span m='729970'>V</span> <span m='731600'>is</span> <span m='731720'>the</span>
  <span m='731810'>set</span> <span m='732020'>of</span> <span m='732170'>eigenvectors</span>
  <span m='733220'>of</span> <span m='733520'>A</span> <span m='733850'>conjugate</span>
  <span m='734240'>transpose</span> <span m='734900'>A,</span> <span m='736160'>and</span>
  <span m='736610'>sigma</span> <span m='737090'>squared</span> <span m='738590'>are</span>
  <span m='738680'>the</span> <span m='738830'>eigenvalues</span> <span m='739700'>of</span>
  <span m='739910'>A</span> <span m='741050'>conjugate</span> <span m='741410'>transpose</span>
  <span m='741860'>times</span> <span m='742110'>A.</span> </p><p><span m='744260'>And</span>
  <span m='744620'>if</span> <span m='744770'>I</span> <span m='744830'>reverse</span>
  <span m='745220'>the</span> <span m='745310'>order</span> <span m='745550'>of</span>
  <span m='745610'>this</span> <span m='745790'>multiplication--</span> <span m='746610'>so</span>
  <span m='746630'>I</span> <span m='746690'>do</span> <span m='747020'>A</span> <span
  m='747513'>times</span> <span m='748006'>A</span> <span m='748500'>conjugate</span>
  <span m='748700'>transpose--</span> <span m='749360'>and</span> <span m='749450'>work</span>
  <span m='749690'>it</span> <span m='749750'>out,</span> <span m='750530'>that</span>
  <span m='750610'>would</span> <span m='750710'>be</span> <span m='750860'>U</span>
  <span m='751270'>sigma</span> <span m='751640'>sigma</span> <span m='752030'>U.</span>
  <span m='753040'>And</span> <span m='753140'>so</span> <span m='753380'>U</span>
  <span m='754010'>are</span> <span m='754130'>the</span> <span m='754280'>eigenvectors</span>
  <span m='754940'>of</span> <span m='755150'>A</span> <span m='756110'>A</span> <span
  m='756590'>conjugate</span> <span m='756950'>transpose,</span> <span m='758060'>and</span>
  <span m='758210'>sigma</span> <span m='758600'>squared</span> <span m='759380'>are</span>
  <span m='759470'>still</span> <span m='759890'>the</span> <span m='760040'>eigenvalues</span>
  <span m='760790'>of</span> <span m='761020'>A</span> <span m='761505'>A</span> <span
  m='761990'>conjugate</span> <span m='762320'>transpose.</span> <span m='765070'>So</span>
  <span m='765220'>what</span> <span m='765340'>are</span> <span m='765430'>these</span>
  <span m='765610'>things</span> <span m='765820'>U</span> <span m='766010'>and</span>
  <span m='766240'>V?</span> <span m='767830'>They</span> <span m='767950'>relate</span>
  <span m='768250'>to</span> <span m='768370'>the</span> <span m='768520'>eigenvectors</span>
  <span m='770200'>of</span> <span m='771280'>the</span> <span m='771370'>product</span>
  <span m='771690'>of</span> <span m='771830'>A</span> <span m='771950'>with</span>
  <span m='772120'>itself,</span> <span m='773290'>this</span> <span m='773440'>particular</span>
  <span m='773980'>product</span> <span m='774320'>of</span> <span m='774410'>A</span>
  <span m='774550'>with</span> <span m='774670'>itself,</span> <span m='774820'>or</span>
  <span m='775060'>this</span> <span m='775330'>particular</span> <span m='775780'>product</span>
  <span m='776110'>of</span> <span m='776200'>A</span> <span m='776340'>with</span>
  <span m='776500'>itself.</span> </p><p><span m='778480'>Sigma</span> <span m='778810'>are</span>
  <span m='778930'>the</span> <span m='779060'>singular</span> <span m='779470'>values.</span>
  <span m='781310'>And</span> <span m='781400'>all</span> <span m='781520'>matrices</span>
  <span m='782060'>possess</span> <span m='782480'>this</span> <span m='782600'>sort</span>
  <span m='782810'>of a</span> <span m='782940'>decomposition.</span> <span m='783750'>They</span>
  <span m='783770'>all</span> <span m='783920'>have</span> <span m='784070'>a</span>
  <span m='784130'>set</span> <span m='784280'>of</span> <span m='784370'>singular</span>
  <span m='784700'>values</span> <span m='785040'>and</span> <span m='785120'>singular</span>
  <span m='785540'>vectors.</span> <span m='786530'>These</span> <span m='786680'>sigmas</span>
  <span m='787400'>are</span> <span m='787530'>called</span> <span m='787700'>the</span>
  <span m='787790'>singular</span> <span m='788120'>values</span> <span m='788630'>of
  the</span> <span m='788870'>A.</span> <span m='789140'>They</span> <span m='789380'>have
  a</span> <span m='789410'>particular</span> <span m='789830'>name.</span> <span
  m='790160'>I'm going</span> <span m='790465'>to show you</span> <span m='790770'>how
  you</span> <span m='790870'>can</span> <span m='790970'>use</span> <span m='791270'>this</span>
  <span m='791460'>decomposition</span> <span m='792110'>to</span> <span m='792200'>do</span>
  <span m='792350'>something</span> <span m='793250'>you</span> <span m='793310'>already</span>
  <span m='793520'>know</span> <span m='793670'>how</span> <span m='793760'>to</span>
  <span m='793850'>do,</span> <span m='794000'>but</span> <span m='794120'>how</span>
  <span m='794210'>to</span> <span m='794330'>do</span> <span m='794520'>it</span>
  <span m='794620'>formally.</span> </p><p><span m='798200'>What</span> <span m='798290'>are</span>
  <span m='798350'>some</span> <span m='798470'>properties</span> <span m='799920'>of</span>
  <span m='800000'>the</span> <span m='800060'>singular</span> <span m='800360'>value</span>
  <span m='800600'>decomposition?</span> <span m='804810'>So</span> <span m='804900'>if</span>
  <span m='804960'>we</span> <span m='805050'>take</span> <span m='805230'>a</span>
  <span m='805270'>matrix</span> <span m='805690'>A</span> <span m='806280'>and</span>
  <span m='806370'>we</span> <span m='806430'>compute</span> <span m='806790'>it's</span>
  <span m='806850'>singular</span> <span m='807240'>value</span> <span m='807510'>decomposition,</span>
  <span m='808320'>this</span> <span m='808530'>is</span> <span m='808650'>how</span>
  <span m='808740'>you</span> <span m='808830'>do</span> <span m='808980'>it</span>
  <span m='809070'>in</span> <span m='809200'>Matlab.</span> <span m='813030'>We'll</span>
  <span m='813120'>find</span> <span m='813360'>out,</span> <span m='813720'>for</span>
  <span m='813840'>this</span> <span m='814050'>matrix,</span> <span m='814530'>U</span>
  <span m='815280'>is</span> <span m='815430'>identity.</span> <span m='816560'>Sigma</span>
  <span m='817080'>is</span> <span m='817380'>identity</span> <span m='817890'>with</span>
  <span m='818040'>an</span> <span m='818130'>extra</span> <span m='818400'>column</span>
  <span m='818910'>pasted</span> <span m='819360'>on</span> <span m='819540'>it.</span>
  <span m='819720'>And</span> <span m='819870'>B</span> <span m='820110'>is</span>
  <span m='820230'>also</span> <span m='820540'>identity.</span> <span m='820920'>I
  mean,</span> <span m='821000'>this</span> <span m='821190'>is</span> <span m='821280'>the</span>
  <span m='821370'>simplest</span> <span m='821850'>possible</span> <span m='823080'>four</span>
  <span m='823320'>by</span> <span m='823470'>three</span> <span m='823680'>matrix</span>
  <span m='824130'>I</span> <span m='824190'>can</span> <span m='824340'>write</span>
  <span m='824520'>down.</span> </p><p><span m='826060'>You don't</span> <span m='826250'>have</span>
  <span m='826340'>to</span> <span m='826440'>know</span> <span m='826620'>how</span>
  <span m='826830'>to</span> <span m='826920'>compute</span> <span m='827220'>the</span>
  <span m='827280'>singular</span> <span m='827610'>value</span> <span m='827850'>decomposition,</span>
  <span m='829200'>you</span> <span m='829290'>just</span> <span m='829400'>need</span>
  <span m='829560'>to</span> <span m='829680'>know</span> <span m='829950'>that</span>
  <span m='830100'>it</span> <span m='830160'>can</span> <span m='830280'>be</span>
  <span m='830340'>computed</span> <span m='830790'>in this</span> <span m='831105'>way.</span>
  <span m='831420'>You</span> <span m='831480'>might</span> <span m='831600'>be</span>
  <span m='831690'>able</span> <span m='831810'>to</span> <span m='831900'>guess</span>
  <span m='832170'>how</span> <span m='832260'>to</span> <span m='832350'>compute</span>
  <span m='832670'>it</span> <span m='833160'>based</span> <span m='833410'>on</span>
  <span m='833490'>what</span> <span m='833580'>we</span> <span m='833730'>did</span>
  <span m='833820'>with</span> <span m='833970'>eigenvalues</span> <span m='834660'>earlier</span>
  <span m='834955'>and</span> <span m='835250'>eigenvectors.</span> <span m='837240'>It'll</span>
  <span m='837390'>turn</span> <span m='837570'>out</span> <span m='837720'>some</span>
  <span m='838050'>of</span> <span m='838140'>the</span> <span m='838230'>columns</span>
  <span m='838650'>of</span> <span m='838740'>sigma</span> <span m='839670'>will</span>
  <span m='839790'>be</span> <span m='839910'>non-zero</span> <span m='840770'>right?</span>
  <span m='840950'>There</span> <span m='841110'>are</span> <span m='841170'>three</span>
  <span m='841470'>non-zero</span> <span m='842010'>columns</span> <span m='842400'>of</span>
  <span m='842490'>sigma.</span> <span m='844390'>And</span> <span m='844510'>the</span>
  <span m='844600'>columns</span> <span m='845050'>of</span> <span m='845210'>V,</span>
  <span m='846850'>they</span> <span m='846970'>correspond</span> <span m='847780'>to</span>
  <span m='847930'>those</span> <span m='848110'>columns</span> <span m='848560'>of</span>
  <span m='848650'>sigma,</span> <span m='850360'>spanned</span> <span m='850870'>the</span>
  <span m='850990'>null</span> <span m='851310'>space</span> <span m='851800'>of</span>
  <span m='851890'>the</span> <span m='851980'>matrix</span> <span m='852400'>A.</span>
  </p><p><span m='856620'>So</span> <span m='856740'>the</span> <span m='856830'>first</span>
  <span m='857040'>three</span> <span m='857250'>columns</span> <span m='857670'>here</span>
  <span m='859050'>are</span> <span m='859170'>non-zero,</span> <span m='860220'>the</span>
  <span m='860310'>first</span> <span m='860550'>three</span> <span m='860760'>columns</span>
  <span m='861150'>of</span> <span m='861280'>V.</span> <span m='864200'>I'm sorry,</span>
  <span m='864650'>the</span> <span m='864770'>first</span> <span m='864950'>three</span>
  <span m='865040'>columns here</span> <span m='865360'>are</span> <span m='865460'>non-zero.</span>
  <span m='865970'>The</span> <span m='866060'>last</span> <span m='866330'>column</span>
  <span m='866660'>is</span> <span m='866750'>0.</span> </p><p><span m='867590'>The</span>
  <span m='867680'>columns</span> <span m='868040'>of</span> <span m='868100'>sigma</span>
  <span m='868400'>which</span> <span m='868580'>are</span> <span m='868700'>0</span>
  <span m='870050'>correspond</span> <span m='870440'>to</span> <span m='870540'>a</span>
  <span m='870590'>particular</span> <span m='871010'>column</span> <span m='871460'>in</span>
  <span m='871690'>V,</span> <span m='872130'>this</span> <span m='872360'>last</span>
  <span m='872630'>column</span> <span m='872930'>here,</span> <span m='873710'>which</span>
  <span m='873920'>lives</span> <span m='874190'>in</span> <span m='874310'>the</span>
  <span m='874430'>null</span> <span m='874840'>space</span> <span m='875240'>of</span>
  <span m='875450'>A.</span> <span m='875840'>So</span> <span m='875960'>you</span>
  <span m='876020'>can</span> <span m='876110'>see,</span> <span m='876230'>if</span>
  <span m='876320'>I</span> <span m='876380'>take</span> <span m='876710'>A and</span>
  <span m='877070'>I</span> <span m='877160'>multiply</span> <span m='877510'>it</span>
  <span m='877600'>by</span> <span m='877790'>any</span> <span m='878000'>vector</span>
  <span m='879110'>that's</span> <span m='879260'>proportional</span> <span m='879830'>to</span>
  <span m='879980'>0, 0,</span> <span m='880480'>0, 1,</span> <span m='881970'>I'll</span>
  <span m='882070'>get</span> <span m='882140'>back</span> <span m='882380'>0.</span>
  <span m='883340'>So</span> <span m='883520'>the</span> <span m='883640'>null</span>
  <span m='884050'>space</span> <span m='884330'>of</span> <span m='884590'>A</span>
  <span m='885830'>is</span> <span m='885920'>spanned</span> <span m='886640'>by</span>
  <span m='886820'>all</span> <span m='887090'>these</span> <span m='887330'>vectors</span>
  <span m='887780'>corresponding</span> <span m='888260'>to</span> <span m='888380'>the</span>
  <span m='888530'>0</span> <span m='888840'>columns</span> <span m='889370'>of</span>
  <span m='889510'>sigma.</span> </p><p><span m='892980'>Some</span> <span m='893160'>of</span>
  <span m='893220'>the</span> <span m='893310'>columns</span> <span m='893580'>of</span>
  <span m='893650'>sigma are</span> <span m='893970'>non-zero.</span> <span m='894840'>These</span>
  <span m='894990'>first</span> <span m='895230'>three</span> <span m='895410'>columns.</span>
  <span m='895890'>And</span> <span m='896040'>the</span> <span m='896190'>rows</span>
  <span m='896970'>of</span> <span m='897120'>U</span> <span m='899040'>corresponding</span>
  <span m='899720'>to</span> <span m='899850'>those</span> <span m='900090'>three</span>
  <span m='900270'>columns</span> <span m='902000'>span</span> <span m='902360'>the</span>
  <span m='902480'>range</span> <span m='902840'>of</span> <span m='902960'>A.</span>
  <span m='903410'>So</span> <span m='903530'>if</span> <span m='903620'>I</span>
  <span m='903680'>do</span> <span m='903830'>the</span> <span m='903950'>singular</span>
  <span m='904310'>value</span> <span m='904550'>decomposition</span> <span m='905240'>of</span>
  <span m='905330'>a</span> <span m='905390'>matrix,</span> <span m='906500'>and</span>
  <span m='906620'>I</span> <span m='906740'>look</span> <span m='907040'>at</span>
  <span m='907880'>U, V,</span> <span m='908360'>and</span> <span m='908510'>sigma</span>
  <span m='909410'>and</span> <span m='909530'>what</span> <span m='909710'>they're</span>
  <span m='909830'>composed</span> <span m='910460'>of--</span> <span m='911060'>where</span>
  <span m='911240'>sigma is</span> <span m='911600'>0</span> <span m='912110'>and</span>
  <span m='912200'>non-zero,</span> <span m='913010'>and</span> <span m='913130'>the</span>
  <span m='913220'>corresponding</span> <span m='913970'>columns</span> <span m='915050'>or</span>
  <span m='915200'>rows</span> <span m='915710'>of</span> <span m='915830'>U</span>
  <span m='916050'>and</span> <span m='916160'>V--</span> <span m='916430'>then</span>
  <span m='916580'>I</span> <span m='916670'>can</span> <span m='916850'>figure</span>
  <span m='917120'>out</span> <span m='917330'>what</span> <span m='917540'>vectors</span>
  <span m='917930'>span</span> <span m='919040'>the</span> <span m='919160'>range</span>
  <span m='919550'>and</span> <span m='919640'>null</span> <span m='919880'>space</span>
  <span m='920390'>of</span> <span m='920480'>the</span> <span m='920570'>matrix</span>
  <span m='920900'>A.</span> </p><p><span m='925110'>Here's</span> <span m='925290'>another</span>
  <span m='925560'>example.</span> <span m='926710'>So</span> <span m='926770'>here</span>
  <span m='926890'>I</span> <span m='927000'>have</span> <span m='927210'>A.</span>
  <span m='927900'>Now</span> <span m='928040'>instead of</span> <span m='928260'>being</span>
  <span m='929130'>three</span> <span m='929480'>rows</span> <span m='929850'>by</span>
  <span m='930000'>four</span> <span m='930240'>columns,</span> <span m='930640'>it's</span>
  <span m='930750'>four</span> <span m='931020'>rows</span> <span m='931320'>by</span>
  <span m='931500'>three</span> <span m='931770'>columns.</span> <span m='932850'>And</span>
  <span m='932970'>here's</span> <span m='933210'>the</span> <span m='933300'>singular</span>
  <span m='933660'>value</span> <span m='933930'>decomposition</span> <span m='934660'>that</span>
  <span m='934740'>comes</span> <span m='934980'>out</span> <span m='935080'>of</span>
  <span m='935170'>Matlab.</span> </p><p><span m='937140'>There</span> <span m='937290'>are</span>
  <span m='937350'>no</span> <span m='937560'>vectors</span> <span m='939090'>that</span>
  <span m='939210'>live</span> <span m='939390'>in</span> <span m='939480'>the</span>
  <span m='939570'>null</span> <span m='939840'>space</span> <span m='940260'>of</span>
  <span m='940410'>A,</span> <span m='941580'>and</span> <span m='941700'>there</span>
  <span m='941880'>are</span> <span m='941910'>no</span> <span m='942300'>0</span>
  <span m='942690'>columns</span> <span m='943140'>in</span> <span m='943260'>sigma.</span>
  <span m='944160'>There's</span> <span m='944280'>no</span> <span m='944430'>corresponding</span>
  <span m='945030'>columns</span> <span m='945450'>in</span> <span m='945600'>V.</span>
  <span m='946975'>There</span> <span m='947280'>are no</span> <span m='947610'>vectors</span>
  <span m='947970'>in</span> <span m='948060'>the</span> <span m='948150'>null</span>
  <span m='948330'>space</span> <span m='948810'>of A.</span> </p><p><span m='950920'>The</span>
  <span m='951040'>range</span> <span m='951370'>of</span> <span m='951490'>A</span>
  <span m='952540'>is</span> <span m='952630'>spanned</span> <span m='953260'>by</span>
  <span m='953410'>the</span> <span m='953560'>rows</span> <span m='954940'>corresponding</span>
  <span m='955480'>to</span> <span m='955600'>the</span> <span m='955760'>non-zero--</span>
  <span m='956225'>the</span> <span m='956690'>rows</span> <span m='957070'>of</span>
  <span m='957220'>U</span> <span m='957940'>corresponding</span> <span m='958420'>to</span>
  <span m='958510'>the</span> <span m='958630'>non-zero</span> <span m='959110'>columns</span>
  <span m='959470'>of</span> <span m='959560'>sigma.</span> <span m='959950'>So</span>
  <span m='960410'>it's</span> <span m='960510'>these</span> <span m='960580'>three</span>
  <span m='960790'>columns</span> <span m='961180'>in</span> <span m='961270'>the</span>
  <span m='961360'>first</span> <span m='961600'>three</span> <span m='961840'>rows.</span>
  <span m='962890'>And</span> <span m='962980'>these</span> <span m='963250'>first</span>
  <span m='963520'>three</span> <span m='963790'>rows,</span> <span m='964390'>clearly</span>
  <span m='964780'>they</span> <span m='964960'>span--</span> <span m='967000'>they</span>
  <span m='967150'>describe</span> <span m='967630'>the</span> <span m='967750'>same</span>
  <span m='968710'>range</span> <span m='969850'>as</span> <span m='970060'>the</span>
  <span m='970210'>three</span> <span m='970450'>columns</span> <span m='970920'>in
  A.</span> </p><p><span m='972040'>So</span> <span m='972190'>the</span> <span m='972280'>singular</span>
  <span m='972580'>value</span> <span m='972880'>decomposition</span> <span m='973540'>gives</span>
  <span m='973750'>us</span> <span m='974890'>direct</span> <span m='975250'>access</span>
  <span m='975670'>to</span> <span m='975820'>the</span> <span m='975940'>null</span>
  <span m='976180'>space</span> <span m='977290'>and</span> <span m='977410'>the</span>
  <span m='977500'>range</span> <span m='977950'>of</span> <span m='978040'>a</span>
  <span m='978070'>matrix.</span> <span m='978810'>That's</span> <span m='978960'>handy.</span>
  <span m='981570'>And</span> <span m='981680'>it can</span> <span m='981820'>be</span>
  <span m='981880'>used</span> <span m='982240'>in</span> <span m='982330'>various</span>
  <span m='982690'>ways.</span> <span m='984170'>So</span> <span m='984190'>here's</span>
  <span m='984400'>one</span> <span m='984550'>example</span> <span m='984910'>where</span>
  <span m='985060'>it</span> <span m='985120'>can</span> <span m='985240'>be</span>
  <span m='985360'>used.</span> </p><p><span m='986140'>Here</span> <span m='986300'>I</span>
  <span m='986500'>have</span> <span m='986890'>a</span> <span m='988180'>fingerprint.</span>
  <span m='989830'>It's</span> <span m='990040'>a</span> <span m='990100'>bitmap.</span>
  <span m='991150'>It's</span> <span m='991330'>a</span> <span m='991390'>square</span>
  <span m='992260'>bit</span> <span m='992440'>of</span> <span m='992530'>data,</span>
  <span m='993070'>like</span> <span m='993250'>a</span> <span m='993310'>matrix,</span>
  <span m='994090'>and</span> <span m='994210'>each</span> <span m='994360'>of</span>
  <span m='994420'>the</span> <span m='994540'>elements</span> <span m='994840'>of</span>
  <span m='994900'>the</span> <span m='994990'>matrix</span> <span m='995350'>takes</span>
  <span m='995590'>on</span> <span m='996190'>a</span> <span m='996280'>value</span>
  <span m='996790'>describing</span> <span m='997690'>how</span> <span m='997960'>dark</span>
  <span m='998320'>or</span> <span m='998470'>light</span> <span m='998740'>that</span>
  <span m='998920'>pixel.</span> <span m='999430'>Let's</span> <span m='999580'>say</span>
  <span m='999700'>it's</span> <span m='999880'>grayscale,</span> <span m='1000870'>and</span>
  <span m='1001050'>it's</span> <span m='1001200'>value's</span> <span m='1001680'>between</span>
  <span m='1002100'>0</span> <span m='1002580'>and</span> <span m='1002730'>255.</span>
  <span m='1003840'>That's</span> <span m='1004020'>pretty</span> <span m='1004260'>typical.</span>
  </p><p><span m='1005820'>So</span> <span m='1005940'>I</span> <span m='1005970'>have</span>
  <span m='1006150'>this</span> <span m='1006330'>matrix,</span> <span m='1006870'>and</span>
  <span m='1006960'>each</span> <span m='1007590'>element</span> <span m='1007930'>to</span>
  <span m='1008010'>the</span> <span m='1008100'>matrix</span> <span m='1008490'>corresponds</span>
  <span m='1009030'>to</span> <span m='1009180'>a</span> <span m='1009210'>pixel.</span>
  <span m='1010410'>And</span> <span m='1010510'>I</span> <span m='1010590'>do</span>
  <span m='1010740'>a</span> <span m='1010770'>singular</span> <span m='1011190'>value</span>
  <span m='1011520'>decomposition.</span> <span m='1013470'>Some</span> <span m='1013680'>of</span>
  <span m='1013770'>the</span> <span m='1013860'>singular</span> <span m='1014280'>values,</span>
  <span m='1014850'>the</span> <span m='1014970'>values</span> <span m='1015300'>of</span>
  <span m='1015360'>sigma,</span> <span m='1015750'>are</span> <span m='1015870'>bigger</span>
  <span m='1016710'>than</span> <span m='1016890'>others.</span> <span m='1017760'>They're</span>
  <span m='1017880'>all</span> <span m='1018000'>positive,</span> <span m='1018760'>but</span>
  <span m='1018780'>some</span> <span m='1018990'>are</span> <span m='1019080'>bigger</span>
  <span m='1019410'>than</span> <span m='1019590'>others.</span> <span m='1020770'>The</span>
  <span m='1020820'>ones</span> <span m='1021180'>that</span> <span m='1021270'>are</span>
  <span m='1021360'>biggest</span> <span m='1021750'>in</span> <span m='1021840'>magnitude</span>
  <span m='1022440'>carry</span> <span m='1022770'>the</span> <span m='1022860'>most</span>
  <span m='1023280'>information</span> <span m='1023940'>content</span> <span m='1024780'>about</span>
  <span m='1025079'>the</span> <span m='1025170'>matrix.</span> </p><p><span m='1026770'>So</span>
  <span m='1026790'>we</span> <span m='1026880'>can</span> <span m='1027000'>do</span>
  <span m='1027089'>data</span> <span m='1027690'>compression</span> <span m='1029130'>by</span>
  <span m='1029670'>neglecting</span> <span m='1030480'>singular</span> <span m='1030900'>values</span>
  <span m='1031349'>that</span> <span m='1031470'>are</span> <span m='1031560'>smaller</span>
  <span m='1032310'>than</span> <span m='1032520'>some</span> <span m='1032819'>threshold,</span>
  <span m='1033869'>and</span> <span m='1033990'>also</span> <span m='1034349'>neglecting</span>
  <span m='1034980'>the</span> <span m='1035170'>corresponding</span> <span m='1035910'>singular</span>
  <span m='1036359'>vectors.</span> <span m='1037849'>And</span> <span m='1037950'>that's</span>
  <span m='1038069'>what</span> <span m='1038190'>I've</span> <span m='1038280'>done</span>
  <span m='1038460'>here.</span> <span m='1038730'>So</span> <span m='1038910'>here's</span>
  <span m='1039150'>the</span> <span m='1039240'>original</span> <span m='1039569'>bitmap</span>
  <span m='1040020'>of</span> <span m='1040109'>the</span> <span m='1040230'>fingerprint.</span>
  <span m='1041400'>I</span> <span m='1041490'>did</span> <span m='1041609'>the</span>
  <span m='1041700'>singular</span> <span m='1042060'>value</span> <span m='1042390'>decomposition,</span>
  <span m='1043680'>and</span> <span m='1043770'>then</span> <span m='1043890'>I</span>
  <span m='1043950'>retained</span> <span m='1044310'>only</span> <span m='1044609'>the</span>
  <span m='1044800'>50</span> <span m='1045329'>biggest</span> <span m='1046079'>singular</span>
  <span m='1046560'>values</span> <span m='1047670'>and</span> <span m='1047760'>I</span>
  <span m='1047819'>left</span> <span m='1048060'>all</span> <span m='1048180'>the</span>
  <span m='1048300'>other</span> <span m='1048480'>singular</span> <span m='1048840'>values</span>
  <span m='1049290'>out.</span> </p><p><span m='1049830'>This</span> <span m='1050220'>bitmap</span>
  <span m='1050600'>was</span> <span m='1050760'>something</span> <span m='1051240'>like,</span>
  <span m='1051960'>I</span> <span m='1052050'>don't</span> <span m='1052170'>know,</span>
  <span m='1052290'>300</span> <span m='1052680'>pixels</span> <span m='1053160'>by</span>
  <span m='1053350'>300</span> <span m='1053670'>pixels,</span> <span m='1054180'>so</span>
  <span m='1054300'>there's</span> <span m='1054450'>like</span> <span m='1055050'>300</span>
  <span m='1055620'>singular</span> <span m='1055980'>values,</span> <span m='1056590'>but</span>
  <span m='1056730'>I</span> <span m='1056820'>got</span> <span m='1057030'>rid</span>
  <span m='1057210'>of</span> <span m='1057300'>5/6</span> <span m='1057980'>of</span>
  <span m='1058080'>the</span> <span m='1058200'>information</span> <span m='1058770'>content.</span>
  <span m='1060480'>I</span> <span m='1060570'>dropped</span> <span m='1061140'>5/6</span>
  <span m='1061950'>of</span> <span m='1062070'>the</span> <span m='1062190'>singular</span>
  <span m='1062580'>vectors,</span> <span m='1063120'>and</span> <span m='1063240'>then</span>
  <span m='1063360'>I</span> <span m='1063420'>reconstructed</span> <span m='1064170'>the</span>
  <span m='1064290'>matrix</span> <span m='1064800'>from</span> <span m='1065040'>the</span>
  <span m='1065170'>singular</span> <span m='1065550'>values</span> <span m='1066000'>and</span>
  <span m='1066150'>those</span> <span m='1066240'>singular</span> <span m='1066600'>vectors,</span>
  <span m='1067320'>and</span> <span m='1067440'>you</span> <span m='1067500'>get</span>
  <span m='1067650'>a</span> <span m='1067710'>faithful</span> <span m='1068190'>representation</span>
  <span m='1068910'>of</span> <span m='1068970'>the</span> <span m='1069090'>original</span>
  <span m='1069450'>fingerprint.</span> </p><p><span m='1071190'>So</span> <span m='1071340'>the</span>
  <span m='1071430'>singular</span> <span m='1071700'>value</span> <span m='1071940'>decomposition</span>
  <span m='1072600'>says</span> <span m='1072750'>something</span> <span m='1073020'>about</span>
  <span m='1073170'>the</span> <span m='1073290'>information</span> <span m='1073800'>content</span>
  <span m='1074340'>in</span> <span m='1074430'>the</span> <span m='1074520'>transformation</span>
  <span m='1075430'>that</span> <span m='1075570'>is</span> <span m='1075750'>the</span>
  <span m='1075870'>matrix,</span> <span m='1076440'>right?</span> <span m='1077100'>There</span>
  <span m='1077250'>are</span> <span m='1077310'>some</span> <span m='1077730'>transformations</span>
  <span m='1078600'>that</span> <span m='1078720'>are</span> <span m='1078810'>of</span>
  <span m='1078960'>lower</span> <span m='1079860'>power</span> <span m='1080490'>or</span>
  <span m='1080730'>importance</span> <span m='1081480'>than</span> <span m='1081840'>others.</span>
  <span m='1083400'>And</span> <span m='1083550'>the</span> <span m='1083640'>magnitude</span>
  <span m='1084150'>of</span> <span m='1084210'>these</span> <span m='1084300'>singular</span>
  <span m='1084630'>values</span> <span m='1084990'>tell</span> <span m='1085170'>you
  what</span> <span m='1085380'>they are.</span> <span m='1086300'>Does</span> <span
  m='1086920'>that</span> <span m='1087030'>makes</span> <span m='1087140'>sense?</span>
  </p><p><span m='1089720'>How</span> <span m='1089870'>else</span> <span m='1089960'>can</span>
  <span m='1090050'>it</span> <span m='1090230'>be</span> <span m='1090320'>used?</span>
  <span m='1090680'>Well,</span> <span m='1091130'>one</span> <span m='1091370'>way</span>
  <span m='1091580'>it can</span> <span m='1091730'>be</span> <span m='1091850'>used</span>
  <span m='1092900'>is</span> <span m='1093440'>finding</span> <span m='1093950'>the</span>
  <span m='1094070'>least</span> <span m='1094370'>square</span> <span m='1094940'>solution</span>
  <span m='1096590'>to</span> <span m='1096680'>the</span> <span m='1096800'>equation</span>
  <span m='1097065'>Ax</span> <span m='1097820'>equals</span> <span m='1098180'>b,</span>
  <span m='1098580'>where</span> <span m='1098780'>A</span> <span m='1098990'>is</span>
  <span m='1099140'>no</span> <span m='1099380'>longer</span> <span m='1100400'>a</span>
  <span m='1100460'>square</span> <span m='1100850'>matrix,</span> <span m='1101940'>OK?</span>
  <span m='1106410'>You've</span> <span m='1106560'>done</span> <span m='1106740'>this</span>
  <span m='1107100'>in</span> <span m='1107310'>other</span> <span m='1107520'>contexts</span>
  <span m='1108030'>before</span> <span m='1108720'>where</span> <span m='1109410'>the</span>
  <span m='1109830'>equations</span> <span m='1110580'>are</span> <span m='1111780'>overspecified.</span>
  <span m='1112860'>We</span> <span m='1112980'>have</span> <span m='1113070'>more</span>
  <span m='1113460'>equations</span> <span m='1114120'>than</span> <span m='1114300'>unknowns,</span>
  <span m='1114840'>like</span> <span m='1115020'>data</span> <span m='1115320'>fitting.</span>
  <span m='1116090'>You</span> <span m='1116220'>form</span> <span m='1116670'>the</span>
  <span m='1116790'>normal</span> <span m='1117270'>equations,</span> <span m='1117840'>you</span>
  <span m='1117930'>multiply</span> <span m='1118410'>both</span> <span m='1118650'>sides</span>
  <span m='1119160'>of</span> <span m='1119460'>Ax</span> <span m='1119820'>equals</span>
  <span m='1120120'>b</span> <span m='1120390'>by</span> <span m='1120630'>A</span>
  <span m='1120840'>transpose,</span> <span m='1122130'>and</span> <span m='1122250'>then</span>
  <span m='1122920'>invert</span> <span m='1123280'>A</span> <span m='1123480'>transpose</span>
  <span m='1124170'>A.</span> </p><p><span m='1125910'>You</span> <span m='1126000'>might</span>
  <span m='1126570'>not</span> <span m='1126780'>be</span> <span m='1127020'>too</span>
  <span m='1127230'>surprised,</span> <span m='1127680'>then,</span> <span m='1127890'>to</span>
  <span m='1128160'>think</span> <span m='1128430'>that</span> <span m='1128550'>singular</span>
  <span m='1128880'>value</span> <span m='1129120'>decomposition</span> <span m='1129780'>could</span>
  <span m='1129900'>be</span> <span m='1130050'>useful</span> <span m='1130380'>here</span>
  <span m='1130590'>too.</span> <span m='1130920'>Since</span> <span m='1131130'>we</span>
  <span m='1131220'>already</span> <span m='1131430'>saw</span> <span m='1132390'>the</span>
  <span m='1132660'>data</span> <span m='1133110'>in</span> <span m='1133320'>a</span>
  <span m='1133380'>singular</span> <span m='1133740'>value</span> <span m='1134010'>decomposition</span>
  <span m='1134790'>corresponds</span> <span m='1135450'>to</span> <span m='1135780'>eigenvectors</span>
  <span m='1136740'>and</span> <span m='1136860'>eigenvalues</span> <span m='1137640'>of</span>
  <span m='1137730'>this</span> <span m='1137950'>A</span> <span m='1138150'>transpose</span>
  <span m='1138630'>A,</span> <span m='1139110'>right?</span> <span m='1140130'>But</span>
  <span m='1140250'>there's</span> <span m='1140400'>a</span> <span m='1140490'>way</span>
  <span m='1140610'>to</span> <span m='1140670'>use</span> <span m='1141750'>this</span>
  <span m='1141930'>sort</span> <span m='1142140'>of</span> <span m='1142200'>decomposition</span>
  <span m='1142950'>formally</span> <span m='1143520'>to</span> <span m='1143670'>solve</span>
  <span m='1143880'>problems</span> <span m='1144360'>that</span> <span m='1144510'>are</span>
  <span m='1145140'>both</span> <span m='1145800'>overspecified</span> <span m='1146830'>and</span>
  <span m='1147120'>underspecified.</span> </p><p><span m='1149730'>Least</span> <span
  m='1150000'>squares</span> <span m='1151830'>means</span> <span m='1152670'>find</span>
  <span m='1153000'>the</span> <span m='1153120'>vector</span> <span m='1153630'>of</span>
  <span m='1153750'>solutions</span> <span m='1154620'>x</span> <span m='1155520'>that</span>
  <span m='1155760'>minimizes</span> <span m='1158250'>this</span> <span m='1158580'>function</span>
  <span m='1159400'>phi.</span> <span m='1161860'>Phi is</span> <span m='1162250'>the</span>
  <span m='1162340'>length</span> <span m='1162670'>of</span> <span m='1162730'>the</span>
  <span m='1162850'>vector</span> <span m='1163780'>given</span> <span m='1163990'>by</span>
  <span m='1164110'>the</span> <span m='1164200'>difference</span> <span m='1164560'>between</span>
  <span m='1165040'>Ax</span> <span m='1165595'>and</span> <span m='1165940'>b.</span>
  <span m='1166450'>It's</span> <span m='1166600'>one</span> <span m='1166810'>measure</span>
  <span m='1167080'>of</span> <span m='1167200'>how</span> <span m='1167350'>far</span>
  <span m='1167650'>an</span> <span m='1167830'>error</span> <span m='1168780'>our</span>
  <span m='1168880'>solution</span> <span m='1169390'>x</span> <span m='1169690'>is.</span>
  <span m='1169900'>So</span> <span m='1170080'>let's</span> <span m='1170300'>define</span>
  <span m='1171370'>the</span> <span m='1171490'>value</span> <span m='1172030'>x</span>
  <span m='1172580'>which</span> <span m='1172690'>is</span> <span m='1172850'>least</span>
  <span m='1173160'>in</span> <span m='1173400'>error.</span> <span m='1174220'>This</span>
  <span m='1174370'>is</span> <span m='1174460'>one</span> <span m='1174670'>definition</span>
  <span m='1175180'>of</span> <span m='1175300'>least</span> <span m='1175720'>squares.</span>
  </p><p><span m='1180490'>And</span> <span m='1180620'>I</span> <span m='1180710'>know</span>
  <span m='1180980'>the</span> <span m='1181070'>singular</span> <span m='1181430'>value</span>
  <span m='1181700'>decomposition</span> <span m='1182630'>of</span> <span m='1183080'>A.</span>
  <span m='1183350'>So</span> <span m='1183650'>A</span> <span m='1183950'>is</span>
  <span m='1184310'>U</span> <span m='1184790'>sigma</span> <span m='1185270'>times</span>
  <span m='1185670'>V.</span> <span m='1185900'>So</span> <span m='1186230'>I have</span>
  <span m='1186410'>U</span> <span m='1186630'>sigma</span> <span m='1187050'>V</span>
  <span m='1187580'>times</span> <span m='1187880'>x.</span> <span m='1188685'>I can</span>
  <span m='1188990'>factor</span> <span m='1189380'>out</span> <span m='1189560'>U,</span>
  <span m='1190610'>and</span> <span m='1190700'>I've</span> <span m='1190760'>got</span>
  <span m='1190850'>a</span> <span m='1190910'>factor</span> <span m='1191240'>of</span>
  <span m='1191330'>U</span> <span m='1191480'>transpose,</span> <span m='1192140'>or</span>
  <span m='1192200'>U</span> <span m='1192400'>conjugate</span> <span m='1192800'>transpose</span>
  <span m='1193280'>multiplying</span> <span m='1193850'>by</span> <span m='1194210'>b.</span>
  <span m='1194960'>So</span> <span m='1195170'>Ax</span> <span m='1195650'>minus</span>
  <span m='1195860'>b</span> <span m='1196160'>is</span> <span m='1196310'>the</span>
  <span m='1196400'>same</span> <span m='1196730'>as</span> <span m='1197420'>U</span>
  <span m='1197600'>times</span> <span m='1197900'>the</span> <span m='1197990'>quantity</span>
  <span m='1198980'>sigma</span> <span m='1199520'>V</span> <span m='1200000'>conjugate</span>
  <span m='1200570'>transpose</span> <span m='1201050'>x</span> <span m='1201590'>minus</span>
  <span m='1201860'>U</span> <span m='1202010'>conjugate</span> <span m='1202340'>transpose</span>
  <span m='1202850'>b.</span> </p><p><span m='1205240'>We</span> <span m='1205330'>want</span>
  <span m='1205480'>to</span> <span m='1205570'>know</span> <span m='1205690'>the</span>
  <span m='1205870'>x</span> <span m='1206170'>that</span> <span m='1206320'>minimizes</span>
  <span m='1207870'>this</span> <span m='1208320'>phi.</span> <span m='1208480'>It's</span>
  <span m='1208630'>an</span> <span m='1208690'>optimization</span> <span m='1209410'>problem.</span>
  <span m='1210130'>We'll</span> <span m='1210220'>talk</span> <span m='1210500'>in</span>
  <span m='1210700'>great</span> <span m='1210910'>detail</span> <span m='1211330'>about</span>
  <span m='1211540'>these</span> <span m='1211660'>sorts</span> <span m='1211900'>of</span>
  <span m='1211960'>problems</span> <span m='1212290'>later.</span> </p><p><span m='1212990'>This</span>
  <span m='1213070'>one</span> <span m='1213250'>is</span> <span m='1213310'>so</span>
  <span m='1213490'>easy</span> <span m='1213730'>to</span> <span m='1213820'>do,</span>
  <span m='1214030'>we</span> <span m='1214090'>can</span> <span m='1214360'>just</span>
  <span m='1214750'>work</span> <span m='1214930'>it</span> <span m='1215020'>out</span>
  <span m='1215350'>in</span> <span m='1215890'>a</span> <span m='1215920'>couple</span>
  <span m='1216250'>lines</span> <span m='1216580'>of</span> <span m='1216650'>text.</span>
  <span m='1218390'>We'll</span> <span m='1218590'>define</span> <span m='1218790'>a</span>
  <span m='1218890'>new</span> <span m='1218920'>set</span> <span m='1219100'>of</span>
  <span m='1219220'>unknowns,</span> <span m='1219610'>y,</span> <span m='1221240'>which</span>
  <span m='1221380'>is</span> <span m='1221470'>V</span> <span m='1221700'>transpose</span>
  <span m='1222310'>times</span> <span m='1222580'>x,</span> <span m='1223810'>and</span>
  <span m='1223950'>a</span> <span m='1224020'>new</span> <span m='1224350'>right-hand</span>
  <span m='1224830'>side</span> <span m='1225130'>for</span> <span m='1225280'>a</span>
  <span m='1225340'>system</span> <span m='1225670'>of</span> <span m='1225760'>equations</span>
  <span m='1226340'>p,</span> <span m='1226690'>which</span> <span m='1226870'>is</span>
  <span m='1226990'>U</span> <span m='1227140'>transpose</span> <span m='1227710'>times</span>
  <span m='1228100'>b.</span> <span m='1229270'>And</span> <span m='1229360'>then</span>
  <span m='1229450'>we</span> <span m='1229510'>can</span> <span m='1229630'>rewrite</span>
  <span m='1230590'>our</span> <span m='1230710'>function</span> <span m='1230965'>phi</span>
  <span m='1231220'>that</span> <span m='1231580'>we're</span> <span m='1231700'>trying</span>
  <span m='1231970'>to</span> <span m='1232120'>minimize.</span> </p><p><span m='1232600'>So
  phi</span> <span m='1233170'>then</span> <span m='1233440'>becomes</span> <span
  m='1234580'>U</span> <span m='1235150'>sigma</span> <span m='1235570'>y</span> <span
  m='1235960'>minus</span> <span m='1236350'>p.</span> <span m='1237720'>U</span>
  <span m='1237920'>is</span> <span m='1238060'>a</span> <span m='1238150'>unitary</span>
  <span m='1238720'>vector.</span> <span m='1239080'>It</span> <span m='1239140'>imparts</span>
  <span m='1239560'>no</span> <span m='1239770'>stretch</span> <span m='1241720'>in</span>
  <span m='1241840'>the</span> <span m='1241960'>two</span> <span m='1242170'>norms,</span>
  <span m='1242500'>so</span> <span m='1242770'>this</span> <span m='1243580'>sigma</span>
  <span m='1244360'>y</span> <span m='1244770'>minus</span> <span m='1245160'>p</span>
  <span m='1245440'>doesn't</span> <span m='1245740'>get</span> <span m='1246610'>elongated</span>
  <span m='1247480'>by</span> <span m='1247870'>multiplication</span> <span m='1248590'>with</span>
  <span m='1248770'>U.</span> </p><p><span m='1249850'>So</span> <span m='1250090'>it's</span>
  <span m='1250300'>length,</span> <span m='1250820'>the</span> <span m='1250950'>length</span>
  <span m='1251160'>of</span> <span m='1251300'>this,</span> <span m='1252280'>is</span>
  <span m='1252430'>the</span> <span m='1252520'>same</span> <span m='1252850'>as</span>
  <span m='1253000'>the</span> <span m='1253120'>length</span> <span m='1253420'>of</span>
  <span m='1253510'>sigma</span> <span m='1253980'>y</span> <span m='1254290'>minus</span>
  <span m='1254570'>p.</span> <span m='1255660'>You</span> <span m='1255700'>can</span>
  <span m='1255790'>prove</span> <span m='1256120'>this.</span> <span m='1257140'>It's</span>
  <span m='1257340'>not</span> <span m='1257470'>very</span> <span m='1257620'>difficult</span>
  <span m='1257920'>to</span> <span m='1258040'>show</span> <span m='1258250'>at</span>
  <span m='1258370'>all.</span> <span m='1258540'>You use</span> <span m='1258820'>the</span>
  <span m='1258910'>definition</span> <span m='1259420'>of</span> <span m='1259520'>the</span>
  <span m='1259610'>two</span> <span m='1259885'>norm to</span> <span m='1260160'>prove</span>
  <span m='1260350'>it.</span> </p><p><span m='1262430'>So</span> <span m='1264190'>phi</span>
  <span m='1264480'>is</span> <span m='1264630'>minimized</span> <span m='1265920'>by</span>
  <span m='1266250'>y's,</span> <span m='1267420'>which</span> <span m='1267600'>makes</span>
  <span m='1267960'>this</span> <span m='1268580'>norm</span> <span m='1269580'>smallest,</span>
  <span m='1270150'>make</span> <span m='1270330'>it</span> <span m='1270390'>closest</span>
  <span m='1270810'>to</span> <span m='1270930'>0.</span> <span m='1274240'>Let</span>
  <span m='1274450'>r</span> <span m='1275400'>be</span> <span m='1275640'>the</span>
  <span m='1275740'>number</span> <span m='1275980'>of</span> <span m='1276070'>non-zero</span>
  <span m='1276640'>singular</span> <span m='1277060'>values,</span> <span m='1277900'>the</span>
  <span m='1278020'>number</span> <span m='1278320'>of</span> <span m='1278440'>those</span>
  <span m='1278620'>sigmas</span> <span m='1279190'>which</span> <span m='1279400'>are</span>
  <span m='1279490'>not</span> <span m='1279670'>equal</span> <span m='1279900'>to</span>
  <span m='1280090'>0.</span> <span m='1282440'>That's</span> <span m='1282610'>also</span>
  <span m='1282850'>the</span> <span m='1282940'>rank</span> <span m='1283210'>of</span>
  <span m='1283330'>A.</span> </p><p><span m='1284360'>Then</span> <span m='1284770'>I</span>
  <span m='1284830'>can</span> <span m='1285010'>rewrite</span> <span m='1285460'>phi</span>
  <span m='1285730'>as</span> <span m='1286840'>the</span> <span m='1286960'>sum</span>
  <span m='1288700'>from</span> <span m='1288850'>i</span> <span m='1289330'>equals
  1</span> <span m='1289670'>to</span> <span m='1289780'>r</span> <span m='1290830'>of</span>
  <span m='1290980'>sigma</span> <span m='1292360'>i i</span> <span m='1293080'>time</span>
  <span m='1293290'>y</span> <span m='1293680'>i</span> <span m='1294070'>minus</span>
  <span m='1294250'>p i</span> <span m='1294820'>squared.</span> <span m='1296060'>That's</span>
  <span m='1296700'>parts</span> <span m='1297100'>of</span> <span m='1297220'>this</span>
  <span m='1298050'>length,</span> <span m='1298870'>this</span> <span m='1299020'>Euclidean</span>
  <span m='1299590'>length,</span> <span m='1300160'>for</span> <span m='1300250'>which</span>
  <span m='1300430'>sigma</span> <span m='1300790'>is</span> <span m='1301060'>non-zero.</span>
  <span m='1302320'>Plus</span> <span m='1303340'>the</span> <span m='1303430'>sum</span>
  <span m='1304330'>from</span> <span m='1304540'>r</span> <span m='1304690'>plus</span>
  <span m='1304960'>1</span> <span m='1305380'>to</span> <span m='1305560'>n,</span>
  <span m='1306530'>the</span> <span m='1306630'>sum</span> <span m='1306730'>over</span>
  <span m='1306880'>the</span> <span m='1306970'>rest</span> <span m='1307270'>of</span>
  <span m='1307870'>the</span> <span m='1307990'>values</span> <span m='1308410'>of</span>
  <span m='1308580'>p,</span> <span m='1310240'>for</span> <span m='1310390'>which</span>
  <span m='1311140'>the</span> <span m='1311230'>corresponding</span> <span m='1311710'>sigmas</span>
  <span m='1312160'>are</span> <span m='1312250'>0.</span> </p><p><span m='1319710'>I</span>
  <span m='1319770'>want</span> <span m='1319890'>to</span> <span m='1319980'>minimize</span>
  <span m='1320790'>phi,</span> <span m='1322080'>and</span> <span m='1322200'>the</span>
  <span m='1322290'>only</span> <span m='1322590'>thing</span> <span m='1322830'>that</span>
  <span m='1322950'>I</span> <span m='1323040'>can</span> <span m='1323220'>change</span>
  <span m='1323790'>to</span> <span m='1323910'>minimize</span> <span m='1324165'>it</span>
  <span m='1324420'>is</span> <span m='1324870'>what?</span> <span m='1328139'>What</span>
  <span m='1328610'>am</span> <span m='1328700'>I</span> <span m='1328790'>free</span>
  <span m='1329150'>to</span> <span m='1329330'>pick</span> <span m='1329690'>in</span>
  <span m='1329840'>this</span> <span m='1330020'>equation</span> <span m='1330530'>in</span>
  <span m='1330650'>order</span> <span m='1330830'>to</span> <span m='1330980'>make</span>
  <span m='1331370'>phi as</span> <span m='1331670'>small as</span> <span m='1332150'>possible?</span>
  <span m='1333930'>Yeah?</span> </p><p><span m='1334595'>AUDIENCE:</span> <span m='1334832'>y.</span>
  </p><p><span m='1335070'>JAMES W. SWAN:</span> <span m='1335220'>y,</span> <span
  m='1336510'>so</span> <span m='1336600'>I</span> <span m='1336630'>need</span> <span
  m='1336810'>to</span> <span m='1336930'>choose</span> <span m='1337290'>the</span>
  <span m='1337410'>y's</span> <span m='1339180'>that</span> <span m='1339270'>make</span>
  <span m='1339510'>this</span> <span m='1339750'>phi</span> <span m='1340020'>as</span>
  <span m='1340110'>small</span> <span m='1340440'>as</span> <span m='1340560'>possible.</span>
  <span m='1341110'>What</span> <span m='1341190'>value</span> <span m='1341850'>should</span>
  <span m='1342030'>I</span> <span m='1342090'>choose</span> <span m='1342450'>for</span>
  <span m='1342570'>the</span> <span m='1342690'>y's?</span> <span m='1346678'>What
  do you</span> <span m='1347172'>think?</span> </p><p><span m='1350630'>AUDIENCE:</span>
  <span m='1350877'>[INAUDIBLE]</span> </p><p><span m='1354480'>JAMES W. SWAN:</span>
  <span m='1354690'>Perfect,</span> <span m='1355170'>right?</span> <span m='1355630'>Choose</span>
  <span m='1356870'>y</span> <span m='1357270'>equals</span> <span m='1358310'>p i</span>
  <span m='1358950'>over</span> <span m='1359270'>sigma</span> <span m='1359635'>i
  i.</span> <span m='1360000'>Right,</span> <span m='1360240'>y i</span> <span m='1360540'>is</span>
  <span m='1360870'>p i</span> <span m='1361200'>over</span> <span m='1361470'>sigma</span>
  <span m='1361880'>i i.</span> <span m='1362610'>Then</span> <span m='1362760'>all</span>
  <span m='1362940'>of</span> <span m='1363030'>these</span> <span m='1363210'>terms</span>
  <span m='1363540'>is</span> <span m='1363630'>0.</span> <span m='1366150'>I</span>
  <span m='1366210'>can't</span> <span m='1366390'>make</span> <span m='1366570'>this</span>
  <span m='1366720'>sum</span> <span m='1366930'>any</span> <span m='1367140'>smaller</span>
  <span m='1367470'>than</span> <span m='1367650'>that.</span> <span m='1368490'>That</span>
  <span m='1368760'>fixes</span> <span m='1369240'>the</span> <span m='1369330'>value</span>
  <span m='1369760'>of</span> <span m='1370930'>y</span> <span m='1371305'>i</span>
  <span m='1372105'>up to</span> <span m='1372530'>r.</span> </p><p><span m='1373980'>I</span>
  <span m='1374040'>can't</span> <span m='1374190'>do</span> <span m='1374310'>anything</span>
  <span m='1374610'>about</span> <span m='1374850'>this</span> <span m='1375090'>left</span>
  <span m='1375490'>over</span> <span m='1375980'>bit here.</span> <span m='1377280'>There's</span>
  <span m='1377430'>no</span> <span m='1377850'>choice</span> <span m='1378340'>of</span>
  <span m='1379350'>y</span> <span m='1379750'>that's</span> <span m='1379920'>going</span>
  <span m='1380040'>to</span> <span m='1380100'>make</span> <span m='1380340'>this</span>
  <span m='1380610'>part</span> <span m='1380970'>and</span> <span m='1381230'>the</span>
  <span m='1381360'>smaller.</span> <span m='1381790'>It's</span> <span m='1381900'>just</span>
  <span m='1382070'>left</span> <span m='1382260'>over.</span> <span m='1382490'>It's</span>
  <span m='1382590'>some</span> <span m='1382800'>remainder</span> <span m='1383340'>that</span>
  <span m='1383430'>we</span> <span m='1383520'>can't</span> <span m='1383730'>make</span>
  <span m='1383910'>any</span> <span m='1384060'>smaller or</span> <span m='1384490'>minimize</span>
  <span m='1384910'>an smaller.</span> <span m='1385410'>There</span> <span m='1385530'>isn't</span>
  <span m='1385770'>an</span> <span m='1385890'>exact</span> <span m='1386190'>solution</span>
  <span m='1387030'>to</span> <span m='1387120'>this</span> <span m='1387270'>problem,</span>
  <span m='1387570'>in</span> <span m='1387660'>many</span> <span m='1387870'>cases.</span>
  </p><p><span m='1390690'>But</span> <span m='1392070'>one</span> <span m='1392250'>way</span>
  <span m='1392370'>this</span> <span m='1392550'>could be</span> <span m='1392790'>0</span>
  <span m='1394290'>is</span> <span m='1394470'>if</span> <span m='1394650'>r</span>
  <span m='1394890'>is</span> <span m='1395010'>equal</span> <span m='1395220'>to</span>
  <span m='1395340'>n.</span> <span m='1397190'>Then</span> <span m='1397380'>there</span>
  <span m='1397500'>are</span> <span m='1397720'>left over</span> <span m='1398400'>unspecified</span>
  <span m='1399180'>terms,</span> <span m='1399570'>and</span> <span m='1399690'>then</span>
  <span m='1399870'>this</span> <span m='1400560'>y</span> <span m='1400860'>i</span>
  <span m='1401100'>equals</span> <span m='1401340'>p i</span> <span m='1401800'>over</span>
  <span m='1401970'>sigma</span> <span m='1402240'>i is</span> <span m='1402510'>the</span>
  <span m='1402630'>exact</span> <span m='1402900'>solution</span> <span m='1403380'>to</span>
  <span m='1403500'>the</span> <span m='1403560'>problem.</span> <span m='1408280'>So</span>
  <span m='1408400'>this</span> <span m='1408940'>is</span> <span m='1409030'>what</span>
  <span m='1409160'>you</span> <span m='1409270'>told</span> <span m='1409500'>me.</span>
  </p><p><span m='1409690'>Choose</span> <span m='1409970'>y i</span> <span m='1410450'>is</span>
  <span m='1410810'>p i</span> <span m='1411100'>over</span> <span m='1411600'>sigma</span>
  <span m='1412020'>i i</span> <span m='1413650'>for</span> <span m='1413920'>i</span>
  <span m='1414550'>bigger</span> <span m='1415150'>than</span> <span m='1415330'>1</span>
  <span m='1415690'>and</span> <span m='1415810'>smaller</span> <span m='1416230'>than</span>
  <span m='1416410'>r.</span> <span m='1418650'>There</span> <span m='1419130'>are</span>
  <span m='1419190'>going</span> <span m='1419310'>to</span> <span m='1419370'>be</span>
  <span m='1419470'>values</span> <span m='1419770'>of</span> <span m='1420070'>y</span>
  <span m='1420280'>i</span> <span m='1420710'>that</span> <span m='1421020'>go</span>
  <span m='1421180'>between</span> <span m='1421840'>r</span> <span m='1422050'>plus</span>
  <span m='1422410'>1</span> <span m='1422920'>and</span> <span m='1423230'>m,</span>
  <span m='1424740'>because</span> <span m='1425090'>A</span> <span m='1425300'>was</span>
  <span m='1425440'>a</span> <span m='1425590'>vector</span> <span m='1425920'>that</span>
  <span m='1426070'>mapped</span> <span m='1426560'>from</span> <span m='1426810'>m
  to</span> <span m='1427160'>n,</span> <span m='1427630'>right?</span> <span m='1427990'>So</span>
  <span m='1428140'>I</span> <span m='1428200'>have</span> <span m='1428380'>extra</span>
  <span m='1428680'>values</span> <span m='1429070'>of</span> <span m='1429190'>y</span>
  <span m='1429490'>that</span> <span m='1429610'>could</span> <span m='1429730'>be</span>
  <span m='1429820'>specified</span> <span m='1430510'>potentially.</span> </p><p><span
  m='1432160'>If</span> <span m='1432280'>that's</span> <span m='1432520'>true,</span>
  <span m='1433480'>if</span> <span m='1433690'>r</span> <span m='1433930'>plus</span>
  <span m='1434230'>1</span> <span m='1435100'>is</span> <span m='1435190'>smaller</span>
  <span m='1435640'>than</span> <span m='1435820'>m,</span> <span m='1436540'>then</span>
  <span m='1436660'>there's</span> <span m='1436810'>some</span> <span m='1436960'>components</span>
  <span m='1437410'>of</span> <span m='1437460'>y</span> <span m='1437710'>that</span>
  <span m='1437860'>I</span> <span m='1437920'>don't</span> <span m='1438100'>get</span>
  <span m='1438250'>to--</span> <span m='1438570'>I</span> <span m='1438760'>can't</span>
  <span m='1439000'>specify,</span> <span m='1439270'>right?</span> <span m='1439770'>My</span>
  <span m='1439880'>system</span> <span m='1440200'>of</span> <span m='1440290'>equations</span>
  <span m='1440800'>is</span> <span m='1440860'>somehow</span> <span m='1441280'>underdetermined.</span>
  <span m='1442930'>I</span> <span m='1443200'>need</span> <span m='1443380'>some</span>
  <span m='1443740'>external</span> <span m='1444340'>information</span> <span m='1444880'>to</span>
  <span m='1445000'>show</span> <span m='1445240'>me</span> <span m='1445390'>what</span>
  <span m='1445540'>values</span> <span m='1446050'>to</span> <span m='1446200'>pick</span>
  <span m='1446860'>for</span> <span m='1447010'>those</span> <span m='1447250'>y</span>
  <span m='1447560'>i.</span> <span m='1447740'>I</span> <span m='1448000'>don't</span>
  <span m='1448120'>know.</span> <span m='1448900'>I</span> <span m='1448960'>can't</span>
  <span m='1449170'>use</span> <span m='1449410'>them.</span> </p><p><span m='1450400'>Sometimes</span>
  <span m='1450790'>people</span> <span m='1451000'>just</span> <span m='1451130'>set</span>
  <span m='1451390'>y i</span> <span m='1451810'>equal</span> <span m='1452080'>to</span>
  <span m='1452200'>0.</span> <span m='1453420'>That's</span> <span m='1453540'>sort</span>
  <span m='1453730'>of</span> <span m='1453790'>silly,</span> <span m='1454260'>but</span>
  <span m='1454420'>that's</span> <span m='1454690'>what's</span> <span m='1454960'>done.</span>
  <span m='1456220'>It's</span> <span m='1456340'>called</span> <span m='1456520'>the</span>
  <span m='1456640'>minimum</span> <span m='1457090'>norm</span> <span m='1457960'>least</span>
  <span m='1458170'>square</span> <span m='1458650'>solution.</span> <span m='1460150'>y</span>
  <span m='1460780'>has</span> <span m='1461020'>minimum</span> <span m='1461410'>length,</span>
  <span m='1461760'>when</span> <span m='1461920'>you</span> <span m='1461980'>set</span>
  <span m='1462130'>all</span> <span m='1462250'>these</span> <span m='1462430'>other</span>
  <span m='1462580'>components</span> <span m='1463090'>to</span> <span m='1463210'>0.</span>
  <span m='1464050'>But</span> <span m='1464170'>the</span> <span m='1464260'>truth</span>
  <span m='1464590'>is,</span> <span m='1465400'>we</span> <span m='1465490'>can't</span>
  <span m='1465670'>specify</span> <span m='1466180'>those</span> <span m='1466390'>components,</span>
  <span m='1467140'>right?</span> <span m='1467720'>We</span> <span m='1467820'>need</span>
  <span m='1467860'>some</span> <span m='1468100'>external</span> <span m='1468580'>information</span>
  <span m='1469090'>in</span> <span m='1469210'>order</span> <span m='1469390'>to</span>
  <span m='1469480'>specify</span> <span m='1469840'>them.</span> </p><p><span m='1471850'>Once</span>
  <span m='1472060'>we</span> <span m='1472150'>know</span> <span m='1472300'>y,</span>
  <span m='1473380'>we</span> <span m='1473470'>can</span> <span m='1473590'>find</span>
  <span m='1473920'>x</span> <span m='1474310'>going</span> <span m='1474550'>back</span>
  <span m='1474680'>to</span> <span m='1474760'>our</span> <span m='1474880'>definition</span>
  <span m='1475165'>of</span> <span m='1475450'>what</span> <span m='1475540'>y</span>
  <span m='1475990'>is.</span> <span m='1476260'>So I</span> <span m='1476360'>multiply</span>
  <span m='1476770'>this</span> <span m='1476950'>equation</span> <span m='1477400'>by</span>
  <span m='1477640'>V</span> <span m='1477900'>on</span> <span m='1478120'>both</span>
  <span m='1478360'>sides,</span> <span m='1478840'>and</span> <span m='1478930'>I'll</span>
  <span m='1479020'>get</span> <span m='1479260'>V y</span> <span m='1479530'>equals</span>
  <span m='1479865'>x.</span> <span m='1482350'>So</span> <span m='1482440'>I</span>
  <span m='1482500'>can</span> <span m='1482650'>find</span> <span m='1482980'>my</span>
  <span m='1483130'>least</span> <span m='1483360'>square</span> <span m='1483700'>solution</span>
  <span m='1484180'>to</span> <span m='1484270'>the</span> <span m='1484390'>problem</span>
  <span m='1484930'>from</span> <span m='1486220'>the</span> <span m='1486310'>singular</span>
  <span m='1486640'>value</span> <span m='1486910'>decomposition.</span> <span m='1487930'>So</span>
  <span m='1488020'>I</span> <span m='1488080'>can</span> <span m='1488200'>find</span>
  <span m='1488380'>the</span> <span m='1488440'>least</span> <span m='1488620'>square</span>
  <span m='1488830'>solution</span> <span m='1489220'>to</span> <span m='1489310'>both</span>
  <span m='1489520'>overdetermined</span> <span m='1490390'>and</span> <span m='1490720'>underdetermined</span>
  <span m='1491500'>problems</span> <span m='1492460'>using</span> <span m='1492850'>singular</span>
  <span m='1493240'>value</span> <span m='1493510'>decomposition.</span> </p><p><span
  m='1495970'>It</span> <span m='1496060'>inherits</span> <span m='1496480'>all</span>
  <span m='1496570'>the</span> <span m='1496660'>properties</span> <span m='1497050'>you</span>
  <span m='1497110'>know</span> <span m='1497260'>of</span> <span m='1497350'>solving</span>
  <span m='1497710'>the</span> <span m='1497800'>normal</span> <span m='1498130'>equations,</span>
  <span m='1498670'>multiplying</span> <span m='1499150'>by A</span> <span m='1499460'>transpose</span>
  <span m='1500500'>the</span> <span m='1500650'>entire</span> <span m='1500950'>equation,</span>
  <span m='1501430'>and</span> <span m='1501550'>solving</span> <span m='1503170'>for</span>
  <span m='1503380'>a least</span> <span m='1503620'>square</span> <span m='1503890'>solution</span>
  <span m='1504370'>that</span> <span m='1504550'>way.</span> <span m='1504760'>But
  that's</span> <span m='1505000'>only</span> <span m='1505150'>good</span> <span
  m='1505330'>for</span> <span m='1505540'>overdetermined</span> <span m='1506230'>systems</span>
  <span m='1506680'>of</span> <span m='1506770'>equations.</span> <span m='1507250'>This</span>
  <span m='1507370'>can</span> <span m='1507520'>work</span> <span m='1507640'>for</span>
  <span m='1507790'>underdetermined</span> <span m='1508420'>equations</span> <span
  m='1508930'>as</span> <span m='1509030'>well.</span> <span m='1509770'>And</span>
  <span m='1509860'>maybe</span> <span m='1510100'>we</span> <span m='1510220'>do</span>
  <span m='1510460'>have</span> <span m='1510700'>extraneous</span> <span m='1511270'>information</span>
  <span m='1512450'>that</span> <span m='1512560'>lets</span> <span m='1512800'>us</span>
  <span m='1512860'>specify</span> <span m='1513460'>these</span> <span m='1513640'>other</span>
  <span m='1513820'>components</span> <span m='1514270'>somehow.</span> <span m='1515080'>Maybe</span>
  <span m='1515350'>we</span> <span m='1515410'>do</span> <span m='1515590'>a</span>
  <span m='1515650'>separate</span> <span m='1516100'>optimization</span> <span m='1517420'>that</span>
  <span m='1517560'>chooses</span> <span m='1518020'>from</span> <span m='1518260'>all</span>
  <span m='1518500'>possible</span> <span m='1518950'>solutions</span> <span m='1520110'>where</span>
  <span m='1520240'>these</span> <span m='1520450'>y i's</span> <span m='1521020'>are</span>
  <span m='1521110'>free,</span> <span m='1521560'>and</span> <span m='1521680'>picks</span>
  <span m='1521920'>the</span> <span m='1522040'>best</span> <span m='1522340'>one</span>
  <span m='1522730'>subject</span> <span m='1523070'>to</span> <span m='1523140'>some</span>
  <span m='1523330'>other</span> <span m='1523510'>constraint.</span> </p><p><span
  m='1525890'>Does</span> <span m='1525990'>it</span> <span m='1526030'>makes</span>
  <span m='1526150'>sense?</span> <span m='1527550'>OK,</span> <span m='1527830'>that's</span>
  <span m='1528100'>the</span> <span m='1528220'>last</span> <span m='1528450'>decomposition</span>
  <span m='1529010'>we're</span> <span m='1529100'>going</span> <span m='1529220'>to</span>
  <span m='1529280'>talk</span> <span m='1529520'>about.</span> <span m='1532070'>It's</span>
  <span m='1532220'>as</span> <span m='1532340'>expensive</span> <span m='1532850'>to</span>
  <span m='1532940'>compute</span> <span m='1533330'>the</span> <span m='1533420'>singular</span>
  <span m='1533780'>value</span> <span m='1534050'>decomposition</span> <span m='1534890'>as</span>
  <span m='1535040'>it</span> <span m='1535130'>is</span> <span m='1535310'>to</span>
  <span m='1535430'>solve</span> <span m='1535780'>a</span> <span m='1535850'>system</span>
  <span m='1536240'>of</span> <span m='1536330'>equations.</span> <span m='1536810'>You</span>
  <span m='1536900'>might</span> <span m='1537020'>have</span> <span m='1537120'>guessed</span>
  <span m='1537500'>that it's</span> <span m='1537660'>got an</span> <span m='1537970'>order</span>
  <span m='1538280'>N</span> <span m='1538580'>cubed</span> <span m='1539270'>flavor</span>
  <span m='1539750'>to</span> <span m='1539960'>it.</span> </p><p><span m='1540470'>It's</span>
  <span m='1540560'>kind</span> <span m='1540680'>of</span> <span m='1540770'>inescapable</span>
  <span m='1542160'>that</span> <span m='1542230'>we</span> <span m='1542390'>run</span>
  <span m='1542570'>up</span> <span m='1542660'>against</span> <span m='1542990'>those</span>
  <span m='1543680'>computational</span> <span m='1544340'>difficulties,</span> <span
  m='1545920'>order</span> <span m='1546310'>N</span> <span m='1546470'>cubed</span>
  <span m='1546740'>computational</span> <span m='1547400'>complexity.</span> <span
  m='1548530'>And</span> <span m='1548630'>there</span> <span m='1548720'>are</span>
  <span m='1548780'>many</span> <span m='1549050'>problems</span> <span m='1549380'>of</span>
  <span m='1549440'>practical</span> <span m='1550010'>interest,</span> <span m='1550730'>particularly</span>
  <span m='1551120'>solutions</span> <span m='1551600'>of</span> <span m='1551660'>PDEs,</span>
  <span m='1552290'>for</span> <span m='1552500'>which</span> <span m='1553490'>that's</span>
  <span m='1553880'>not</span> <span m='1554180'>going</span> <span m='1554540'>to</span>
  <span m='1554930'>cut</span> <span m='1555110'>it.</span> <span m='1556000'>Where</span>
  <span m='1556310'>you</span> <span m='1556700'>couldn't</span> <span m='1557180'>solve</span>
  <span m='1557690'>the</span> <span m='1557810'>problem</span> <span m='1559250'>with</span>
  <span m='1559460'>that</span> <span m='1559700'>sort</span> <span m='1559970'>of</span>
  <span m='1560150'>scaling</span> <span m='1560780'>in</span> <span m='1560930'>time.</span>
  <span m='1561330'>You</span> <span m='1561410'>couldn't</span> <span m='1561650'>compute</span>
  <span m='1563420'>the</span> <span m='1563540'>Gaussian</span> <span m='1563930'>elimination,</span>
  <span m='1564710'>or</span> <span m='1564800'>the</span> <span m='1564890'>singular</span>
  <span m='1565250'>value</span> <span m='1565490'>decomposition,</span> <span m='1566540'>or</span>
  <span m='1566900'>an</span> <span m='1567140'>eigenvalue</span> <span m='1567710'>decomposition.</span>
  <span m='1568970'>It</span> <span m='1569060'>won't</span> <span m='1569300'>work.</span>
  </p><p><span m='1569960'>And</span> <span m='1570110'>in</span> <span m='1570230'>those</span>
  <span m='1570440'>cases,</span> <span m='1571490'>we</span> <span m='1571610'>appeal</span>
  <span m='1571940'>to</span> <span m='1572540'>not</span> <span m='1572840'>exact</span>
  <span m='1573440'>solution</span> <span m='1574010'>methods,</span> <span m='1574520'>but</span>
  <span m='1574820'>approximate</span> <span m='1575390'>solution</span> <span m='1575810'>methods.</span>
  <span m='1577010'>So</span> <span m='1577700'>instead</span> <span m='1578180'>of</span>
  <span m='1578360'>trying</span> <span m='1578600'>to</span> <span m='1578690'>get</span>
  <span m='1578810'>an</span> <span m='1578870'>exact</span> <span m='1579230'>solution,</span>
  <span m='1580120'>we'll</span> <span m='1580220'>try</span> <span m='1580370'>to</span>
  <span m='1580430'>formulate</span> <span m='1580820'>one</span> <span m='1581060'>that's</span>
  <span m='1581420'>good</span> <span m='1581630'>enough.</span> <span m='1582080'>We</span>
  <span m='1582200'>already</span> <span m='1582410'>know</span> <span m='1582590'>the</span>
  <span m='1582650'>computer</span> <span m='1583010'>introduces</span> <span m='1583550'>numerical</span>
  <span m='1584060'>error</span> <span m='1584390'>anyways.</span> <span m='1586070'>Maybe</span>
  <span m='1586310'>we</span> <span m='1586460'>don't</span> <span m='1586640'>need</span>
  <span m='1586850'>machine</span> <span m='1587240'>precision</span> <span m='1587720'>in</span>
  <span m='1587840'>our</span> <span m='1587930'>solution</span> <span m='1588440'>or</span>
  <span m='1588560'>something</span> <span m='1588890'>close</span> <span m='1589190'>to</span>
  <span m='1589280'>machine</span> <span m='1589580'>precision</span> <span m='1590060'>in</span>
  <span m='1590180'>our</span> <span m='1590240'>solution.</span> <span m='1590600'>Maybe</span>
  <span m='1590780'>we're</span> <span m='1590900'>solving</span> <span m='1591230'>engineering</span>
  <span m='1591710'>problem,</span> <span m='1592130'>and</span> <span m='1592250'>we're</span>
  <span m='1592370'>willing</span> <span m='1592640'>to</span> <span m='1592790'>accept</span>
  <span m='1593480'>relative</span> <span m='1593960'>errors</span> <span m='1594230'>on</span>
  <span m='1594350'>the</span> <span m='1594440'>order</span> <span m='1594680'>of</span>
  <span m='1594770'>10</span> <span m='1594980'>to</span> <span m='1595070'>the</span>
  <span m='1595160'>minus</span> <span m='1595490'>3</span> <span m='1596300'>or</span>
  <span m='1596390'>10</span> <span m='1596570'>to</span> <span m='1596690'>the</span>
  <span m='1596750'>minus</span> <span m='1597080'>5,</span> <span m='1597770'>some</span>
  <span m='1597980'>specified</span> <span m='1598580'>tolerance</span> <span m='1599180'>that</span>
  <span m='1599300'>we</span> <span m='1599450'>apply</span> <span m='1599840'>to</span>
  <span m='1599960'>the</span> <span m='1600050'>problem.</span> </p><p><span m='1601550'>And</span>
  <span m='1601670'>in</span> <span m='1601790'>those</span> <span m='1601940'>circumstances,</span>
  <span m='1602720'>we</span> <span m='1602870'>use</span> <span m='1603290'>iterative</span>
  <span m='1603710'>methods</span> <span m='1604250'>to</span> <span m='1604400'>solve</span>
  <span m='1604760'>systems</span> <span m='1605180'>of</span> <span m='1605270'>equations</span>
  <span m='1605840'>instead</span> <span m='1606095'>of</span> <span m='1607050'>exact</span>
  <span m='1607400'>methods,</span> <span m='1607880'>elimination</span> <span m='1608480'>methods,</span>
  <span m='1609020'>or</span> <span m='1609260'>metrics</span> <span m='1609740'>decomposition</span>
  <span m='1610250'>methods.</span> <span m='1613830'>These</span> <span m='1613980'>algorithms</span>
  <span m='1614550'>are</span> <span m='1614670'>all</span> <span m='1614790'>based</span>
  <span m='1615210'>on</span> <span m='1615540'>iterative</span> <span m='1615960'>refinement</span>
  <span m='1616560'>of</span> <span m='1616680'>an</span> <span m='1616770'>initial</span>
  <span m='1617200'>guess.</span> <span m='1617580'>So</span> <span m='1617820'>if</span>
  <span m='1617910'>we</span> <span m='1618030'>have</span> <span m='1618180'>some</span>
  <span m='1618390'>system</span> <span m='1618720'>of</span> <span m='1618810'>equations</span>
  <span m='1619260'>we're</span> <span m='1619350'>trying</span> <span m='1619590'>to</span>
  <span m='1619680'>solve,</span> <span m='1620050'>Ax</span> <span m='1620430'>equals</span>
  <span m='1620730'>b,</span> <span m='1622350'>we'll</span> <span m='1622530'>formulate</span>
  <span m='1623130'>some</span> <span m='1623460'>linear</span> <span m='1623910'>map,</span>
  <span m='1624750'>right?</span> <span m='1625410'>xi</span> <span m='1625860'>plus</span>
  <span m='1626190'>1</span> <span m='1626730'>will</span> <span m='1626820'>be</span>
  <span m='1626910'>some</span> <span m='1627150'>matrix</span> <span m='1627570'>C</span>
  <span m='1628710'>times</span> <span m='1629130'>x i</span> <span m='1629910'>plus</span>
  <span m='1630270'>some</span> <span m='1630570'>little</span> <span m='1630780'>vector</span>
  <span m='1631140'>c</span> <span m='1631500'>where</span> <span m='1631740'>x i</span>
  <span m='1632370'>is</span> <span m='1632550'>my</span> <span m='1632790'>last</span>
  <span m='1633230'>best</span> <span m='1633540'>guess</span> <span m='1634470'>for</span>
  <span m='1634560'>the</span> <span m='1634650'>solution</span> <span m='1635070'>to</span>
  <span m='1635160'>this</span> <span m='1635310'>problem,</span> <span m='1636140'>and</span>
  <span m='1636270'>x i</span> <span m='1636640'>plus</span> <span m='1636900'>1</span>
  <span m='1637080'>is</span> <span m='1637200'>my</span> <span m='1637440'>next</span>
  <span m='1637860'>best</span> <span m='1638160'>guess</span> <span m='1638790'>for</span>
  <span m='1638880'>the</span> <span m='1638970'>solution</span> <span m='1639390'>to</span>
  <span m='1639480'>this</span> <span m='1639660'>problem.</span> <span m='1640320'>And</span>
  <span m='1640440'>I'm</span> <span m='1640530'>hoping,</span> <span m='1641370'>as</span>
  <span m='1641520'>I</span> <span m='1641790'>apply</span> <span m='1642420'>this</span>
  <span m='1642690'>map</span> <span m='1643710'>more</span> <span m='1643950'>and</span>
  <span m='1644040'>more</span> <span m='1644250'>times,</span> <span m='1644700'>I'm</span>
  <span m='1644850'>creeping</span> <span m='1645330'>closer</span> <span m='1645840'>to</span>
  <span m='1645960'>the</span> <span m='1646110'>exact</span> <span m='1646440'>solution</span>
  <span m='1647010'>to</span> <span m='1647130'>the</span> <span m='1647250'>original</span>
  <span m='1647640'>system</span> <span m='1648030'>of</span> <span m='1648120'>equations.</span>
  </p><p><span m='1649590'>The</span> <span m='1649680'>map</span> <span m='1649950'>will</span>
  <span m='1650340'>converge</span> <span m='1651960'>when</span> <span m='1652170'>x
  i</span> <span m='1652590'>plus</span> <span m='1652890'>1</span> <span m='1653610'>approaches</span>
  <span m='1654120'>x i,</span> <span m='1654630'>when</span> <span m='1654750'>the</span>
  <span m='1654840'>map</span> <span m='1655080'>isn't</span> <span m='1655290'>making</span>
  <span m='1655590'>any</span> <span m='1655740'>changes</span> <span m='1656190'>to</span>
  <span m='1656310'>the</span> <span m='1656400'>vector</span> <span m='1656730'>anymore.</span>
  <span m='1659250'>And</span> <span m='1661710'>the</span> <span m='1661830'>converged</span>
  <span m='1662340'>value</span> <span m='1663630'>will</span> <span m='1663750'>be</span>
  <span m='1663870'>a</span> <span m='1663930'>solution</span> <span m='1664800'>when</span>
  <span m='1667360'>x i--</span> <span m='1668490'>which</span> <span m='1668670'>is</span>
  <span m='1668760'>equal</span> <span m='1669030'>to</span> <span m='1669320'>i</span>
  <span m='1669630'>minus</span> <span m='1670170'>c</span> <span m='1670560'>inverse</span>
  <span m='1671040'>times</span> <span m='1671250'>c,</span> <span m='1671910'>if</span>
  <span m='1672090'>I</span> <span m='1672210'>replace</span> <span m='1672600'>x</span>
  <span m='1672780'>i</span> <span m='1672920'>was</span> <span m='1673090'>1</span>
  <span m='1673440'>with</span> <span m='1673620'>x</span> <span m='1673830'>i</span>
  <span m='1673950'>appear,</span> <span m='1674370'>so</span> <span m='1674490'>I</span>
  <span m='1674580'>say</span> <span m='1674970'>that</span> <span m='1675150'>my</span>
  <span m='1675300'>map</span> <span m='1675570'>has</span> <span m='1675750'>converged--</span>
  <span m='1676650'>when</span> <span m='1676800'>this</span> <span m='1677040'>value</span>
  <span m='1678000'>is</span> <span m='1678120'>equivalent</span> <span m='1678540'>to</span>
  <span m='1678680'>A</span> <span m='1678930'>inverse</span> <span m='1679320'>times</span>
  <span m='1679590'>B,</span> <span m='1680040'>when</span> <span m='1680160'>it's</span>
  <span m='1680310'>a</span> <span m='1680370'>solution</span> <span m='1680850'>to</span>
  <span m='1680940'>the</span> <span m='1681090'>original</span> <span m='1681390'>problem,</span>
  <span m='1682020'>right?</span> <span m='1683880'>So</span> <span m='1684030'>my</span>
  <span m='1684150'>map may</span> <span m='1684450'>converge.</span> <span m='1685480'>It</span>
  <span m='1685530'>may</span> <span m='1685690'>not</span> <span m='1685780'>converge</span>
  <span m='1686160'>to</span> <span m='1686250'>a</span> <span m='1686310'>solution</span>
  <span m='1686670'>of</span> <span m='1686730'>the</span> <span m='1686820'>problem</span>
  <span m='1687120'>I</span> <span m='1687230'>like,</span> <span m='1688320'>but</span>
  <span m='1688440'>if</span> <span m='1688530'>it</span> <span m='1688590'>satisfies</span>
  <span m='1689160'>this</span> <span m='1689340'>condition,</span> <span m='1689790'>then</span>
  <span m='1689940'>has</span> <span m='1690300'>converged</span> <span m='1691680'>to</span>
  <span m='1691800'>be</span> <span m='1691920'>a</span> <span m='1691950'>solution</span>
  <span m='1692340'>of</span> <span m='1692400'>the</span> <span m='1692490'>problem</span>
  <span m='1692730'>that</span> <span m='1692880'>I</span> <span m='1692940'>like</span>
  <span m='1693210'>as</span> <span m='1693340'>well.</span> </p><p><span m='1694270'>And</span>
  <span m='1694370'>so</span> <span m='1694390'>it's</span> <span m='1694500'>all</span>
  <span m='1694680'>about</span> <span m='1694940'>using</span> <span m='1695370'>this</span>
  <span m='1696030'>C</span> <span m='1696390'>here</span> <span m='1696810'>and</span>
  <span m='1696960'>this</span> <span m='1697170'>little</span> <span m='1697440'>c</span>
  <span m='1697680'>here</span> <span m='1698400'>so</span> <span m='1698820'>that</span>
  <span m='1699090'>this</span> <span m='1699300'>map</span> <span m='1700500'>converges</span>
  <span m='1701000'>to</span> <span m='1701160'>solution</span> <span m='1701580'>of</span>
  <span m='1701640'>the</span> <span m='1701730'>problem</span> <span m='1702000'>I'm</span>
  <span m='1702100'>after.</span> <span m='1702720'>And</span> <span m='1702810'>there</span>
  <span m='1702900'>are</span> <span m='1702960'>lots</span> <span m='1703290'>of</span>
  <span m='1703380'>schemes</span> <span m='1703800'>for</span> <span m='1703950'>doing</span>
  <span m='1704220'>this.</span> <span m='1705000'>Some</span> <span m='1705210'>of</span>
  <span m='1705270'>them</span> <span m='1705390'>are</span> <span m='1705480'>kind</span>
  <span m='1705660'>of</span> <span m='1705750'>ad</span> <span m='1705930'>hoc.</span>
  <span m='1706680'>I'm</span> <span m='1706710'>going to</span> <span m='1706800'>show</span>
  <span m='1706980'>you</span> <span m='1707100'>one</span> <span m='1707250'>right</span>
  <span m='1707430'>now.</span> <span m='1708230'>And</span> <span m='1708540'>then</span>
  <span m='1709620'>when</span> <span m='1709740'>we</span> <span m='1709800'>do</span>
  <span m='1709920'>optimization,</span> <span m='1710490'>we'll</span> <span m='1710580'>talk</span>
  <span m='1710790'>about</span> <span m='1711030'>a</span> <span m='1711240'>more</span>
  <span m='1711450'>formal</span> <span m='1711870'>way</span> <span m='1712230'>of</span>
  <span m='1712500'>doing</span> <span m='1712830'>this</span> <span m='1714210'>for</span>
  <span m='1714360'>which</span> <span m='1714540'>you</span> <span m='1714630'>can</span>
  <span m='1714810'>guarantee</span> <span m='1715210'>very</span> <span m='1715440'>rapid</span>
  <span m='1715770'>convergence</span> <span m='1716340'>to</span> <span m='1716490'>a</span>
  <span m='1716520'>solution.</span> </p><p><span m='1718100'>So</span> <span m='1718210'>here's</span>
  <span m='1718410'>a</span> <span m='1718470'>system</span> <span m='1718800'>of</span>
  <span m='1718890'>equations</span> <span m='1719340'>I'd</span> <span m='1719460'>like</span>
  <span m='1719640'>to</span> <span m='1719760'>solve.</span> <span m='1720020'>It's</span>
  <span m='1720170'>not</span> <span m='1720240'>a</span> <span m='1720270'>very</span>
  <span m='1720420'>big</span> <span m='1720630'>one.</span> <span m='1721510'>It</span>
  <span m='1721920'>doesn't</span> <span m='1722100'>really</span> <span m='1722280'>make</span>
  <span m='1722430'>sense</span> <span m='1722700'>to</span> <span m='1722820'>solve</span>
  <span m='1723060'>this</span> <span m='1723240'>one</span> <span m='1723450'>iteratively,</span>
  <span m='1724050'>but</span> <span m='1724170'>it's</span> <span m='1724320'>a</span>
  <span m='1724380'>nice</span> <span m='1724650'>illustration.</span> <span m='1725940'>One</span>
  <span m='1726270'>way</span> <span m='1727020'>to</span> <span m='1727140'>go</span>
  <span m='1727290'>about</span> <span m='1727650'>formulating</span> <span m='1728340'>this</span>
  <span m='1728550'>map</span> <span m='1729570'>is</span> <span m='1729840'>to</span>
  <span m='1730170'>split</span> <span m='1731760'>this</span> <span m='1731970'>matrix</span>
  <span m='1732420'>into</span> <span m='1732630'>two</span> <span m='1732810'>parts.</span>
  </p><p><span m='1733290'>So I'll</span> <span m='1733440'>split</span> <span m='1733740'>it</span>
  <span m='1733830'>into</span> <span m='1734040'>a</span> <span m='1734100'>diagonal</span>
  <span m='1734550'>part</span> <span m='1735420'>and</span> <span m='1735540'>an</span>
  <span m='1735660'>off</span> <span m='1735840'>diagonal</span> <span m='1736280'>part.</span>
  <span m='1737160'>So</span> <span m='1737270'>I</span> <span m='1737320'>haven't</span>
  <span m='1737490'>changed</span> <span m='1737910'>the</span> <span m='1738030'>problem</span>
  <span m='1738300'>at</span> <span m='1738390'>all</span> <span m='1738570'>by</span>
  <span m='1738720'>doing</span> <span m='1739050'>that.</span> <span m='1740070'>And</span>
  <span m='1740160'>then</span> <span m='1740290'>I'm</span> <span m='1740350'>going</span>
  <span m='1740450'>to</span> <span m='1740530'>rename</span> <span m='1741150'>this</span>
  <span m='1741420'>x</span> <span m='1742050'>x i</span> <span m='1742680'>plus</span>
  <span m='1743010'>1,</span> <span m='1743740'>and</span> <span m='1743940'>I'm</span>
  <span m='1744000'>going</span> <span m='1744120'>to</span> <span m='1744180'>rename</span>
  <span m='1744540'>this</span> <span m='1744840'>x</span> <span m='1745755'>x i.</span>
  <span m='1747060'>And</span> <span m='1747210'>then</span> <span m='1747450'>move</span>
  <span m='1747810'>this</span> <span m='1748680'>matrix</span> <span m='1749040'>vector</span>
  <span m='1749310'>product</span> <span m='1749640'>to</span> <span m='1749760'>the</span>
  <span m='1749850'>other</span> <span m='1750030'>side</span> <span m='1750210'>of</span>
  <span m='1750270'>the</span> <span m='1750420'>equation.</span> </p><p><span m='1750870'>And</span>
  <span m='1750960'>here's</span> <span m='1751290'>my</span> <span m='1751470'>map.</span>
  <span m='1752400'>Of course,</span> <span m='1752630'>this</span> <span m='1753090'>matrix</span>
  <span m='1753420'>multiplied</span> <span m='1753750'>doesn't</span> <span m='1753960'>make</span>
  <span m='1754110'>any--</span> <span m='1754350'>it's</span> <span m='1754500'>not</span>
  <span m='1755340'>useful</span> <span m='1755700'>to</span> <span m='1755790'>write</span>
  <span m='1755970'>it</span> <span m='1756060'>out</span> <span m='1756210'>explicitly.</span>
  <span m='1756780'>This</span> <span m='1756990'>is</span> <span m='1757080'>just</span>
  <span m='1757290'>identity.</span> <span m='1759070'>So</span> <span m='1759300'>I</span>
  <span m='1759390'>can</span> <span m='1759600'>drop</span> <span m='1759960'>this</span>
  <span m='1760140'>entirely.</span> <span m='1760840'>This</span> <span m='1760920'>is</span>
  <span m='1761010'>just</span> <span m='1761190'>x i</span> <span m='1761580'>plus</span>
  <span m='1761880'>one.</span> </p><p><span m='1762090'>So</span> <span m='1762240'>here's</span>
  <span m='1762420'>my</span> <span m='1762570'>map.</span> <span m='1763320'>Take</span>
  <span m='1763500'>an</span> <span m='1763590'>initial</span> <span m='1763920'>guess,</span>
  <span m='1765630'>multiply</span> <span m='1766140'>it</span> <span m='1766200'>by</span>
  <span m='1766350'>this</span> <span m='1766530'>matrix,</span> <span m='1767430'>add</span>
  <span m='1767640'>the</span> <span m='1767760'>vector</span> <span m='1768090'>1,</span>
  <span m='1768360'>0,</span> <span m='1769230'>and</span> <span m='1769350'>repeat</span>
  <span m='1769770'>over</span> <span m='1770100'>and</span> <span m='1770190'>over</span>
  <span m='1770400'>and</span> <span m='1770520'>over</span> <span m='1770730'>again.</span>
  <span m='1771600'>Hopefully--</span> <span m='1772440'>we</span> <span m='1772530'>don't</span>
  <span m='1772680'>really</span> <span m='1772860'>know--</span> <span m='1773130'>but</span>
  <span m='1773250'>hopefully,</span> <span m='1773700'>it's</span> <span m='1773820'>going</span>
  <span m='1773970'>to</span> <span m='1774030'>converge</span> <span m='1774540'>to</span>
  <span m='1774660'>a</span> <span m='1774720'>solution</span> <span m='1775140'>of</span>
  <span m='1775200'>the</span> <span m='1775800'>original</span> <span m='1776220'>linear</span>
  <span m='1776550'>equations.</span> </p><p><span m='1778530'>I</span> <span m='1778570'>didn't</span>
  <span m='1778720'>make</span> <span m='1778930'>up</span> <span m='1779080'>that</span>
  <span m='1779230'>method.</span> <span m='1779710'>That's</span> <span m='1779890'>a</span>
  <span m='1779920'>method</span> <span m='1780190'>called</span> <span m='1780460'>Jacobi</span>
  <span m='1780940'>Iteration.</span> <span m='1782490'>And</span> <span m='1782600'>the</span>
  <span m='1782680'>strategy</span> <span m='1783220'>is</span> <span m='1783370'>to</span>
  <span m='1783490'>split</span> <span m='1784000'>the</span> <span m='1784090'>matrix</span>
  <span m='1784510'>A</span> <span m='1785560'>into</span> <span m='1785770'>two</span>
  <span m='1785920'>parts--</span> <span m='1786280'>a</span> <span m='1786360'>sum</span>
  <span m='1786610'>of</span> <span m='1786730'>its</span> <span m='1786880'>diagonal</span>
  <span m='1787450'>elements,</span> <span m='1788050'>and</span> <span m='1788200'>it's</span>
  <span m='1788320'>off</span> <span m='1788530'>diagonal</span> <span m='1789010'>elements--</span>
  <span m='1791050'>and</span> <span m='1791230'>rewrite</span> <span m='1792540'>the</span>
  <span m='1792610'>original</span> <span m='1793000'>equations</span> <span m='1793570'>as</span>
  <span m='1793690'>an</span> <span m='1793780'>iterative</span> <span m='1794140'>map.</span>
  </p><p><span m='1794410'>So</span> <span m='1794620'>D</span> <span m='1795630'>times</span>
  <span m='1795910'>x i</span> <span m='1796240'>plus</span> <span m='1796540'>1</span>
  <span m='1797470'>is</span> <span m='1797620'>equal</span> <span m='1797830'>to</span>
  <span m='1797980'>minus</span> <span m='1798370'>r</span> <span m='1798550'>times</span>
  <span m='1798850'>x i</span> <span m='1799320'>plus</span> <span m='1799570'>b.</span>
  <span m='1800650'>Or</span> <span m='1801460'>x</span> <span m='1801620'>i</span>
  <span m='1801810'>plus</span> <span m='1802060'>1</span> <span m='1802270'>is</span>
  <span m='1802450'>D</span> <span m='1802780'>inverse</span> <span m='1804220'>times</span>
  <span m='1804580'>minus</span> <span m='1804840'>r</span> <span m='1805000'>x</span>
  <span m='1805170'>i</span> <span m='1805420'>plus</span> <span m='1805570'>b.</span>
  <span m='1807600'>If</span> <span m='1807720'>the</span> <span m='1807810'>equations</span>
  <span m='1808320'>converge,</span> <span m='1808890'>then</span> <span m='1809340'>D</span>
  <span m='1809595'>plus</span> <span m='1809850'>r</span> <span m='1810060'>times</span>
  <span m='1810360'>x i</span> <span m='1811100'>has</span> <span m='1811290'>to</span>
  <span m='1811380'>be</span> <span m='1811460'>equal</span> <span m='1811710'>to</span>
  <span m='1811860'>b,</span> <span m='1812610'>we</span> <span m='1812730'>will</span>
  <span m='1812880'>have</span> <span m='1812970'>found</span> <span m='1813270'>a</span>
  <span m='1813330'>solution.</span> <span m='1813780'>If</span> <span m='1814020'>it</span>
  <span m='1814080'>converges,</span> <span m='1814770'>right?</span> <span m='1815040'>If</span>
  <span m='1815220'>these</span> <span m='1815430'>iterations</span> <span m='1816030'>approach</span>
  <span m='1817710'>a</span> <span m='1817770'>steady</span> <span m='1818190'>value.</span>
  <span m='1819150'>If</span> <span m='1819330'>they</span> <span m='1819420'>don't</span>
  <span m='1819600'>change</span> <span m='1819930'>from</span> <span m='1820080'>iteration</span>
  <span m='1820530'>to</span> <span m='1820640'>iteration.</span> <span m='1820770'>Is</span>
  </p><p><span m='1821940'>The</span> <span m='1822030'>nice</span> <span m='1822390'>thing</span>
  <span m='1822600'>about</span> <span m='1822780'>the</span> <span m='1822870'>Jacobi</span>
  <span m='1823290'>method</span> <span m='1823710'>is it</span> <span m='1823800'>turns</span>
  <span m='1824070'>the</span> <span m='1824190'>hard</span> <span m='1824490'>problem,</span>
  <span m='1824830'>the order</span> <span m='1825170'>N</span> <span m='1825360'>cubed</span>
  <span m='1825810'>problem</span> <span m='1827540'>of</span> <span m='1827790'>computing</span>
  <span m='1828300'>A</span> <span m='1828470'>inverse</span> <span m='1828840'>B,</span>
  <span m='1829920'>into</span> <span m='1830190'>a</span> <span m='1830250'>succession</span>
  <span m='1830790'>of</span> <span m='1830910'>easy</span> <span m='1831240'>problems,</span>
  <span m='1831750'>D</span> <span m='1831960'>inverse</span> <span m='1832470'>times</span>
  <span m='1832870'>some</span> <span m='1833760'>vector</span> <span m='1834120'>C.</span>
  <span m='1837270'>How</span> <span m='1837390'>many</span> <span m='1837660'>calculations</span>
  <span m='1838480'>does</span> <span m='1838650'>it</span> <span m='1838710'>take</span>
  <span m='1838900'>to</span> <span m='1839010'>compute</span> <span m='1839430'>that</span>
  <span m='1839640'>D</span> <span m='1839880'>inverse?</span> <span m='1844710'>N,</span>
  <span m='1845240'>that's</span> <span m='1845420'>right,</span> <span m='1845710'>order</span>
  <span m='1845990'>N.</span> </p><p><span m='1846470'>It's</span> <span m='1846560'>just</span>
  <span m='1846710'>a</span> <span m='1846800'>diagonal</span> <span m='1847220'>matrix.</span>
  <span m='1847620'>I</span> <span m='1847730'>invert</span> <span m='1848090'>each</span>
  <span m='1848330'>of</span> <span m='1848420'>its</span> <span m='1848570'>diagonal</span>
  <span m='1849020'>elements,</span> <span m='1849410'>and</span> <span m='1849480'>I'm</span>
  <span m='1849590'>done.</span> <span m='1849880'>So</span> <span m='1850460'>I</span>
  <span m='1850520'>went</span> <span m='1850700'>from</span> <span m='1850880'>order</span>
  <span m='1851270'>N</span> <span m='1851510'>cubed,</span> <span m='1852770'>which</span>
  <span m='1852950'>was</span> <span m='1853040'>going</span> <span m='1853160'>to</span>
  <span m='1853220'>be</span> <span m='1853310'>hard,</span> <span m='1853790'>into</span>
  <span m='1854060'>a</span> <span m='1854120'>succession</span> <span m='1854780'>of</span>
  <span m='1854860'>order</span> <span m='1855170'>N</span> <span m='1855590'>problems.</span>
  <span m='1857320'>So</span> <span m='1857390'>as</span> <span m='1857450'>long</span>
  <span m='1857630'>as</span> <span m='1857720'>it</span> <span m='1857810'>doesn't</span>
  <span m='1858080'>take</span> <span m='1858320'>me</span> <span m='1858950'>order</span>
  <span m='1859220'>N</span> <span m='1859340'>squared</span> <span m='1859730'>iterations</span>
  <span m='1860810'>to</span> <span m='1860930'>get</span> <span m='1861110'>to</span>
  <span m='1861230'>the</span> <span m='1861350'>solution</span> <span m='1861830'>that</span>
  <span m='1861950'>I</span> <span m='1862070'>want,</span> <span m='1863060'>I'm</span>
  <span m='1863120'>going</span> <span m='1863240'>to</span> <span m='1863300'>be</span>
  <span m='1863390'>OK.</span> <span m='1863670'>This</span> <span m='1863870'>is</span>
  <span m='1863960'>going</span> <span m='1864080'>to</span> <span m='1864140'>be</span>
  <span m='1864200'>a</span> <span m='1864260'>viable</span> <span m='1864650'>way</span>
  <span m='1864860'>to</span> <span m='1865010'>solve</span> <span m='1865250'>this</span>
  <span m='1865400'>problem</span> <span m='1865640'>faster</span> <span m='1866630'>than</span>
  <span m='1866780'>finding</span> <span m='1867140'>the exact</span> <span m='1867390'>solution.</span>
  </p><p><span m='1873240'>How</span> <span m='1873300'>do</span> <span m='1873360'>you</span>
  <span m='1873450'>know</span> <span m='1873630'>that</span> <span m='1873780'>it</span>
  <span m='1873840'>converges?</span> <span m='1875640'>That's</span> <span m='1875850'>the</span>
  <span m='1875940'>question.</span> <span m='1877020'>Is</span> <span m='1877230'>this</span>
  <span m='1877410'>thing</span> <span m='1877680'>actually</span> <span m='1878070'>going</span>
  <span m='1878190'>to</span> <span m='1878250'>converge</span> <span m='1878940'>or</span>
  <span m='1879090'>not,</span> <span m='1880290'>or</span> <span m='1880390'>are</span>
  <span m='1880470'>these</span> <span m='1880650'>iterations</span> <span m='1881160'>just</span>
  <span m='1881280'>going</span> <span m='1881400'>to</span> <span m='1881460'>run</span>
  <span m='1881730'>on</span> <span m='1882090'>and</span> <span m='1882210'>on</span>
  <span m='1882450'>forever?</span> <span m='1883980'>Well,</span> <span m='1884080'>one</span>
  <span m='1884400'>way</span> <span m='1884550'>to</span> <span m='1884670'>check</span>
  <span m='1885060'>whether</span> <span m='1885330'>it will</span> <span m='1885480'>converge</span>
  <span m='1885900'>or</span> <span m='1885990'>not</span> <span m='1886620'>is to</span>
  <span m='1886950'>go</span> <span m='1887070'>back</span> <span m='1887250'>up</span>
  <span m='1887370'>to</span> <span m='1887460'>this</span> <span m='1887600'>equation</span>
  <span m='1888090'>here,</span> <span m='1889590'>and</span> <span m='1889750'>substitute</span>
  <span m='1890890'>b</span> <span m='1891220'>equals</span> <span m='1891730'>Ax,</span>
  <span m='1892450'>where</span> <span m='1892690'>x</span> <span m='1892960'>is</span>
  <span m='1893110'>the</span> <span m='1893230'>exact</span> <span m='1893620'>solution</span>
  <span m='1894220'>to</span> <span m='1894310'>the</span> <span m='1894430'>problem.</span>
  </p><p><span m='1897420'>And</span> <span m='1897510'>you</span> <span m='1897570'>can</span>
  <span m='1897720'>transform,</span> <span m='1898095'>then,</span> <span m='1898750'>this</span>
  <span m='1898980'>equation</span> <span m='1900330'>into</span> <span m='1900600'>one</span>
  <span m='1900810'>that</span> <span m='1900930'>looks</span> <span m='1901170'>like</span>
  <span m='1901410'>x i</span> <span m='1901800'>plus</span> <span m='1902070'>1</span>
  <span m='1902280'>minus</span> <span m='1902670'>x</span> <span m='1903570'>equal</span>
  <span m='1904020'>to</span> <span m='1904410'>minus</span> <span m='1905430'>D</span>
  <span m='1905640'>inverse</span> <span m='1906240'>times</span> <span m='1906630'>r</span>
  <span m='1907710'>x i</span> <span m='1908490'>minus</span> <span m='1908850'>x.</span>
  <span m='1909930'>And</span> <span m='1910020'>if</span> <span m='1910110'>I</span>
  <span m='1910200'>take</span> <span m='1910410'>the</span> <span m='1910500'>norm</span>
  <span m='1910740'>of</span> <span m='1910920'>both</span> <span m='1911160'>sides</span>
  <span m='1912780'>and</span> <span m='1912900'>I apply</span> <span m='1913270'>our</span>
  <span m='1913500'>normal</span> <span m='1914010'>equality--</span> <span m='1915270'>where</span>
  <span m='1915390'>the</span> <span m='1916110'>norm</span> <span m='1916710'>of</span>
  <span m='1916890'>a</span> <span m='1916950'>matrix</span> <span m='1917340'>vector</span>
  <span m='1917610'>product</span> <span m='1918000'>is</span> <span m='1918060'>smaller</span>
  <span m='1919140'>than</span> <span m='1919320'>the</span> <span m='1919410'>product</span>
  <span m='1919800'>of</span> <span m='1919890'>the</span> <span m='1920010'>norms</span>
  <span m='1920640'>of</span> <span m='1920760'>the</span> <span m='1920850'>matrices</span>
  <span m='1921460'>of</span> <span m='1921570'>the</span> <span m='1921690'>vectors--</span>
  <span m='1922860'>then</span> <span m='1923660'>I</span> <span m='1923840'>can</span>
  <span m='1923970'>get</span> <span m='1924090'>a</span> <span m='1924120'>ratio</span>
  <span m='1924630'>like</span> <span m='1924900'>this.</span> <span m='1926070'>That</span>
  <span m='1926250'>the</span> <span m='1926760'>absolute</span> <span m='1927360'>error</span>
  <span m='1927890'>in</span> <span m='1928040'>iteration</span> <span m='1928990'>I</span>
  <span m='1929220'>plus</span> <span m='1929550'>1</span> <span m='1930060'>divided</span>
  <span m='1930420'>by</span> <span m='1930540'>the</span> <span m='1930690'>absolute</span>
  <span m='1931260'>error</span> <span m='1931730'>in</span> <span m='1931850'>iteration</span>
  <span m='1932370'>i</span> <span m='1933090'>is</span> <span m='1933180'>smaller</span>
  <span m='1934230'>than</span> <span m='1934380'>the</span> <span m='1934470'>norm</span>
  <span m='1934710'>of</span> <span m='1934770'>this</span> <span m='1934920'>matrix.</span>
  </p><p><span m='1937410'>So</span> <span m='1938970'>if</span> <span m='1939260'>I'm</span>
  <span m='1939380'>converging,</span> <span m='1940900'>then</span> <span m='1941030'>what</span>
  <span m='1941150'>I</span> <span m='1941240'>expect</span> <span m='1941810'>is</span>
  <span m='1942110'>this</span> <span m='1942890'>ratio</span> <span m='1944000'>should</span>
  <span m='1944150'>be</span> <span m='1944240'>smaller</span> <span m='1944600'>than</span>
  <span m='1944810'>1.</span> <span m='1945320'>The</span> <span m='1945500'>error</span>
  <span m='1945830'>in</span> <span m='1945950'>my</span> <span m='1946100'>next</span>
  <span m='1946460'>approximation</span> <span m='1947240'>should</span> <span m='1947390'>be</span>
  <span m='1947510'>smaller</span> <span m='1948500'>than</span> <span m='1948650'>the</span>
  <span m='1948770'>error</span> <span m='1948890'>in</span> <span m='1948980'>my</span>
  <span m='1949100'>current</span> <span m='1949430'>approximation.</span> <span m='1950080'>That</span>
  <span m='1950180'>makes</span> <span m='1950320'>sense?</span> <span m='1951450'>So</span>
  <span m='1951770'>that means</span> <span m='1951950'>that</span> <span m='1952220'>I</span>
  <span m='1952400'>would</span> <span m='1952550'>hope</span> <span m='1953390'>that</span>
  <span m='1953510'>the</span> <span m='1953630'>norm</span> <span m='1953990'>of</span>
  <span m='1954110'>this</span> <span m='1954290'>matrix</span> <span m='1955100'>is</span>
  <span m='1955220'>also</span> <span m='1955580'>smaller</span> <span m='1956000'>than</span>
  <span m='1956180'>1.</span> </p><p><span m='1956690'>If</span> <span m='1956810'>it</span>
  <span m='1956900'>is,</span> <span m='1957140'>then</span> <span m='1957260'>I'm</span>
  <span m='1957350'>going</span> <span m='1957470'>to</span> <span m='1957530'>be</span>
  <span m='1957590'>guaranteed</span> <span m='1958280'>to</span> <span m='1958460'>converge.</span>
  <span m='1960290'>So</span> <span m='1960500'>for</span> <span m='1960650'>a</span>
  <span m='1960680'>particular</span> <span m='1962180'>coefficient</span> <span m='1962810'>matrix,</span>
  <span m='1963290'>for a</span> <span m='1963410'>system</span> <span m='1963710'>of</span>
  <span m='1963800'>linear</span> <span m='1964040'>equations</span> <span m='1964490'>I'm</span>
  <span m='1964580'>trying</span> <span m='1964730'>to</span> <span m='1964820'>solve,</span>
  <span m='1965120'>I</span> <span m='1965240'>may</span> <span m='1965710'>be</span>
  <span m='1965900'>able</span> <span m='1966050'>to</span> <span m='1966120'>find--</span>
  <span m='1967010'>I</span> <span m='1967070'>may</span> <span m='1967220'>find</span>
  <span m='1967580'>that</span> <span m='1967730'>this</span> <span m='1967940'>is</span>
  <span m='1968060'>true.</span> <span m='1970430'>And</span> <span m='1970550'>then</span>
  <span m='1970940'>I</span> <span m='1971060'>can</span> <span m='1971180'>apply</span>
  <span m='1971450'>this</span> <span m='1971600'>method,</span> <span m='1971960'>and</span>
  <span m='1972050'>I'll</span> <span m='1972200'>converge</span> <span m='1972680'>to</span>
  <span m='1972800'>a</span> <span m='1972860'>solution.</span> </p><p><span m='1974980'>We</span>
  <span m='1975070'>call</span> <span m='1975250'>this</span> <span m='1975370'>sort</span>
  <span m='1975550'>of</span> <span m='1975640'>convergence</span> <span m='1976840'>linear.</span>
  <span m='1978100'>Whatever</span> <span m='1978400'>this</span> <span m='1978640'>number</span>
  <span m='1979090'>is,</span> <span m='1979350'>it</span> <span m='1979450'>tells</span>
  <span m='1979780'>me</span> <span m='1979990'>the</span> <span m='1980680'>fraction</span>
  <span m='1981460'>by</span> <span m='1981640'>which</span> <span m='1981940'>the</span>
  <span m='1982120'>error</span> <span m='1982450'>is</span> <span m='1982600'>reduced</span>
  <span m='1983080'>from</span> <span m='1983320'>iteration</span> <span m='1983890'>to</span>
  <span m='1984010'>iteration.</span> <span m='1984940'>So</span> <span m='1985090'>suppose</span>
  <span m='1985480'>this</span> <span m='1985690'>is</span> <span m='1985810'>1/10.</span>
  <span m='1987810'>Then</span> <span m='1988360'>the</span> <span m='1988510'>absolute</span>
  <span m='1988930'>error</span> <span m='1989080'>is</span> <span m='1989170'>going</span>
  <span m='1989290'>to</span> <span m='1989350'>be</span> <span m='1989440'>reduced</span>
  <span m='1990010'>by</span> <span m='1990190'>a</span> <span m='1990250'>factor</span>
  <span m='1990580'>of</span> <span m='1990670'>10</span> <span m='1991510'>in</span>
  <span m='1991690'>each</span> <span m='1991930'>iteration.</span> <span m='1994300'>It's</span>
  <span m='1994420'>not</span> <span m='1994570'>going</span> <span m='1994690'>to</span>
  <span m='1994750'>be</span> <span m='1994870'>1/10</span> <span m='1995390'>usually.</span>
  <span m='1995720'>It's</span> <span m='1995800'>going</span> <span m='1995920'>to</span>
  <span m='1995980'>be</span> <span m='1996040'>something</span> <span m='1996490'>that's</span>
  <span m='1996700'>a</span> <span m='1996730'>little</span> <span m='1996910'>bit</span>
  <span m='1997060'>bigger</span> <span m='1997270'>than</span> <span m='1997450'>that</span>
  <span m='1997690'>typically,</span> <span m='1998200'>but</span> <span m='1998770'>that's</span>
  <span m='1998980'>the</span> <span m='1999100'>idea.</span> </p><p><span m='2000600'>You</span>
  <span m='2000720'>can</span> <span m='2000870'>show--</span> <span m='2001260'>I</span>
  <span m='2001320'>would</span> <span m='2001410'>encourage</span> <span m='2001710'>you</span>
  <span m='2001770'>to</span> <span m='2001890'>try</span> <span m='2002070'>to</span>
  <span m='2002130'>work</span> <span m='2002340'>this</span> <span m='2002520'>out</span>
  <span m='2002700'>on</span> <span m='2002790'>your</span> <span m='2002970'>own--</span>
  <span m='2003250'>but</span> <span m='2003290'>you</span> <span m='2003360'>can</span>
  <span m='2003450'>show</span> <span m='2003630'>that</span> <span m='2003780'>the</span>
  <span m='2003930'>infinity</span> <span m='2004560'>norm</span> <span m='2005310'>of</span>
  <span m='2005460'>this</span> <span m='2005700'>product--</span> <span m='2009060'>infinity</span>
  <span m='2009510'>norm</span> <span m='2009750'>of</span> <span m='2009810'>this</span>
  <span m='2009960'>product</span> <span m='2010350'>is</span> <span m='2010440'>equal</span>
  <span m='2010710'>to</span> <span m='2010840'>this.</span> <span m='2013050'>And</span>
  <span m='2013140'>if</span> <span m='2013260'>I</span> <span m='2013380'>ask</span>
  <span m='2013830'>that</span> <span m='2014370'>the</span> <span m='2014550'>infinity</span>
  <span m='2015090'>norm</span> <span m='2015450'>of</span> <span m='2015540'>this</span>
  <span m='2015720'>product</span> <span m='2016040'>be</span> <span m='2016130'>smaller</span>
  <span m='2016560'>than</span> <span m='2016740'>1,</span> <span m='2017040'>that's</span>
  <span m='2017280'>guaranteed</span> <span m='2018540'>when</span> <span m='2018720'>the</span>
  <span m='2018810'>diagonal</span> <span m='2019320'>values</span> <span m='2019740'>of</span>
  <span m='2019830'>the</span> <span m='2019920'>matrix</span> <span m='2020400'>and</span>
  <span m='2020490'>absolute</span> <span m='2020910'>value</span> <span m='2021450'>are</span>
  <span m='2021540'>bigger</span> <span m='2021960'>than</span> <span m='2022650'>the</span>
  <span m='2022770'>sum</span> <span m='2023370'>of</span> <span m='2023490'>the</span>
  <span m='2023640'>off</span> <span m='2023850'>diagonal</span> <span m='2024330'>values</span>
  <span m='2024810'>in</span> <span m='2024930'>a</span> <span m='2024960'>particular</span>
  <span m='2025380'>row</span> <span m='2025680'>or</span> <span m='2025770'>a</span>
  <span m='2025800'>particular</span> <span m='2026220'>column.</span> <span m='2026670'>And</span>
  <span m='2026910'>that</span> <span m='2027030'>kind</span> <span m='2027150'>of</span>
  <span m='2027210'>matrix</span> <span m='2027600'>we</span> <span m='2027690'>call</span>
  <span m='2027870'>diagonally</span> <span m='2028530'>dominant.</span> <span m='2029370'>The</span>
  <span m='2029460'>diagonal</span> <span m='2029910'>values</span> <span m='2030330'>are</span>
  <span m='2030390'>bigger</span> <span m='2030630'>than</span> <span m='2030810'>the</span>
  <span m='2030930'>sum</span> <span m='2031320'>and</span> <span m='2031410'>absolute
  value</span> <span m='2031770'>of the</span> <span m='2032060'>off</span> <span
  m='2032370'>diagonal</span> <span m='2032850'>pieces.</span> </p><p><span m='2033570'>So</span>
  <span m='2033740'>diagonally</span> <span m='2034150'>dominant</span> <span m='2034530'>matrices,</span>
  <span m='2035490'>which</span> <span m='2035640'>come</span> <span m='2035820'>up</span>
  <span m='2035940'>quite</span> <span m='2036180'>often,</span> <span m='2037290'>can</span>
  <span m='2037410'>be--</span> <span m='2037890'>those</span> <span m='2038400'>linear</span>
  <span m='2038700'>equations</span> <span m='2039060'>based</span> <span m='2039240'>on</span>
  <span m='2039330'>those</span> <span m='2039480'>matrices</span> <span m='2039960'>can</span>
  <span m='2040050'>be</span> <span m='2040140'>solved</span> <span m='2041280'>reasonable</span>
  <span m='2041820'>efficiency</span> <span m='2042360'>using</span> <span m='2042660'>the</span>
  <span m='2042750'>Jacobi</span> <span m='2043170'>method.</span> <span m='2044670'>There</span>
  <span m='2044760'>are</span> <span m='2044790'>better</span> <span m='2045000'>methods</span>
  <span m='2045330'>to</span> <span m='2045430'>choose.</span> <span m='2045720'>I'll</span>
  <span m='2045780'>show</span> <span m='2045960'>you</span> <span m='2046080'>one</span>
  <span m='2046230'>in</span> <span m='2046350'>a</span> <span m='2046380'>second.</span>
  <span m='2047350'>But</span> <span m='2047790'>you</span> <span m='2047910'>can</span>
  <span m='2048030'>guarantee</span> <span m='2048449'>that</span> <span m='2048600'>this</span>
  <span m='2048810'>is</span> <span m='2048900'>going</span> <span m='2049020'>to</span>
  <span m='2049080'>converge</span> <span m='2049590'>to</span> <span m='2049710'>a</span>
  <span m='2049770'>solution,</span> <span m='2050550'>and</span> <span m='2050670'>that</span>
  <span m='2050820'>the</span> <span m='2050909'>solution</span> <span m='2051270'>will</span>
  <span m='2051360'>be</span> <span m='2051449'>the</span> <span m='2051540'>right</span>
  <span m='2051750'>solution</span> <span m='2052230'>to</span> <span m='2052350'>the</span>
  <span m='2052440'>linear</span> <span m='2052710'>equations</span> <span m='2053159'>you
  were</span> <span m='2053280'>trying</span> <span m='2053550'>to</span> <span m='2053639'>solve.</span>
  </p><p><span m='2059440'>So</span> <span m='2059620'>if</span> <span m='2059889'>the</span>
  <span m='2059980'>goal</span> <span m='2060280'>is</span> <span m='2060400'>just</span>
  <span m='2060580'>to</span> <span m='2060699'>turn</span> <span m='2061150'>hard</span>
  <span m='2061540'>problems</span> <span m='2062170'>into</span> <span m='2062550'>easier</span>
  <span m='2063010'>to</span> <span m='2063100'>solve</span> <span m='2063489'>problems,</span>
  <span m='2063850'>then</span> <span m='2064139'>there</span> <span m='2064270'>are</span>
  <span m='2064360'>other</span> <span m='2064659'>natural</span> <span m='2065199'>ways</span>
  <span m='2065500'>to</span> <span m='2065620'>want</span> <span m='2065739'>to</span>
  <span m='2065800'>split</span> <span m='2067050'>a</span> <span m='2067120'>matrix.</span>
  <span m='2067540'>So</span> <span m='2067840'>maybe</span> <span m='2068050'>you</span>
  <span m='2068130'>want</span> <span m='2068260'>to</span> <span m='2068320'>split</span>
  <span m='2068620'>into</span> <span m='2069310'>A</span> <span m='2069820'>lower</span>
  <span m='2070330'>triangular</span> <span m='2070929'>part</span> <span m='2071949'>which</span>
  <span m='2072100'>contains</span> <span m='2072730'>the</span> <span m='2072850'>diagonal</span>
  <span m='2073449'>elements</span> <span m='2073929'>of</span> <span m='2074080'>A,</span>
  <span m='2074829'>and</span> <span m='2075219'>an</span> <span m='2075370'>upper</span>
  <span m='2075639'>triangular</span> <span m='2076090'>part</span> <span m='2076300'>which</span>
  <span m='2076449'>has</span> <span m='2076600'>no</span> <span m='2076810'>diagonal</span>
  <span m='2077260'>elements</span> <span m='2077710'>of</span> <span m='2077840'>A.</span>
  <span m='2078280'>We</span> <span m='2078340'>just</span> <span m='2078460'>split</span>
  <span m='2078850'>this</span> <span m='2079060'>thing</span> <span m='2079239'>apart.</span>
  <span m='2081130'>And</span> <span m='2081250'>then</span> <span m='2081340'>we</span>
  <span m='2081429'>could</span> <span m='2081580'>rewrite</span> <span m='2082210'>our</span>
  <span m='2082389'>system</span> <span m='2082750'>of</span> <span m='2082840'>equations</span>
  <span m='2083370'>is</span> <span m='2083500'>an</span> <span m='2083620'>iterative</span>
  <span m='2083949'>map</span> <span m='2084310'>like</span> <span m='2084489'>this,</span>
  <span m='2084949'>L</span> <span m='2085400'>times x i</span> <span m='2085750'>plus</span>
  <span m='2086139'>1</span> <span m='2086860'>is</span> <span m='2087010'>minus</span>
  <span m='2087370'>U</span> <span m='2087540'>times</span> <span m='2087810'>x i</span>
  <span m='2087980'>plus</span> <span m='2088449'>b.</span> </p><p><span m='2090429'>All</span>
  <span m='2090580'>I</span> <span m='2090639'>have</span> <span m='2090760'>to</span>
  <span m='2090850'>do</span> <span m='2091000'>is</span> <span m='2091090'>invert</span>
  <span m='2091480'>l</span> <span m='2091810'>to</span> <span m='2091960'>find</span>
  <span m='2092199'>my</span> <span m='2092320'>next</span> <span m='2092590'>iteration.</span>
  <span m='2093550'>And</span> <span m='2093670'>how</span> <span m='2094000'>expensive</span>
  <span m='2094810'>computationally</span> <span m='2095590'>is</span> <span m='2095739'>it</span>
  <span m='2095860'>to</span> <span m='2096010'>solve</span> <span m='2096610'>a</span>
  <span m='2096670'>system</span> <span m='2097030'>of</span> <span m='2097150'>equations</span>
  <span m='2097760'>which</span> <span m='2097840'>is</span> <span m='2097990'>triangular?</span>
  <span m='2100360'>This is</span> <span m='2100460'>a</span> <span m='2100550'>process</span>
  <span m='2100930'>we</span> <span m='2101050'>call</span> <span m='2101230'>back</span>
  <span m='2101560'>substitution.</span> <span m='2102630'>Its</span> <span m='2102880'>order--</span>
  </p><p><span m='2103540'>AUDIENCE:</span> <span m='2103772'>N</span> <span m='2104005'>squared.</span>
  </p><p><span m='2104470'>JAMES W. SWAN:</span> <span m='2104545'>--N</span> <span
  m='2104620'>squared.</span> <span m='2105820'>So</span> <span m='2106120'>we</span>
  <span m='2106270'>still</span> <span m='2106480'>beat</span> <span m='2106790'>N</span>
  <span m='2107050'>cubed.</span> <span m='2108160'>One</span> <span m='2108340'>would</span>
  <span m='2108490'>hope</span> <span m='2109800'>that</span> <span m='2109990'>it</span>
  <span m='2110050'>doesn't</span> <span m='2110250'>require</span> <span m='2110530'>too</span>
  <span m='2110740'>many</span> <span m='2110950'>iterations</span> <span m='2111640'>to</span>
  <span m='2111790'>do</span> <span m='2112030'>this.</span> <span m='2112420'>But</span>
  <span m='2112570'>in</span> <span m='2112660'>principle,</span> <span m='2113360'>we</span>
  <span m='2113380'>can</span> <span m='2113500'>do</span> <span m='2113590'>this</span>
  <span m='2113740'>order</span> <span m='2113950'>N</span> <span m='2114070'>squared</span>
  <span m='2114430'>operations</span> <span m='2115160'>many</span> <span m='2115270'>times.</span>
  <span m='2116500'>And</span> <span m='2117310'>it'll</span> <span m='2117490'>turn</span>
  <span m='2117700'>out</span> <span m='2117820'>that</span> <span m='2117940'>this</span>
  <span m='2118090'>sort</span> <span m='2118330'>of</span> <span m='2118450'>a</span>
  <span m='2118510'>map</span> <span m='2118840'>converges</span> <span m='2119770'>to</span>
  <span m='2119890'>the</span> <span m='2120010'>solution</span> <span m='2120520'>that</span>
  <span m='2120640'>we're</span> <span m='2120760'>after.</span> </p><p><span m='2122080'>It</span>
  <span m='2122170'>converges</span> <span m='2122650'>when</span> <span m='2122830'>matrices</span>
  <span m='2123430'>are</span> <span m='2123550'>either</span> <span m='2123760'>diagonally</span>
  <span m='2124240'>dominant</span> <span m='2124750'>as</span> <span m='2124930'>before,</span>
  <span m='2125710'>or</span> <span m='2125860'>they're</span> <span m='2125980'>symmetric</span>
  <span m='2126640'>and</span> <span m='2127030'>they're</span> <span m='2127240'>positive</span>
  <span m='2127780'>definite.</span> <span m='2128470'>Positive</span> <span m='2128830'>definite</span>
  <span m='2129160'>means</span> <span m='2129410'>all</span> <span m='2129640'>the</span>
  <span m='2129820'>eigenvalues</span> <span m='2130630'>of</span> <span m='2130720'>the</span>
  <span m='2130810'>matrix</span> <span m='2131680'>are</span> <span m='2132280'>bigger</span>
  <span m='2132640'>than</span> <span m='2132820'>0.</span> <span m='2140680'>So</span>
  <span m='2140800'>try the</span> <span m='2140940'>iterative</span> <span m='2141760'>method</span>
  <span m='2142060'>solving</span> <span m='2142600'>some</span> <span m='2142810'>equations</span>
  <span m='2143380'>and</span> <span m='2143470'>see</span> <span m='2143650'>how</span>
  <span m='2143770'>we</span> <span m='2143860'>convert.</span> <span m='2144250'>Yes?</span>
  </p><p><span m='2144640'>AUDIENCE:</span> <span m='2144796'>How</span> <span m='2144952'>do
  you</span> <span m='2145580'>justify</span> <span m='2146050'>ignoring</span> <span
  m='2146520'>the diagonal</span> <span m='2146990'>elements</span> <span m='2147460'>in
  that</span> <span m='2147930'>method?</span> </p><p><span m='2151120'>JAMES W. SWAN:</span>
  <span m='2151270'>So</span> <span m='2151660'>the</span> <span m='2151840'>question</span>
  <span m='2152170'>was,</span> <span m='2152320'>how</span> <span m='2152470'>do</span>
  <span m='2152530'>you</span> <span m='2152680'>justify</span> <span m='2153370'>ignoring</span>
  <span m='2154000'>the</span> <span m='2154090'>diagonal</span> <span m='2154540'>elements</span>
  <span m='2154960'>in</span> <span m='2155050'>this</span> <span m='2155200'>method.</span>
  <span m='2156300'>Maybe</span> <span m='2156590'>I</span> <span m='2156620'>was</span>
  <span m='2156700'>going</span> <span m='2156820'>too</span> <span m='2156940'>fast</span>
  <span m='2157240'>or</span> <span m='2157310'>I</span> <span m='2157330'>misspoke.</span>
  <span m='2157810'>So</span> <span m='2158620'>I'm</span> <span m='2158740'>going</span>
  <span m='2158860'>to</span> <span m='2158920'>split A</span> <span m='2159340'>into</span>
  <span m='2160120'>a</span> <span m='2160210'>lower</span> <span m='2160570'>triangular</span>
  <span m='2161050'>matrix</span> <span m='2161500'>that</span> <span m='2161980'>has</span>
  <span m='2162460'>all</span> <span m='2162670'>the</span> <span m='2162790'>diagonal</span>
  <span m='2163240'>elements,</span> <span m='2164200'>and</span> <span m='2164350'>U</span>
  <span m='2165250'>is</span> <span m='2165400'>the</span> <span m='2165580'>upper</span>
  <span m='2165850'>parts</span> <span m='2166690'>with</span> <span m='2166840'>none</span>
  <span m='2167020'>of</span> <span m='2167080'>those</span> <span m='2167410'>diagonal</span>
  <span m='2167770'>elements</span> <span m='2168140'>on</span> <span m='2168240'>it.</span>
  <span m='2168360'>Does that</span> <span m='2168610'>make</span> <span m='2168730'>sense?</span>
  </p><p><span m='2169000'>AUDIENCE:</span> <span m='2169187'>Yeah.</span> </p><p><span
  m='2169750'>JAMES W. SWAN:</span> <span m='2169855'>Thank</span> <span m='2169960'>you</span>
  <span m='2170080'>for</span> <span m='2170380'>asking</span> <span m='2170680'>that</span>
  <span m='2170800'>question.</span> <span m='2171180'>I</span> <span m='2171220'>hope</span>
  <span m='2171610'>that's</span> <span m='2171850'>clear.</span> <span m='2172430'>l</span>
  <span m='2173230'>holds</span> <span m='2173500'>onto</span> <span m='2173770'>the</span>
  <span m='2173860'>diagonal</span> <span m='2174280'>pieces</span> <span m='2174700'>and</span>
  <span m='2174910'>U</span> <span m='2175690'>takes</span> <span m='2175990'>those</span>
  <span m='2176300'>away.</span> <span m='2179790'>So</span> <span m='2179890'>let's</span>
  <span m='2180040'>try</span> <span m='2180260'>it.</span> </p><p><span m='2180490'>On</span>
  <span m='2180610'>a</span> <span m='2180640'>matrix</span> <span m='2181030'>like</span>
  <span m='2181210'>this,</span> <span m='2181660'>the</span> <span m='2181820'>exact</span>
  <span m='2182110'>solution</span> <span m='2183310'>to</span> <span m='2183430'>this</span>
  <span m='2183550'>system</span> <span m='2184000'>of</span> <span m='2184090'>equations</span>
  <span m='2184600'>is</span> <span m='2184690'>3/4,</span> <span m='2185480'>1/2,</span>
  <span m='2186130'>and</span> <span m='2186220'>1/4.</span> <span m='2187210'>All</span>
  <span m='2187280'>right,</span> <span m='2187410'>we'll</span> <span m='2187510'>try</span>
  <span m='2187780'>Jacobi,</span> <span m='2188890'>we'll</span> <span m='2188980'>have</span>
  <span m='2189130'>to</span> <span m='2189190'>give</span> <span m='2189340'>it</span>
  <span m='2189430'>some</span> <span m='2189610'>initial</span> <span m='2189910'>guess</span>
  <span m='2190150'>for</span> <span m='2190270'>the</span> <span m='2190360'>solution,</span>
  <span m='2190930'>right?</span> <span m='2191530'>We're</span> <span m='2191620'>talking</span>
  <span m='2191800'>about</span> <span m='2191920'>places</span> <span m='2193150'>where</span>
  <span m='2193360'>you</span> <span m='2193450'>can</span> <span m='2193600'>derive</span>
  <span m='2193990'>those</span> <span m='2194200'>initial</span> <span m='2194500'>guesses</span>
  <span m='2194890'>from</span> <span m='2196330'>later</span> <span m='2196600'>on</span>
  <span m='2196690'>in</span> <span m='2196750'>the</span> <span m='2196840'>course,</span>
  <span m='2197160'>but we</span> <span m='2197260'>have</span> <span m='2197380'>to</span>
  <span m='2197500'>start</span> <span m='2198190'>the</span> <span m='2198340'>iterative</span>
  <span m='2198700'>process</span> <span m='2199300'>with</span> <span m='2199450'>some</span>
  <span m='2200060'>guess</span> <span m='2200590'>at</span> <span m='2200710'>the</span>
  <span m='2200830'>solutions.</span> </p><p><span m='2201730'>So</span> <span m='2201850'>here's</span>
  <span m='2202090'>an</span> <span m='2202180'>initial</span> <span m='2202510'>guess.</span>
  <span m='2203380'>We'll</span> <span m='2203530'>apply</span> <span m='2203830'>this</span>
  <span m='2204070'>map.</span> <span m='2204550'>Here's</span> <span m='2204760'>Gauss-Seidel</span>
  <span m='2205410'>with</span> <span m='2205540'>the</span> <span m='2205630'>same</span>
  <span m='2205930'>initial</span> <span m='2206260'>guess,</span> <span m='2207010'>and</span>
  <span m='2207100'>we'll</span> <span m='2207220'>apply</span> <span m='2207550'>this</span>
  <span m='2207760'>map.</span> <span m='2208670'>They're</span> <span m='2208780'>both</span>
  <span m='2209110'>linearly</span> <span m='2209950'>convergent,</span> <span m='2212120'>so</span>
  <span m='2212200'>the</span> <span m='2212290'>relative</span> <span m='2212710'>error</span>
  <span m='2212920'>will</span> <span m='2213040'>go</span> <span m='2213250'>down</span>
  <span m='2213700'>by</span> <span m='2213880'>a</span> <span m='2213940'>fixed</span>
  <span m='2214300'>factor</span> <span m='2215350'>after</span> <span m='2215650'>each</span>
  <span m='2216160'>iteration.</span> </p><p><span m='2217660'>Iteration</span> <span
  m='2218140'>one,</span> <span m='2218410'>the</span> <span m='2218530'>relative</span>
  <span m='2218860'>error in</span> <span m='2219010'>Jacobi</span> <span m='2219460'>will</span>
  <span m='2219550'>be</span> <span m='2219670'>38%.</span> <span m='2220470'>In</span>
  <span m='2220800'>Gauss-Seidel,</span> <span m='2221260'>it'll be</span> <span m='2221680'>40%.</span>
  <span m='2222910'>If</span> <span m='2223000'>we</span> <span m='2223120'>apply</span>
  <span m='2223510'>this</span> <span m='2223750'>all</span> <span m='2223840'>the</span>
  <span m='2223900'>way</span> <span m='2223990'>down</span> <span m='2224170'>to</span>
  <span m='2224290'>10</span> <span m='2224500'>iterations,</span> <span m='2225190'>the</span>
  <span m='2225280'>relative</span> <span m='2225720'>error</span> <span m='2226630'>Jacobi</span>
  <span m='2227110'>will</span> <span m='2227200'>be</span> <span m='2227320'>1.7%,</span>
  <span m='2228560'>and</span> <span m='2228690'>the</span> <span m='2228800'>relative</span>
  <span m='2228910'>error in</span> <span m='2229130'>Gauss-Seidel</span> <span m='2229720'>0.08%.</span>
  </p><p><span m='2231360'>And</span> <span m='2231460'>we</span> <span m='2231550'>can</span>
  <span m='2231670'>go</span> <span m='2231850'>on</span> <span m='2232150'>and</span>
  <span m='2232270'>on</span> <span m='2232480'>with</span> <span m='2232570'>these</span>
  <span m='2232750'>iterations</span> <span m='2233320'>if</span> <span m='2233440'>we</span>
  <span m='2233500'>want</span> <span m='2234550'>until</span> <span m='2234760'>we</span>
  <span m='2234910'>get</span> <span m='2235600'>sufficiently</span> <span m='2236200'>converged,</span>
  <span m='2236680'>we</span> <span m='2236740'>get</span> <span m='2236830'>to</span>
  <span m='2236950'>a</span> <span m='2236980'>point</span> <span m='2237220'>where</span>
  <span m='2237400'>the</span> <span m='2237520'>relative</span> <span m='2238000'>error</span>
  <span m='2238270'>is</span> <span m='2238420'>small</span> <span m='2238810'>enough</span>
  <span m='2239320'>that</span> <span m='2239470'>we're</span> <span m='2239620'>happy</span>
  <span m='2239980'>to</span> <span m='2240160'>accept</span> <span m='2240550'>this</span>
  <span m='2240760'>answer</span> <span m='2241180'>as</span> <span m='2241360'>a</span>
  <span m='2241420'>solution</span> <span m='2242590'>to</span> <span m='2242710'>our</span>
  <span m='2242830'>system</span> <span m='2243190'>of</span> <span m='2243280'>equations.</span>
  <span m='2244660'>So</span> <span m='2244780'>we</span> <span m='2244870'>traded</span>
  <span m='2245830'>the</span> <span m='2245950'>burden</span> <span m='2246760'>of</span>
  <span m='2246880'>doing</span> <span m='2247150'>all</span> <span m='2247240'>these</span>
  <span m='2247420'>calculations</span> <span m='2248200'>to</span> <span m='2248320'>do</span>
  <span m='2248450'>elimination</span> <span m='2249810'>for</span> <span m='2250430'>a</span>
  <span m='2250570'>faster,</span> <span m='2252650'>less</span> <span m='2252910'>computationally</span>
  <span m='2253630'>complex</span> <span m='2254080'>methodology.</span> <span m='2255250'>But</span>
  <span m='2255490'>the</span> <span m='2255580'>trade</span> <span m='2255895'>off</span>
  <span m='2256210'>was</span> <span m='2256540'>we</span> <span m='2256630'>don't</span>
  <span m='2256780'>get</span> <span m='2256910'>an</span> <span m='2257000'>exact</span>
  <span m='2257680'>solution</span> <span m='2258160'>anymore.</span> <span m='2258620'>We're</span>
  <span m='2258720'>going</span> <span m='2258730'>to</span> <span m='2258790'>have</span>
  <span m='2258940'>finite</span> <span m='2259390'>precision</span> <span m='2260140'>in</span>
  <span m='2260350'>the</span> <span m='2260440'>result,</span> <span m='2260890'>and</span>
  <span m='2260980'>we</span> <span m='2261070'>have</span> <span m='2261220'>to</span>
  <span m='2261340'>specify</span> <span m='2262060'>the</span> <span m='2262180'>tolerance</span>
  <span m='2262750'>that</span> <span m='2262870'>we</span> <span m='2262960'>want</span>
  <span m='2263110'>to</span> <span m='2263170'>converge</span> <span m='2263710'>to.</span>
  </p><p><span m='2264820'>We're</span> <span m='2264910'>going</span> <span m='2265030'>to</span>
  <span m='2265090'>see</span> <span m='2265270'>now--</span> <span m='2265450'>this</span>
  <span m='2266080'>is</span> <span m='2266170'>the</span> <span m='2266260'>hook</span>
  <span m='2266440'>into</span> <span m='2266590'>the</span> <span m='2266680'>next</span>
  <span m='2266890'>part</span> <span m='2267040'>of</span> <span m='2267100'>that</span>
  <span m='2267250'>class--</span> <span m='2267860'>we're</span> <span m='2267880'>going</span>
  <span m='2268000'>to</span> <span m='2268060'>talk</span> <span m='2268330'>about</span>
  <span m='2268630'>solutions</span> <span m='2269260'>of</span> <span m='2269440'>nonlinear</span>
  <span m='2270070'>equations</span> <span m='2270740'>next</span> <span m='2271660'>for</span>
  <span m='2271810'>which</span> <span m='2272260'>there</span> <span m='2272410'>are</span>
  <span m='2272470'>almost</span> <span m='2272740'>no</span> <span m='2273070'>non-linear</span>
  <span m='2273610'>equations</span> <span m='2274090'>that</span> <span m='2274210'>we</span>
  <span m='2274270'>can</span> <span m='2274390'>solve</span> <span m='2274690'>exactly.</span>
  <span m='2275140'>They</span> <span m='2275290'>all</span> <span m='2275590'>have</span>
  <span m='2275740'>to be</span> <span m='2275920'>solved</span> <span m='2276300'>using</span>
  <span m='2276470'>these</span> <span m='2276900'>iterative</span> <span m='2277070'>methods.</span>
  <span m='2278980'>You</span> <span m='2279040'>can</span> <span m='2279130'>use</span>
  <span m='2279250'>these</span> <span m='2279430'>iterative</span> <span m='2279790'>methods</span>
  <span m='2280240'>for</span> <span m='2280450'>linear</span> <span m='2280750'>equations.</span>
  <span m='2281320'>It's</span> <span m='2281410'>very</span> <span m='2281710'>common</span>
  <span m='2282010'>to</span> <span m='2282100'>do</span> <span m='2282250'>it</span>
  <span m='2282340'>this</span> <span m='2282550'>way.</span> </p><p><span m='2283120'>In</span>
  <span m='2283210'>my</span> <span m='2283360'>group,</span> <span m='2283600'>we</span>
  <span m='2283690'>solve</span> <span m='2283900'>lots</span> <span m='2284140'>of</span>
  <span m='2284230'>systems</span> <span m='2284620'>of</span> <span m='2284740'>linear</span>
  <span m='2285040'>equations</span> <span m='2285520'>associated</span> <span m='2285970'>with</span>
  <span m='2286090'>hydrodynamic</span> <span m='2286750'>problems.</span> <span m='2287860'>These</span>
  <span m='2288310'>come</span> <span m='2288490'>up</span> <span m='2288730'>when</span>
  <span m='2288880'>you're</span> <span m='2288970'>talking</span> <span m='2289330'>about,</span>
  <span m='2290670'>say,</span> <span m='2291070'>low</span> <span m='2291280'>Reynolds</span>
  <span m='2291550'>number</span> <span m='2291820'>flows,</span> <span m='2292330'>which</span>
  <span m='2292510'>are</span> <span m='2292630'>linear</span> <span m='2293590'>sorts</span>
  <span m='2293830'>of</span> <span m='2293920'>fluid</span> <span m='2294280'>flow</span>
  <span m='2294550'>problems.</span> <span m='2295420'>They're</span> <span m='2295570'>big.</span>
  <span m='2295990'>It's</span> <span m='2296230'>really</span> <span m='2296500'>hard</span>
  <span m='2296740'>to</span> <span m='2296890'>do</span> <span m='2297070'>Gaussian</span>
  <span m='2297480'>elimination,</span> <span m='2298050'>so</span> <span m='2299010'>you</span>
  <span m='2299160'>apply</span> <span m='2299440'>different</span> <span m='2299620'>iterative</span>
  <span m='2300050'>methods.</span> </p><p><span m='2300180'>You</span> <span m='2300270'>can
  do</span> <span m='2300340'>Gauss-Seidel.</span> <span m='2300910'>You</span> <span
  m='2301030'>can</span> <span m='2301120'>do</span> <span m='2301210'>Jacobi.</span>
  <span m='2302120'>We'll</span> <span m='2302320'>learn</span> <span m='2302530'>about</span>
  <span m='2302800'>more</span> <span m='2302980'>advanced</span> <span m='2303430'>ones</span>
  <span m='2303790'>like</span> <span m='2304360'>PCG,</span> <span m='2305170'>which</span>
  <span m='2305330'>you're</span> <span m='2305410'>applying</span> <span m='2305890'>on</span>
  <span m='2306010'>your</span> <span m='2306130'>homework</span> <span m='2306460'>now,</span>
  <span m='2306880'>and you</span> <span m='2306970'>should</span> <span m='2307120'>be</span>
  <span m='2307180'>seeing</span> <span m='2308200'>that</span> <span m='2308320'>it</span>
  <span m='2308380'>converges</span> <span m='2308950'>relatively</span> <span m='2309460'>quickly</span>
  <span m='2309970'>in</span> <span m='2310060'>cases</span> <span m='2310540'>where</span>
  <span m='2311080'>exact</span> <span m='2311370'>elimination</span> <span m='2311990'>doesn't</span>
  <span m='2312170'>work.</span> <span m='2312430'>We'll</span> <span m='2312550'>learn,</span>
  <span m='2312790'>actually,</span> <span m='2313090'>how</span> <span m='2313180'>to</span>
  <span m='2313300'>do</span> <span m='2313540'>that</span> <span m='2313720'>method.</span>
  <span m='2314050'>That's</span> <span m='2314230'>one</span> <span m='2314350'>that</span>
  <span m='2314440'>we</span> <span m='2314560'>apply</span> <span m='2314800'>in</span>
  <span m='2314890'>my</span> <span m='2315040'>own</span> <span m='2315160'>group.</span>
  <span m='2315400'>It's</span> <span m='2315520'>pretty</span> <span m='2315730'>common</span>
  <span m='2316030'>to</span> <span m='2316180'>use</span> <span m='2316450'>out</span>
  <span m='2316600'>there.</span> <span m='2318070'>Yes?</span> </p><p><span m='2318370'>AUDIENCE:</span>
  <span m='2318600'>One</span> <span m='2318830'>question,</span> <span m='2319290'>is
  that that</span> <span m='2319750'>Gauss,</span> <span m='2320210'>[INAUDIBLE]</span>
  </p><p><span m='2323440'>JAMES W. SWAN:</span> <span m='2323560'>Order</span> <span
  m='2323680'>N</span> <span m='2323830'>squared.</span> </p><p><span m='2325930'>AUDIENCE:</span>
  <span m='2326110'>Yeah,</span> <span m='2326290'>that's what</span> <span m='2326650'>I
  meant.</span> <span m='2327708'>So</span> <span m='2328196'>now we've</span> <span
  m='2328684'>got an</span> <span m='2329172'>[INAUDIBLE].</span> <span m='2330148'>So
  we</span> <span m='2330636'>basically have</span> <span m='2331124'>[INAUDIBLE]</span>
  <span m='2332100'>iterations,</span> <span m='2332590'>right?</span> </p><p><span
  m='2334486'>JAMES W. SWAN:</span> <span m='2334723'>This</span> <span m='2334960'>is</span>
  <span m='2335050'>a</span> <span m='2335080'>wonderful</span> <span m='2335440'>question.</span>
  <span m='2336240'>So</span> <span m='2337230'>this</span> <span m='2337630'>is</span>
  <span m='2337990'>a</span> <span m='2338320'>pathological</span> <span m='2339040'>problem</span>
  <span m='2339490'>in</span> <span m='2339640'>the</span> <span m='2339730'>sense</span>
  <span m='2340120'>that</span> <span m='2341290'>it</span> <span m='2341380'>requires</span>
  <span m='2342220'>a</span> <span m='2342280'>lot</span> <span m='2342490'>of</span>
  <span m='2342550'>calculations</span> <span m='2343300'>to</span> <span m='2343360'>get</span>
  <span m='2343480'>an</span> <span m='2343570'>iterative</span> <span m='2343960'>solution</span>
  <span m='2344610'>here.</span> <span m='2345550'>We</span> <span m='2345670'>haven't</span>
  <span m='2345880'>gotten</span> <span m='2346120'>to</span> <span m='2346270'>an</span>
  <span m='2346420'>end</span> <span m='2346840'>that's</span> <span m='2347110'>big</span>
  <span m='2347380'>enough</span> <span m='2348220'>that</span> <span m='2348340'>the</span>
  <span m='2348430'>computational</span> <span m='2349100'>complexities</span> <span
  m='2350290'>crossover.</span> <span m='2351700'>So</span> <span m='2351850'>for</span>
  <span m='2352000'>small</span> <span m='2352360'>Ns,</span> <span m='2353530'>probably</span>
  <span m='2353980'>the</span> <span m='2354310'>factor</span> <span m='2354670'>in</span>
  <span m='2354790'>front</span> <span m='2355000'>of</span> <span m='2355080'>N--</span>
  <span m='2355810'>whatever</span> <span m='2356080'>number</span> <span m='2356380'>that</span>
  <span m='2356620'>is--</span> <span m='2357200'>and</span> <span m='2357330'>maybe</span>
  <span m='2357520'>even</span> <span m='2357760'>the</span> <span m='2357850'>smaller</span>
  <span m='2358300'>factors,</span> <span m='2359000'>order</span> <span m='2359260'>N</span>
  <span m='2359410'>squared</span> <span m='2359860'>factors</span> <span m='2360400'>on</span>
  <span m='2360550'>that</span> <span m='2360700'>order</span> <span m='2360940'>N</span>
  <span m='2361090'>cubed,</span> <span m='2361240'>play</span> <span m='2361450'>a</span>
  <span m='2361480'>big</span> <span m='2361690'>role</span> <span m='2362080'>in</span>
  <span m='2362170'>how</span> <span m='2362320'>long</span> <span m='2362440'>it</span>
  <span m='2362500'>takes</span> <span m='2362740'>to</span> <span m='2362830'>actually</span>
  <span m='2363280'>complete</span> <span m='2363670'>this</span> <span m='2363880'>thing.</span>
  <span m='2364660'>But</span> <span m='2364810'>modern</span> <span m='2365200'>problems</span>
  <span m='2365680'>are</span> <span m='2365770'>so</span> <span m='2366040'>big</span>
  <span m='2367000'>that</span> <span m='2367120'>we</span> <span m='2367210'>almost</span>
  <span m='2367510'>always</span> <span m='2368140'>are</span> <span m='2368290'>running</span>
  <span m='2368650'>out</span> <span m='2368750'>to</span> <span m='2369000'>Ns</span>
  <span m='2369460'>that</span> <span m='2369580'>are</span> <span m='2369670'>large</span>
  <span m='2370060'>enough</span> <span m='2370480'>that</span> <span m='2370600'>we</span>
  <span m='2370690'>see</span> <span m='2370840'>a</span> <span m='2370900'>crossover.</span>
  </p><p><span m='2371590'>You'll</span> <span m='2371740'>see</span> <span m='2371920'>this</span>
  <span m='2372100'>in</span> <span m='2372190'>your</span> <span m='2372280'>homework</span>
  <span m='2372890'>this</span> <span m='2373130'>week.</span> <span m='2374110'>You</span>
  <span m='2374260'>won't</span> <span m='2374620'>see</span> <span m='2374830'>this</span>
  <span m='2375010'>crossover</span> <span m='2375430'>at</span> <span m='2375520'>N</span>
  <span m='2375670'>equals</span> <span m='2375870'>3.</span> <span m='2376030'>You're</span>
  <span m='2376090'>going</span> <span m='2376200'>to</span> <span m='2376270'>see</span>
  <span m='2376360'>it</span> <span m='2376450'>out</span> <span m='2376600'>at</span>
  <span m='2376720'>N</span> <span m='2376910'>equals</span> <span m='2377350'>500</span>
  <span m='2378220'>or</span> <span m='2378430'>1,200,</span> <span m='2380110'>big</span>
  <span m='2380740'>problems.</span> <span m='2381600'>Then</span> <span m='2381910'>we're</span>
  <span m='2382060'>going</span> <span m='2382180'>to</span> <span m='2382270'>encounter</span>
  <span m='2382750'>this</span> <span m='2382930'>crossover.</span> <span m='2383210'>That's</span>
  <span m='2383320'>a</span> <span m='2383380'>wonderful</span> <span m='2383710'>question.</span>
  <span m='2384100'>So</span> <span m='2384280'>first</span> <span m='2384500'>small</span>
  <span m='2384970'>system</span> <span m='2385360'>sizes,</span> <span m='2388240'>iterative</span>
  <span m='2388540'>methods</span> <span m='2389110'>maybe</span> <span m='2389470'>don't</span>
  <span m='2389730'>buy</span> <span m='2390020'>you</span> <span m='2390430'>much.</span>
  </p><p><span m='2391120'>I</span> <span m='2391150'>suppose</span> <span m='2391390'>it</span>
  <span m='2391450'>depends</span> <span m='2391690'>on</span> <span m='2391750'>the</span>
  <span m='2391870'>application</span> <span m='2392410'>though,</span> <span m='2392780'>right?</span>
  <span m='2393000'>If</span> <span m='2393010'>you're</span> <span m='2393100'>doing</span>
  <span m='2393340'>something</span> <span m='2394510'>that</span> <span m='2394630'>involves</span>
  <span m='2395170'>solving</span> <span m='2395770'>problems</span> <span m='2396430'>on</span>
  <span m='2397510'>embedded</span> <span m='2397930'>hardware,</span> <span m='2398860'>in</span>
  <span m='2399010'>some</span> <span m='2399190'>sort</span> <span m='2399370'>of</span>
  <span m='2399460'>sensor</span> <span m='2400390'>or</span> <span m='2400840'>control</span>
  <span m='2401420'>valve,</span> <span m='2402460'>there</span> <span m='2402550'>may</span>
  <span m='2402670'>be</span> <span m='2402790'>very</span> <span m='2403030'>limited</span>
  <span m='2403600'>memory</span> <span m='2404230'>or</span> <span m='2404350'>computational</span>
  <span m='2404725'>capacity</span> <span m='2405580'>available</span> <span m='2406000'>to</span>
  <span m='2406120'>you.</span> <span m='2406290'>And you</span> <span m='2406360'>may</span>
  <span m='2406660'>actually</span> <span m='2406960'>apply</span> <span m='2407350'>an</span>
  <span m='2407740'>iterative</span> <span m='2408190'>method</span> <span m='2408490'>like</span>
  <span m='2408760'>this</span> <span m='2409810'>to</span> <span m='2410770'>a</span>
  <span m='2410830'>problem</span> <span m='2411220'>that that</span> <span m='2411610'>controller</span>
  <span m='2412120'>needs</span> <span m='2412360'>to</span> <span m='2412480'>solve,</span>
  <span m='2412750'>for</span> <span m='2412870'>example.</span> <span m='2415330'>It</span>
  <span m='2415420'>just</span> <span m='2415580'>may</span> <span m='2415680'>not</span>
  <span m='2415840'>have</span> <span m='2415990'>the</span> <span m='2416320'>capability</span>
  <span m='2417370'>of</span> <span m='2417460'>storing</span> <span m='2418120'>and</span>
  <span m='2418200'>inverting</span> <span m='2419350'>what</span> <span m='2419500'>we</span>
  <span m='2419650'>would</span> <span m='2419740'>consider,</span> <span m='2420370'>today,</span>
  <span m='2420880'>a</span> <span m='2420940'>relatively</span> <span m='2421450'>small</span>
  <span m='2422650'>matrix</span> <span m='2423130'>because</span> <span m='2423490'>the</span>
  <span m='2423730'>hardware</span> <span m='2424810'>doesn't</span> <span m='2425350'>have</span>
  <span m='2425500'>that</span> <span m='2425620'>sort</span> <span m='2425770'>of</span>
  <span m='2425860'>capability.</span> </p><p><span m='2426670'>So</span> <span m='2428080'>there</span>
  <span m='2428200'>could</span> <span m='2428290'>be</span> <span m='2428380'>cases</span>
  <span m='2428710'>where</span> <span m='2428800'>you</span> <span m='2428890'>might</span>
  <span m='2429040'>choose</span> <span m='2429370'>something</span> <span m='2429730'>that's</span>
  <span m='2429880'>slower</span> <span m='2430450'>but</span> <span m='2430690'>feasible,</span>
  <span m='2432250'>versus</span> <span m='2432550'>something</span> <span m='2433000'>that's</span>
  <span m='2433300'>faster</span> <span m='2434050'>and</span> <span m='2434200'>exact,</span>
  <span m='2434650'>because</span> <span m='2435730'>there</span> <span m='2435820'>are</span>
  <span m='2435850'>other</span> <span m='2436000'>constraints.</span> <span m='2436990'>They</span>
  <span m='2437110'>do</span> <span m='2437260'>exist,</span> <span m='2437650'>but</span>
  <span m='2438460'>modern</span> <span m='2439210'>computers</span> <span m='2439630'>are</span>
  <span m='2439690'>pretty</span> <span m='2439900'>efficient.</span> <span m='2440560'>Your</span>
  <span m='2440710'>cell</span> <span m='2440950'>phone</span> <span m='2441250'>is</span>
  <span m='2441910'>faster</span> <span m='2442420'>than</span> <span m='2442660'>the</span>
  <span m='2442720'>fastest</span> <span m='2443140'>computers</span> <span m='2443590'>in</span>
  <span m='2443650'>the</span> <span m='2443740'>world</span> <span m='2444460'>20</span>
  <span m='2444760'>years</span> <span m='2444940'>ago.</span> <span m='2446410'>We're</span>
  <span m='2447130'>doing</span> <span m='2447280'>OK.</span> <span m='2447550'>So</span>
  <span m='2447670'>we've</span> <span m='2447730'>got</span> <span m='2447830'>to</span>
  <span m='2447890'>get</span> <span m='2447970'>out</span> <span m='2448060'>to</span>
  <span m='2448150'>big</span> <span m='2448480'>system</span> <span m='2448810'>sizes,</span>
  <span m='2449170'>big</span> <span m='2449330'>problem</span> <span m='2449890'>sizes,</span>
  <span m='2450340'>before</span> <span m='2450640'>this</span> <span m='2450970'>starts</span>
  <span m='2451300'>to</span> <span m='2451390'>pay</span> <span m='2451600'>off.</span>
  <span m='2452060'>But</span> <span m='2452620'>it</span> <span m='2452680'>does</span>
  <span m='2452920'>for</span> <span m='2453070'>many</span> <span m='2453220'>practical</span>
  <span m='2453640'>problems.</span> </p><p><span m='2455210'>OK</span> <span m='2455390'>I'll</span>
  <span m='2456440'>close</span> <span m='2456740'>with</span> <span m='2456890'>this,</span>
  <span m='2457100'>because</span> <span m='2457550'>this</span> <span m='2458180'>is</span>
  <span m='2458270'>the</span> <span m='2458390'>hook</span> <span m='2458810'>into</span>
  <span m='2459020'>solving</span> <span m='2459410'>nonlinear</span> <span m='2459920'>equations.</span>
  <span m='2463690'>So</span> <span m='2463810'>I</span> <span m='2463870'>showed</span>
  <span m='2464140'>you</span> <span m='2464230'>these</span> <span m='2464440'>two</span>
  <span m='2464680'>iterative</span> <span m='2465040'>methods,</span> <span m='2465370'>and</span>
  <span m='2465460'>they</span> <span m='2465550'>kind</span> <span m='2465670'>of</span>
  <span m='2465730'>had</span> <span m='2466000'>stringent</span> <span m='2467080'>requirements</span>
  <span m='2467830'>for</span> <span m='2467980'>when</span> <span m='2468220'>they</span>
  <span m='2468370'>were</span> <span m='2468550'>actually</span> <span m='2469150'>going</span>
  <span m='2469270'>to</span> <span m='2469360'>converge,</span> <span m='2470080'>right?</span>
  <span m='2470770'>I</span> <span m='2470860'>had</span> <span m='2470950'>to</span>
  <span m='2471040'>have</span> <span m='2471190'>a</span> <span m='2471230'>diagonally</span>
  <span m='2471820'>dominant</span> <span m='2472240'>system</span> <span m='2472600'>of</span>
  <span m='2472720'>equations</span> <span m='2473350'>for</span> <span m='2473560'>Jacobi</span>
  <span m='2474190'>to</span> <span m='2474370'>converge.</span> <span m='2475460'>I</span>
  <span m='2475560'>had</span> <span m='2475660'>to</span> <span m='2475760'>have</span>
  <span m='2475960'>diagonal</span> <span m='2476410'>dominance</span> <span m='2477120'>or</span>
  <span m='2477370'>symmetric</span> <span m='2477940'>positive</span> <span m='2478360'>definite</span>
  <span m='2478720'>matrices.</span> <span m='2479260'>These</span> <span m='2479350'>things</span>
  <span m='2479650'>exist</span> <span m='2480130'>and</span> <span m='2480280'>they</span>
  <span m='2480460'>come</span> <span m='2480610'>up</span> <span m='2480730'>in</span>
  <span m='2480820'>lots</span> <span m='2481000'>of</span> <span m='2481060'>physical</span>
  <span m='2481390'>problems,</span> <span m='2481750'>but</span> <span m='2481840'>I</span>
  <span m='2481900'>had</span> <span m='2482020'>to</span> <span m='2482080'>have</span>
  <span m='2482380'>it</span> <span m='2482980'>in</span> <span m='2483100'>order</span>
  <span m='2483280'>for</span> <span m='2483430'>Gauss-Seidel</span> <span m='2484300'>to</span>
  <span m='2484450'>converge.</span> </p><p><span m='2485050'>What</span> <span m='2485200'>if</span>
  <span m='2485320'>I</span> <span m='2485500'>have</span> <span m='2485650'>a</span>
  <span m='2485710'>system</span> <span m='2486010'>of</span> <span m='2486100'>equations</span>
  <span m='2486700'>that</span> <span m='2486820'>doesn't</span> <span m='2487150'>work</span>
  <span m='2487420'>that</span> <span m='2487630'>way?</span> <span m='2488450'>Or</span>
  <span m='2488550'>what</span> <span m='2488560'>if</span> <span m='2488680'>I</span>
  <span m='2488710'>have an</span> <span m='2488920'>iterative</span> <span m='2489280'>map</span>
  <span m='2489610'>that</span> <span m='2489760'>I</span> <span m='2489910'>like</span>
  <span m='2490320'>for</span> <span m='2490510'>some</span> <span m='2490720'>reason,</span>
  <span m='2491650'>but</span> <span m='2491800'>it</span> <span m='2491890'>doesn't</span>
  <span m='2492250'>appear</span> <span m='2492670'>to</span> <span m='2492820'>converge?</span>
  <span m='2493900'>Maybe</span> <span m='2494140'>it</span> <span m='2494290'>converges</span>
  <span m='2494590'>under</span> <span m='2494800'>some</span> <span m='2495010'>circumstances,</span>
  <span m='2495820'>but</span> <span m='2495940'>not</span> <span m='2496180'>others.</span>
  <span m='2497270'>Well,</span> <span m='2497370'>there's</span> <span m='2497440'>a</span>
  <span m='2497500'>way</span> <span m='2497710'>to</span> <span m='2497890'>modify</span>
  <span m='2498490'>these</span> <span m='2498700'>iterative</span> <span m='2499180'>maps,</span>
  <span m='2499930'>called</span> <span m='2500140'>successive</span> <span m='2500740'>over-relaxation,</span>
  <span m='2503300'>which</span> <span m='2503380'>can</span> <span m='2503560'>help</span>
  <span m='2503980'>promote</span> <span m='2504610'>convergence.</span> </p><p><span
  m='2506120'>So</span> <span m='2506140'>suppose</span> <span m='2506410'>we</span>
  <span m='2506500'>have</span> <span m='2506590'>an</span> <span m='2506680'>iterative</span>
  <span m='2507040'>map</span> <span m='2507250'>like</span> <span m='2507430'>this,</span>
  <span m='2507670'>x i</span> <span m='2508060'>plus</span> <span m='2508360'>1</span>
  <span m='2509260'>is</span> <span m='2509350'>some</span> <span m='2509620'>function</span>
  <span m='2510610'>of</span> <span m='2510730'>the</span> <span m='2510820'>previous</span>
  <span m='2511300'>iteration</span> <span m='2511780'>value.</span> <span m='2512310'>Doesn't</span>
  <span m='2512320'>matter</span> <span m='2512530'>what</span> <span m='2512680'>it</span>
  <span m='2512770'>is.</span> <span m='2512980'>It</span> <span m='2513040'>could</span>
  <span m='2513160'>be</span> <span m='2513280'>linear,</span> <span m='2513590'>could</span>
  <span m='2513730'>be</span> <span m='2513820'>non-linear.</span> <span m='2514420'>We</span>
  <span m='2514480'>don't</span> <span m='2514660'>actually</span> <span m='2514930'>care.</span>
  </p><p><span m='2517760'>The</span> <span m='2517890'>sought after</span> <span
  m='2518330'>solution</span> <span m='2518720'>is</span> <span m='2518810'>found</span>
  <span m='2519050'>when</span> <span m='2519200'>x i</span> <span m='2519500'>plus</span>
  <span m='2519800'>1</span> <span m='2520610'>is</span> <span m='2520760'>equal</span>
  <span m='2521000'>to</span> <span m='2521150'>x i.</span> <span m='2521630'>So</span>
  <span m='2521780'>this</span> <span m='2521960'>map</span> <span m='2522380'>is</span>
  <span m='2522500'>one</span> <span m='2522770'>the</span> <span m='2522890'>convergence</span>
  <span m='2523540'>to</span> <span m='2523590'>the</span> <span m='2523760'>exact</span>
  <span m='2524150'>solution</span> <span m='2524690'>of</span> <span m='2524750'>the</span>
  <span m='2524870'>problem</span> <span m='2525170'>that</span> <span m='2525320'>we</span>
  <span m='2525470'>want.</span> <span m='2526250'>We've</span> <span m='2526430'>somehow</span>
  <span m='2526730'>guaranteed</span> <span m='2527210'>that</span> <span m='2527360'>that's</span>
  <span m='2527600'>the</span> <span m='2527690'>case,</span> <span m='2528650'>but</span>
  <span m='2528770'>it</span> <span m='2528830'>has</span> <span m='2529070'>to</span>
  <span m='2529190'>converge.</span> </p><p><span m='2530990'>One</span> <span m='2531260'>way</span>
  <span m='2531410'>to</span> <span m='2531500'>modify</span> <span m='2531980'>that</span>
  <span m='2532160'>map</span> <span m='2532760'>is</span> <span m='2532880'>to</span>
  <span m='2532970'>say</span> <span m='2533210'>x i</span> <span m='2533600'>plus</span>
  <span m='2533930'>1</span> <span m='2534890'>is</span> <span m='2535070'>1</span>
  <span m='2535970'>minus</span> <span m='2536300'>some</span> <span m='2536510'>scalar</span>
  <span m='2536930'>value</span> <span m='2537290'>omega</span> <span m='2537890'>times</span>
  <span m='2538190'>x i</span> <span m='2539210'>plus</span> <span m='2540050'>omega</span>
  <span m='2540620'>times</span> <span m='2541320'>f.</span> <span m='2543020'>You</span>
  <span m='2543140'>can</span> <span m='2543290'>confirm</span> <span m='2543830'>that</span>
  <span m='2543950'>if</span> <span m='2544070'>you</span> <span m='2544160'>substitute</span>
  <span m='2544880'>x i</span> <span m='2545270'>plus</span> <span m='2545540'>1</span>
  <span m='2546050'>equals</span> <span m='2546350'>x</span> <span m='2546590'>i</span>
  <span m='2546980'>into</span> <span m='2547670'>this</span> <span m='2547850'>equation,</span>
  <span m='2548520'>you'll</span> <span m='2548570'>come</span> <span m='2548780'>up</span>
  <span m='2548900'>with</span> <span m='2549080'>the</span> <span m='2549200'>same</span>
  <span m='2550910'>fixed</span> <span m='2551240'>points</span> <span m='2551990'>of</span>
  <span m='2552140'>this</span> <span m='2552360'>iterative</span> <span m='2552740'>map</span>
  <span m='2553940'>x i</span> <span m='2554255'>is</span> <span m='2554570'>equal</span>
  <span m='2554810'>to</span> <span m='2554960'>f</span> <span m='2555200'>of</span>
  <span m='2555320'>x i.</span> <span m='2556500'>So</span> <span m='2556610'>you</span>
  <span m='2556670'>haven't</span> <span m='2556880'>changed</span> <span m='2558140'>what</span>
  <span m='2558410'>value</span> <span m='2558800'>will</span> <span m='2558980'>converge</span>
  <span m='2559520'>here,</span> <span m='2560210'>but</span> <span m='2560300'>you've</span>
  <span m='2560480'>affected</span> <span m='2560990'>the</span> <span m='2561110'>rate</span>
  <span m='2561530'>at</span> <span m='2561620'>which</span> <span m='2561830'>it</span>
  <span m='2561880'>converges.</span> </p><p><span m='2562460'>Here</span> <span m='2562720'>you're</span>
  <span m='2562880'>saying</span> <span m='2563220'>x i</span> <span m='2563620'>plus</span>
  <span m='2563840'>1</span> <span m='2564530'>is</span> <span m='2564620'>some</span>
  <span m='2564890'>fraction</span> <span m='2565640'>of</span> <span m='2565760'>my</span>
  <span m='2565940'>previous</span> <span m='2566330'>solution</span> <span m='2567860'>plus</span>
  <span m='2568730'>some</span> <span m='2569000'>fraction</span> <span m='2569540'>of</span>
  <span m='2569630'>this</span> <span m='2569870'>f.</span> <span m='2570290'>And</span>
  <span m='2570410'>I</span> <span m='2570470'>get</span> <span m='2570590'>to</span>
  <span m='2570680'>control</span> <span m='2571190'>how</span> <span m='2571370'>big</span>
  <span m='2571580'>those</span> <span m='2571760'>different</span> <span m='2572060'>fractions.</span>
  <span m='2573890'>So if</span> <span m='2574100'>things</span> <span m='2574370'>aren't</span>
  <span m='2574520'>converging</span> <span m='2575150'>well</span> <span m='2577130'>for</span>
  <span m='2577310'>a</span> <span m='2577340'>map</span> <span m='2577640'>like</span>
  <span m='2577850'>this,</span> <span m='2578410'>then</span> <span m='2578510'>I</span>
  <span m='2578570'>could</span> <span m='2578690'>try</span> <span m='2579080'>successive</span>
  <span m='2579650'>over-relaxation,</span> <span m='2580700'>and</span> <span m='2580820'>I</span>
  <span m='2580880'>could</span> <span m='2581030'>adjust</span> <span m='2581510'>this</span>
  <span m='2581690'>relaxation</span> <span m='2582380'>parameter</span> <span m='2583400'>to</span>
  <span m='2583460'>be</span> <span m='2583580'>some</span> <span m='2583850'>fraction,</span>
  <span m='2584810'>some</span> <span m='2585020'>number</span> <span m='2585290'>between</span>
  <span m='2585590'>0</span> <span m='2586010'>and</span> <span m='2586220'>1,</span>
  <span m='2587890'>until</span> <span m='2588190'>I</span> <span m='2588280'>start</span>
  <span m='2588490'>to</span> <span m='2588610'>observe</span> <span m='2589030'>convergence.</span>
  <span m='2590050'>And</span> <span m='2590200'>there</span> <span m='2590290'>are</span>
  <span m='2590320'>some</span> <span m='2590500'>rules</span> <span m='2590890'>one</span>
  <span m='2591100'>can</span> <span m='2591280'>use</span> <span m='2591550'>to</span>
  <span m='2591670'>try</span> <span m='2591850'>to</span> <span m='2591940'>promote</span>
  <span m='2592240'>convergence</span> <span m='2592810'>with</span> <span m='2592960'>this</span>
  <span m='2593110'>kind</span> <span m='2593380'>of</span> <span m='2593800'>successive</span>
  <span m='2594430'>over-relaxation.</span> </p><p><span m='2595310'>This</span> <span
  m='2595420'>is</span> <span m='2595510'>a</span> <span m='2595540'>very</span> <span
  m='2595780'>generic</span> <span m='2596410'>technique</span> <span m='2596665'>that</span>
  <span m='2596920'>one</span> <span m='2597070'>can</span> <span m='2597250'>apply.</span>
  <span m='2597370'>If you</span> <span m='2597770'>have</span> <span m='2597900'>any</span>
  <span m='2598140'>iterative</span> <span m='2598480'>map</span> <span m='2598870'>you're</span>
  <span m='2598960'>trying</span> <span m='2599230'>to</span> <span m='2599350'>apply,</span>
  <span m='2600700'>it</span> <span m='2600880'>should</span> <span m='2601090'>go</span>
  <span m='2601600'>to</span> <span m='2601720'>the</span> <span m='2601840'>solution</span>
  <span m='2602260'>you</span> <span m='2602350'>want</span> <span m='2602840'>but</span>
  <span m='2602860'>it</span> <span m='2602920'>doesn't</span> <span m='2603220'>converge</span>
  <span m='2603790'>for</span> <span m='2603940'>some</span> <span m='2604120'>reason,</span>
  <span m='2604570'>then</span> <span m='2604630'>you</span> <span m='2604720'>can</span>
  <span m='2604870'>use</span> <span m='2605440'>this</span> <span m='2605650'>relaxation</span>
  <span m='2606400'>technique</span> <span m='2606820'>to</span> <span m='2606970'>promote</span>
  <span m='2607630'>convergence</span> <span m='2608200'>to</span> <span m='2608320'>the</span>
  <span m='2608440'>solution.</span> <span m='2609250'>You</span> <span m='2609340'>may</span>
  <span m='2609580'>slow</span> <span m='2610180'>the</span> <span m='2610300'>convergence</span>
  <span m='2610840'>way</span> <span m='2611050'>down.</span> </p><p><span m='2611770'>It</span>
  <span m='2611810'>may</span> <span m='2611920'>be</span> <span m='2612070'>very</span>
  <span m='2612280'>slow</span> <span m='2612670'>to</span> <span m='2612760'>converge,</span>
  <span m='2613700'>but</span> <span m='2613720'>it</span> <span m='2613780'>will</span>
  <span m='2613990'>converge.</span> <span m='2614680'>And</span> <span m='2614800'>after</span>
  <span m='2615070'>all,</span> <span m='2615820'>an</span> <span m='2616030'>answer</span>
  <span m='2616360'>is</span> <span m='2616450'>better</span> <span m='2616690'>than</span>
  <span m='2616990'>no</span> <span m='2617290'>answer,</span> <span m='2617620'>no</span>
  <span m='2617710'>matter</span> <span m='2617890'>how</span> <span m='2618040'>long</span>
  <span m='2618160'>it</span> <span m='2618220'>takes</span> <span m='2618460'>to</span>
  <span m='2618550'>get</span> <span m='2618730'>it.</span> <span m='2618940'>So</span>
  <span m='2619610'>sometimes</span> <span m='2619940'>you've</span> <span m='2620020'>got
  to</span> <span m='2620140'>get</span> <span m='2620260'>these</span> <span m='2620440'>things</span>
  <span m='2620740'>by</span> <span m='2620950'>hook</span> <span m='2621100'>or</span>
  <span m='2621160'>by</span> <span m='2621310'>crook.</span> </p><p><span m='2623670'>So</span>
  <span m='2623910'>for example,</span> <span m='2624360'>you</span> <span m='2624450'>can</span>
  <span m='2624570'>apply</span> <span m='2624840'>this</span> <span m='2625020'>to</span>
  <span m='2625140'>Jacobi.</span> <span m='2625710'>This</span> <span m='2625890'>was</span>
  <span m='2626040'>the</span> <span m='2626160'>original</span> <span m='2626520'>Jacobi</span>
  <span m='2627030'>map.</span> <span m='2628620'>And</span> <span m='2628740'>we</span>
  <span m='2628800'>just</span> <span m='2628980'>take</span> <span m='2629190'>that.</span>
  <span m='2629430'>We</span> <span m='2629580'>add</span> <span m='2630660'>1</span>
  <span m='2630870'>minus</span> <span m='2631230'>omega</span> <span m='2631570'>times</span>
  <span m='2631860'>x i</span> <span m='2632730'>plus</span> <span m='2633150'>omega</span>
  <span m='2633640'>times</span> <span m='2633990'>this</span> <span m='2634170'>factor</span>
  <span m='2634560'>over</span> <span m='2634740'>here.</span> <span m='2635680'>And</span>
  <span m='2635780'>now</span> <span m='2635880'>we</span> <span m='2635980'>can</span>
  <span m='2636000'>choose</span> <span m='2636390'>omega</span> <span m='2637530'>so</span>
  <span m='2637890'>that</span> <span m='2638130'>this</span> <span m='2638280'>solution</span>
  <span m='2638760'>converges.</span> <span m='2639300'>We</span> <span m='2639430'>always</span>
  <span m='2639720'>make</span> <span m='2639960'>omega</span> <span m='2640860'>small</span>
  <span m='2641370'>enough</span> <span m='2642120'>so</span> <span m='2642360'>that</span>
  <span m='2642540'>the</span> <span m='2642660'>diagonal</span> <span m='2643350'>values</span>
  <span m='2643770'>of</span> <span m='2643890'>our</span> <span m='2643980'>matrix</span>
  <span m='2644550'>appear</span> <span m='2645240'>big</span> <span m='2645510'>enough</span>
  <span m='2646500'>that</span> <span m='2646590'>the</span> <span m='2646680'>matrix</span>
  <span m='2647010'>looks</span> <span m='2647220'>like</span> <span m='2647400'>it's</span>
  <span m='2647580'>diagonally</span> <span m='2648120'>dominated.</span> </p><p><span
  m='2649770'>You</span> <span m='2649860'>could</span> <span m='2649980'>go</span>
  <span m='2650100'>back</span> <span m='2650310'>to</span> <span m='2650430'>that</span>
  <span m='2650730'>same</span> <span m='2651150'>convergence</span> <span m='2651690'>analysis</span>
  <span m='2652230'>that</span> <span m='2652320'>I</span> <span m='2652410'>showed</span>
  <span m='2652620'>you</span> <span m='2652710'>before</span> <span m='2653490'>and</span>
  <span m='2653580'>try</span> <span m='2653790'>to</span> <span m='2653910'>apply</span>
  <span m='2654340'>it</span> <span m='2654510'>to</span> <span m='2654660'>this</span>
  <span m='2655620'>over-relaxation</span> <span m='2657900'>form</span> <span m='2658410'>of</span>
  <span m='2658550'>Jacobi</span> <span m='2658840'>and</span> <span m='2659130'>see</span>
  <span m='2659340'>that,</span> <span m='2659540'>while</span> <span m='2659670'>there's</span>
  <span m='2659880'>always</span> <span m='2660180'>going</span> <span m='2660300'>to</span>
  <span m='2660360'>be</span> <span m='2660420'>some</span> <span m='2660720'>value</span>
  <span m='2661110'>of</span> <span m='2661230'>omega</span> <span m='2661560'>that's</span>
  <span m='2661710'>small</span> <span m='2662040'>enough,</span> <span m='2662760'>that</span>
  <span m='2662910'>this</span> <span m='2663120'>thing</span> <span m='2663390'>will</span>
  <span m='2664200'>converge.</span> <span m='2665420'>It</span> <span m='2665510'>will</span>
  <span m='2665610'>look</span> <span m='2666210'>effectively</span> <span m='2666960'>diagonally</span>
  <span m='2667500'>dominant,</span> <span m='2667920'>because</span> <span m='2668670'>omega</span>
  <span m='2669390'>inverse</span> <span m='2669900'>times</span> <span m='2670290'>D</span>
  <span m='2671190'>will</span> <span m='2671340'>be</span> <span m='2671490'>big</span>
  <span m='2671670'>enough,</span> <span m='2672150'>or</span> <span m='2672390'>omega</span>
  <span m='2672780'>times</span> <span m='2673080'>D</span> <span m='2673230'>inverse</span>
  <span m='2673590'>will</span> <span m='2673740'>be</span> <span m='2673860'>small</span>
  <span m='2674250'>enough.</span> <span m='2674865'>Does</span> <span m='2675120'>that</span>
  <span m='2675230'>make</span> <span m='2675370'>sense?</span> <span m='2676840'>You
  can</span> <span m='2677300'>apply</span> <span m='2677510'>the</span> <span m='2677580'>same</span>
  <span m='2677820'>sort</span> <span m='2677970'>of</span> <span m='2678060'>damping</span>
  <span m='2678420'>method</span> <span m='2678750'>to</span> <span m='2678870'>Gauss-Seidel</span>
  <span m='2679160'>as well.</span> <span m='2679590'>It's</span> <span m='2679800'>very</span>
  <span m='2680070'>common</span> <span m='2680310'>to</span> <span m='2680430'>do</span>
  <span m='2680610'>this.</span> </p><p><span m='2682360'>The</span> <span m='2682500'>relaxation</span>
  <span m='2683250'>parameter</span> <span m='2683670'>acts</span> <span m='2683940'>like</span>
  <span m='2684090'>an</span> <span m='2684180'>effective</span> <span m='2685020'>increase</span>
  <span m='2685560'>in</span> <span m='2685650'>the</span> <span m='2685770'>eigenvalues</span>
  <span m='2686550'>of</span> <span m='2687240'>the</span> <span m='2687300'>matrix.</span>
  <span m='2687700'>So</span> <span m='2687780'>you</span> <span m='2687840'>can</span>
  <span m='2687930'>think</span> <span m='2688050'>about</span> <span m='2688360'>L.</span>
  <span m='2688710'>That's</span> <span m='2688920'>a</span> <span m='2688950'>lower</span>
  <span m='2689220'>triangular</span> <span m='2689670'>matrix.</span> <span m='2690150'>It's</span>
  <span m='2690330'>diagonal</span> <span m='2690840'>values</span> <span m='2691410'>are</span>
  <span m='2691710'>its</span> <span m='2691890'>eigenvalues.</span> <span m='2694310'>The</span>
  <span m='2694410'>diagonal</span> <span m='2694770'>values</span> <span m='2695160'>of</span>
  <span m='2695280'>L inverse--</span> <span m='2696190'>well,</span> <span m='2697510'>1</span>
  <span m='2697800'>over</span> <span m='2698040'>those</span> <span m='2698250'>diagonal</span>
  <span m='2698640'>values</span> <span m='2699000'>are</span> <span m='2699060'>the</span>
  <span m='2699210'>eigenvalues</span> <span m='2699870'>of</span> <span m='2700010'>L
  inverse.</span> </p><p><span m='2700820'>And</span> <span m='2701270'>so</span>
  <span m='2701400'>if</span> <span m='2701480'>we</span> <span m='2701580'>make</span>
  <span m='2701880'>omega</span> <span m='2702870'>very</span> <span m='2703110'>small,</span>
  <span m='2703560'>then</span> <span m='2703680'>we</span> <span m='2703800'>make</span>
  <span m='2704100'>the</span> <span m='2704340'>eigenvalues</span> <span m='2705060'>of</span>
  <span m='2705150'>L</span> <span m='2705300'>inverse</span> <span m='2705750'>very</span>
  <span m='2705960'>small,</span> <span m='2706630'>or</span> <span m='2706770'>the</span>
  <span m='2706920'>eigenvalues</span> <span m='2707230'>or</span> <span m='2707540'>L</span>
  <span m='2707790'>very</span> <span m='2708090'>big.</span> <span m='2708510'>And</span>
  <span m='2708630'>again,</span> <span m='2708840'>the</span> <span m='2708930'>matrix</span>
  <span m='2709260'>starts</span> <span m='2709800'>to</span> <span m='2709890'>look</span>
  <span m='2710640'>diagonally</span> <span m='2711210'>dominated.</span> <span m='2712170'>And</span>
  <span m='2712290'>you</span> <span m='2712350'>can</span> <span m='2712500'>promote</span>
  <span m='2712800'>convergence</span> <span m='2713460'>in</span> <span m='2713550'>this</span>
  <span m='2713740'>way.</span> </p><p><span m='2715330'>So</span> <span m='2715380'>even</span>
  <span m='2715590'>though</span> <span m='2715800'>this</span> <span m='2716010'>may</span>
  <span m='2716160'>be</span> <span m='2716280'>slow,</span> <span m='2717810'>you</span>
  <span m='2717960'>can</span> <span m='2718140'>use</span> <span m='2718410'>it</span>
  <span m='2718500'>to</span> <span m='2718620'>guarantee</span> <span m='2719040'>convergence</span>
  <span m='2719640'>of</span> <span m='2719730'>some</span> <span m='2719910'>iterative</span>
  <span m='2720240'>procedures,</span> <span m='2721170'>not</span> <span m='2721290'>just</span>
  <span m='2721470'>for</span> <span m='2721590'>linear</span> <span m='2721890'>equations,</span>
  <span m='2722340'>but</span> <span m='2722460'>for</span> <span m='2722610'>non-linear</span>
  <span m='2723240'>equations</span> <span m='2723720'>as well.</span> <span m='2723840'>And</span>
  <span m='2724110'>we'll</span> <span m='2724200'>see,</span> <span m='2724660'>there</span>
  <span m='2724800'>are</span> <span m='2724890'>good</span> <span m='2725100'>ways</span>
  <span m='2725370'>of</span> <span m='2725430'>choosing</span> <span m='2725820'>omega</span>
  <span m='2726270'>for</span> <span m='2726420'>certain</span> <span m='2726690'>classes</span>
  <span m='2727230'>of</span> <span m='2727350'>non-linear</span> <span m='2727890'>equations.</span>
  <span m='2729010'>We'll</span> <span m='2729120'>apply</span> <span m='2729390'>Newton-Raphson</span>
  <span m='2730110'>method,</span> <span m='2730440'>and</span> <span m='2730560'>then</span>
  <span m='2730670'>will</span> <span m='2730830'>damp</span> <span m='2731190'>it</span>
  <span m='2731490'>using</span> <span m='2731820'>exactly</span> <span m='2732330'>the</span>
  <span m='2732450'>sort</span> <span m='2732660'>of</span> <span m='2732750'>procedure.</span>
  <span m='2733590'>And</span> <span m='2733890'>I'll</span> <span m='2734010'>show</span>
  <span m='2734190'>you</span> <span m='2734280'>how</span> <span m='2734370'>you</span>
  <span m='2734520'>can</span> <span m='2734730'>choose</span> <span m='2737190'>a</span>
  <span m='2737310'>nearly</span> <span m='2737910'>optimal</span> <span m='2738390'>value</span>
  <span m='2738870'>for</span> <span m='2739170'>omega</span> <span m='2740260'>to</span>
  <span m='2740700'>promote</span> <span m='2741180'>convergence</span> <span m='2741860'>to</span>
  <span m='2741900'>the</span> <span m='2742020'>solution.</span> </p><p><span m='2743610'>Any</span>
  <span m='2743880'>questions?</span> <span m='2746480'>No,</span> <span m='2748460'>let</span>
  <span m='2748550'>me</span> <span m='2748640'>address</span> <span m='2748850'>one</span>
  <span m='2748940'>more</span> <span m='2749060'>thing</span> <span m='2749240'>before</span>
  <span m='2749420'>you</span> <span m='2749510'>go.</span> <span m='2750140'>We've</span>
  <span m='2750350'>scheduled</span> <span m='2750890'>times</span> <span m='2751370'>for</span>
  <span m='2751550'>the</span> <span m='2751730'>quizzes.</span> <span m='2753140'>They</span>
  <span m='2753440'>are</span> <span m='2753680'>going</span> <span m='2753890'>to</span>
  <span m='2753950'>be</span> <span m='2754040'>in</span> <span m='2754130'>the</span>
  <span m='2754250'>evenings</span> <span m='2755180'>on</span> <span m='2755390'>the</span>
  <span m='2755480'>dates</span> <span m='2755840'>that</span> <span m='2755960'>are</span>
  <span m='2756050'>specified</span> <span m='2756800'>on</span> <span m='2757010'>the</span>
  <span m='2757100'>syllabus.</span> </p><p><span m='2758180'>We</span> <span m='2758780'>wanted</span>
  <span m='2759500'>to</span> <span m='2759680'>do</span> <span m='2759860'>them</span>
  <span m='2760130'>during</span> <span m='2760400'>the</span> <span m='2760490'>daytime.</span>
  <span m='2761060'>It</span> <span m='2761180'>was</span> <span m='2761360'>really</span>
  <span m='2761810'>difficult</span> <span m='2762350'>to</span> <span m='2762470'>schedule</span>
  <span m='2762890'>a</span> <span m='2762980'>room</span> <span m='2763400'>that</span>
  <span m='2763490'>was</span> <span m='2763610'>big</span> <span m='2763760'>enough</span>
  <span m='2763910'>for</span> <span m='2764060'>this</span> <span m='2764210'>class,</span>
  <span m='2764970'>so</span> <span m='2765110'>they</span> <span m='2765200'>have</span>
  <span m='2765320'>to</span> <span m='2765410'>be</span> <span m='2765530'>from</span>
  <span m='2765710'>7:00</span> <span m='2766070'>to</span> <span m='2766250'>9:00</span>
  <span m='2766790'>in</span> <span m='2767090'>the</span> <span m='2767300'>gymnasium.</span>
  <span m='2767990'>I</span> <span m='2768050'>apologize</span> <span m='2768590'>for</span>
  <span m='2768740'>that.</span> <span m='2769910'>We</span> <span m='2769970'>spent</span>
  <span m='2770150'>several</span> <span m='2770420'>days</span> <span m='2770750'>looking</span>
  <span m='2771020'>around</span> <span m='2771290'>trying</span> <span m='2771500'>to</span>
  <span m='2771590'>find</span> <span m='2771770'>a</span> <span m='2771800'>place</span>
  <span m='2772130'>where</span> <span m='2772280'>we</span> <span m='2772400'>could</span>
  <span m='2772520'>put</span> <span m='2772940'>everybody</span> <span m='2774050'>so
  you</span> <span m='2774190'>would</span> <span m='2774290'>all</span> <span m='2774380'>get</span>
  <span m='2774530'>the</span> <span m='2774620'>same</span> <span m='2775070'>experience</span>
  <span m='2775910'>in</span> <span m='2776060'>the</span> <span m='2776180'>quiz.</span>
  </p><p><span m='2777680'>I</span> <span m='2777740'>know</span> <span m='2778040'>that</span>
  <span m='2778340'>the</span> <span m='2778490'>November</span> <span m='2779030'>quiz</span>
  <span m='2779540'>comes</span> <span m='2779960'>back</span> <span m='2780200'>to</span>
  <span m='2780320'>back</span> <span m='2780590'>with</span> <span m='2780800'>the</span>
  <span m='2780890'>thermodynamics</span> <span m='2782390'>exam</span> <span m='2783020'>as</span>
  <span m='2783230'>well.</span> <span m='2784130'>That's</span> <span m='2785510'>frustrating.</span>
  <span m='2786030'>Thermodynamics</span> <span m='2786710'>is</span> <span m='2786830'>the</span>
  <span m='2786950'>next</span> <span m='2787220'>day.</span> <span m='2787850'>That</span>
  <span m='2788000'>week</span> <span m='2788300'>is</span> <span m='2788870'>tricky.</span>
  <span m='2789170'>That's</span> <span m='2789523'>AICHE,</span> <span m='2790230'>so</span>
  <span m='2790340'>most</span> <span m='2790640'>of</span> <span m='2790700'>the</span>
  <span m='2790790'>faculty</span> <span m='2791360'>have</span> <span m='2791570'>to</span>
  <span m='2791750'>travel.</span> <span m='2793050'>We</span> <span m='2793130'>won't</span>
  <span m='2793280'>be</span> <span m='2793340'>able</span> <span m='2793490'>to</span>
  <span m='2793580'>teach,</span> <span m='2794090'>but</span> <span m='2794300'>you</span>
  <span m='2794420'>won't</span> <span m='2794570'>have</span> <span m='2794720'>classes</span>
  <span m='2795380'>one</span> <span m='2795560'>of</span> <span m='2795620'>those</span>
  <span m='2795860'>days</span> <span m='2796350'>so</span> <span m='2797030'>you</span>
  <span m='2797120'>have</span> <span m='2797270'>extra</span> <span m='2797540'>time</span>
  <span m='2797900'>to</span> <span m='2798110'>study.</span> <span m='2799910'>And</span>
  <span m='2800120'>Columbus</span> <span m='2800570'>Day</span> <span m='2800690'>also</span>
  <span m='2800930'>falls</span> <span m='2801200'>in</span> <span m='2801290'>that</span>
  <span m='2801440'>week,</span> <span m='2801750'>so</span> <span m='2801770'>there's</span>
  <span m='2801950'>no</span> <span m='2802130'>way</span> <span m='2802430'>to</span>
  <span m='2802580'>put</span> <span m='2802760'>three</span> <span m='2803000'>exams</span>
  <span m='2803720'>in</span> <span m='2803990'>four</span> <span m='2804200'>days</span>
  <span m='2804590'>without</span> <span m='2804980'>having</span> <span m='2805350'>them</span>
  <span m='2805480'>come</span> <span m='2805860'>right</span> <span m='2806330'>back</span>
  <span m='2806510'>to</span> <span m='2806630'>back.</span> </p><p><span m='2806830'>Believe</span>
  <span m='2807020'>me,</span> <span m='2807550'>we</span> <span m='2807800'>thought</span>
  <span m='2807980'>about</span> <span m='2808190'>this</span> <span m='2808460'>and</span>
  <span m='2808610'>tried</span> <span m='2808850'>to</span> <span m='2808940'>get</span>
  <span m='2809060'>things</span> <span m='2809240'>scheduled</span> <span m='2809840'>as</span>
  <span m='2810620'>efficiently</span> <span m='2811070'>as</span> <span m='2811160'>we</span>
  <span m='2811250'>could</span> <span m='2811430'>for</span> <span m='2811640'>you,</span>
  <span m='2811790'>but</span> <span m='2811910'>sometimes</span> <span m='2812300'>there</span>
  <span m='2812420'>are</span> <span m='2812630'>constraints</span> <span m='2813200'>that</span>
  <span m='2813320'>are</span> <span m='2813380'>outside</span> <span m='2813680'>of</span>
  <span m='2813770'>our</span> <span m='2813890'>control.</span> <span m='2814350'>But</span>
  <span m='2814370'>the</span> <span m='2814460'>quiz</span> <span m='2814730'>times</span>
  <span m='2815120'>are</span> <span m='2815450'>set.</span> <span m='2816180'>There's</span>
  <span m='2816340'>going</span> <span m='2816530'>to</span> <span m='2816650'>be</span>
  <span m='2816720'>done</span> <span m='2816890'>in</span> <span m='2816980'>October</span>
  <span m='2817400'>and</span> <span m='2817520'>one</span> <span m='2817670'>in</span>
  <span m='2817730'>November.</span> <span m='2818260'>They'll</span> <span m='2818350'>be</span>
  <span m='2818450'>in</span> <span m='2818540'>the</span> <span m='2818600'>evening,</span>
  <span m='2819380'>and</span> <span m='2819500'>they'll</span> <span m='2819590'>be</span>
  <span m='2819740'>in</span> <span m='2819830'>the</span> <span m='2819920'>gymnasium.</span>
  <span m='2820790'>I'll</span> <span m='2821000'>give</span> <span m='2821120'>you</span>
  <span m='2821180'>directions</span> <span m='2821720'>to</span> <span m='2821930'>it</span>
  <span m='2822050'>before</span> <span m='2823250'>the</span> <span m='2823350'>exam,</span>
  <span m='2823640'>just</span> <span m='2823790'>say</span> <span m='2823890'>you</span>
  <span m='2823940'>know</span> <span m='2824090'>exactly</span> <span m='2824480'>where</span>
  <span m='2824590'>to</span> <span m='2825020'>go,</span> <span m='2825990'>OK?</span>
  <span m='2826280'>Thank you,</span> <span m='2826660'>guys.</span> </p><p></p>
type: course
uid: 72e0947eabbb0ab24ae80b96b1b5bddb

---
None