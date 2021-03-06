---
about_this_resource_text: <p><strong>Description:</strong> Differentiates between
  independent and dependent events as it pertains to probability, covering applications
  like coin flips, the distribution of birthdays, hashing, and cryptography.</p> <p><strong>Speaker:</strong>
  Tom Leighton</p>
course_id: 6-042j-mathematics-for-computer-science-fall-2010
embedded_media:
- id: Video-YouTube-Stream
  media_location: l1BCv3qqW4A
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: Video-YouTube-Stream
  type: Video
  uid: a52df46cbb6534cbe79d5fc6c16e6cc2
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/l1BCv3qqW4A/default.jpg
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9a184358de4112231f7a9572d24c5ffb
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-20-independence/id503873536?i=110644970
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: Video-iTunes U-MP4
  type: Video
  uid: b9995047bedb38dcd756cd7f537b179e
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.042JF10/MIT6_042JF10_lec20_300k.mp4
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9d5fd5dc02063e81400a5f261a3f3ca6
- id: 3Play-3PlayYouTubeid-MP4
  media_location: l1BCv3qqW4A
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 60cee165c5aeb639ce9cf23f6ffe5ddc
- id: l1BCv3qqW4A.srt
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-20-independence/l1BCv3qqW4A.srt
  title: 3play caption file
  type: null
  uid: cfe55d12f44c87aa20b182086f43cc02
- id: l1BCv3qqW4A.pdf
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-20-independence/l1BCv3qqW4A.pdf
  title: 3play pdf file
  type: null
  uid: 6388bd9f7ac0cad66c505d5f76c4ffef
- id: Caption-3Play YouTube id-SRT
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3c8393ed8433941fe3abf3b999f48460
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 8e18030450f67e1dd860281e4c93b825
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f4b0fe14ee7a6cda81ecb6243d8f26d5
inline_embed_id: 75747037lecture20:independence6438382
layout: video
order_index: null
parent_uid: 7e5e792254d703550b60881541fa6160
related_resources_text: ''
short_url: lecture-20-independence
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-20-independence
template_type: Tabbed
title: 'Lecture 20: Independence'
transcript: '<p><span m=''390''>The</span> <span m=''510''>following</span> <span
  m=''950''>content</span> <span m=''1550''>is</span> <span m=''1660''>provided</span>
  <span m=''2110''>under</span> <span m=''2390''>a</span> <span m=''2430''>Creative</span>
  <span m=''2830''>Commons</span> <span m=''3230''>license.</span> <span m=''4340''>Your</span>
  <span m=''4530''>support</span> <span m=''5030''>will</span> <span m=''5200''>help</span>
  <span m=''5440''>MIT</span> <span m=''5890''>OpenCourseWare</span> <span m=''6680''>continue</span>
  <span m=''7190''>to</span> <span m=''7270''>offer</span> <span m=''7690''>high</span>
  <span m=''7930''>quality</span> <span m=''8450''>educational</span> <span m=''9070''>resources</span>
  <span m=''9700''>for</span> <span m=''9850''>free.</span> <span m=''11050''>To</span>
  <span m=''11060''>make</span> <span m=''11260''>a</span> <span m=''11310''>donation</span>
  <span m=''11990''>or</span> <span m=''12260''>view</span> <span m=''12700''>additional</span>
  <span m=''13130''>materials</span> <span m=''13660''>from</span> <span m=''13810''>hundreds</span>
  <span m=''14250''>of</span> <span m=''14360''>MIT</span> <span m=''14780''>courses,</span>
  <span m=''15900''>visit</span> <span m=''16110''>MIT</span> <span m=''16530''>OpenCourseWare</span>
  <span m=''17580''>at</span> <span m=''17750''>ocw.mit.edu.</span> </p><p><span m=''23224''>TOM
  LEIGHTON:</span> <span m=''23700''>Today</span> <span m=''24220''>we''re</span>
  <span m=''24360''>going</span> <span m=''24470''>to</span> <span m=''24560''>talk</span>
  <span m=''25030''>about</span> <span m=''25710''>the</span> <span m=''25810''>concept</span>
  <span m=''27080''>of</span> <span m=''27170''>independence.</span> <span m=''29560''>In</span>
  <span m=''29860''>probability,</span> <span m=''30940''>we</span> <span m=''31100''>say</span>
  <span m=''31560''>that</span> <span m=''36660''>an</span> <span m=''36830''>event</span>
  <span m=''37490''>A</span> <span m=''41760''>is</span> <span m=''42060''>independent</span>
  <span m=''50510''>of</span> <span m=''50800''>an event</span> <span m=''51120''>B</span>
  <span m=''57710''>if</span> <span m=''57930''>one</span> <span m=''58170''>of</span>
  <span m=''58260''>two</span> <span m=''58460''>conditions</span> <span m=''59060''>hold.</span>
  <span m=''60210''>First,</span> <span m=''62210''>if</span> <span m=''62430''>the</span>
  <span m=''62530''>probability</span> <span m=''63100''>of</span> <span m=''63180''>A</span>
  <span m=''63430''>given</span> <span m=''63760''>B</span> <span m=''64910''>is</span>
  <span m=''65129''>just</span> <span m=''65650''>the</span> <span m=''65730''>same</span>
  <span m=''66160''>as</span> <span m=''66270''>the</span> <span m=''66360''>probability</span>
  <span m=''66930''>of</span> <span m=''67020''>A</span> <span m=''68910''>or</span>
  <span m=''70320''>if</span> <span m=''71650''>B</span> <span m=''71930''>can''t</span>
  <span m=''72270''>happen,</span> <span m=''72940''>namely</span> <span m=''73250''>the</span>
  <span m=''73350''>probability</span> <span m=''73930''>of</span> <span m=''74000''>B</span>
  <span m=''74770''>is</span> <span m=''74970''>0.</span> </p><p><span m=''76470''>In</span>
  <span m=''76600''>other</span> <span m=''76790''>words,</span> <span m=''77700''>A</span>
  <span m=''77940''>is</span> <span m=''78080''>independent</span> <span m=''78600''>of</span>
  <span m=''78730''>B</span> <span m=''79710''>if</span> <span m=''79950''>knowing</span>
  <span m=''80500''>that</span> <span m=''80670''>B</span> <span m=''80870''>happened</span>
  <span m=''82450''>doesn''t</span> <span m=''82870''>change</span> <span m=''84060''>the</span>
  <span m=''84170''>probability</span> <span m=''84820''>that</span> <span m=''85010''>A</span>
  <span m=''85160''>is</span> <span m=''85310''>going</span> <span m=''85430''>to</span>
  <span m=''85490''>happen.</span> <span m=''86060''>So</span> <span m=''86950''>knowing</span>
  <span m=''88830''>that</span> <span m=''88900''>this</span> <span m=''89070''>event</span>
  <span m=''89300''>occurs</span> <span m=''89720''>doesn''t</span> <span m=''90060''>influence</span>
  <span m=''90510''>the</span> <span m=''90580''>probability</span> <span m=''91070''>that</span>
  <span m=''91200''>A</span> <span m=''91370''>occurs.</span> <span m=''92460''>And</span>
  <span m=''92680''>there''s</span> <span m=''92810''>a</span> <span m=''92890''>special</span>
  <span m=''93320''>case</span> <span m=''93780''>where</span> <span m=''93880''>they''re</span>
  <span m=''94030''>independent</span> <span m=''94640''>because</span> <span m=''95400''>you</span>
  <span m=''95700''>know</span> <span m=''96015''>that</span> <span m=''96330''>B</span>
  <span m=''96550''>can''t</span> <span m=''96820''>happen.</span> <span m=''97820''>If</span>
  <span m=''97930''>the</span> <span m=''98030''>probability</span> <span m=''98590''>of</span>
  <span m=''98660''>B</span> <span m=''99130''>happening</span> <span m=''99550''>is</span>
  <span m=''99710''>0,</span> <span m=''101020''>then</span> <span m=''101260''>everything</span>
  <span m=''101630''>is</span> <span m=''101730''>independent</span> <span m=''102370''>of</span>
  <span m=''102520''>B.</span> </p><p><span m=''104271''>Now,</span> <span m=''104770''>the</span>
  <span m=''104920''>typical</span> <span m=''105350''>example</span> <span m=''106410''>that</span>
  <span m=''106550''>gets</span> <span m=''106810''>used</span> <span m=''107260''>is</span>
  <span m=''107380''>when</span> <span m=''107530''>you</span> <span m=''107630''>flip</span>
  <span m=''107990''>two</span> <span m=''108190''>coins.</span> <span m=''113970''>So</span>
  <span m=''114160''>say</span> <span m=''114410''>we</span> <span m=''114570''>flip</span>
  <span m=''115230''>two</span> <span m=''115750''>fair,</span> <span m=''118590''>independent</span>
  <span m=''119230''>coins.</span> <span m=''128020''>And</span> <span m=''128320''>let''s</span>
  <span m=''128590''>let</span> <span m=''129419''>B</span> <span m=''130639''>be</span>
  <span m=''130789''>the</span> <span m=''130949''>event</span> <span m=''133180''>that</span>
  <span m=''133310''>the</span> <span m=''133420''>first</span> <span m=''133930''>coin</span>
  <span m=''138740''>is</span> <span m=''139620''>heads</span> <span m=''141090''>and</span>
  <span m=''141650''>that</span> <span m=''142040''>means</span> <span m=''142530''>that</span>
  <span m=''142930''>the</span> <span m=''143020''>probability</span> <span m=''144400''>of</span>
  <span m=''144570''>B</span> <span m=''144850''>happening</span> <span m=''145930''>is</span>
  <span m=''146110''>1/2,</span> <span m=''147320''>because</span> <span m=''147680''>we''ve</span>
  <span m=''147860''>assumed</span> <span m=''148170''>it''s</span> <span m=''148310''>a</span>
  <span m=''148360''>fair</span> <span m=''148690''>coin,</span> <span m=''150040''>and</span>
  <span m=''150260''>we''ll</span> <span m=''150360''>let</span> <span m=''150610''>A</span>
  <span m=''151150''>be</span> <span m=''151340''>the</span> <span m=''151520''>event</span>
  <span m=''152130''>that</span> <span m=''152270''>the</span> <span m=''152370''>second</span>
  <span m=''152860''>coin</span> <span m=''155580''>comes</span> <span m=''155880''>out</span>
  <span m=''156110''>heads.</span> <span m=''158120''>So</span> <span m=''158280''>we</span>
  <span m=''158390''>know</span> <span m=''158610''>the</span> <span m=''158710''>probability</span>
  <span m=''159240''>of</span> <span m=''159340''>A</span> <span m=''159670''>is</span>
  <span m=''159840''>1/2</span> <span m=''160490''>because</span> <span m=''160690''>it''s</span>
  <span m=''160880''>fair.</span> </p><p><span m=''165180''>And</span> <span m=''165620''>because</span>
  <span m=''166810''>they''re</span> <span m=''167020''>independent,</span> <span
  m=''170140''>we</span> <span m=''170300''>can</span> <span m=''170440''>conclude</span>
  <span m=''171060''>that</span> <span m=''171170''>the</span> <span m=''171260''>probability</span>
  <span m=''172980''>of</span> <span m=''173210''>A</span> <span m=''173560''>given</span>
  <span m=''173950''>B</span> <span m=''175460''>is</span> <span m=''175710''>1/2,</span>
  <span m=''176900''>which</span> <span m=''177140''>is</span> <span m=''177260''>the</span>
  <span m=''177350''>probability</span> <span m=''177940''>of</span> <span m=''178050''>A.</span>
  <span m=''179920''>In</span> <span m=''180050''>other</span> <span m=''180250''>words,</span>
  <span m=''181780''>seeing</span> <span m=''182250''>the</span> <span m=''182330''>result</span>
  <span m=''182830''>of</span> <span m=''182890''>the</span> <span m=''182960''>second</span>
  <span m=''183390''>coin</span> <span m=''183830''>doesn''t</span> <span m=''184210''>tell</span>
  <span m=''184510''>you</span> <span m=''184720''>anything</span> <span m=''185060''>about</span>
  <span m=''185990''>the</span> <span m=''186100''>result</span> <span m=''186640''>of</span>
  <span m=''186760''>the</span> <span m=''186840''>first</span> <span m=''187150''>coin.</span>
  </p><p><span m=''189190''>Now</span> <span m=''189910''>actually,</span> <span m=''191540''>when</span>
  <span m=''191660''>you</span> <span m=''191760''>flip</span> <span m=''192050''>two</span>
  <span m=''192250''>coins,</span> <span m=''193300''>it''s</span> <span m=''193490''>not</span>
  <span m=''193740''>just</span> <span m=''194250''>always</span> <span m=''194800''>the</span>
  <span m=''194920''>case</span> <span m=''195330''>if</span> <span m=''195420''>they''re</span>
  <span m=''195600''>independent.</span> <span m=''197520''>Can</span> <span m=''197660''>anybody</span>
  <span m=''198080''>think</span> <span m=''198360''>of</span> <span m=''198440''>an</span>
  <span m=''198500''>example</span> <span m=''199060''>where</span> <span m=''199240''>you</span>
  <span m=''199360''>can</span> <span m=''199510''>flip</span> <span m=''199920''>a</span>
  <span m=''200000''>pair</span> <span m=''200280''>of</span> <span m=''200360''>coins</span>
  <span m=''201730''>and</span> <span m=''201910''>they</span> <span m=''202040''>are</span>
  <span m=''202230''>dependent</span> <span m=''203020''>somehow,</span> <span m=''203550''>they''re</span>
  <span m=''203660''>not</span> <span m=''203960''>independent?</span> <span m=''205820''>Yeah.</span>
  </p><p><span m=''206270''>AUDIENCE: Well,</span> <span m=''206751''>if</span> <span
  m=''206911''>you</span> <span m=''206964''>have</span> <span m=''207017''>to</span>
  <span m=''207071''>get</span> <span m=''207232''>two</span> <span m=''207713''>heads</span>
  <span m=''208194''>and</span> <span m=''208675''>two</span> <span m=''209156''>tails?</span>
  </p><p><span m=''209640''>TOM LEIGHTON: If</span> <span m=''209770''>you</span>
  <span m=''209900''>have</span> <span m=''210400''>to</span> <span m=''210500''>get</span>
  <span m=''210840''>two</span> <span m=''211020''>heads</span> <span m=''211320''>or</span>
  <span m=''211430''>two</span> <span m=''211540''>tails.</span> <span m=''213500''>Well,</span>
  <span m=''213690''>how</span> <span m=''213890''>would</span> <span m=''214080''>you</span>
  <span m=''214230''>have</span> <span m=''214410''>to</span> <span m=''214910''>get?</span>
  </p><p><span m=''215200''>AUDIENCE: The</span> <span m=''215490''>probability</span>
  <span m=''215982''>of</span> <span m=''216474''>getting</span> <span m=''216966''>two</span>
  <span m=''217458''>heads</span> <span m=''219426''>should</span> <span m=''219918''>be</span>
  <span m=''220410''>1/4</span> <span m=''220902''>[INAUDIBLE].</span> </p><p><span
  m=''222378''>TOM LEIGHTON:</span> <span m=''222870''>Well,</span> <span m=''223270''>then</span>
  <span m=''223440''>they</span> <span m=''223495''>would</span> <span m=''223550''>be</span>
  <span m=''223700''>independent</span> <span m=''224250''>in</span> <span m=''224320''>that</span>
  <span m=''224550''>case.</span> <span m=''225220''>Yeah.</span> </p><p><span m=''225515''>AUDIENCE:</span>
  <span m=''225810''>If</span> <span m=''225930''>you</span> <span m=''226080''>glue</span>
  <span m=''226330''>the</span> <span m=''226490''>coins</span> <span m=''226650''>together.</span>
  </p><p><span m=''227100''>TOM LEIGHTON:</span> <span m=''227360''>Yeah.</span> <span
  m=''228150''>I</span> <span m=''228250''>mean,</span> <span m=''228370''>this</span>
  <span m=''228510''>is</span> <span m=''228610''>a</span> <span m=''228700''>silly</span>
  <span m=''229060''>example,</span> <span m=''229550''>but</span> <span m=''229680''>I</span>
  <span m=''229740''>got</span> <span m=''230290''>two</span> <span m=''230630''>fair</span>
  <span m=''230940''>coins</span> <span m=''231370''>here.</span> <span m=''233160''>I</span>
  <span m=''233300''>could</span> <span m=''234200''>clip</span> <span m=''234540''>them</span>
  <span m=''234720''>together</span> <span m=''236220''>and</span> <span m=''236370''>now</span>
  <span m=''236510''>I</span> <span m=''236640''>flip</span> <span m=''236950''>them</span>
  <span m=''238080''>and</span> <span m=''238250''>odds</span> <span m=''238460''>are</span>
  <span m=''238520''>pretty</span> <span m=''238750''>good</span> <span m=''239030''>they''re</span>
  <span m=''239150''>both</span> <span m=''239620''>going</span> <span m=''239720''>to</span>
  <span m=''239760''>be</span> <span m=''239890''>heads</span> <span m=''240120''>or</span>
  <span m=''240220''>both</span> <span m=''240490''>be</span> <span m=''240630''>tails.</span>
  <span m=''241990''>If</span> <span m=''242140''>you</span> <span m=''242270''>know</span>
  <span m=''242610''>what</span> <span m=''242760''>happened</span> <span m=''243130''>to</span>
  <span m=''243200''>the</span> <span m=''243300''>right</span> <span m=''243570''>coin,</span>
  <span m=''244230''>it</span> <span m=''244680''>will</span> <span m=''244920''>tell</span>
  <span m=''245100''>you</span> <span m=''245230''>what</span> <span m=''245330''>happened</span>
  <span m=''245630''>to</span> <span m=''245670''>the</span> <span m=''245750''>left</span>
  <span m=''246030''>coin.</span> </p><p><span m=''247040''>Now,</span> <span m=''247160''>that''s</span>
  <span m=''247370''>a</span> <span m=''247460''>pretty</span> <span m=''248080''>contrived</span>
  <span m=''248810''>example,</span> <span m=''250600''>but</span> <span m=''250870''>it</span>
  <span m=''250950''>is</span> <span m=''251200''>illustrative</span> <span m=''251950''>of</span>
  <span m=''252080''>what</span> <span m=''252250''>happens</span> <span m=''252740''>in</span>
  <span m=''252860''>practice.</span> <span m=''254000''>In</span> <span m=''254140''>practice,</span>
  <span m=''254750''>we</span> <span m=''255000''>assume</span> <span m=''255850''>independence</span>
  <span m=''257610''>even</span> <span m=''257990''>though</span> <span m=''258200''>there</span>
  <span m=''258370''>can</span> <span m=''258760''>be</span> <span m=''258910''>subtle</span>
  <span m=''259339''>dependencies</span> <span m=''260550''>and</span> <span m=''260680''>this</span>
  <span m=''260839''>could</span> <span m=''260950''>lead</span> <span m=''261149''>to</span>
  <span m=''261220''>trouble.</span> <span m=''261620''>In</span> <span m=''261690''>fact,</span>
  <span m=''261899''>we''re</span> <span m=''261970''>going</span> <span m=''262050''>to</span>
  <span m=''262089''>give</span> <span m=''262200''>a</span> <span m=''262270''>lot</span>
  <span m=''262530''>of</span> <span m=''262610''>examples</span> <span m=''263650''>where</span>
  <span m=''263910''>it</span> <span m=''263960''>leads</span> <span m=''264190''>to</span>
  <span m=''264270''>trouble</span> <span m=''264590''>today</span> <span m=''265340''>and</span>
  <span m=''265570''>also</span> <span m=''266090''>for</span> <span m=''266220''>the</span>
  <span m=''266320''>rest</span> <span m=''266570''>of</span> <span m=''266610''>the</span>
  <span m=''266700''>course.</span> <span m=''267560''>Because</span> <span m=''267730''>we''re</span>
  <span m=''267910''>always</span> <span m=''268320''>going</span> <span m=''268440''>to</span>
  <span m=''268510''>want</span> <span m=''268730''>to</span> <span m=''268820''>assume</span>
  <span m=''269200''>independence</span> <span m=''270390''>and</span> <span m=''270600''>when</span>
  <span m=''270770''>we</span> <span m=''270890''>do,</span> <span m=''271150''>we''re</span>
  <span m=''271250''>going</span> <span m=''271330''>to</span> <span m=''271370''>get</span>
  <span m=''271560''>very</span> <span m=''271830''>nice</span> <span m=''272090''>results,</span>
  <span m=''273400''>but</span> <span m=''273560''>things</span> <span m=''273940''>aren''t</span>
  <span m=''274290''>always</span> <span m=''274730''>independent</span> <span m=''275020''>in</span>
  <span m=''275310''>practice</span> <span m=''275820''>and</span> <span m=''275900''>establishing</span>
  <span m=''276530''>independence</span> <span m=''277240''>is</span> <span m=''277370''>a</span>
  <span m=''277420''>hard</span> <span m=''277690''>thing</span> <span m=''277860''>to</span>
  <span m=''277970''>do.</span> </p><p><span m=''279860''>For</span> <span m=''280030''>that</span>
  <span m=''280250''>matter,</span> <span m=''280510''>while</span> <span m=''280720''>we''re</span>
  <span m=''280850''>on</span> <span m=''280940''>the</span> <span m=''281030''>subject,</span>
  <span m=''281930''>we</span> <span m=''282050''>always</span> <span m=''282250''>talk</span>
  <span m=''282430''>about</span> <span m=''282660''>fair</span> <span m=''282930''>coins.</span>
  <span m=''283450''>You</span> <span m=''283540''>flip</span> <span m=''283750''>a</span>
  <span m=''283820''>coin</span> <span m=''284220''>and</span> <span m=''284295''>it''s</span>
  <span m=''284370''>fair.</span> <span m=''285650''>You</span> <span m=''285760''>know,</span>
  <span m=''286340''>that''s</span> <span m=''286600''>not</span> <span m=''286760''>always</span>
  <span m=''287000''>to</span> <span m=''287200''>either.</span> <span m=''287450''>There''s</span>
  <span m=''288660''>actually</span> <span m=''288920''>a</span> <span m=''288970''>famous</span>
  <span m=''289390''>mathematician</span> <span m=''290130''>named</span> <span m=''290740''>Persi</span>
  <span m=''291080''>Diaconis</span> <span m=''292710''>who</span> <span m=''292830''>used</span>
  <span m=''293100''>to</span> <span m=''293310''>down</span> <span m=''293900''>the</span>
  <span m=''294000''>street</span> <span m=''294210''>at</span> <span m=''294280''>Harvard</span>
  <span m=''295100''>and</span> <span m=''295760''>he</span> <span m=''295910''>came</span>
  <span m=''296230''>and</span> <span m=''296320''>gave</span> <span m=''296480''>a</span>
  <span m=''296540''>talk</span> <span m=''296920''>one</span> <span m=''297160''>day</span>
  <span m=''298070''>at</span> <span m=''298260''>MIT</span> <span m=''298720''>in</span>
  <span m=''298790''>the</span> <span m=''298870''>math</span> <span m=''299120''>department</span>
  <span m=''299610''>and</span> <span m=''299690''>he''s</span> <span m=''299880''>a</span>
  <span m=''299960''>probabalist.</span> <span m=''300540''>He</span> <span m=''300760''>does</span>
  <span m=''300950''>probability</span> <span m=''301530''>theory</span> <span m=''302060''>and</span>
  <span m=''302380''>is</span> <span m=''302550''>a</span> <span m=''302730''>very</span>
  <span m=''302920''>cool</span> <span m=''303110''>guy.</span> </p><p><span m=''303830''>And</span>
  <span m=''304170''>so</span> <span m=''304820''>he</span> <span m=''305770''>flipped</span>
  <span m=''306220''>a</span> <span m=''306280''>coin,</span> <span m=''306930''>got</span>
  <span m=''307090''>a</span> <span m=''307130''>quarter</span> <span m=''307570''>from</span>
  <span m=''307700''>somebody</span> <span m=''307890''>in</span> <span m=''308000''>the</span>
  <span m=''308090''>audience</span> <span m=''308520''>and</span> <span m=''308680''>flipped</span>
  <span m=''309050''>it</span> <span m=''310180''>and</span> <span m=''310290''>he</span>
  <span m=''310400''>flip</span> <span m=''310680''>that</span> <span m=''310780''>I</span>
  <span m=''310870''>think</span> <span m=''311310''>10</span> <span m=''311760''>or</span>
  <span m=''311850''>20</span> <span m=''312200''>straight</span> <span m=''312580''>times</span>
  <span m=''313050''>all</span> <span m=''313360''>the</span> <span m=''313460''>way</span>
  <span m=''313700''>to</span> <span m=''313770''>the</span> <span m=''313900''>roof,</span>
  <span m=''315310''>caught</span> <span m=''315640''>it,</span> <span m=''315960''>turned</span>
  <span m=''316210''>it</span> <span m=''316280''>over.</span> <span m=''316900''>Every</span>
  <span m=''317200''>time</span> <span m=''317460''>it</span> <span m=''317530''>was</span>
  <span m=''317690''>heads.</span> <span m=''318812''>And</span> <span m=''319160''>he</span>
  <span m=''319225''>goes,</span> <span m=''319290''>now</span> <span m=''319420''>what''s</span>
  <span m=''319660''>the</span> <span m=''319790''>probability</span> <span m=''320510''>of</span>
  <span m=''320570''>that</span> <span m=''320780''>happening?</span> <span m=''322190''>Well,</span>
  <span m=''322350''>you</span> <span m=''322430''>know,</span> <span m=''322620''>it''s</span>
  <span m=''322960''>1/2</span> <span m=''323510''>to</span> <span m=''323620''>the</span>
  <span m=''323700''>20th</span> <span m=''324170''>or</span> <span m=''324220''>whatever,</span>
  <span m=''324800''>not</span> <span m=''325120''>very</span> <span m=''325370''>likely.</span>
  <span m=''326130''>How</span> <span m=''326540''>could</span> <span m=''326650''>he</span>
  <span m=''326760''>always</span> <span m=''327110''>make</span> <span m=''327250''>it</span>
  <span m=''327320''>come</span> <span m=''327465''>out</span> <span m=''327610''>heads?</span>
  </p><p><span m=''328730''>Well,</span> <span m=''329130''>Persi</span> <span m=''329490''>was</span>
  <span m=''329640''>an</span> <span m=''329700''>unusual</span> <span m=''330210''>guy</span>
  <span m=''330950''>and</span> <span m=''331140''>in</span> <span m=''331230''>fact,</span>
  <span m=''331620''>he''d</span> <span m=''331780''>spent</span> <span m=''332120''>months</span>
  <span m=''332820''>in</span> <span m=''332920''>the</span> <span m=''333010''>strobe</span>
  <span m=''333500''>lab</span> <span m=''335130''>over</span> <span m=''335350''>at</span>
  <span m=''335400''>Harvard</span> <span m=''336300''>practicing</span> <span m=''337480''>to</span>
  <span m=''337630''>make</span> <span m=''337810''>it</span> <span m=''337980''>always</span>
  <span m=''338480''>rotate</span> <span m=''339040''>seven</span> <span m=''339400''>times,</span>
  <span m=''341250''>three</span> <span m=''341590''>of</span> <span m=''341730''>them</span>
  <span m=''341780''>on</span> <span m=''341820''>the</span> <span m=''341860''>way</span>
  <span m=''342000''>up,</span> <span m=''342240''>one</span> <span m=''342390''>at</span>
  <span m=''342430''>the</span> <span m=''342530''>top,</span> <span m=''342810''>and</span>
  <span m=''342900''>then</span> <span m=''343020''>three</span> <span m=''343230''>down.</span>
  <span m=''343460''>And</span> <span m=''343590''>he</span> <span m=''343845''>could</span>
  <span m=''344100''>actually</span> <span m=''344180''>see</span> <span m=''345390''>how</span>
  <span m=''345540''>many</span> <span m=''345740''>rotations</span> <span m=''346010''>it</span>
  <span m=''346280''>had</span> <span m=''346410''>done</span> <span m=''346580''>to</span>
  <span m=''346630''>make</span> <span m=''346800''>sure</span> <span m=''347070''>it</span>
  <span m=''347130''>was</span> <span m=''347260''>seven,</span> <span m=''348420''>so</span>
  <span m=''348590''>it</span> <span m=''348670''>always</span> <span m=''349210''>came</span>
  <span m=''349450''>out</span> <span m=''349620''>heads.</span> </p><p><span m=''350950''>Now,</span>
  <span m=''351350''>he</span> <span m=''351580''>is</span> <span m=''351690''>an</span>
  <span m=''351750''>unusual</span> <span m=''352170''>fellow.</span> <span m=''352560''>He</span>
  <span m=''352950''>was</span> <span m=''354020''>1</span> <span m=''354500''>of</span>
  <span m=''354640''>10</span> <span m=''354980''>people</span> <span m=''355340''>in</span>
  <span m=''355400''>the</span> <span m=''355500''>world</span> <span m=''356250''>that</span>
  <span m=''356360''>could</span> <span m=''356520''>do</span> <span m=''356660''>a</span>
  <span m=''356740''>perfect</span> <span m=''357310''>shuffle</span> <span m=''357840''>reliably</span>
  <span m=''358600''>on</span> <span m=''358700''>a</span> <span m=''358760''>deck</span>
  <span m=''359000''>of</span> <span m=''359090''>cards</span> <span m=''360660''>and</span>
  <span m=''360750''>that''s</span> <span m=''360920''>a</span> <span m=''360960''>very</span>
  <span m=''361380''>hard</span> <span m=''361590''>thing</span> <span m=''361730''>to</span>
  <span m=''361800''>do.</span> <span m=''361940''>He</span> <span m=''362060''>said</span>
  <span m=''362330''>he</span> <span m=''362430''>had</span> <span m=''362470''>to</span>
  <span m=''362510''>practice</span> <span m=''362970''>8</span> <span m=''363170''>hours</span>
  <span m=''363480''>a</span> <span m=''363570''>day</span> <span m=''364270''>for</span>
  <span m=''364400''>over</span> <span m=''364580''>six</span> <span m=''364860''>months</span>
  <span m=''366330''>to</span> <span m=''366410''>be</span> <span m=''366620''>able</span>
  <span m=''366780''>to</span> <span m=''366870''>do</span> <span m=''367080''>it</span>
  <span m=''367190''>every</span> <span m=''367440''>time.</span> <span m=''367800''>In</span>
  <span m=''368080''>fact,</span> <span m=''368160''>he</span> <span m=''368270''>gave</span>
  <span m=''368380''>another</span> <span m=''368630''>talk</span> <span m=''368900''>at</span>
  <span m=''368950''>MIT</span> <span m=''369390''>where</span> <span m=''369465''>he</span>
  <span m=''369540''>came</span> <span m=''369830''>in</span> <span m=''369930''>and</span>
  <span m=''370060''>he</span> <span m=''370610''>made</span> <span m=''370860''>magic</span>
  <span m=''371180''>tricks,</span> <span m=''371870''>actually</span> <span m=''372210''>based</span>
  <span m=''372460''>on</span> <span m=''372510''>mathematics.</span> <span m=''373520''>And</span>
  <span m=''374100''>you</span> <span m=''374260''>would</span> <span m=''374450''>cut</span>
  <span m=''374680''>a</span> <span m=''374720''>deck,</span> <span m=''375650''>he</span>
  <span m=''375830''>would</span> <span m=''375990''>feel</span> <span m=''376220''>it</span>
  <span m=''376450''>like</span> <span m=''376660''>this</span> <span m=''377440''>and</span>
  <span m=''377590''>tell</span> <span m=''377720''>you</span> <span m=''378090''>where</span>
  <span m=''378340''>you</span> <span m=''378460''>cut,</span> <span m=''378710''>how</span>
  <span m=''378870''>many</span> <span m=''379040''>cards</span> <span m=''379500''>were</span>
  <span m=''379570''>in</span> <span m=''379640''>the</span> <span m=''379770''>part</span>
  <span m=''380000''>you</span> <span m=''380080''>picked</span> <span m=''380350''>up</span>
  <span m=''381620''>and</span> <span m=''381770''>then</span> <span m=''381930''>do</span>
  <span m=''382090''>his</span> <span m=''382240''>eight</span> <span m=''382390''>perfect</span>
  <span m=''382800''>shuffles,</span> <span m=''383220''>which</span> <span m=''383390''>is</span>
  <span m=''383490''>enough</span> <span m=''383710''>to</span> <span m=''383960''>return</span>
  <span m=''384215''>a</span> <span m=''384470''>normal</span> <span m=''384770''>52-card</span>
  <span m=''385480''>deck</span> <span m=''385980''>back</span> <span m=''386390''>to</span>
  <span m=''386520''>its</span> <span m=''386660''>original</span> <span m=''387300''>order.</span>
  </p><p><span m=''388720''>And</span> <span m=''388820''>then</span> <span m=''388870''>using</span>
  <span m=''389360''>this,</span> <span m=''390440''>he</span> <span m=''390580''>could</span>
  <span m=''390680''>play</span> <span m=''390810''>the</span> <span m=''390920''>game</span>
  <span m=''391170''>where</span> <span m=''391320''>pick</span> <span m=''391540''>any</span>
  <span m=''391690''>card,</span> <span m=''392960''>you</span> <span m=''393090''>stick</span>
  <span m=''393370''>it</span> <span m=''393460''>in,</span> <span m=''394360''>he</span>
  <span m=''394520''>feels</span> <span m=''395290''>where</span> <span m=''395480''>the</span>
  <span m=''395610''>card</span> <span m=''395940''>went,</span> <span m=''396650''>and</span>
  <span m=''396800''>then</span> <span m=''396920''>using</span> <span m=''397160''>mathematics,</span>
  <span m=''397800''>he</span> <span m=''397900''>could</span> <span m=''398030''>shuffle</span>
  <span m=''398480''>the</span> <span m=''398600''>deck</span> <span m=''398780''>eight</span>
  <span m=''398960''>times</span> <span m=''399260''>and</span> <span m=''399360''>make</span>
  <span m=''399500''>the</span> <span m=''399570''>card</span> <span m=''399830''>come</span>
  <span m=''399990''>out</span> <span m=''400180''>anywhere</span> <span m=''400500''>he</span>
  <span m=''400620''>wanted</span> <span m=''401450''>in</span> <span m=''401580''>the</span>
  <span m=''401670''>deck.</span> <span m=''402670''>So</span> <span m=''403050''>he</span>
  <span m=''403110''>had</span> <span m=''403210''>a</span> <span m=''403260''>lot</span>
  <span m=''403480''>going</span> <span m=''403710''>on</span> <span m=''403850''>upstairs</span>
  <span m=''404310''>too.</span> </p><p><span m=''406000''>He</span> <span m=''406210''>had</span>
  <span m=''406340''>an</span> <span m=''406400''>interesting</span> <span m=''406720''>life</span>
  <span m=''406960''>history.</span> <span m=''407910''>He</span> <span m=''408080''>ran</span>
  <span m=''408420''>away</span> <span m=''408710''>from</span> <span m=''408910''>home</span>
  <span m=''409890''>as</span> <span m=''410130''>a</span> <span m=''410180''>young</span>
  <span m=''410430''>child</span> <span m=''410880''>and</span> <span m=''411165''>joined</span>
  <span m=''411450''>the</span> <span m=''411560''>traveling</span> <span m=''412100''>circus.</span>
  <span m=''414150''>And</span> <span m=''414300''>then</span> <span m=''414420''>somehow</span>
  <span m=''414980''>from</span> <span m=''415190''>there,</span> <span m=''416050''>he</span>
  <span m=''416170''>joined</span> <span m=''416500''>the</span> <span m=''416570''>faculty</span>
  <span m=''417030''>at</span> <span m=''417100''>Harvard.</span> <span m=''417580''>You</span>
  <span m=''417870''>know,</span> <span m=''418060''>there''s</span> <span m=''418220''>an</span>
  <span m=''418380''>amazing</span> <span m=''419000''>story.</span> </p><p><span
  m=''421190''>And</span> <span m=''421400''>actually</span> <span m=''421710''>your</span>
  <span m=''421970''>story</span> <span m=''422180''>about</span> <span m=''422430''>Persi</span>
  <span m=''422897''>is</span> <span m=''424300''>he</span> <span m=''424490''>was</span>
  <span m=''424650''>the</span> <span m=''424760''>first</span> <span m=''425230''>guy</span>
  <span m=''425510''>to</span> <span m=''425590''>get</span> <span m=''425800''>kicked</span>
  <span m=''426050''>out</span> <span m=''426190''>of</span> <span m=''426380''>casinos</span>
  <span m=''427020''>for</span> <span m=''427160''>card</span> <span m=''427480''>counting.</span>
  <span m=''428060''>He</span> <span m=''428440''>figured</span> <span m=''428730''>that</span>
  <span m=''428900''>out</span> <span m=''429070''>way</span> <span m=''429260''>before</span>
  <span m=''429980''>the</span> <span m=''430090''>MIT</span> <span m=''430590''>team</span>
  <span m=''430900''>and</span> <span m=''430960''>the</span> <span m=''431040''>movie</span>
  <span m=''431450''><i>21.</i></span> <span m=''432970''>Down</span> <span m=''433130''>in</span>
  <span m=''433290''>Puerto</span> <span m=''433670''>Rico,</span> <span m=''434050''>he</span>
  <span m=''434190''>used</span> <span m=''434330''>to</span> <span m=''434400''>play</span>
  <span m=''434720''>and</span> <span m=''434960''>then</span> <span m=''435060''>they</span>
  <span m=''435170''>finally</span> <span m=''435550''>figured</span> <span m=''435860''>him</span>
  <span m=''436070''>out</span> <span m=''436250''>and</span> <span m=''436470''>he</span>
  <span m=''436610''>got</span> <span m=''436820''>booted.</span> </p><p><span m=''439470''>So</span>
  <span m=''439950''>back</span> <span m=''440190''>to</span> <span m=''440280''>independence,</span>
  <span m=''442600''>let''s</span> <span m=''442840''>do</span> <span m=''443630''>another</span>
  <span m=''444230''>picture</span> <span m=''444550''>example.</span> <span m=''446230''>Say</span>
  <span m=''446490''>that</span> <span m=''446630''>my</span> <span m=''446770''>sample</span>
  <span m=''447230''>space</span> <span m=''447820''>looks</span> <span m=''448060''>like</span>
  <span m=''448290''>this</span> <span m=''449720''>and</span> <span m=''449900''>I''ve</span>
  <span m=''449990''>got</span> <span m=''450220''>two</span> <span m=''450410''>events,</span>
  <span m=''451560''>A</span> <span m=''452480''>and</span> <span m=''453400''>B</span>
  <span m=''453730''>and</span> <span m=''453810''>they</span> <span m=''453900''>look</span>
  <span m=''454170''>like</span> <span m=''454380''>this,</span> <span m=''454650''>so</span>
  <span m=''454740''>they''re</span> <span m=''455110''>dis-joined.</span> <span m=''456456''>Are</span>
  <span m=''456840''>A</span> <span m=''457060''>and</span> <span m=''457430''>B</span>
  <span m=''457670''>independent?</span> <span m=''460340''>No.</span> <span m=''461410''>In</span>
  <span m=''461520''>fact</span> <span m=''461990''>what</span> <span m=''462270''>is</span>
  <span m=''462530''>the</span> <span m=''462640''>probability</span> <span m=''463310''>of</span>
  <span m=''463400''>A</span> <span m=''463570''>given</span> <span m=''463850''>B</span>
  <span m=''466590''>as</span> <span m=''466800''>I''ve</span> <span m=''466920''>drawn</span>
  <span m=''467390''>it?</span> </p><p><span m=''467780''>AUDIENCE:</span> <span m=''468170''>0.</span>
  </p><p><span m=''468560''>TOM LEIGHTON:</span> <span m=''468950''>0.</span> <span
  m=''469940''>Because</span> <span m=''470150''>if</span> <span m=''470550''>B</span>
  <span m=''470810''>occurs,</span> <span m=''472050''>you''re</span> <span m=''472280''>outside</span>
  <span m=''472780''>of</span> <span m=''472880''>A.</span> <span m=''474371''>And</span>
  <span m=''474870''>so</span> <span m=''475120''>this</span> <span m=''475510''>does</span>
  <span m=''475690''>not</span> <span m=''475930''>equal</span> <span m=''476075''>the</span>
  <span m=''476220''>probability</span> <span m=''476800''>of</span> <span m=''476870''>A</span>
  <span m=''477175''>as</span> <span m=''477480''>long</span> <span m=''477700''>as</span>
  <span m=''477790''>it''s</span> <span m=''477960''>not</span> <span m=''478410''>0.</span>
  <span m=''479860''>So</span> <span m=''480130''>disjoint</span> <span m=''480880''>events</span>
  <span m=''483200''>don''t</span> <span m=''483700''>imply</span> <span m=''484010''>that</span>
  <span m=''484320''>they''re</span> <span m=''484710''>independent.</span> </p><p><span
  m=''492730''>Now,</span> <span m=''493420''>what''s</span> <span m=''493700''>the</span>
  <span m=''493810''>picture</span> <span m=''494150''>look</span> <span m=''494490''>like</span>
  <span m=''495510''>for</span> <span m=''495670''>them</span> <span m=''495840''>to</span>
  <span m=''495910''>be</span> <span m=''496050''>independent?</span> <span m=''496630''>What</span>
  <span m=''496735''>is</span> <span m=''496840''>the</span> <span m=''496960''>right</span>
  <span m=''497500''>picture</span> <span m=''497800''>to</span> <span m=''497900''>draw</span>
  <span m=''498230''>here?</span> <span m=''499926''>So</span> <span m=''500310''>I</span>
  <span m=''500410''>got</span> <span m=''500580''>my</span> <span m=''500700''>sample</span>
  <span m=''501150''>space</span> <span m=''502400''>and</span> <span m=''502570''>say</span>
  <span m=''502860''>I</span> <span m=''502880''>make</span> <span m=''503300''>this</span>
  <span m=''503680''>half</span> <span m=''504080''>the</span> <span m=''504170''>sample</span>
  <span m=''504580''>space</span> <span m=''504930''>be</span> <span m=''505210''>A.</span>
  <span m=''506930''>Well,</span> <span m=''507230''>then</span> <span m=''507560''>B</span>
  <span m=''508070''>to</span> <span m=''508140''>be</span> <span m=''508270''>independent,</span>
  <span m=''509880''>would</span> <span m=''510450''>look</span> <span m=''510650''>something--</span>
  <span m=''511110''>I</span> <span m=''511295''>didn''t</span> <span m=''511480''>quite</span>
  <span m=''511860''>draw</span> <span m=''512130''>it.</span> <span m=''512175''>I</span>
  <span m=''512220''>actually</span> <span m=''512580''>have</span> <span m=''512770''>it</span>
  <span m=''512850''>be</span> <span m=''512960''>50-50.</span> </p><p><span m=''515309''>So</span>
  <span m=''516370''>if</span> <span m=''517140''>a</span> <span m=''517429''>is</span>
  <span m=''517700''>50%</span> <span m=''518539''>of</span> <span m=''518669''>S,</span>
  <span m=''519270''>like</span> <span m=''519470''>this</span> <span m=''519710''>half,</span>
  <span m=''521100''>then</span> <span m=''521860''>for</span> <span m=''522010''>A</span>
  <span m=''522159''>to</span> <span m=''522240''>be</span> <span m=''522320''>independent</span>
  <span m=''522890''>of</span> <span m=''522980''>B,</span> <span m=''523382''>A</span>
  <span m=''523784''>intersect</span> <span m=''524186''>B,</span> <span m=''525790''>this</span>
  <span m=''525990''>part,</span> <span m=''527360''>has</span> <span m=''527660''>to</span>
  <span m=''527730''>be</span> <span m=''527860''>50%</span> <span m=''528490''>of</span>
  <span m=''528550''>B.</span> <span m=''529850''>Because</span> <span m=''530540''>the</span>
  <span m=''530640''>probability</span> <span m=''531860''>of</span> <span m=''532040''>A</span>
  <span m=''532390''>given</span> <span m=''532680''>B</span> <span m=''533920''>must</span>
  <span m=''534190''>equal</span> <span m=''534520''>the</span> <span m=''534610''>probability</span>
  <span m=''535190''>of</span> <span m=''535270''>A</span> <span m=''536500''>to</span>
  <span m=''536720''>be</span> <span m=''536820''>independent.</span> <span m=''538170''>So</span>
  <span m=''538210''>this</span> <span m=''538440''>would</span> <span m=''538540''>be</span>
  <span m=''538670''>a</span> <span m=''538750''>picture</span> <span m=''539170''>where</span>
  <span m=''539480''>they</span> <span m=''539660''>are</span> <span m=''539870''>independent.</span>
  </p><p><span m=''543560''>Now,</span> <span m=''543650''>independent</span> <span
  m=''544180''>events</span> <span m=''544570''>are</span> <span m=''544660''>really</span>
  <span m=''544950''>nice</span> <span m=''545210''>to</span> <span m=''545330''>work</span>
  <span m=''545620''>with</span> <span m=''545970''>and</span> <span m=''546605''>in</span>
  <span m=''546890''>part</span> <span m=''547200''>because</span> <span m=''547410''>they</span>
  <span m=''547490''>have</span> <span m=''547600''>a</span> <span m=''547640''>very</span>
  <span m=''548000''>simple</span> <span m=''548540''>rule</span> <span m=''549560''>for</span>
  <span m=''549720''>computing</span> <span m=''550170''>the</span> <span m=''550260''>probability</span>
  <span m=''551080''>of</span> <span m=''551220''>an</span> <span m=''551330''>intersection</span>
  <span m=''552060''>of</span> <span m=''552190''>events</span> <span m=''555070''>and</span>
  <span m=''555160''>it''s</span> <span m=''555300''>called</span> <span m=''555640''>the</span>
  <span m=''555720''>product</span> <span m=''556210''>rule</span> <span m=''557860''>for</span>
  <span m=''558290''>independent</span> <span m=''558730''>events.</span> <span m=''574150''>And</span>
  <span m=''574670''>that</span> <span m=''574970''>says</span> <span m=''575470''>that</span>
  <span m=''575590''>if</span> <span m=''575830''>A</span> <span m=''577230''>is</span>
  <span m=''577700''>independent</span> <span m=''578290''>of</span> <span m=''578370''>B,</span>
  <span m=''584620''>then</span> <span m=''585110''>the</span> <span m=''585200''>probability</span>
  <span m=''585990''>of</span> <span m=''586215''>A</span> <span m=''586440''>and</span>
  <span m=''586950''>B</span> <span m=''587240''>or</span> <span m=''587410''>A</span>
  <span m=''587580''>intersect</span> <span m=''588110''>B</span> <span m=''591000''>is</span>
  <span m=''591280''>just</span> <span m=''591560''>the</span> <span m=''591640''>product</span>
  <span m=''593160''>of</span> <span m=''593630''>their</span> <span m=''593780''>probabilities</span>
  <span m=''594680''>separately,</span> <span m=''595880''>the</span> <span m=''596010''>probability</span>
  <span m=''596690''>of</span> <span m=''596770''>A</span> <span m=''596940''>times</span>
  <span m=''597280''>the</span> <span m=''597360''>probability</span> <span m=''597930''>of</span>
  <span m=''598040''>B.</span> </p><p><span m=''599290''>So</span> <span m=''599430''>let''s</span>
  <span m=''599680''>prove</span> <span m=''600030''>this.</span> <span m=''605630''>And</span>
  <span m=''605810''>there''s</span> <span m=''605990''>two</span> <span m=''606180''>cases,</span>
  <span m=''606850''>depending</span> <span m=''607230''>on</span> <span m=''607410''>whether</span>
  <span m=''607670''>or</span> <span m=''607710''>not</span> <span m=''608560''>B</span>
  <span m=''608770''>can</span> <span m=''608900''>happen,</span> <span m=''609390''>if</span>
  <span m=''609550''>the</span> <span m=''609640''>probability</span> <span m=''610150''>of</span>
  <span m=''610220''>B</span> <span m=''610470''>is</span> <span m=''610620''>0</span>
  <span m=''610870''>or</span> <span m=''610970''>not.</span> <span m=''612490''>So</span>
  <span m=''612830''>case</span> <span m=''613120''>1</span> <span m=''617120''>is</span>
  <span m=''617740''>B</span> <span m=''617930''>can''t</span> <span m=''618210''>happen.</span>
  <span m=''618880''>The</span> <span m=''618950''>probability</span> <span m=''619390''>of</span>
  <span m=''619490''>B</span> <span m=''619690''>is</span> <span m=''619860''>0.</span>
  <span m=''622220''>In</span> <span m=''622350''>this</span> <span m=''622590''>case,</span>
  <span m=''625090''>what''s</span> <span m=''625300''>the</span> <span m=''625390''>probability</span>
  <span m=''625930''>of</span> <span m=''625965''>A</span> <span m=''626000''>and</span>
  <span m=''626490''>B?</span> <span m=''630680''>B</span> <span m=''630840''>can''t</span>
  <span m=''631110''>happen.</span> <span m=''632330''>0.</span> </p><p><span m=''633170''>If</span>
  <span m=''633390''>B</span> <span m=''633530''>can''t</span> <span m=''633810''>happen,</span>
  <span m=''634190''>then</span> <span m=''634970''>they</span> <span m=''635060''>both</span>
  <span m=''635330''>can''t.</span> <span m=''636620''>You</span> <span m=''636720''>can''t</span>
  <span m=''636950''>have</span> <span m=''637150''>both</span> <span m=''637360''>of</span>
  <span m=''637440''>them</span> <span m=''637560''>happening</span> <span m=''638800''>and</span>
  <span m=''639020''>that</span> <span m=''639210''>equals</span> <span m=''641070''>the</span>
  <span m=''641140''>probability</span> <span m=''641630''>of</span> <span m=''641710''>A</span>
  <span m=''643700''>times</span> <span m=''644020''>the</span> <span m=''644100''>probability</span>
  <span m=''644525''>of</span> <span m=''644950''>B</span> <span m=''647080''>because</span>
  <span m=''647290''>the</span> <span m=''647360''>probability</span> <span m=''647780''>of</span>
  <span m=''647850''>B</span> <span m=''647990''>is</span> <span m=''648150''>0.</span>
  <span m=''648670''>So</span> <span m=''648840''>that</span> <span m=''648980''>case</span>
  <span m=''649230''>works.</span> </p><p><span m=''653170''>Case</span> <span m=''653460''>2</span>
  <span m=''655680''>is</span> <span m=''656040''>the</span> <span m=''656130''>probability</span>
  <span m=''656710''>of</span> <span m=''656790''>B</span> <span m=''657150''>is</span>
  <span m=''657290''>bigger</span> <span m=''657550''>than</span> <span m=''657710''>0.</span>
  <span m=''661720''>In</span> <span m=''661850''>that</span> <span m=''662060''>case,</span>
  <span m=''662500''>we</span> <span m=''662610''>have</span> <span m=''664730''>the</span>
  <span m=''664810''>probability</span> <span m=''665400''>of</span> <span m=''665445''>A</span>
  <span m=''665490''>and</span> <span m=''665860''>B,</span> <span m=''668020''>A</span>
  <span m=''668190''>intersect</span> <span m=''668660''>B,</span> <span m=''669766''>well,</span>
  <span m=''670140''>from</span> <span m=''670220''>the</span> <span m=''670300''>definition,</span>
  <span m=''670980''>is</span> <span m=''671080''>the</span> <span m=''671170''>probability</span>
  <span m=''671690''>of</span> <span m=''671770''>B</span> <span m=''673390''>times</span>
  <span m=''673850''>the</span> <span m=''673930''>probability</span> <span m=''674630''>of</span>
  <span m=''674820''>A</span> <span m=''675080''>given</span> <span m=''675390''>B.</span>
  <span m=''676900''>We</span> <span m=''677000''>did</span> <span m=''677150''>that</span>
  <span m=''677320''>last</span> <span m=''677620''>time.</span> <span m=''679270''>And</span>
  <span m=''679480''>by</span> <span m=''679640''>independence,</span> <span m=''681160''>this</span>
  <span m=''681390''>is</span> <span m=''681500''>just</span> <span m=''681810''>the</span>
  <span m=''681900''>probability</span> <span m=''682400''>of</span> <span m=''682480''>A</span>
  <span m=''684370''>because</span> <span m=''684630''>A</span> <span m=''684880''>is</span>
  <span m=''685155''>independent</span> <span m=''685292''>of</span> <span m=''685430''>B,</span>
  <span m=''686630''>so</span> <span m=''686860''>we''re</span> <span m=''687020''>done.</span>
  </p><p><span m=''693280''>In</span> <span m=''693370''>fact,</span> <span m=''694360''>many</span>
  <span m=''694750''>texts</span> <span m=''695270''>will</span> <span m=''695470''>define</span>
  <span m=''697610''>independence</span> <span m=''698420''>by</span> <span m=''698640''>this</span>
  <span m=''698840''>product</span> <span m=''699230''>rule.</span> <span m=''700460''>Many</span>
  <span m=''700750''>texts</span> <span m=''701100''>will</span> <span m=''701250''>say</span>
  <span m=''701730''>that</span> <span m=''701990''>A</span> <span m=''702320''>and</span>
  <span m=''702690''>B</span> <span m=''702890''>are</span> <span m=''702990''>independent</span>
  <span m=''703650''>if</span> <span m=''703870''>this</span> <span m=''704110''>is</span>
  <span m=''704240''>true.</span> <span m=''706320''>And</span> <span m=''706520''>it''s</span>
  <span m=''706650''>equivalent,</span> <span m=''707310''>it</span> <span m=''707420''>turns</span>
  <span m=''707700''>out.</span> <span m=''708070''>We</span> <span m=''708180''>won''t</span>
  <span m=''708360''>prove</span> <span m=''708610''>that</span> <span m=''708780''>here,</span>
  <span m=''709100''>but</span> <span m=''709760''>if</span> <span m=''709880''>you</span>
  <span m=''709970''>use</span> <span m=''710240''>this</span> <span m=''710460''>as</span>
  <span m=''710540''>the</span> <span m=''710640''>definition,</span> <span m=''711810''>then</span>
  <span m=''711980''>you</span> <span m=''712090''>can</span> <span m=''712220''>derive</span>
  <span m=''712620''>our</span> <span m=''712830''>definition</span> <span m=''713460''>as</span>
  <span m=''713560''>a</span> <span m=''713630''>result.</span> <span m=''714170''>So</span>
  <span m=''714320''>this</span> <span m=''714550''>is</span> <span m=''714660''>an</span>
  <span m=''714750''>equivalent</span> <span m=''715300''>definition</span> <span
  m=''715820''>of</span> <span m=''715900''>independence.</span> </p><p><span m=''719960''>Another</span>
  <span m=''720240''>nice</span> <span m=''720580''>fact</span> <span m=''721730''>about</span>
  <span m=''722460''>independent</span> <span m=''723040''>events</span> <span m=''723570''>is</span>
  <span m=''723940''>that</span> <span m=''725210''>it''s</span> <span m=''725420''>a</span>
  <span m=''725660''>symmetric</span> <span m=''726310''>relationship.</span> <span
  m=''732210''>It''s</span> <span m=''732630''>called</span> <span m=''732870''>the</span>
  <span m=''732960''>symmetry</span> <span m=''733470''>of</span> <span m=''733550''>independence.</span>
  <span m=''746330''>That</span> <span m=''746560''>says</span> <span m=''746970''>that</span>
  <span m=''747360''>if</span> <span m=''747590''>they</span> <span m=''747895''>A</span>
  <span m=''748960''>is</span> <span m=''749560''>independent</span> <span m=''750150''>of</span>
  <span m=''750270''>B,</span> <span m=''754540''>then</span> <span m=''754730''>the</span>
  <span m=''754820''>reverse</span> <span m=''755230''>is</span> <span m=''755340''>true.</span>
  <span m=''756440''>B</span> <span m=''757460''>is</span> <span m=''758020''>independent</span>
  <span m=''758590''>of</span> <span m=''758690''>A.</span> <span m=''763048''>Now,</span>
  <span m=''763500''>we</span> <span m=''763610''>won''t</span> <span m=''764020''>prove</span>
  <span m=''764490''>that.</span> <span m=''766240''>It''s</span> <span m=''766410''>actually</span>
  <span m=''766780''>easier</span> <span m=''767100''>to</span> <span m=''767420''>see</span>
  <span m=''767540''>that</span> <span m=''767660''>it''s</span> <span m=''767780''>true</span>
  <span m=''768590''>if</span> <span m=''768760''>this</span> <span m=''768970''>were</span>
  <span m=''769030''>the</span> <span m=''769140''>definition</span> <span m=''771550''>of</span>
  <span m=''771710''>independence</span> <span m=''772380''>because</span> <span m=''773510''>A</span>
  <span m=''773700''>intersect</span> <span m=''774200''>B</span> <span m=''774370''>is</span>
  <span m=''774490''>the</span> <span m=''774570''>same</span> <span m=''774810''>as</span>
  <span m=''774940''>B</span> <span m=''775130''>intersect</span> <span m=''775530''>A</span>
  <span m=''777006''>and</span> <span m=''777500''>multiplication</span> <span m=''778280''>is</span>
  <span m=''778540''>commutative.</span> <span m=''779750''>So</span> <span m=''779930''>it''s</span>
  <span m=''780040''>easier</span> <span m=''780320''>to</span> <span m=''780410''>see</span>
  <span m=''780660''>it</span> <span m=''780740''>if</span> <span m=''780820''>we</span>
  <span m=''780920''>had</span> <span m=''780980''>used</span> <span m=''781230''>that</span>
  <span m=''781440''>definition.</span> </p><p><span m=''783980''>So</span> <span
  m=''785660''>because</span> <span m=''786080''>of</span> <span m=''786180''>this</span>
  <span m=''786360''>we</span> <span m=''786520''>often</span> <span m=''786750''>just</span>
  <span m=''786900''>say</span> <span m=''787150''>A</span> <span m=''787400''>and</span>
  <span m=''787700''>B</span> <span m=''787860''>are</span> <span m=''787950''>independent</span>
  <span m=''788770''>because</span> <span m=''788940''>it</span> <span m=''789010''>doesn''t</span>
  <span m=''789260''>matter</span> <span m=''789540''>which</span> <span m=''789760''>order</span>
  <span m=''790360''>you''re</span> <span m=''790490''>taking</span> <span m=''790790''>them</span>
  <span m=''790950''>in.</span> <span m=''793450''>All</span> <span m=''793530''>right,</span>
  <span m=''793640''>any</span> <span m=''793790''>questions</span> <span m=''795090''>about</span>
  <span m=''795260''>the</span> <span m=''795340''>definition</span> <span m=''797420''>so</span>
  <span m=''797550''>far?</span> <span m=''799171''>All</span> <span m=''799610''>right.</span>
  <span m=''799970''>Let''s</span> <span m=''800420''>do</span> <span m=''800900''>some</span>
  <span m=''801100''>examples.</span> </p><p><span m=''814590''>Let''s</span> <span
  m=''814680''>say</span> <span m=''814830''>I</span> <span m=''814920''>have</span>
  <span m=''815220''>two</span> <span m=''815780''>independent</span> <span m=''816680''>fair</span>
  <span m=''817050''>coins.</span> <span m=''827730''>And</span> <span m=''828010''>I''m</span>
  <span m=''828110''>going</span> <span m=''828230''>to</span> <span m=''828270''>have</span>
  <span m=''828820''>the</span> <span m=''828990''>event</span> <span m=''829510''>A</span>
  <span m=''831440''>be</span> <span m=''832970''>the</span> <span m=''833050''>situation</span>
  <span m=''833960''>when</span> <span m=''834170''>the</span> <span m=''834280''>coins</span>
  <span m=''835060''>match,</span> <span m=''836330''>both</span> <span m=''836590''>heads,</span>
  <span m=''836890''>both</span> <span m=''837100''>tails.</span> <span m=''841700''>And</span>
  <span m=''842010''>B</span> <span m=''842290''>is</span> <span m=''842430''>going</span>
  <span m=''842560''>to</span> <span m=''842620''>be</span> <span m=''842750''>the</span>
  <span m=''842900''>event</span> <span m=''844570''>that</span> <span m=''844740''>the</span>
  <span m=''844830''>first</span> <span m=''845220''>coin</span> <span m=''845600''>is</span>
  <span m=''845895''>heads.</span> <span m=''852420''>And</span> <span m=''852820''>I</span>
  <span m=''852870''>want</span> <span m=''853130''>to</span> <span m=''853180''>know,</span>
  <span m=''853500''>are</span> <span m=''853635''>A</span> <span m=''853770''>and</span>
  <span m=''854260''>B</span> <span m=''854940''>independent?</span> <span m=''858300''>Are</span>
  <span m=''858430''>those</span> <span m=''858810''>independent</span> <span m=''859530''>events?</span>
  </p><p><span m=''862995''>Well,</span> <span m=''864890''>what''s</span> <span m=''865090''>the</span>
  <span m=''865200''>first</span> <span m=''866840''>answer</span> <span m=''867200''>to</span>
  <span m=''867260''>this?</span> <span m=''867650''>I</span> <span m=''867690''>mean,</span>
  <span m=''869040''>A</span> <span m=''869610''>is</span> <span m=''869960''>event</span>
  <span m=''870260''>the</span> <span m=''870350''>coins</span> <span m=''870720''>match.</span>
  <span m=''871290''>B</span> <span m=''871555''>tells</span> <span m=''871820''>me</span>
  <span m=''871890''>what</span> <span m=''872010''>the</span> <span m=''872090''>first</span>
  <span m=''872350''>coin</span> <span m=''872620''>was.</span> <span m=''873670''>So</span>
  <span m=''873790''>the</span> <span m=''873870''>first</span> <span m=''874160''>inclination</span>
  <span m=''874760''>here</span> <span m=''875100''>is</span> <span m=''875190''>that</span>
  <span m=''875440''>these</span> <span m=''875650''>are</span> <span m=''875710''>dependent</span>
  <span m=''876340''>events</span> <span m=''878370''>because</span> <span m=''879380''>I</span>
  <span m=''879500''>know</span> <span m=''879740''>something</span> <span m=''879960''>about</span>
  <span m=''880170''>the</span> <span m=''880250''>first</span> <span m=''880540''>coin,</span>
  <span m=''880785''>so</span> <span m=''881030''>that</span> <span m=''881200''>might</span>
  <span m=''881470''>tell</span> <span m=''881640''>me</span> <span m=''881760''>something</span>
  <span m=''882090''>about</span> <span m=''882380''>the</span> <span m=''882450''>probability</span>
  <span m=''883020''>they</span> <span m=''883170''>match.</span> <span m=''884510''>There</span>
  <span m=''884680''>could</span> <span m=''884880''>be</span> <span m=''884980''>some</span>
  <span m=''885190''>dependence</span> <span m=''885690''>here.</span> </p><p><span
  m=''887080''>Now,</span> <span m=''887250''>in</span> <span m=''887340''>fact,</span>
  <span m=''887750''>because</span> <span m=''887850''>it''s</span> <span m=''887960''>set</span>
  <span m=''888190''>up,</span> <span m=''889010''>they''re</span> <span m=''889110''>independent</span>
  <span m=''890110''>and</span> <span m=''890240''>we</span> <span m=''890360''>can</span>
  <span m=''890510''>check</span> <span m=''890780''>that</span> <span m=''890980''>by</span>
  <span m=''891090''>just</span> <span m=''892330''>doing</span> <span m=''892560''>the</span>
  <span m=''892650''>calculation,</span> <span m=''893390''>computing</span> <span
  m=''893880''>the</span> <span m=''893960''>probability</span> <span m=''894500''>of</span>
  <span m=''894580''>A</span> <span m=''894720''>given</span> <span m=''894970''>B.</span>
  <span m=''898440''>Maybe</span> <span m=''898640''>I</span> <span m=''898690''>can</span>
  <span m=''898820''>do</span> <span m=''898920''>that.</span> <span m=''899220''>I''ll</span>
  <span m=''899336''>do</span> <span m=''899453''>that</span> <span m=''899570''>here.</span>
  <span m=''900910''>The</span> <span m=''901570''>probability</span> <span m=''902170''>of</span>
  <span m=''902340''>A</span> <span m=''903460''>given</span> <span m=''903780''>B</span>
  <span m=''906360''>is,</span> <span m=''907410''>well,</span> <span m=''909320''>the</span>
  <span m=''909430''>condition</span> <span m=''910890''>that</span> <span m=''911040''>they''re</span>
  <span m=''911200''>going</span> <span m=''911310''>to</span> <span m=''911370''>match</span>
  <span m=''911970''>given</span> <span m=''912190''>that</span> <span m=''912310''>the</span>
  <span m=''912400''>first</span> <span m=''912690''>point</span> <span m=''912870''>is</span>
  <span m=''913000''>heads</span> <span m=''913440''>means</span> <span m=''914370''>it''s</span>
  <span m=''914550''>the</span> <span m=''914630''>same</span> <span m=''914960''>as</span>
  <span m=''915110''>the</span> <span m=''915200''>second</span> <span m=''915570''>coin</span>
  <span m=''915820''>being</span> <span m=''916040''>heads.</span> <span m=''918280''>This</span>
  <span m=''918450''>is</span> <span m=''918510''>the</span> <span m=''918600''>probability</span>
  <span m=''919280''>the</span> <span m=''919340''>second</span> <span m=''919780''>coin</span>
  <span m=''922168''>is</span> <span m=''922640''>heads</span> <span m=''925260''>and</span>
  <span m=''925390''>that''s</span> <span m=''925630''>just</span> <span m=''925890''>1/2</span>
  <span m=''927380''>because</span> <span m=''927530''>it''s</span> <span m=''927680''>a</span>
  <span m=''927730''>fair</span> <span m=''927990''>coin</span> <span m=''930020''>and</span>
  <span m=''930240''>independent</span> <span m=''930740''>of</span> <span m=''930800''>the</span>
  <span m=''930880''>first</span> <span m=''931230''>one.</span> </p><p><span m=''931440''>Now,</span>
  <span m=''931940''>the</span> <span m=''932030''>probability</span> <span m=''934170''>of</span>
  <span m=''935350''>A,</span> <span m=''936900''>by</span> <span m=''937100''>itself,</span>
  <span m=''937520''>the</span> <span m=''937620''>events</span> <span m=''937920''>the</span>
  <span m=''938020''>coins</span> <span m=''938370''>match,</span> <span m=''938820''>what''s</span>
  <span m=''939090''>that?</span> <span m=''939860''>How</span> <span m=''940000''>much</span>
  <span m=''940190''>is</span> <span m=''940280''>that?</span> <span m=''948340''>What''s</span>
  <span m=''948540''>the</span> <span m=''948630''>probability</span> <span m=''949120''>the</span>
  <span m=''949220''>coins</span> <span m=''949580''>match?</span> </p><p><span m=''952640''>AUDIENCE:</span>
  <span m=''952950''>[INAUDIBLE].</span> </p><p><span m=''953945''>TOM LEIGHTON:</span>
  <span m=''954440''>1/4</span> <span m=''954890''>plus</span> <span m=''955210''>1/4.</span>
  <span m=''955680''>I''ve</span> <span m=''955900''>got</span> <span m=''956030''>1/4</span>
  <span m=''956160''>chance</span> <span m=''956480''>of</span> <span m=''956560''>heads,</span>
  <span m=''956820''>heads</span> <span m=''958020''>1/4</span> <span m=''958450''>chance</span>
  <span m=''958740''>of</span> <span m=''958830''>tails,</span> <span m=''959200''>tails,</span>
  <span m=''959560''>so</span> <span m=''959730''>it''s</span> <span m=''959870''>1/2,</span>
  <span m=''962100''>so</span> <span m=''962930''>it</span> <span m=''963000''>works</span>
  <span m=''963280''>out.</span> <span m=''963670''>The</span> <span m=''964920''>probability</span>
  <span m=''965560''>of</span> <span m=''965660''>A</span> <span m=''965800''>given</span>
  <span m=''966050''>B</span> <span m=''966430''>equals</span> <span m=''967570''>the</span>
  <span m=''967670''>probability</span> <span m=''968100''>of</span> <span m=''968220''>A.</span>
  <span m=''968340''>They''re</span> <span m=''968440''>both</span> <span m=''968770''>1/2.</span>
  <span m=''970200''>So</span> <span m=''971640''>A</span> <span m=''972020''>and</span>
  <span m=''972330''>B</span> <span m=''972540''>are</span> <span m=''972640''>independent</span>
  <span m=''973270''>events</span> <span m=''974770''>because</span> <span m=''974920''>that''s</span>
  <span m=''975160''>just</span> <span m=''975340''>the</span> <span m=''975430''>definition</span>
  <span m=''976400''>even</span> <span m=''976640''>though</span> <span m=''976725''>it</span>
  <span m=''976810''>looked</span> <span m=''977180''>like</span> <span m=''977370''>there</span>
  <span m=''977460''>might</span> <span m=''977670''>have</span> <span m=''977750''>been</span>
  <span m=''977830''>some</span> <span m=''977970''>dependence</span> <span m=''978500''>lurking</span>
  <span m=''978850''>around</span> <span m=''979190''>here.</span> </p><p><span m=''981170''>Now,</span>
  <span m=''981760''>this</span> <span m=''981950''>example</span> <span m=''982410''>that</span>
  <span m=''982500''>I</span> <span m=''982570''>just</span> <span m=''982780''>did</span>
  <span m=''982910''>is</span> <span m=''982990''>a</span> <span m=''983070''>little</span>
  <span m=''983350''>misleading.</span> <span m=''984630''>The</span> <span m=''985130''>intuition</span>
  <span m=''986120''>they</span> <span m=''986290''>probably</span> <span m=''986920''>are</span>
  <span m=''986980''>dependent</span> <span m=''987950''>actually</span> <span m=''988360''>is</span>
  <span m=''988490''>good</span> <span m=''988660''>intuition</span> <span m=''989140''>in</span>
  <span m=''989220''>this</span> <span m=''989380''>case</span> <span m=''990970''>because</span>
  <span m=''991330''>if</span> <span m=''991490''>I</span> <span m=''991590''>don''t</span>
  <span m=''992060''>have</span> <span m=''992370''>fair</span> <span m=''992680''>coins,</span>
  <span m=''994970''>they</span> <span m=''995130''>are</span> <span m=''995320''>dependent.</span>
  <span m=''997520''>All</span> <span m=''997650''>right.</span> <span m=''997850''>So</span>
  <span m=''998020''>in</span> <span m=''998090''>particular,</span> <span m=''999230''>let''s</span>
  <span m=''999340''>look</span> <span m=''999490''>at</span> <span m=''999560''>what</span>
  <span m=''999700''>happens</span> <span m=''1000220''>if</span> <span m=''1001150''>the</span>
  <span m=''1001640''>probability</span> <span m=''1002220''>of</span> <span m=''1002295''>a</span>
  <span m=''1002370''>heads</span> <span m=''1003680''>is</span> <span m=''1003870''>p</span>
  <span m=''1005220''>and</span> <span m=''1005400''>the</span> <span m=''1005470''>probability</span>
  <span m=''1006030''>of</span> <span m=''1006130''>tails</span> <span m=''1007840''>is</span>
  <span m=''1007990''>1</span> <span m=''1008240''>minus</span> <span m=''1008610''>p</span>
  <span m=''1008900''>for</span> <span m=''1008990''>both</span> <span m=''1009280''>coins.</span>
  </p><p><span m=''1012070''>So</span> <span m=''1012220''>let''s</span> <span m=''1012420''>compute</span>
  <span m=''1014200''>the</span> <span m=''1014600''>probability</span> <span m=''1015220''>of</span>
  <span m=''1015290''>A</span> <span m=''1015460''>given</span> <span m=''1015730''>B.</span>
  <span m=''1018260''>What</span> <span m=''1018430''>is</span> <span m=''1018610''>it</span>
  <span m=''1019510''>in</span> <span m=''1019630''>this</span> <span m=''1019790''>case?</span>
  <span m=''1022600''>Well,</span> <span m=''1022900''>it''s</span> <span m=''1023165''>the</span>
  <span m=''1023253''>probability</span> <span m=''1023341''>the</span> <span m=''1023430''>second</span>
  <span m=''1023720''>coin</span> <span m=''1023950''>is</span> <span m=''1024050''>heads.</span>
  <span m=''1024380''>What''s</span> <span m=''1024579''>that?</span> <span m=''1028319''>p</span>
  <span m=''1030450''>because</span> <span m=''1030560''>both</span> <span m=''1030750''>of</span>
  <span m=''1030940''>them</span> <span m=''1031109''>are</span> <span m=''1031190''>heads</span>
  <span m=''1031440''>with</span> <span m=''1031540''>probability,</span> <span m=''1032060''>p.</span>
  <span m=''1032700''>They''re</span> <span m=''1032859''>independent</span> <span
  m=''1033390''>still.</span> <span m=''1034109''>The</span> <span m=''1034230''>two</span>
  <span m=''1034380''>coins</span> <span m=''1034690''>are</span> <span m=''1034750''>independent.</span>
  </p><p><span m=''1036130''>And</span> <span m=''1036250''>now</span> <span m=''1036390''>let''s</span>
  <span m=''1036609''>look</span> <span m=''1036760''>at</span> <span m=''1036819''>the</span>
  <span m=''1036900''>probability</span> <span m=''1038369''>that</span> <span m=''1038440''>the</span>
  <span m=''1038530''>coins</span> <span m=''1038920''>match.</span> <span m=''1040859''>Well,</span>
  <span m=''1041150''>it''s</span> <span m=''1041270''>a</span> <span m=''1041329''>probability</span>
  <span m=''1041869''>of</span> <span m=''1041940''>heads,</span> <span m=''1042210''>heads</span>
  <span m=''1042530''>and</span> <span m=''1042569''>the</span> <span m=''1042609''>probability</span>
  <span m=''1042970''>of</span> <span m=''1043040''>tails,</span> <span m=''1043400''>tails.</span>
  <span m=''1044520''>Heads,</span> <span m=''1044849''>heads</span> <span m=''1045960''>is</span>
  <span m=''1046150''>p</span> <span m=''1046339''>times</span> <span m=''1046740''>p.</span>
  <span m=''1048180''>Tails,</span> <span m=''1048680''>tails</span> <span m=''1049200''>is</span>
  <span m=''1049310''>1</span> <span m=''1049570''>minus</span> <span m=''1049970''>p</span>
  <span m=''1050290''>squared.</span> <span m=''1054050''>So</span> <span m=''1054300''>to</span>
  <span m=''1054570''>independent,</span> <span m=''1055450''>I</span> <span m=''1055540''>need</span>
  <span m=''1055950''>this</span> <span m=''1056250''>to</span> <span m=''1056320''>equal</span>
  <span m=''1056710''>that</span> <span m=''1057840''>or</span> <span m=''1058110''>to</span>
  <span m=''1058170''>have</span> <span m=''1059516''>the</span> <span m=''1059890''>probability</span>
  <span m=''1060370''>of</span> <span m=''1060540''>B</span> <span m=''1060710''>be</span>
  <span m=''1060880''>0.</span> </p><p><span m=''1062330''>So</span> <span m=''1063300''>A</span>
  <span m=''1063580''>and</span> <span m=''1063970''>B</span> <span m=''1066670''>are</span>
  <span m=''1066870''>independent</span> <span m=''1070000''>if</span> <span m=''1070240''>and</span>
  <span m=''1070340''>only</span> <span m=''1070730''>if--</span> <span m=''1072380''>the</span>
  <span m=''1072520''>first</span> <span m=''1072850''>case</span> <span m=''1073220''>is</span>
  <span m=''1074220''>probability</span> <span m=''1074880''>B</span> <span m=''1076206''>is</span>
  <span m=''1076570''>0,</span> <span m=''1077330''>which</span> <span m=''1077750''>means</span>
  <span m=''1078110''>that</span> <span m=''1078770''>p</span> <span m=''1079040''>equals</span>
  <span m=''1079310''>0,</span> <span m=''1082970''>or</span> <span m=''1083840''>that</span>
  <span m=''1084390''>has</span> <span m=''1084660''>to</span> <span m=''1084720''>equal</span>
  <span m=''1085040''>this.</span> <span m=''1088470''>So</span> <span m=''1088780''>p</span>
  <span m=''1089080''>would</span> <span m=''1089190''>have</span> <span m=''1089370''>to</span>
  <span m=''1089450''>equal</span> <span m=''1089810''>1</span> <span m=''1090110''>minus</span>
  <span m=''1092090''>2p</span> <span m=''1093690''>plus</span> <span m=''1093980''>2p</span>
  <span m=''1094390''>squared,</span> <span m=''1095770''>just</span> <span m=''1096850''>square</span>
  <span m=''1097130''>that</span> <span m=''1097380''>out</span> <span m=''1097590''>there.</span>
  <span m=''1099420''>So</span> <span m=''1099750''>let''s</span> <span m=''1100010''>solve</span>
  <span m=''1100400''>this.</span> <span m=''1100750''>That</span> <span m=''1100970''>happens</span>
  <span m=''1101460''>if</span> <span m=''1101610''>and</span> <span m=''1101700''>only</span>
  <span m=''1102050''>if</span> <span m=''1103550''>0</span> <span m=''1104140''>equals</span>
  <span m=''1104580''>1</span> <span m=''1104910''>minus</span> <span m=''1105390''>3p</span>
  <span m=''1106590''>plus</span> <span m=''1107000''>2p</span> <span m=''1107420''>squared.</span>
  <span m=''1109630''>That''s</span> <span m=''1110060''>true</span> <span m=''1110380''>if</span>
  <span m=''1110540''>and</span> <span m=''1110630''>only</span> <span m=''1110970''>if</span>
  <span m=''1112270''>0</span> <span m=''1112740''>equals--</span> <span m=''1113160''>I</span>
  <span m=''1113270''>factor</span> <span m=''1113760''>this--</span> <span m=''1114090''>it''s</span>
  <span m=''1114340''>1</span> <span m=''1114650''>minus</span> <span m=''1114990''>2p</span>
  <span m=''1116460''>times</span> <span m=''1116680''>1</span> <span m=''1116870''>minus</span>
  <span m=''1117200''>p</span> <span m=''1118946''>and</span> <span m=''1119360''>that''s</span>
  <span m=''1119600''>if</span> <span m=''1119750''>and</span> <span m=''1119840''>only</span>
  <span m=''1120170''>if</span> <span m=''1121280''>p</span> <span m=''1121500''>is</span>
  <span m=''1121630''>1/2</span> <span m=''1123460''>or</span> <span m=''1123710''>p</span>
  <span m=''1124060''>is</span> <span m=''1124490''>1,</span> <span m=''1126300''>two</span>
  <span m=''1126530''>roots.</span> </p><p><span m=''1128510''>So</span> <span m=''1128740''>if</span>
  <span m=''1128810''>the</span> <span m=''1128910''>coins</span> <span m=''1129330''>are</span>
  <span m=''1129440''>always</span> <span m=''1129790''>heads,</span> <span m=''1130690''>they''re</span>
  <span m=''1130840''>independent.</span> <span m=''1131160''>If</span> <span m=''1131480''>they''re</span>
  <span m=''1131630''>always</span> <span m=''1131980''>tails,</span> <span m=''1132690''>the</span>
  <span m=''1133090''>events</span> <span m=''1133460''>are</span> <span m=''1133530''>independent</span>
  <span m=''1134040''>or</span> <span m=''1134280''>if</span> <span m=''1134350''>they''re</span>
  <span m=''1134480''>fair</span> <span m=''1134830''>coins,</span> <span m=''1136840''>these</span>
  <span m=''1137110''>two</span> <span m=''1137270''>events</span> <span m=''1137610''>are</span>
  <span m=''1137680''>independent.</span> <span m=''1138300''>But</span> <span m=''1138460''>anything</span>
  <span m=''1138920''>else,</span> <span m=''1140580''>they''re</span> <span m=''1140740''>not</span>
  <span m=''1141250''>independent</span> <span m=''1141750''>anymore.</span> <span
  m=''1144280''>Any</span> <span m=''1144340''>questions?</span> <span m=''1146320''>And</span>
  <span m=''1146470''>now</span> <span m=''1146510''>you</span> <span m=''1146550''>can</span>
  <span m=''1146606''>sort</span> <span m=''1146663''>of</span> <span m=''1146720''>see</span>
  <span m=''1147140''>if</span> <span m=''1149380''>the</span> <span m=''1149690''>coins</span>
  <span m=''1149920''>are</span> <span m=''1149970''>likely</span> <span m=''1150310''>to</span>
  <span m=''1150380''>be</span> <span m=''1151320''>tails</span> <span m=''1151800''>and</span>
  <span m=''1151850''>the</span> <span m=''1151920''>first</span> <span m=''1152210''>one</span>
  <span m=''1152290''>comes</span> <span m=''1152520''>up</span> <span m=''1152650''>heads,</span>
  <span m=''1153360''>that</span> <span m=''1153580''>should</span> <span m=''1153830''>influence</span>
  <span m=''1154780''>the</span> <span m=''1154890''>probability</span> <span m=''1155350''>the</span>
  <span m=''1155450''>coins</span> <span m=''1155760''>match.</span> <span m=''1157361''>It</span>
  <span m=''1157740''>should</span> <span m=''1157990''>change.</span> </p><p><span
  m=''1161220''>Questions?</span> <span m=''1162530''>All</span> <span m=''1162620''>right.</span>
  <span m=''1162790''>So</span> <span m=''1162880''>there''s</span> <span m=''1163020''>a</span>
  <span m=''1163070''>nice</span> <span m=''1163340''>application</span> <span m=''1163950''>of</span>
  <span m=''1164030''>this</span> <span m=''1164310''>to</span> <span m=''1164400''>getting</span>
  <span m=''1164730''>an</span> <span m=''1164810''>edge</span> <span m=''1165480''>in</span>
  <span m=''1165630''>ultimate</span> <span m=''1166050''>Frisbee.</span> <span m=''1167860''>Now,</span>
  <span m=''1169030''>when</span> <span m=''1169150''>you''re</span> <span m=''1169240''>playing</span>
  <span m=''1169580''>ultimate,</span> <span m=''1170400''>you''ve</span> <span m=''1170520''>got</span>
  <span m=''1170650''>to</span> <span m=''1170710''>decide</span> <span m=''1171040''>who</span>
  <span m=''1171210''>gets</span> <span m=''1171680''>the</span> <span m=''1171750''>Frisbee</span>
  <span m=''1172090''>first.</span> <span m=''1173740''>And</span> <span m=''1174420''>sometimes</span>
  <span m=''1174850''>you</span> <span m=''1174920''>don''t</span> <span m=''1175100''>have</span>
  <span m=''1175320''>a</span> <span m=''1175400''>coin</span> <span m=''1175960''>to</span>
  <span m=''1176050''>flip,</span> <span m=''1177140''>call</span> <span m=''1177370''>heads</span>
  <span m=''1177590''>or</span> <span m=''1177650''>tails,</span> <span m=''1178400''>but</span>
  <span m=''1178460''>you</span> <span m=''1178530''>do</span> <span m=''1178700''>have</span>
  <span m=''1178870''>the</span> <span m=''1178950''>Frisbee.</span> </p><p><span
  m=''1180860''>Now,</span> <span m=''1181030''>you</span> <span m=''1181160''>could</span>
  <span m=''1181290''>flip</span> <span m=''1181590''>the</span> <span m=''1181680''>Frisbee</span>
  <span m=''1182115''>and</span> <span m=''1182550''>call</span> <span m=''1183150''>right</span>
  <span m=''1183400''>side</span> <span m=''1183630''>up</span> <span m=''1183890''>or</span>
  <span m=''1184030''>not,</span> <span m=''1184950''>but</span> <span m=''1185080''>the</span>
  <span m=''1185170''>problem</span> <span m=''1185590''>is</span> <span m=''1185830''>the</span>
  <span m=''1185930''>Frisbee</span> <span m=''1186350''>is</span> <span m=''1186530''>known</span>
  <span m=''1187070''>not</span> <span m=''1187290''>to</span> <span m=''1187340''>be</span>
  <span m=''1187480''>a</span> <span m=''1187530''>fair</span> <span m=''1187790''>coin.</span>
  <span m=''1189020''>When</span> <span m=''1189090''>you</span> <span m=''1189170''>toss</span>
  <span m=''1189490''>it</span> <span m=''1189560''>up</span> <span m=''1189650''>in</span>
  <span m=''1189730''>the</span> <span m=''1189850''>air,</span> <span m=''1190050''>it''s</span>
  <span m=''1190190''>likely</span> <span m=''1190720''>to</span> <span m=''1190800''>wind</span>
  <span m=''1191130''>up</span> <span m=''1191390''>on,</span> <span m=''1191700''>I</span>
  <span m=''1191750''>guess,</span> <span m=''1191940''>the</span> <span m=''1192350''>curved</span>
  <span m=''1192640''>edge</span> <span m=''1193170''>down.</span> <span m=''1193980''>So</span>
  <span m=''1194110''>that</span> <span m=''1194290''>wouldn''t</span> <span m=''1194500''>be</span>
  <span m=''1194620''>fair</span> <span m=''1195160''>to</span> <span m=''1195250''>call</span>
  <span m=''1195480''>heads</span> <span m=''1195680''>or</span> <span m=''1195740''>tails.</span>
  </p><p><span m=''1197690''>So</span> <span m=''1197980''>the</span> <span m=''1198080''>standard</span>
  <span m=''1198440''>solution</span> <span m=''1198940''>is</span> <span m=''1199270''>to</span>
  <span m=''1199380''>flip</span> <span m=''1199680''>the</span> <span m=''1199940''>two</span>
  <span m=''1200240''>Frisbees</span> <span m=''1200730''>at</span> <span m=''1200800''>the</span>
  <span m=''1200880''>same</span> <span m=''1201170''>time</span> <span m=''1201620''>or</span>
  <span m=''1201750''>one</span> <span m=''1202080''>Frisbee</span> <span m=''1202450''>twice</span>
  <span m=''1203520''>and</span> <span m=''1203810''>somebody</span> <span m=''1204180''>calls</span>
  <span m=''1204620''>same</span> <span m=''1205190''>or</span> <span m=''1205360''>different,</span>
  <span m=''1207570''>that</span> <span m=''1208790''>the</span> <span m=''1208880''>two</span>
  <span m=''1209040''>Frisbees</span> <span m=''1209560''>both</span> <span m=''1209940''>come</span>
  <span m=''1210110''>up</span> <span m=''1210250''>on</span> <span m=''1210340''>the</span>
  <span m=''1210420''>same</span> <span m=''1210850''>way</span> <span m=''1211440''>or</span>
  <span m=''1211660''>they</span> <span m=''1211780''>come</span> <span m=''1211950''>up</span>
  <span m=''1212090''>different</span> <span m=''1212380''>ways</span> <span m=''1213750''>and</span>
  <span m=''1213900''>then</span> <span m=''1214040''>if</span> <span m=''1214110''>you</span>
  <span m=''1214220''>called</span> <span m=''1214510''>it</span> <span m=''1214640''>right,</span>
  <span m=''1215010''>you</span> <span m=''1215130''>get</span> <span m=''1215270''>to</span>
  <span m=''1215340''>start</span> <span m=''1215570''>with</span> <span m=''1215700''>a</span>
  <span m=''1215740''>Frisbee.</span> <span m=''1217000''>And</span> <span m=''1217140''>the</span>
  <span m=''1217280''>idea</span> <span m=''1217660''>behind</span> <span m=''1218080''>this</span>
  <span m=''1218460''>is</span> <span m=''1218700''>that</span> <span m=''1219145''>that</span>
  <span m=''1220650''>simulates</span> <span m=''1221080''>a</span> <span m=''1221130''>fair</span>
  <span m=''1221390''>coin,</span> <span m=''1222700''>that</span> <span m=''1223180''>the</span>
  <span m=''1223270''>probability</span> <span m=''1223770''>that</span> <span m=''1223920''>they''re</span>
  <span m=''1224632''>the</span> <span m=''1224990''>same</span> <span m=''1225650''>is</span>
  <span m=''1225820''>50-50.</span> </p><p><span m=''1227970''>What</span> <span m=''1228090''>do</span>
  <span m=''1228130''>you</span> <span m=''1228200''>think.</span> <span m=''1228390''>Is</span>
  <span m=''1228470''>that</span> <span m=''1228610''>a</span> <span m=''1228660''>fair</span>
  <span m=''1228930''>way</span> <span m=''1229090''>to</span> <span m=''1229180''>decide</span>
  <span m=''1230290''>who</span> <span m=''1230410''>starts</span> <span m=''1230710''>first?</span>
  <span m=''1232300''>Yeah.</span> </p><p><span m=''1232560''>AUDIENCE:</span> <span
  m=''1233006''>No.</span> </p><p><span m=''1233452''>TOM LEIGHTON:</span> <span m=''1233900''>No.</span>
  <span m=''1234510''>Yeah,</span> <span m=''1235030''>that''s</span> <span m=''1235240''>right.</span>
  <span m=''1235500''>It''s</span> <span m=''1235680''>not.</span> <span m=''1237740''>Now,</span>
  <span m=''1238140''>it</span> <span m=''1238290''>is</span> <span m=''1239770''>in</span>
  <span m=''1239930''>the</span> <span m=''1240050''>case</span> <span m=''1240520''>when</span>
  <span m=''1242410''>the</span> <span m=''1242520''>coin</span> <span m=''1242800''>was</span>
  <span m=''1242950''>fair,</span> <span m=''1243590''>but</span> <span m=''1243710''>we</span>
  <span m=''1243800''>know</span> <span m=''1243940''>the</span> <span m=''1244050''>Frisbee</span>
  <span m=''1244330''>is</span> <span m=''1244400''>not</span> <span m=''1244610''>fair.</span>
  <span m=''1245610''>And</span> <span m=''1245720''>in</span> <span m=''1245830''>fact,</span>
  <span m=''1245875''>you</span> <span m=''1245920''>can</span> <span m=''1246220''>see</span>
  <span m=''1246620''>this</span> <span m=''1246900''>from</span> <span m=''1248470''>this</span>
  <span m=''1248720''>probability.</span> <span m=''1250040''>This</span> <span m=''1250250''>is</span>
  <span m=''1250340''>the</span> <span m=''1250440''>probability</span> <span m=''1251250''>of</span>
  <span m=''1251400''>a</span> <span m=''1251460''>match,</span> <span m=''1254680''>which</span>
  <span m=''1255590''>is</span> <span m=''1258360''>fine</span> <span m=''1258750''>at</span>
  <span m=''1258850''>p</span> <span m=''1259005''>equal</span> <span m=''1259160''>1/2,</span>
  <span m=''1260530''>but</span> <span m=''1260650''>in</span> <span m=''1260760''>fact,</span>
  <span m=''1261190''>if</span> <span m=''1261770''>you</span> <span m=''1261920''>analyze</span>
  <span m=''1262380''>this</span> <span m=''1262550''>equation,</span> <span m=''1263090''>you</span>
  <span m=''1263190''>find</span> <span m=''1263520''>out</span> <span m=''1263660''>its</span>
  <span m=''1263840''>minimum</span> <span m=''1264390''>value</span> <span m=''1266300''>is</span>
  <span m=''1266760''>at</span> <span m=''1266980''>p</span> <span m=''1267140''>equals</span>
  <span m=''1267410''>1/2</span> <span m=''1267950''>and</span> <span m=''1268250''>as</span>
  <span m=''1268380''>p</span> <span m=''1268770''>starts</span> <span m=''1269070''>moving</span>
  <span m=''1269320''>away</span> <span m=''1269660''>from</span> <span m=''1269830''>1/2</span>
  <span m=''1270200''>towards</span> <span m=''1270570''>0</span> <span m=''1270940''>or</span>
  <span m=''1271060''>to</span> <span m=''1271140''>1,</span> <span m=''1271860''>it</span>
  <span m=''1272010''>gets</span> <span m=''1272240''>bigger.</span> <span m=''1274520''>And</span>
  <span m=''1274700''>we</span> <span m=''1274820''>know</span> <span m=''1275240''>that</span>
  <span m=''1275450''>for</span> <span m=''1275560''>Frisbees,</span> <span m=''1275885''>p</span>
  <span m=''1276210''>is</span> <span m=''1276600''>not</span> <span m=''1276840''>1/2.</span>
  <span m=''1277610''>This</span> <span m=''1277870''>means</span> <span m=''1278510''>that</span>
  <span m=''1279190''>the</span> <span m=''1279290''>probability</span> <span m=''1279770''>of</span>
  <span m=''1279830''>a</span> <span m=''1279890''>match</span> <span m=''1280490''>is</span>
  <span m=''1280680''>better</span> <span m=''1281080''>than</span> <span m=''1281250''>50%.</span>
  </p><p><span m=''1283610''>So</span> <span m=''1283840''>if</span> <span m=''1283910''>you''re</span>
  <span m=''1284020''>ever</span> <span m=''1284260''>playing</span> <span m=''1284540''>ultimate,</span>
  <span m=''1285020''>always</span> <span m=''1285370''>call</span> <span m=''1285600''>same</span>
  <span m=''1287040''>because</span> <span m=''1287270''>you''re</span> <span m=''1287306''>going</span>
  <span m=''1287343''>to</span> <span m=''1287380''>have</span> <span m=''1287550''>a</span>
  <span m=''1287600''>better</span> <span m=''1287870''>than</span> <span m=''1287970''>50-50</span>
  <span m=''1288490''>chance</span> <span m=''1288860''>of</span> <span m=''1289120''>getting</span>
  <span m=''1289260''>to</span> <span m=''1289340''>start</span> <span m=''1289600''>with</span>
  <span m=''1289680''>the</span> <span m=''1289720''>Frisbee.</span> <span m=''1290720''>It''s</span>
  <span m=''1290850''>not</span> <span m=''1291040''>a</span> <span m=''1291090''>fair</span>
  <span m=''1292120''>example.</span> <span m=''1295390''>There</span> <span m=''1295560''>is</span>
  <span m=''1295820''>another</span> <span m=''1296050''>example</span> <span m=''1296480''>of</span>
  <span m=''1296530''>how</span> <span m=''1296710''>to</span> <span m=''1296790''>make</span>
  <span m=''1297300''>a</span> <span m=''1297380''>fair</span> <span m=''1297700''>coin</span>
  <span m=''1298000''>from</span> <span m=''1299300''>a</span> <span m=''1299380''>biased</span>
  <span m=''1299800''>coin</span> <span m=''1300090''>to</span> <span m=''1300210''>an</span>
  <span m=''1300290''>unbiased</span> <span m=''1300790''>coin</span> <span m=''1300905''>in</span>
  <span m=''1301020''>homework,</span> <span m=''1301850''>ways</span> <span m=''1302230''>of</span>
  <span m=''1302370''>doing</span> <span m=''1302720''>this</span> <span m=''1303560''>that</span>
  <span m=''1303680''>are</span> <span m=''1303860''>fair.</span> <span m=''1304760''>Because</span>
  <span m=''1304960''>often</span> <span m=''1305230''>you</span> <span m=''1305310''>have</span>
  <span m=''1306480''>biased</span> <span m=''1306960''>random</span> <span m=''1307270''>numbers</span>
  <span m=''1307650''>and</span> <span m=''1307710''>you</span> <span m=''1307810''>want</span>
  <span m=''1307990''>to</span> <span m=''1308040''>get</span> <span m=''1308160''>unbiased</span>
  <span m=''1308760''>or</span> <span m=''1309440''>maybe</span> <span m=''1309640''>you</span>
  <span m=''1309710''>got</span> <span m=''1309830''>a</span> <span m=''1309870''>fair</span>
  <span m=''1310150''>coin</span> <span m=''1310920''>and</span> <span m=''1311040''>you</span>
  <span m=''1311120''>want</span> <span m=''1311310''>to</span> <span m=''1311350''>make</span>
  <span m=''1311580''>something</span> <span m=''1311830''>that</span> <span m=''1312300''>comes</span>
  <span m=''1312550''>up</span> <span m=''1312660''>heads</span> <span m=''1312890''>with</span>
  <span m=''1312960''>probability</span> <span m=''1313420''>1/3.</span> <span m=''1314570''>How</span>
  <span m=''1314830''>do</span> <span m=''1314890''>you</span> <span m=''1315020''>actually</span>
  <span m=''1315370''>do</span> <span m=''1315560''>that</span> <span m=''1315800''>in</span>
  <span m=''1315900''>a</span> <span m=''1315960''>way</span> <span m=''1316160''>that</span>
  <span m=''1316270''>works?</span> <span m=''1317720''>Any</span> <span m=''1317900''>questions</span>
  <span m=''1319550''>on</span> <span m=''1319660''>that?</span> </p><p><span m=''1324210''>The</span>
  <span m=''1324290''>next</span> <span m=''1324570''>example</span> <span m=''1325440''>is</span>
  <span m=''1325670''>from</span> <span m=''1326020''>the</span> <span m=''1326200''>first</span>
  <span m=''1327080''>OJ</span> <span m=''1327500''>Simpson</span> <span m=''1327980''>trial.</span>
  <span m=''1329190''>How</span> <span m=''1329370''>many</span> <span m=''1329550''>people</span>
  <span m=''1330050''>here</span> <span m=''1330230''>know</span> <span m=''1330410''>who</span>
  <span m=''1330620''>OJ</span> <span m=''1330870''>Simpson</span> <span m=''1331250''>is?</span>
  <span m=''1332930''>OK,</span> <span m=''1333120''>so</span> <span m=''1333240''>he''s</span>
  <span m=''1333330''>still</span> <span m=''1333550''>pretty</span> <span m=''1333760''>famous.</span>
  <span m=''1335610''>Now,</span> <span m=''1336300''>as</span> <span m=''1336430''>you</span>
  <span m=''1336530''>probably</span> <span m=''1336890''>know</span> <span m=''1337080''>then</span>
  <span m=''1337240''>he</span> <span m=''1337340''>was</span> <span m=''1337510''>a</span>
  <span m=''1337570''>famous</span> <span m=''1338010''>football</span> <span m=''1338410''>player.</span>
  <span m=''1339040''>Back</span> <span m=''1339230''>when</span> <span m=''1339370''>I</span>
  <span m=''1339440''>was</span> <span m=''1339630''>a</span> <span m=''1339710''>kid,</span>
  <span m=''1340520''>he</span> <span m=''1340650''>was</span> <span m=''1342010''>a</span>
  <span m=''1342550''>famous</span> <span m=''1342810''>college</span> <span m=''1343210''>player,</span>
  <span m=''1343500''>then</span> <span m=''1343580''>he</span> <span m=''1343660''>was</span>
  <span m=''1343780''>a</span> <span m=''1343830''>famous</span> <span m=''1344220''>pro</span>
  <span m=''1344640''>player</span> <span m=''1346460''>and</span> <span m=''1346650''>then</span>
  <span m=''1346780''>he</span> <span m=''1346850''>was</span> <span m=''1346990''>an</span>
  <span m=''1347070''>actor,</span> <span m=''1347620''>famous</span> <span m=''1347970''>actor.</span>
  </p><p><span m=''1349100''>And</span> <span m=''1349180''>then</span> <span m=''1350840''>he</span>
  <span m=''1351320''>was</span> <span m=''1351490''>accused</span> <span m=''1351940''>of</span>
  <span m=''1352070''>murdering</span> <span m=''1352520''>his</span> <span m=''1352660''>wife</span>
  <span m=''1353630''>in</span> <span m=''1353750''>a</span> <span m=''1353820''>gory</span>
  <span m=''1354430''>knifing</span> <span m=''1355150''>and</span> <span m=''1355570''>a</span>
  <span m=''1355620''>friend</span> <span m=''1355980''>of</span> <span m=''1356050''>his</span>
  <span m=''1356180''>wife''s.</span> <span m=''1357570''>And</span> <span m=''1358190''>ultimately,</span>
  <span m=''1358940''>the</span> <span m=''1359070''>jury</span> <span m=''1359480''>found</span>
  <span m=''1359695''>him</span> <span m=''1359910''>not</span> <span m=''1360220''>guilty,</span>
  <span m=''1361060''>but</span> <span m=''1361200''>pretty</span> <span m=''1361370''>much</span>
  <span m=''1361640''>everybody</span> <span m=''1362130''>in</span> <span m=''1362200''>the</span>
  <span m=''1362290''>country</span> <span m=''1362710''>thought</span> <span m=''1363020''>he</span>
  <span m=''1363150''>did</span> <span m=''1363330''>it.</span> <span m=''1363820''>He</span>
  <span m=''1363960''>looked</span> <span m=''1364530''>really</span> <span m=''1364750''>guilty.</span>
  <span m=''1366050''>And</span> <span m=''1366350''>it</span> <span m=''1366400''>was</span>
  <span m=''1366540''>a</span> <span m=''1366600''>big</span> <span m=''1367290''>media</span>
  <span m=''1367760''>event,</span> <span m=''1368400''>one</span> <span m=''1368560''>of</span>
  <span m=''1368720''>the</span> <span m=''1368890''>first</span> <span m=''1369210''>big</span>
  <span m=''1369410''>trial</span> <span m=''1369870''>events</span> <span m=''1370180''>on</span>
  <span m=''1370310''>TV.</span> <span m=''1371280''>And</span> <span m=''1371470''>so</span>
  <span m=''1371650''>all</span> <span m=''1371940''>the</span> <span m=''1372040''>proceedings</span>
  <span m=''1372520''>were</span> <span m=''1372635''>on</span> <span m=''1372750''>TV</span>
  <span m=''1373200''>and</span> <span m=''1373500''>everybody</span> <span m=''1374070''>watched</span>
  <span m=''1374390''>them.</span> <span m=''1374930''>We''d</span> <span m=''1375120''>all</span>
  <span m=''1375300''>go</span> <span m=''1375480''>home</span> <span m=''1375820''>to</span>
  <span m=''1375930''>watch</span> <span m=''1376230''>the</span> <span m=''1376360''>OJ</span>
  <span m=''1377240''>hearing.</span> <span m=''1377580''>It</span> <span m=''1377690''>was</span>
  <span m=''1377830''>amazing.</span> </p><p><span m=''1379930''>Now,</span> <span
  m=''1381620''>during</span> <span m=''1381960''>the</span> <span m=''1382100''>indictment</span>
  <span m=''1382580''>proceedings,</span> <span m=''1383270''>there</span> <span m=''1383430''>was</span>
  <span m=''1383570''>a</span> <span m=''1383620''>huge</span> <span m=''1384040''>dispute</span>
  <span m=''1384670''>over</span> <span m=''1384900''>what</span> <span m=''1385180''>independence</span>
  <span m=''1385920''>was</span> <span m=''1387140''>and</span> <span m=''1387300''>does</span>
  <span m=''1387480''>it</span> <span m=''1387590''>matter.</span> <span m=''1389650''>The</span>
  <span m=''1389810''>issue</span> <span m=''1390080''>arose</span> <span m=''1390560''>when</span>
  <span m=''1390630''>the</span> <span m=''1390720''>prosecution</span> <span m=''1392010''>witness</span>
  <span m=''1393240''>claimed</span> <span m=''1393810''>that</span> <span m=''1394140''>only</span>
  <span m=''1394410''>1</span> <span m=''1394750''>in</span> <span m=''1394920''>200</span>
  <span m=''1395490''>Americans</span> <span m=''1396740''>had</span> <span m=''1397020''>a</span>
  <span m=''1397080''>certain</span> <span m=''1397750''>blood</span> <span m=''1398050''>type</span>
  <span m=''1398730''>that</span> <span m=''1398900''>matched</span> <span m=''1399230''>the</span>
  <span m=''1399330''>blood</span> <span m=''1399620''>type</span> <span m=''1399900''>found</span>
  <span m=''1400420''>at</span> <span m=''1400580''>the</span> <span m=''1400670''>scene</span>
  <span m=''1400910''>of</span> <span m=''1400980''>the</span> <span m=''1401040''>crime,</span>
  <span m=''1401840''>which</span> <span m=''1402080''>was</span> <span m=''1402550''>alleged</span>
  <span m=''1402900''>to</span> <span m=''1402950''>be</span> <span m=''1403150''>OJ''s</span>
  <span m=''1403540''>blood.</span> <span m=''1404450''>And</span> <span m=''1404710''>this</span>
  <span m=''1404860''>was</span> <span m=''1405110''>during</span> <span m=''1405330''>the</span>
  <span m=''1405440''>indictment</span> <span m=''1406030''>and</span> <span m=''1406150''>back</span>
  <span m=''1406380''>then</span> <span m=''1406610''>DNA</span> <span m=''1406980''>tests</span>
  <span m=''1407450''>took</span> <span m=''1407580''>a</span> <span m=''1407620''>long</span>
  <span m=''1407910''>time</span> <span m=''1408720''>and</span> <span m=''1408840''>they</span>
  <span m=''1408910''>weren''t</span> <span m=''1409110''>ready</span> <span m=''1409350''>yet.</span>
  <span m=''1410590''>And</span> <span m=''1410930''>the</span> <span m=''1411020''>witness</span>
  <span m=''1411630''>presented</span> <span m=''1413080''>the</span> <span m=''1413200''>following</span>
  <span m=''1413710''>facts</span> <span m=''1413940''>and</span> <span m=''1414170''>this</span>
  <span m=''1414380''>was</span> <span m=''1414560''>the</span> <span m=''1415510''>crime</span>
  <span m=''1415890''>lab</span> <span m=''1416200''>guy,</span> <span m=''1417540''>the</span>
  <span m=''1417640''>police</span> <span m=''1418020''>guy.</span> </p><p><span m=''1432500''>He</span>
  <span m=''1432700''>said</span> <span m=''1433210''>that</span> <span m=''1433510''>1</span>
  <span m=''1433750''>in</span> <span m=''1433920''>10</span> <span m=''1434220''>people,</span>
  <span m=''1435830''>roughly,</span> <span m=''1437860''>matched</span> <span m=''1438310''>type</span>
  <span m=''1438740''>O</span> <span m=''1438960''>blood.</span> <span m=''1444000''>And</span>
  <span m=''1444410''>that</span> <span m=''1444560''>1</span> <span m=''1444830''>in</span>
  <span m=''1444940''>5</span> <span m=''1445360''>people</span> <span m=''1447440''>matched</span>
  <span m=''1448410''>the</span> <span m=''1448580''>Rh</span> <span m=''1449110''>factor</span>
  <span m=''1450000''>positive.</span> <span m=''1453910''>And</span> <span m=''1454310''>that</span>
  <span m=''1454480''>1</span> <span m=''1454710''>in</span> <span m=''1454810''>4</span>
  <span m=''1455130''>people</span> <span m=''1458040''>match</span> <span m=''1458620''>a</span>
  <span m=''1458710''>certain</span> <span m=''1459000''>kind</span> <span m=''1459180''>of</span>
  <span m=''1459310''>marker,</span> <span m=''1459820''>which</span> <span m=''1460610''>I</span>
  <span m=''1460720''>don''t</span> <span m=''1460840''>remember</span> <span m=''1461060''>what</span>
  <span m=''1461230''>it</span> <span m=''1461330''>was.</span> <span m=''1461610''>We''ll</span>
  <span m=''1461750''>just</span> <span m=''1461870''>call</span> <span m=''1461985''>it</span>
  <span m=''1462100''>marker</span> <span m=''1462550''>XYZ,</span> <span m=''1463950''>some</span>
  <span m=''1464150''>other</span> <span m=''1464840''>factor</span> <span m=''1465270''>of</span>
  <span m=''1465340''>the</span> <span m=''1465420''>blood.</span> <span m=''1466920''>And</span>
  <span m=''1467060''>then</span> <span m=''1467220''>this</span> <span m=''1467370''>conclusion</span>
  <span m=''1467980''>was</span> <span m=''1468520''>that</span> <span m=''1469800''>this</span>
  <span m=''1470010''>means</span> <span m=''1470330''>that</span> <span m=''1471000''>1</span>
  <span m=''1471290''>in</span> <span m=''1471430''>200</span> <span m=''1473370''>match</span>
  <span m=''1473740''>all</span> <span m=''1473930''>three</span> <span m=''1479350''>factors.</span>
  </p><p><span m=''1480720''>And</span> <span m=''1481660''>this</span> <span m=''1481870''>seems</span>
  <span m=''1482140''>reasonable</span> <span m=''1482580''>because</span> <span m=''1482835''>there''s</span>
  <span m=''1483970''>1/10</span> <span m=''1484260''>of</span> <span m=''1484650''>the</span>
  <span m=''1484715''>people</span> <span m=''1484780''>have</span> <span m=''1485000''>O,</span>
  <span m=''1485880''>if</span> <span m=''1486200''>15</span> <span m=''1486320''>of</span>
  <span m=''1486673''>them</span> <span m=''1487380''>have</span> <span m=''1488200''>positive</span>
  <span m=''1488470''>Rh</span> <span m=''1489130''>factor</span> <span m=''1489920''>and</span>
  <span m=''1490160''>then</span> <span m=''1490300''>1/4</span> <span m=''1490980''>of</span>
  <span m=''1491060''>all</span> <span m=''1491215''>of</span> <span m=''1491370''>those</span>
  <span m=''1492190''>have</span> <span m=''1492400''>this</span> <span m=''1492550''>marker,</span>
  <span m=''1493320''>that''s</span> <span m=''1493490''>1</span> <span m=''1493625''>in</span>
  <span m=''1493760''>200.</span> <span m=''1497430''>Now,</span> <span m=''1497680''>it''s</span>
  <span m=''1497790''>important</span> <span m=''1498270''>because</span> <span m=''1499550''>OJ''s</span>
  <span m=''1500070''>blood</span> <span m=''1500810''>and</span> <span m=''1500980''>the</span>
  <span m=''1501040''>blood</span> <span m=''1501670''>at</span> <span m=''1501880''>the</span>
  <span m=''1501960''>crime</span> <span m=''1502330''>scene</span> <span m=''1503630''>both</span>
  <span m=''1504670''>matched</span> <span m=''1505010''>all</span> <span m=''1505190''>three.</span>
  <span m=''1507310''>So</span> <span m=''1507520''>the</span> <span m=''1507640''>implication,</span>
  <span m=''1508330''>of</span> <span m=''1508430''>course,</span> <span m=''1508590''>is</span>
  <span m=''1508720''>that</span> <span m=''1508840''>OJ</span> <span m=''1508980''>is</span>
  <span m=''1509270''>looking</span> <span m=''1509470''>like</span> <span m=''1509710''>the</span>
  <span m=''1509780''>guy</span> <span m=''1510000''>who</span> <span m=''1510150''>did</span>
  <span m=''1510350''>it.</span> <span m=''1511620''>And</span> <span m=''1511780''>the</span>
  <span m=''1511860''>question</span> <span m=''1512260''>was,</span> <span m=''1512640''>well,</span>
  <span m=''1513640''>is</span> <span m=''1513900''>the</span> <span m=''1514010''>1</span>
  <span m=''1514195''>in</span> <span m=''1514380''>200</span> <span m=''1514980''>really</span>
  <span m=''1515250''>true?</span> <span m=''1516670''>We</span> <span m=''1516840''>can</span>
  <span m=''1516970''>sample</span> <span m=''1517800''>these</span> <span m=''1518080''>three</span>
  <span m=''1518290''>in</span> <span m=''1518335''>the</span> <span m=''1518380''>populations</span>
  <span m=''1519060''>and</span> <span m=''1519220''>see</span> <span m=''1519520''>they''re</span>
  <span m=''1519620''>true,</span> <span m=''1519720''>but</span> <span m=''1520350''>is</span>
  <span m=''1520570''>1</span> <span m=''1520860''>in</span> <span m=''1520970''>200</span>
  <span m=''1521450''>really</span> <span m=''1521700''>true?</span> </p><p><span
  m=''1523850''>Now,</span> <span m=''1524560''>it</span> <span m=''1524710''>would</span>
  <span m=''1525030''>be</span> <span m=''1525540''>if,</span> <span m=''1525810''>in</span>
  <span m=''1525950''>fact,</span> <span m=''1526540''>we</span> <span m=''1526700''>verified</span>
  <span m=''1527660''>that</span> <span m=''1528090''>1/5</span> <span m=''1528540''>of</span>
  <span m=''1528640''>the</span> <span m=''1528710''>type</span> <span m=''1528930''>O</span>
  <span m=''1529150''>people</span> <span m=''1529490''>have</span> <span m=''1529700''>positive</span>
  <span m=''1531360''>and</span> <span m=''1531520''>1/4</span> <span m=''1532120''>of</span>
  <span m=''1532250''>the</span> <span m=''1532320''>O</span> <span m=''1532390''>positive</span>
  <span m=''1533140''>people</span> <span m=''1533480''>have</span> <span m=''1533870''>the</span>
  <span m=''1533980''>XYZ</span> <span m=''1534530''>marker.</span> <span m=''1536500''>But</span>
  <span m=''1537590''>well,</span> <span m=''1537820''>we</span> <span m=''1537940''>don''t</span>
  <span m=''1538500''>necessarily</span> <span m=''1539160''>know</span> <span m=''1539480''>that</span>
  <span m=''1539860''>unless</span> <span m=''1540120''>we</span> <span m=''1540230''>go</span>
  <span m=''1540420''>figure</span> <span m=''1541110''>that</span> <span m=''1541350''>out.</span>
  <span m=''1542820''>If</span> <span m=''1542950''>you</span> <span m=''1543110''>assume</span>
  <span m=''1543650''>they''re</span> <span m=''1543840''>independent,</span> <span
  m=''1545030''>then</span> <span m=''1545190''>it</span> <span m=''1545240''>would</span>
  <span m=''1545370''>be</span> <span m=''1545500''>true.</span> <span m=''1546280''>The</span>
  <span m=''1546380''>product</span> <span m=''1546820''>rule</span> <span m=''1546990''>will</span>
  <span m=''1547160''>tell</span> <span m=''1547390''>us</span> <span m=''1547520''>that</span>
  <span m=''1547690''>if</span> <span m=''1547770''>you</span> <span m=''1547900''>assume</span>
  <span m=''1548370''>they''re</span> <span m=''1548530''>independent.</span> </p><p><span
  m=''1550280''>So</span> <span m=''1550740''>during</span> <span m=''1550970''>the</span>
  <span m=''1551080''>trial,</span> <span m=''1552090''>a</span> <span m=''1552190''>special</span>
  <span m=''1552640''>math</span> <span m=''1553320''>defense</span> <span m=''1553760''>counsel</span>
  <span m=''1554180''>showed</span> <span m=''1554460''>up,</span> <span m=''1555310''>not</span>
  <span m=''1555540''>part</span> <span m=''1555720''>of</span> <span m=''1555760''>the</span>
  <span m=''1555820''>normal</span> <span m=''1556180''>defense</span> <span m=''1556590''>team,</span>
  <span m=''1556790''>but</span> <span m=''1556860''>he</span> <span m=''1556920''>was</span>
  <span m=''1557070''>brought</span> <span m=''1557360''>in</span> <span m=''1558280''>as</span>
  <span m=''1558470''>a</span> <span m=''1558640''>mathematician</span> <span m=''1559005''>and</span>
  <span m=''1559370''>lawyer</span> <span m=''1560480''>and</span> <span m=''1560670''>he</span>
  <span m=''1561890''>crosses</span> <span m=''1562580''>the</span> <span m=''1562790''>police</span>
  <span m=''1563150''>guy</span> <span m=''1563300''>on</span> <span m=''1563610''>the</span>
  <span m=''1563920''>stand.</span> <span m=''1564570''>And</span> <span m=''1564790''>he</span>
  <span m=''1564990''>asked</span> <span m=''1565350''>the</span> <span m=''1565500''>police</span>
  <span m=''1565910''>guy,</span> <span m=''1566280''>the</span> <span m=''1566420''>lab</span>
  <span m=''1566700''>guy</span> <span m=''1567480''>if</span> <span m=''1567650''>it</span>
  <span m=''1567740''>is</span> <span m=''1567920''>known</span> <span m=''1568520''>that</span>
  <span m=''1568650''>these</span> <span m=''1568900''>three</span> <span m=''1569120''>factors</span>
  <span m=''1569840''>are</span> <span m=''1570470''>independent.</span> <span m=''1573350''>Well,</span>
  <span m=''1573670''>the</span> <span m=''1573760''>poor</span> <span m=''1574370''>police</span>
  <span m=''1574670''>lab</span> <span m=''1574930''>guy</span> <span m=''1575230''>never</span>
  <span m=''1575430''>heard</span> <span m=''1575640''>the</span> <span m=''1575720''>word</span>
  <span m=''1575900''>independent</span> <span m=''1576370''>before,</span> <span
  m=''1576790''>didn''t</span> <span m=''1576870''>know</span> <span m=''1577010''>what</span>
  <span m=''1577180''>it</span> <span m=''1577260''>meant</span> <span m=''1578370''>and</span>
  <span m=''1579080''>the</span> <span m=''1579170''>defense</span> <span m=''1579600''>counsel</span>
  <span m=''1579990''>proceeded</span> <span m=''1580380''>to</span> <span m=''1580450''>crucify</span>
  <span m=''1580990''>him</span> <span m=''1581420''>on</span> <span m=''1581610''>the</span>
  <span m=''1581700''>stand.</span> <span m=''1582680''>And</span> <span m=''1582950''>then</span>
  <span m=''1583180''>in</span> <span m=''1583440''>the</span> <span m=''1583450''>end,</span>
  <span m=''1583460''>all</span> <span m=''1583470''>he</span> <span m=''1583480''>could</span>
  <span m=''1583610''>say</span> <span m=''1583725''>was,</span> <span m=''1583840''>look,</span>
  <span m=''1584310''>we</span> <span m=''1584440''>just</span> <span m=''1584650''>get</span>
  <span m=''1584840''>these</span> <span m=''1585040''>things</span> <span m=''1585170''>and</span>
  <span m=''1585300''>we</span> <span m=''1585440''>multiply</span> <span m=''1585740''>them.</span>
  <span m=''1586210''>That''s</span> <span m=''1586430''>what</span> <span m=''1586500''>we''re</span>
  <span m=''1586620''>supposed</span> <span m=''1586900''>to</span> <span m=''1586990''>do.</span>
  </p><p><span m=''1589500''>It</span> <span m=''1589905''>was</span> <span m=''1590310''>a</span>
  <span m=''1590360''>little</span> <span m=''1590500''>scary.</span> <span m=''1590950''>The</span>
  <span m=''1591030''>actual</span> <span m=''1591450''>transcript--</span> <span
  m=''1592480''>you</span> <span m=''1592560''>can</span> <span m=''1592690''>still</span>
  <span m=''1592880''>get</span> <span m=''1593050''>it--</span> <span m=''1593120''>is</span>
  <span m=''1593190''>a</span> <span m=''1593240''>little</span> <span m=''1593640''>scary.</span>
  <span m=''1594620''>The</span> <span m=''1594730''>same</span> <span m=''1595060''>problem</span>
  <span m=''1595450''>arises</span> <span m=''1595950''>today</span> <span m=''1596260''>with</span>
  <span m=''1596410''>DNA</span> <span m=''1596810''>testing.</span> <span m=''1597990''>Only</span>
  <span m=''1598280''>there,</span> <span m=''1599250''>you''ve</span> <span m=''1599380''>got</span>
  <span m=''1599820''>lots</span> <span m=''1600200''>of</span> <span m=''1600300''>these</span>
  <span m=''1600560''>things</span> <span m=''1601880''>and</span> <span m=''1602090''>you</span>
  <span m=''1602180''>multiply</span> <span m=''1602910''>them</span> <span m=''1603020''>all</span>
  <span m=''1603200''>together</span> <span m=''1603720''>and</span> <span m=''1603820''>you</span>
  <span m=''1603920''>get</span> <span m=''1603980''>probabilities</span> <span m=''1604620''>like</span>
  <span m=''1604870''>one</span> <span m=''1605210''>in</span> <span m=''1605880''>many</span>
  <span m=''1606150''>billion</span> <span m=''1607190''>probability</span> <span
  m=''1607790''>of</span> <span m=''1607870''>a</span> <span m=''1607920''>match.</span>
  </p><p><span m=''1610260''>Now,</span> <span m=''1610950''>there''s</span> <span
  m=''1611140''>probably</span> <span m=''1611530''>a</span> <span m=''1611580''>higher</span>
  <span m=''1611870''>level</span> <span m=''1612140''>of</span> <span m=''1612200''>science</span>
  <span m=''1612620''>going</span> <span m=''1612840''>on</span> <span m=''1613410''>with</span>
  <span m=''1613520''>DNA</span> <span m=''1613900''>testing,</span> <span m=''1615430''>but</span>
  <span m=''1615560''>it''s</span> <span m=''1615690''>even</span> <span m=''1615900''>harder</span>
  <span m=''1616370''>to</span> <span m=''1616610''>really</span> <span m=''1617080''>establish</span>
  <span m=''1617650''>independence.</span> <span m=''1619440''>If</span> <span m=''1619530''>you</span>
  <span m=''1619680''>assume</span> <span m=''1620200''>it,</span> <span m=''1620620''>fine.</span>
  <span m=''1621560''>The</span> <span m=''1621650''>math</span> <span m=''1621910''>works</span>
  <span m=''1622180''>out</span> <span m=''1622320''>great.</span> <span m=''1622690''>You</span>
  <span m=''1622790''>just</span> <span m=''1622990''>multiply</span> <span m=''1623220''>them</span>
  <span m=''1623450''>together.</span> <span m=''1624280''>But</span> <span m=''1624460''>how</span>
  <span m=''1624650''>do</span> <span m=''1624710''>you</span> <span m=''1624820''>know</span>
  <span m=''1625020''>it''s</span> <span m=''1625150''>really</span> <span m=''1625470''>true?</span>
  <span m=''1626840''>How</span> <span m=''1627020''>do</span> <span m=''1627080''>you</span>
  <span m=''1627540''>know</span> <span m=''1628000''>that</span> <span m=''1628230''>maybe</span>
  <span m=''1628460''>a</span> <span m=''1628520''>lot</span> <span m=''1628900''>of</span>
  <span m=''1628960''>people</span> <span m=''1629210''>that</span> <span m=''1629310''>have</span>
  <span m=''1629500''>those</span> <span m=''1629840''>four</span> <span m=''1630330''>markers</span>
  <span m=''1630790''>and</span> <span m=''1630890''>DNA</span> <span m=''1631310''>don''t</span>
  <span m=''1631590''>happen</span> <span m=''1631910''>to</span> <span m=''1631980''>just</span>
  <span m=''1632250''>have</span> <span m=''1632400''>the</span> <span m=''1632500''>fifth</span>
  <span m=''1632880''>also,</span> <span m=''1634120''>but</span> <span m=''1634300''>it</span>
  <span m=''1634470''>really</span> <span m=''1634770''>is</span> <span m=''1635160''>totally</span>
  <span m=''1635770''>unrelated.</span> </p><p><span m=''1637160''>And</span> <span
  m=''1637310''>to</span> <span m=''1637390''>know</span> <span m=''1637610''>that</span>
  <span m=''1637820''>for</span> <span m=''1637920''>sure,</span> <span m=''1638900''>you</span>
  <span m=''1639060''>got</span> <span m=''1639210''>to</span> <span m=''1639280''>test</span>
  <span m=''1639630''>hundreds</span> <span m=''1640060''>of</span> <span m=''1640120''>millions</span>
  <span m=''1640460''>of</span> <span m=''1640540''>people,</span> <span m=''1641920''>which</span>
  <span m=''1642290''>we</span> <span m=''1642450''>really</span> <span m=''1642680''>haven''t</span>
  <span m=''1643060''>done</span> <span m=''1643270''>yet,</span> <span m=''1643840''>and</span>
  <span m=''1644020''>not</span> <span m=''1644190''>just</span> <span m=''1644380''>a</span>
  <span m=''1644430''>few</span> <span m=''1644620''>guys</span> <span m=''1645070''>in</span>
  <span m=''1645150''>Detroit</span> <span m=''1646320''>to</span> <span m=''1646430''>be</span>
  <span m=''1646510''>able</span> <span m=''1646610''>to</span> <span m=''1646670''>conclude</span>
  <span m=''1648330''>independence</span> <span m=''1648930''>of</span> <span m=''1649030''>1</span>
  <span m=''1649280''>in</span> <span m=''1649315''>a</span> <span m=''1649350''>billion</span>
  <span m=''1649670''>probabilities.</span> </p><p><span m=''1651800''>So</span> <span
  m=''1651990''>for</span> <span m=''1652180''>us,</span> <span m=''1652330''>this</span>
  <span m=''1652470''>is</span> <span m=''1652580''>a</span> <span m=''1652630''>lot</span>
  <span m=''1652860''>easier.</span> <span m=''1653160''>In</span> <span m=''1653220''>the</span>
  <span m=''1653300''>classroom,</span> <span m=''1653860''>we</span> <span m=''1654000''>assume</span>
  <span m=''1654390''>independence</span> <span m=''1654670''>and</span> <span m=''1654950''>we''ll</span>
  <span m=''1655100''>keep</span> <span m=''1655320''>doing</span> <span m=''1655520''>that</span>
  <span m=''1655690''>left</span> <span m=''1655950''>and</span> <span m=''1656030''>right,</span>
  <span m=''1657550''>but</span> <span m=''1657680''>it</span> <span m=''1657770''>doesn''t</span>
  <span m=''1658360''>mean</span> <span m=''1658630''>it''s</span> <span m=''1658800''>true</span>
  <span m=''1660210''>in</span> <span m=''1660360''>reality.</span> <span m=''1660620''>In</span>
  <span m=''1660880''>fact,</span> <span m=''1662070''>in</span> <span m=''1662190''>the</span>
  <span m=''1662370''>last</span> <span m=''1662700''>week</span> <span m=''1662810''>of</span>
  <span m=''1662870''>class.</span> <span m=''1663380''>We''ll</span> <span m=''1663590''>talk</span>
  <span m=''1663850''>about</span> <span m=''1664130''>how</span> <span m=''1664430''>false</span>
  <span m=''1665000''>assumption</span> <span m=''1665410''>of</span> <span m=''1665490''>independence</span>
  <span m=''1666720''>on</span> <span m=''1666930''>mortgage</span> <span m=''1667370''>failures</span>
  <span m=''1668650''>led</span> <span m=''1668980''>to</span> <span m=''1669060''>the</span>
  <span m=''1669170''>subprime</span> <span m=''1669640''>mortgage</span> <span m=''1670000''>disaster</span>
  <span m=''1670490''>in</span> <span m=''1670560''>the</span> <span m=''1670640''>recession.</span>
  <span m=''1671780''>It</span> <span m=''1671920''>was</span> <span m=''1672040''>all</span>
  <span m=''1672220''>because</span> <span m=''1672560''>of</span> <span m=''1672740''>some</span>
  <span m=''1672790''>mathematics</span> <span m=''1673330''>mistakes</span> <span
  m=''1674180''>that</span> <span m=''1674440''>people</span> <span m=''1674710''>made.</span>
  </p><p><span m=''1677530''>Now,</span> <span m=''1677960''>this</span> <span m=''1678140''>example</span>
  <span m=''1678600''>raises</span> <span m=''1678930''>the</span> <span m=''1679010''>question</span>
  <span m=''1679460''>of,</span> <span m=''1679910''>what</span> <span m=''1680180''>does</span>
  <span m=''1680320''>independence</span> <span m=''1680920''>mean</span> <span m=''1681160''>when</span>
  <span m=''1681270''>you</span> <span m=''1681340''>have</span> <span m=''1681520''>more</span>
  <span m=''1681720''>than</span> <span m=''1681900''>two</span> <span m=''1682160''>events?</span>
  <span m=''1684570''>We</span> <span m=''1684750''>defined</span> <span m=''1685220''>independence</span>
  <span m=''1685670''>when</span> <span m=''1685750''>there</span> <span m=''1685820''>is</span>
  <span m=''1685890''>two</span> <span m=''1686030''>events,</span> <span m=''1686360''>but</span>
  <span m=''1686450''>here</span> <span m=''1686680''>there''s</span> <span m=''1686980''>three.</span>
  <span m=''1688280''>And</span> <span m=''1688460''>so</span> <span m=''1688600''>to</span>
  <span m=''1688660''>be</span> <span m=''1688780''>careful,</span> <span m=''1689180''>we</span>
  <span m=''1689270''>got</span> <span m=''1689410''>to</span> <span m=''1689770''>actually</span>
  <span m=''1690080''>define</span> <span m=''1691450''>dependence</span> <span m=''1691990''>among</span>
  <span m=''1692300''>more</span> <span m=''1692680''>than</span> <span m=''1693160''>two</span>
  <span m=''1693370''>events</span> <span m=''1695360''>and</span> <span m=''1695430''>in</span>
  <span m=''1695490''>this</span> <span m=''1695690''>case,</span> <span m=''1696010''>we</span>
  <span m=''1696150''>talk</span> <span m=''1696480''>about</span> <span m=''1697690''>the</span>
  <span m=''1697830''>events</span> <span m=''1698200''>as</span> <span m=''1698320''>being</span>
  <span m=''1698570''>mutually</span> <span m=''1699250''>independent.</span> <span
  m=''1700990''>So</span> <span m=''1701140''>let</span> <span m=''1701250''>me</span>
  <span m=''1701360''>define</span> <span m=''1701820''>that.</span> </p><p><span
  m=''1716770''>So</span> <span m=''1716810''>if</span> <span m=''1716910''>I''ve</span>
  <span m=''1717030''>got</span> <span m=''1717230''>events</span> <span m=''1718450''>A1,</span>
  <span m=''1719890''>A2,</span> <span m=''1720874''>up</span> <span m=''1721366''>to</span>
  <span m=''1721860''>An,</span> <span m=''1724330''>we</span> <span m=''1724450''>say</span>
  <span m=''1724710''>they</span> <span m=''1724940''>are</span> <span m=''1725420''>mutually</span>
  <span m=''1726130''>independent</span> <span m=''1735670''>if,</span> <span m=''1736120''>and</span>
  <span m=''1736220''>this</span> <span m=''1736380''>is</span> <span m=''1736470''>a</span>
  <span m=''1736520''>little</span> <span m=''1736780''>complicated</span> <span m=''1737450''>notation,</span>
  <span m=''1739150''>but</span> <span m=''1739520''>for</span> <span m=''1739710''>all</span>
  <span m=''1740300''>i</span> <span m=''1742490''>and</span> <span m=''1742860''>for</span>
  <span m=''1743090''>all</span> <span m=''1743700''>sets</span> <span m=''1744780''>j</span>
  <span m=''1746480''>that</span> <span m=''1747040''>are</span> <span m=''1747340''>subsets</span>
  <span m=''1747840''>of</span> <span m=''1747930''>the</span> <span m=''1748070''>events,</span>
  <span m=''1750740''>but</span> <span m=''1750980''>not</span> <span m=''1751200''>including</span>
  <span m=''1751610''>i,</span> <span m=''1757500''>then</span> <span m=''1757770''>the</span>
  <span m=''1757880''>probability</span> <span m=''1759380''>that</span> <span m=''1759460''>the</span>
  <span m=''1759610''>i-th</span> <span m=''1759910''>event</span> <span m=''1760120''>occurs</span>
  <span m=''1761260''>given</span> <span m=''1762560''>that</span> <span m=''1763070''>all</span>
  <span m=''1763340''>the</span> <span m=''1763480''>events</span> <span m=''1763890''>in</span>
  <span m=''1763940''>the</span> <span m=''1764020''>subset</span> <span m=''1764490''>occurred,</span>
  <span m=''1768280''>is</span> <span m=''1768540''>the</span> <span m=''1768620''>same</span>
  <span m=''1769010''>as</span> <span m=''1769140''>the</span> <span m=''1769240''>probability</span>
  <span m=''1769770''>of</span> <span m=''1769840''>the</span> <span m=''1769940''>i-th</span>
  <span m=''1770210''>event</span> <span m=''1770480''>occurring</span> <span m=''1770870''>by</span>
  <span m=''1771050''>itself.</span> <span m=''1773280''>Or</span> <span m=''1773670''>there''s</span>
  <span m=''1773880''>a</span> <span m=''1773940''>special</span> <span m=''1774280''>case</span>
  <span m=''1774660''>where</span> <span m=''1775080''>the</span> <span m=''1775220''>chance</span>
  <span m=''1775570''>the</span> <span m=''1775810''>other</span> <span m=''1776060''>events</span>
  <span m=''1776390''>occur</span> <span m=''1776680''>is</span> <span m=''1776830''>0.</span>
  </p><p><span m=''1786710''>In</span> <span m=''1786890''>other</span> <span m=''1787100''>words,</span>
  <span m=''1787650''>a</span> <span m=''1787750''>collection</span> <span m=''1788250''>of</span>
  <span m=''1788320''>events</span> <span m=''1788740''>is</span> <span m=''1788860''>mutually</span>
  <span m=''1789330''>independent</span> <span m=''1791020''>if</span> <span m=''1791430''>any</span>
  <span m=''1791740''>knowledge</span> <span m=''1792220''>about</span> <span m=''1792580''>any</span>
  <span m=''1793510''>of</span> <span m=''1793640''>the</span> <span m=''1793730''>rest</span>
  <span m=''1794020''>of</span> <span m=''1794060''>the</span> <span m=''1794190''>events,</span>
  <span m=''1795070''>happening</span> <span m=''1795520''>or</span> <span m=''1795570''>not,</span>
  <span m=''1795960''>does</span> <span m=''1796110''>not</span> <span m=''1796390''>influence</span>
  <span m=''1797730''>the</span> <span m=''1797830''>event</span> <span m=''1798110''>you''re</span>
  <span m=''1798210''>looking</span> <span m=''1798470''>at</span> <span m=''1799030''>for</span>
  <span m=''1799190''>each</span> <span m=''1799410''>of</span> <span m=''1799480''>those</span>
  <span m=''1799670''>events.</span> <span m=''1800970''>So</span> <span m=''1801040''>no</span>
  <span m=''1801380''>information</span> <span m=''1801860''>about</span> <span m=''1802080''>any</span>
  <span m=''1802320''>of</span> <span m=''1802360''>the</span> <span m=''1802500''>other</span>
  <span m=''1802660''>markers</span> <span m=''1803080''>the</span> <span m=''1803190''>blood</span>
  <span m=''1803950''>influences</span> <span m=''1804630''>the</span> <span m=''1804760''>i-th</span>
  <span m=''1805045''>marker</span> <span m=''1805690''>for</span> <span m=''1805870''>any</span>
  <span m=''1806060''>i.</span> <span m=''1806980''>The</span> <span m=''1807080''>probabilities</span>
  <span m=''1807660''>are</span> <span m=''1807770''>unchanged.</span> </p><p><span
  m=''1809770''>Now,</span> <span m=''1809900''>there''s</span> <span m=''1810080''>an</span>
  <span m=''1810150''>equivalent</span> <span m=''1810790''>definitions</span> <span
  m=''1811430''>based</span> <span m=''1811710''>and</span> <span m=''1811780''>the</span>
  <span m=''1811860''>product</span> <span m=''1812340''>rule.</span> <span m=''1814691''>Let</span>
  <span m=''1815160''>me</span> <span m=''1815300''>show</span> <span m=''1815440''>you</span>
  <span m=''1815580''>that</span> <span m=''1815840''>version</span> <span m=''1816040''>because</span>
  <span m=''1816240''>that''s</span> <span m=''1816480''>easier</span> <span m=''1816860''>to</span>
  <span m=''1816940''>work</span> <span m=''1817240''>with</span> <span m=''1817400''>usually.</span>
  <span m=''1832850''>This</span> <span m=''1833040''>is</span> <span m=''1833170''>the</span>
  <span m=''1833250''>product</span> <span m=''1833750''>rule</span> <span m=''1834000''>form</span>
  <span m=''1843130''>and</span> <span m=''1843740''>it</span> <span m=''1843880''>says</span>
  <span m=''1844360''>that</span> <span m=''1844600''>A1,</span> <span m=''1845280''>A2,</span>
  <span m=''1846992''>up</span> <span m=''1847420''>to</span> <span m=''1847850''>An</span>
  <span m=''1849100''>are</span> <span m=''1850090''>mutually</span> <span m=''1850550''>independent</span>
  <span m=''1857900''>if</span> <span m=''1858480''>for</span> <span m=''1858810''>any</span>
  <span m=''1859110''>subset</span> <span m=''1859740''>of</span> <span m=''1859840''>the</span>
  <span m=''1859960''>events</span> <span m=''1867560''>the</span> <span m=''1867910''>probability</span>
  <span m=''1869210''>of</span> <span m=''1869730''>each</span> <span m=''1869960''>of</span>
  <span m=''1870030''>those</span> <span m=''1870280''>events</span> <span m=''1870660''>in</span>
  <span m=''1870730''>the</span> <span m=''1870800''>subset</span> <span m=''1871280''>happening,</span>
  <span m=''1871880''>all</span> <span m=''1872170''>them</span> <span m=''1872310''>happening,</span>
  <span m=''1876140''>is</span> <span m=''1876300''>simply</span> <span m=''1876750''>the</span>
  <span m=''1876860''>product</span> <span m=''1878500''>of</span> <span m=''1878700''>their</span>
  <span m=''1878890''>individual</span> <span m=''1879400''>probabilities.</span>
  </p><p><span m=''1886810''>So</span> <span m=''1887330''>independence</span> <span
  m=''1889260''>means</span> <span m=''1889810''>that</span> <span m=''1890740''>if</span>
  <span m=''1890800''>you</span> <span m=''1890910''>want</span> <span m=''1891060''>the</span>
  <span m=''1891160''>probability</span> <span m=''1891650''>of</span> <span m=''1891710''>a</span>
  <span m=''1891790''>bunch</span> <span m=''1892060''>of</span> <span m=''1892150''>events</span>
  <span m=''1892440''>occurring,</span> <span m=''1893430''>just</span> <span m=''1893940''>multiply</span>
  <span m=''1894480''>them</span> <span m=''1894630''>out</span> <span m=''1894740''>individually.</span>
  <span m=''1896060''>And</span> <span m=''1896190''>that</span> <span m=''1896430''>follows</span>
  <span m=''1896860''>for</span> <span m=''1897030''>independence</span> <span m=''1897370''>or</span>
  <span m=''1897710''>it</span> <span m=''1897910''>could</span> <span m=''1898050''>be</span>
  <span m=''1898310''>the</span> <span m=''1898440''>definition</span> <span m=''1898990''>of</span>
  <span m=''1899060''>independence,</span> <span m=''1899600''>depending</span> <span
  m=''1899900''>on</span> <span m=''1900000''>how</span> <span m=''1900040''>you</span>
  <span m=''1900160''>want</span> <span m=''1900330''>to</span> <span m=''1900400''>do</span>
  <span m=''1900590''>it.</span> <span m=''1901080''>So</span> <span m=''1901250''>either</span>
  <span m=''1901405''>of</span> <span m=''1901560''>these</span> <span m=''1901800''>are</span>
  <span m=''1901860''>good</span> <span m=''1902040''>enough</span> <span m=''1902290''>for</span>
  <span m=''1902390''>you</span> <span m=''1902460''>to</span> <span m=''1902530''>use</span>
  <span m=''1902890''>as</span> <span m=''1903330''>a</span> <span m=''1903400''>definition</span>
  <span m=''1903990''>or</span> <span m=''1904180''>a</span> <span m=''1904270''>result</span>
  <span m=''1905090''>for</span> <span m=''1905240''>independence.</span> <span m=''1907200''>And</span>
  <span m=''1907350''>so</span> <span m=''1907450''>the</span> <span m=''1907540''>blood</span>
  <span m=''1907810''>guy,</span> <span m=''1908000''>of</span> <span m=''1908080''>course,</span>
  <span m=''1908440''>is</span> <span m=''1908540''>just</span> <span m=''1908920''>multiplying</span>
  <span m=''1909220''>them</span> <span m=''1909520''>out</span> <span m=''1910030''>because</span>
  <span m=''1911020''>they''re</span> <span m=''1911180''>assumed</span> <span m=''1911490''>to</span>
  <span m=''1911550''>be</span> <span m=''1911670''>independent,</span> <span m=''1912390''>so</span>
  <span m=''1912600''>it''s</span> <span m=''1912730''>OK</span> <span m=''1913000''>that</span>
  <span m=''1913240''>way.</span> </p><p><span m=''1915180''>Let''s</span> <span m=''1915500''>do</span>
  <span m=''1915600''>an</span> <span m=''1915680''>example.</span> <span m=''1928920''>So</span>
  <span m=''1929340''>for</span> <span m=''1929520''>example,</span> <span m=''1929900''>say</span>
  <span m=''1930100''>we</span> <span m=''1930210''>have</span> <span m=''1930380''>three</span>
  <span m=''1930630''>events.</span> <span m=''1935160''>A1,</span> <span m=''1936440''>A2,</span>
  <span m=''1936955''>and</span> <span m=''1937280''>A3</span> <span m=''1939570''>are</span>
  <span m=''1939850''>mutually</span> <span m=''1940310''>independent</span> <span
  m=''1945430''>if,</span> <span m=''1946190''>these</span> <span m=''1946450''>are</span>
  <span m=''1946490''>the</span> <span m=''1946580''>things</span> <span m=''1946800''>you</span>
  <span m=''1946900''>have</span> <span m=''1947020''>to</span> <span m=''1947120''>check,</span>
  <span m=''1948450''>probability</span> <span m=''1949220''>A1</span> <span m=''1950970''>and</span>
  <span m=''1951130''>A2</span> <span m=''1952810''>is</span> <span m=''1953140''>just</span>
  <span m=''1953370''>the</span> <span m=''1954820''>probability</span> <span m=''1955190''>of</span>
  <span m=''1955340''>A1</span> <span m=''1955600''>times</span> <span m=''1955770''>the</span>
  <span m=''1955940''>probability</span> <span m=''1956340''>of</span> <span m=''1956440''>A2.</span>
  <span m=''1959160''>Then</span> <span m=''1959330''>you''d</span> <span m=''1959550''>check</span>
  <span m=''1961406''>that</span> <span m=''1961820''>the</span> <span m=''1962160''>probability</span>
  <span m=''1962600''>of</span> <span m=''1962800''>A1</span> <span m=''1963050''>and</span>
  <span m=''1963140''>A3</span> <span m=''1964900''>is</span> <span m=''1965090''>the</span>
  <span m=''1965180''>product</span> <span m=''1965610''>of</span> <span m=''1965690''>their</span>
  <span m=''1965880''>probabilities,</span> <span m=''1967490''>A1</span> <span m=''1967750''>and</span>
  <span m=''1967890''>A3.</span> <span m=''1974170''>And</span> <span m=''1974490''>you''d</span>
  <span m=''1974640''>check</span> <span m=''1975390''>the</span> <span m=''1975450''>probability</span>
  <span m=''1976180''>of</span> <span m=''1976950''>A2</span> <span m=''1977250''>and</span>
  <span m=''1977550''>A3</span> <span m=''1978950''>is</span> <span m=''1979260''>the</span>
  <span m=''1979350''>product</span> <span m=''1979810''>of</span> <span m=''1979890''>their</span>
  <span m=''1980090''>probabilities.</span> </p><p><span m=''1986160''>And</span>
  <span m=''1986400''>there''s</span> <span m=''1986550''>one</span> <span m=''1986760''>more</span>
  <span m=''1986930''>thing</span> <span m=''1987130''>to</span> <span m=''1987220''>check.</span>
  <span m=''1987550''>What''s</span> <span m=''1987740''>that?</span> <span m=''1990290''>All</span>
  <span m=''1990650''>of</span> <span m=''1990700''>them.</span> <span m=''1992120''>The</span>
  <span m=''1992250''>probability</span> <span m=''1993790''>of</span> <span m=''1993860''>all</span>
  <span m=''1994160''>of</span> <span m=''1994260''>them</span> <span m=''2000230''>is</span>
  <span m=''2000440''>the</span> <span m=''2000550''>product</span> <span m=''2001420''>of</span>
  <span m=''2001590''>each</span> <span m=''2001810''>of</span> <span m=''2002010''>them</span>
  <span m=''2003090''>together</span> <span m=''2003390''>here.</span> <span m=''2007940''>So</span>
  <span m=''2008100''>if</span> <span m=''2008170''>you</span> <span m=''2008280''>want</span>
  <span m=''2008470''>to</span> <span m=''2008520''>show</span> <span m=''2008950''>the</span>
  <span m=''2009090''>three</span> <span m=''2009470''>events</span> <span m=''2009820''>are</span>
  <span m=''2009870''>mutually</span> <span m=''2010220''>independent,</span> <span
  m=''2011050''>these</span> <span m=''2011310''>are</span> <span m=''2011340''>the</span>
  <span m=''2011410''>four</span> <span m=''2011640''>things</span> <span m=''2011890''>you</span>
  <span m=''2012030''>check.</span> <span m=''2013410''>That''s</span> <span m=''2013610''>one</span>
  <span m=''2013790''>way</span> <span m=''2013880''>to</span> <span m=''2013990''>do</span>
  <span m=''2014190''>it,</span> <span m=''2016170''>which</span> <span m=''2016400''>is</span>
  <span m=''2016700''>the</span> <span m=''2016810''>case</span> <span m=''2017090''>of</span>
  <span m=''2017145''>the</span> <span m=''2017200''>blood</span> <span m=''2017460''>typing</span>
  <span m=''2017850''>in</span> <span m=''2017895''>the</span> <span m=''2017940''>situation.</span>
  </p><p><span m=''2020816''>All</span> <span m=''2021260''>right.</span> <span m=''2021530''>Let''s</span>
  <span m=''2021730''>do</span> <span m=''2023210''>an</span> <span m=''2023280''>example.</span>
  <span m=''2029470''>Well,</span> <span m=''2029730''>for</span> <span m=''2029840''>example,</span>
  <span m=''2030700''>if</span> <span m=''2030780''>I</span> <span m=''2030850''>flip</span>
  <span m=''2031280''>three</span> <span m=''2032630''>unbiased,</span> <span m=''2033510''>mutually</span>
  <span m=''2033890''>independent</span> <span m=''2034230''>coins.</span> <span m=''2035290''>The</span>
  <span m=''2035790''>probability</span> <span m=''2036310''>of</span> <span m=''2036430''>two</span>
  <span m=''2036690''>of</span> <span m=''2036740''>them</span> <span m=''2036910''>being</span>
  <span m=''2037160''>heads</span> <span m=''2037540''>is</span> <span m=''2037640''>1/4.</span>
  <span m=''2038170''>The</span> <span m=''2038270''>probability</span> <span m=''2038680''>of</span>
  <span m=''2038840''>three</span> <span m=''2039000''>being</span> <span m=''2039240''>heads</span>
  <span m=''2039590''>is</span> <span m=''2040300''>1/8</span> <span m=''2041010''>and</span>
  <span m=''2041140''>so</span> <span m=''2041330''>forth.</span> <span m=''2045010''>Let''s</span>
  <span m=''2045310''>do</span> <span m=''2045960''>a</span> <span m=''2046060''>trickier</span>
  <span m=''2046560''>example.</span> <span m=''2047750''>This</span> <span m=''2047980''>is</span>
  <span m=''2048120''>a</span> <span m=''2048219''>question</span> <span m=''2048710''>that</span>
  <span m=''2048730''>was</span> <span m=''2048889''>on</span> <span m=''2049000''>the</span>
  <span m=''2049090''>final</span> <span m=''2049420''>exam</span> <span m=''2049900''>a</span>
  <span m=''2049949''>few</span> <span m=''2050139''>years</span> <span m=''2050400''>ago</span>
  <span m=''2052000''>and</span> <span m=''2053389''>a</span> <span m=''2053460''>lot</span>
  <span m=''2053750''>of</span> <span m=''2053790''>the</span> <span m=''2053880''>class</span>
  <span m=''2054195''>missed</span> <span m=''2054510''>it.</span> <span m=''2055340''>So</span>
  <span m=''2055590''>now</span> <span m=''2055840''>we''ll</span> <span m=''2055980''>do</span>
  <span m=''2056179''>it</span> <span m=''2056239''>here.</span> </p><p><span m=''2061610''>Say</span>
  <span m=''2061775''>I</span> <span m=''2061940''>flip</span> <span m=''2063469''>three</span>
  <span m=''2064690''>fair,</span> <span m=''2067050''>mutually</span> <span m=''2067580''>independent</span>
  <span m=''2072020''>coins</span> <span m=''2075449''>and</span> <span m=''2075710''>my</span>
  <span m=''2076110''>events</span> <span m=''2076719''>are</span> <span m=''2076780''>going</span>
  <span m=''2076880''>to</span> <span m=''2076960''>be</span> <span m=''2078420''>A1</span>
  <span m=''2079300''>is</span> <span m=''2079500''>the</span> <span m=''2079670''>event</span>
  <span m=''2082360''>coin</span> <span m=''2082800''>1</span> <span m=''2084480''>matches</span>
  <span m=''2084889''>coin</span> <span m=''2085150''>2.</span> <span m=''2091449''>The</span>
  <span m=''2091570''>second</span> <span m=''2091989''>event,</span> <span m=''2092320''>A2,</span>
  <span m=''2094050''>is</span> <span m=''2094230''>the</span> <span m=''2094360''>event</span>
  <span m=''2094730''>that</span> <span m=''2094850''>coin</span> <span m=''2095429''>2</span>
  <span m=''2096080''>matches</span> <span m=''2097460''>coin</span> <span m=''2097950''>3.</span>
  <span m=''2099420''>And</span> <span m=''2099910''>the</span> <span m=''2100000''>third</span>
  <span m=''2100310''>event,</span> <span m=''2101540''>A3,</span> <span m=''2103030''>is</span>
  <span m=''2103190''>the</span> <span m=''2103320''>event</span> <span m=''2103750''>that</span>
  <span m=''2104150''>coin</span> <span m=''2104450''>3</span> <span m=''2105570''>matches</span>
  <span m=''2106030''>coin</span> <span m=''2106420''>1.</span> </p><p><span m=''2109980''>And</span>
  <span m=''2110280''>the</span> <span m=''2110350''>question</span> <span m=''2110820''>was,</span>
  <span m=''2112290''>are</span> <span m=''2112500''>these</span> <span m=''2113120''>three</span>
  <span m=''2113520''>events</span> <span m=''2115180''>mutually</span> <span m=''2115650''>independent?</span>
  <span m=''2118040''>Prove</span> <span m=''2118280''>your</span> <span m=''2118440''>answer.</span>
  <span m=''2121040''>Let''s</span> <span m=''2121240''>try</span> <span m=''2121430''>to</span>
  <span m=''2121610''>figure</span> <span m=''2121850''>that</span> <span m=''2122080''>out.</span>
  <span m=''2131960''>The</span> <span m=''2132060''>coins,</span> <span m=''2132490''>of</span>
  <span m=''2132570''>course,</span> <span m=''2132930''>are</span> <span m=''2132980''>mutually</span>
  <span m=''2133320''>independent,</span> <span m=''2133810''>but</span> <span m=''2133820''>what</span>
  <span m=''2133980''>about</span> <span m=''2134270''>these</span> <span m=''2134520''>events?</span>
  <span m=''2136150''>So</span> <span m=''2136560''>let''s</span> <span m=''2137050''>start</span>
  <span m=''2137320''>doing</span> <span m=''2137530''>it.</span> <span m=''2137640''>What''s</span>
  <span m=''2137860''>the</span> <span m=''2137960''>probability</span> <span m=''2140140''>one</span>
  <span m=''2140520''>of</span> <span m=''2140570''>the</span> <span m=''2140720''>events</span>
  <span m=''2141110''>occurring?</span> <span m=''2144510''>Well,</span> <span m=''2146340''>you</span>
  <span m=''2146470''>got</span> <span m=''2146650''>to</span> <span m=''2146690''>get</span>
  <span m=''2147330''>the</span> <span m=''2147440''>two</span> <span m=''2147660''>coins</span>
  <span m=''2148100''>at</span> <span m=''2148170''>hand</span> <span m=''2148570''>to</span>
  <span m=''2148650''>match,</span> <span m=''2149840''>so</span> <span m=''2149990''>that''s</span>
  <span m=''2150240''>the</span> <span m=''2150330''>probability</span> <span m=''2150930''>of</span>
  <span m=''2151000''>a</span> <span m=''2151040''>heads,</span> <span m=''2151370''>heads</span>
  <span m=''2153160''>plus</span> <span m=''2153425''>the</span> <span m=''2153690''>probability</span>
  <span m=''2154130''>of</span> <span m=''2154180''>a</span> <span m=''2154260''>tails,</span>
  <span m=''2154660''>tails.</span> <span m=''2156710''>That''s</span> <span m=''2157310''>1/4</span>
  <span m=''2158220''>plus</span> <span m=''2158670''>1/4</span> <span m=''2159910''>equals</span>
  <span m=''2160260''>1/2.</span> </p><p><span m=''2165920''>Now,</span> <span m=''2166220''>the</span>
  <span m=''2166330''>probability</span> <span m=''2168920''>of</span> <span m=''2169250''>Ai</span>
  <span m=''2169830''>and</span> <span m=''2170340''>Aj,</span> <span m=''2171480''>i</span>
  <span m=''2171670''>and</span> <span m=''2171816''>j</span> <span m=''2171963''>are</span>
  <span m=''2172110''>1</span> <span m=''2172350''>to</span> <span m=''2172430''>3,</span>
  <span m=''2173280''>they''re</span> <span m=''2173570''>different,</span> <span
  m=''2175780''>but</span> <span m=''2175930''>what</span> <span m=''2176090''>is</span>
  <span m=''2176500''>a</span> <span m=''2176560''>way</span> <span m=''2176740''>of</span>
  <span m=''2176820''>characterizing</span> <span m=''2177570''>that</span> <span
  m=''2177860''>case?</span> <span m=''2180120''>Say</span> <span m=''2180510''>event</span>
  <span m=''2180690''>1</span> <span m=''2180920''>occurred</span> <span m=''2181105''>and</span>
  <span m=''2181290''>event</span> <span m=''2181450''>2</span> <span m=''2181610''>occurred,</span>
  <span m=''2182920''>how</span> <span m=''2183130''>would</span> <span m=''2183190''>I</span>
  <span m=''2183250''>characterize</span> <span m=''2183510''>that?</span> <span m=''2188330''>Yeah.</span>
  </p><p><span m=''2188610''>AUDIENCE: All</span> <span m=''2188703''>the</span> <span
  m=''2188796''>same.</span> </p><p><span m=''2189782''>TOM LEIGHTON:</span> <span
  m=''2190230''>All</span> <span m=''2190700''>of</span> <span m=''2190806''>them.</span>
  <span m=''2190913''>Yeah.</span> <span m=''2191190''>All</span> <span m=''2191510''>of</span>
  <span m=''2191650''>the</span> <span m=''2191670''>coins</span> <span m=''2192010''>are</span>
  <span m=''2192140''>the</span> <span m=''2192220''>same</span> <span m=''2193300''>because</span>
  <span m=''2193470''>if</span> <span m=''2193560''>A1</span> <span m=''2193730''>and</span>
  <span m=''2194170''>A2</span> <span m=''2194340''>occur,</span> <span m=''2194410''>I</span>
  <span m=''2194650''>know</span> <span m=''2194810''>1</span> <span m=''2195080''>matches</span>
  <span m=''2195450''>2</span> <span m=''2195720''>a</span> <span m=''2195800''>2</span>
  <span m=''2195970''>matches</span> <span m=''2196340''>3.</span> <span m=''2197290''>If</span>
  <span m=''2197480''>A1</span> <span m=''2197950''>and</span> <span m=''2198060''>A3</span>
  <span m=''2198430''>happen,</span> <span m=''2198940''>1</span> <span m=''2199260''>matches</span>
  <span m=''2199730''>2</span> <span m=''2199920''>and</span> <span m=''2199990''>1</span>
  <span m=''2200230''>matches</span> <span m=''2200600''>3,</span> <span m=''2200910''>so</span>
  <span m=''2200965''>they''re</span> <span m=''2201020''>all</span> <span m=''2201140''>the</span>
  <span m=''2201240''>same</span> <span m=''2201890''>and</span> <span m=''2201990''>the</span>
  <span m=''2202070''>same</span> <span m=''2202340''>for</span> <span m=''2202480''>A2</span>
  <span m=''2202900''>and</span> <span m=''2203000''>A3.</span> <span m=''2203830''>If</span>
  <span m=''2203950''>2</span> <span m=''2204140''>matches</span> <span m=''2204480''>3</span>
  <span m=''2204620''>and</span> <span m=''2204760''>3</span> <span m=''2204900''>matches</span>
  <span m=''2205220''>1,</span> <span m=''2205490''>they''re</span> <span m=''2205620''>all</span>
  <span m=''2205800''>the</span> <span m=''2205900''>same.</span> <span m=''2206630''>So</span>
  <span m=''2206800''>this</span> <span m=''2207140''>is</span> <span m=''2207240''>the</span>
  <span m=''2207350''>same</span> <span m=''2207840''>as</span> <span m=''2208060''>saying</span>
  <span m=''2209080''>all</span> <span m=''2209380''>three</span> <span m=''2209600''>coins</span>
  <span m=''2209950''>are</span> <span m=''2210010''>the</span> <span m=''2210080''>same.</span>
  <span m=''2213890''>It</span> <span m=''2214020''>could</span> <span m=''2214120''>all</span>
  <span m=''2214220''>be</span> <span m=''2214350''>heads</span> <span m=''2214730''>or</span>
  <span m=''2214840''>all</span> <span m=''2214950''>be</span> <span m=''2215270''>tails.</span>
  </p><p><span m=''2217160''>And</span> <span m=''2217370''>that''s</span> <span m=''2217610''>an</span>
  <span m=''2217730''>8</span> <span m=''2218650''>plus</span> <span m=''2219050''>8,</span>
  <span m=''2220320''>which</span> <span m=''2220480''>is</span> <span m=''2220580''>1/4</span>
  <span m=''2222290''>and</span> <span m=''2223050''>that</span> <span m=''2223280''>means</span>
  <span m=''2223750''>equals</span> <span m=''2226100''>the</span> <span m=''2226170''>probability</span>
  <span m=''2226660''>of</span> <span m=''2226730''>Ai</span> <span m=''2227900''>times</span>
  <span m=''2228230''>the</span> <span m=''2228310''>probability</span> <span m=''2229040''>of</span>
  <span m=''2229140''>Aj,</span> <span m=''2231520''>which</span> <span m=''2231730''>is</span>
  <span m=''2231780''>what</span> <span m=''2231950''>I</span> <span m=''2232030''>need</span>
  <span m=''2232710''>for</span> <span m=''2233160''>independence.</span> <span m=''2235850''>And</span>
  <span m=''2236040''>then</span> <span m=''2236210''>they</span> <span m=''2236360''>said</span>
  <span m=''2236780''>they''re</span> <span m=''2236900''>done.</span> <span m=''2239070''>They</span>
  <span m=''2239230''>are</span> <span m=''2239440''>independent,</span> <span m=''2241230''>the</span>
  <span m=''2241330''>three</span> <span m=''2241570''>events.</span> <span m=''2243520''>You</span>
  <span m=''2243680''>like</span> <span m=''2243870''>that</span> <span m=''2244030''>answer?</span>
  <span m=''2245640''>What''s</span> <span m=''2245850''>missing?</span> </p><p><span
  m=''2248260''>The</span> <span m=''2248360''>last</span> <span m=''2248700''>case.</span>
  <span m=''2249410''>They</span> <span m=''2249520''>didn''t</span> <span m=''2249750''>check</span>
  <span m=''2250070''>the</span> <span m=''2250160''>last</span> <span m=''2250570''>case</span>
  <span m=''2251770''>and</span> <span m=''2251880''>we</span> <span m=''2251980''>got</span>
  <span m=''2252130''>to</span> <span m=''2252200''>do</span> <span m=''2252360''>that</span>
  <span m=''2252560''>to</span> <span m=''2252640''>have</span> <span m=''2252770''>mutual</span>
  <span m=''2253090''>independence.</span> <span m=''2253680''>So</span> <span m=''2253780''>let''s</span>
  <span m=''2254010''>look</span> <span m=''2254180''>at</span> <span m=''2254260''>that.</span>
  <span m=''2255681''>The</span> <span m=''2256070''>last</span> <span m=''2256410''>case</span>
  <span m=''2256580''>is</span> <span m=''2256750''>probability</span> <span m=''2257190''>A1</span>
  <span m=''2257800''>intersect</span> <span m=''2258350''>A2</span> <span m=''2258940''>intersect</span>
  <span m=''2259600''>A3.</span> <span m=''2262060''>What</span> <span m=''2262260''>is</span>
  <span m=''2262400''>the</span> <span m=''2262490''>probability</span> <span m=''2263240''>that</span>
  <span m=''2264200''>all</span> <span m=''2264470''>three</span> <span m=''2264690''>events</span>
  <span m=''2265000''>occur?</span> </p><p><span m=''2269950''>Well,</span> <span
  m=''2272180''>the</span> <span m=''2272300''>coins</span> <span m=''2272630''>all</span>
  <span m=''2272780''>have</span> <span m=''2272950''>to</span> <span m=''2273040''>match,</span>
  <span m=''2273380''>right?</span> <span m=''2275560''>If</span> <span m=''2275710''>all</span>
  <span m=''2275880''>the</span> <span m=''2275960''>coins</span> <span m=''2276240''>match,</span>
  <span m=''2276620''>all</span> <span m=''2276930''>three</span> <span m=''2277090''>events</span>
  <span m=''2277380''>occur,</span> <span m=''2277730''>right?</span> <span m=''2279830''>And</span>
  <span m=''2279960''>what''s</span> <span m=''2280130''>the</span> <span m=''2280220''>probability</span>
  <span m=''2280750''>all</span> <span m=''2280910''>3</span> <span m=''2281090''>coins</span>
  <span m=''2281420''>match?</span> <span m=''2284260''>1/4,</span> <span m=''2284900''>just</span>
  <span m=''2285190''>the</span> <span m=''2285270''>same</span> <span m=''2285520''>as</span>
  <span m=''2285610''>this,</span> <span m=''2285730''>is</span> <span m=''2285850''>1/4.</span>
  <span m=''2287770''>Does</span> <span m=''2287920''>that</span> <span m=''2288210''>equal</span>
  <span m=''2289380''>probability</span> <span m=''2289990''>of</span> <span m=''2290080''>A1</span>
  <span m=''2290870''>times</span> <span m=''2291520''>the</span> <span m=''2291600''>probability</span>
  <span m=''2292090''>of</span> <span m=''2292180''>A2</span> <span m=''2293070''>times</span>
  <span m=''2293810''>the</span> <span m=''2293890''>probability</span> <span m=''2295280''>of</span>
  <span m=''2295390''>A3?</span> </p><p><span m=''2300090''>What''s</span> <span m=''2300320''>that?</span>
  <span m=''2302120''>1/8.</span> <span m=''2303680''>This</span> <span m=''2303880''>is</span>
  <span m=''2303990''>1/8.</span> <span m=''2305620''>They</span> <span m=''2305780''>are</span>
  <span m=''2305870''>not</span> <span m=''2306090''>equal.</span> <span m=''2309270''>They</span>
  <span m=''2309440''>are</span> <span m=''2309520''>not</span> <span m=''2309970''>mutually</span>
  <span m=''2310360''>independent</span> <span m=''2310830''>events.</span> <span
  m=''2312779''>All</span> <span m=''2313252''>right?</span> <span m=''2317520''>Any</span>
  <span m=''2317660''>questions</span> <span m=''2318040''>about</span> <span m=''2318260''>that?</span>
  <span m=''2319702''>It</span> <span m=''2320090''>might</span> <span m=''2320420''>well</span>
  <span m=''2320670''>be</span> <span m=''2320780''>something</span> <span m=''2321010''>like</span>
  <span m=''2321180''>this</span> <span m=''2321303''>on</span> <span m=''2321426''>the</span>
  <span m=''2321550''>final</span> <span m=''2321840''>this</span> <span m=''2322030''>year,</span>
  <span m=''2322810''>a</span> <span m=''2322960''>good,</span> <span m=''2323030''>decent</span>
  <span m=''2323450''>chance.</span> </p><p><span m=''2324960''>So</span> <span m=''2325150''>if</span>
  <span m=''2325250''>you</span> <span m=''2325540''>start</span> <span m=''2325790''>going</span>
  <span m=''2325940''>along,</span> <span m=''2326280''>looks</span> <span m=''2326590''>like</span>
  <span m=''2326770''>they''re</span> <span m=''2326920''>independent,</span> <span
  m=''2327610''>but</span> <span m=''2327730''>you</span> <span m=''2327820''>forget</span>
  <span m=''2328050''>to</span> <span m=''2328120''>check</span> <span m=''2328360''>that</span>
  <span m=''2328520''>last</span> <span m=''2328770''>case,</span> <span m=''2329130''>which</span>
  <span m=''2329190''>shows</span> <span m=''2329550''>they''re</span> <span m=''2329710''>not</span>
  <span m=''2330190''>mutual</span> <span m=''2330530''>independent.</span> <span
  m=''2332580''>So</span> <span m=''2332700''>you''ve</span> <span m=''2332760''>got</span>
  <span m=''2332880''>to</span> <span m=''2332950''>check</span> <span m=''2333290''>for</span>
  <span m=''2333450''>all</span> <span m=''2333630''>pairs</span> <span m=''2334240''>and</span>
  <span m=''2334610''>all</span> <span m=''2334890''>subsets</span> <span m=''2335410''>of</span>
  <span m=''2335490''>events</span> <span m=''2336320''>for</span> <span m=''2336440''>mutual</span>
  <span m=''2336790''>independence.</span> <span m=''2340040''>Any</span> <span m=''2340870''>questions</span>
  <span m=''2341300''>about</span> <span m=''2341540''>that?</span> </p><p><span m=''2346370''>Now,</span>
  <span m=''2346930''>this</span> <span m=''2347170''>is</span> <span m=''2347300''>actually</span>
  <span m=''2347730''>an</span> <span m=''2347820''>interesting</span> <span m=''2348250''>example</span>
  <span m=''2349960''>because</span> <span m=''2350450''>in</span> <span m=''2350560''>this</span>
  <span m=''2350800''>case,</span> <span m=''2352830''>all</span> <span m=''2353200''>pairs</span>
  <span m=''2353840''>were</span> <span m=''2354000''>independent</span> <span m=''2354690''>and</span>
  <span m=''2354860''>when</span> <span m=''2354960''>that</span> <span m=''2355160''>happens,</span>
  <span m=''2356290''>we</span> <span m=''2356560''>give</span> <span m=''2356720''>that</span>
  <span m=''2356870''>a</span> <span m=''2356920''>special</span> <span m=''2357340''>name</span>
  <span m=''2358490''>and</span> <span m=''2358650''>it''s</span> <span m=''2358800''>called</span>
  <span m=''2359240''>pairwise</span> <span m=''2360100''>independence,</span> <span
  m=''2360820''>not</span> <span m=''2361190''>too</span> <span m=''2361340''>surprising.</span>
  <span m=''2362415''>And</span> <span m=''2362880''>that</span> <span m=''2363030''>can</span>
  <span m=''2363160''>be</span> <span m=''2363260''>useful</span> <span m=''2365910''>because</span>
  <span m=''2366060''>there''s</span> <span m=''2366180''>many</span> <span m=''2366430''>times</span>
  <span m=''2366790''>where</span> <span m=''2366890''>you</span> <span m=''2366990''>do</span>
  <span m=''2367190''>get</span> <span m=''2367370''>pairwise</span> <span m=''2367840''>independence,</span>
  <span m=''2368340''>but</span> <span m=''2368470''>not</span> <span m=''2368750''>mutual</span>
  <span m=''2369130''>independence.</span> <span m=''2370840''>So</span> <span m=''2371140''>let</span>
  <span m=''2371182''>me</span> <span m=''2371225''>give</span> <span m=''2371267''>you</span>
  <span m=''2371310''>that</span> <span m=''2371520''>definition.</span> </p><p><span
  m=''2378760''>So</span> <span m=''2379010''>a</span> <span m=''2379070''>collection</span>
  <span m=''2379440''>of</span> <span m=''2379510''>events</span> <span m=''2381360''>A1</span>
  <span m=''2381850''>through</span> <span m=''2382010''>An</span> <span m=''2384460''>are</span>
  <span m=''2384820''>said</span> <span m=''2385020''>to</span> <span m=''2385090''>be</span>
  <span m=''2385310''>pairwise</span> <span m=''2389610''>independent</span> <span
  m=''2395610''>if</span> <span m=''2396690''>for</span> <span m=''2396950''>all</span>
  <span m=''2397380''>i</span> <span m=''2398100''>and</span> <span m=''2398290''>j,</span>
  <span m=''2399830''>where</span> <span m=''2400460''>i</span> <span m=''2400760''>doesn''t</span>
  <span m=''2401120''>equal</span> <span m=''2401480''>j,</span> <span m=''2404980''>Ai</span>
  <span m=''2405960''>and</span> <span m=''2406240''>Aj</span> <span m=''2407860''>are</span>
  <span m=''2408070''>independent.</span> <span m=''2414230''>Now,</span> <span m=''2414430''>as</span>
  <span m=''2414510''>we</span> <span m=''2414610''>saw</span> <span m=''2415010''>in</span>
  <span m=''2415080''>this</span> <span m=''2415280''>example,</span> <span m=''2415840''>in</span>
  <span m=''2415900''>this</span> <span m=''2416060''>example,</span> <span m=''2417620''>it</span>
  <span m=''2417780''>was</span> <span m=''2418120''>pairwise</span> <span m=''2418700''>independence</span>
  <span m=''2420110''>because</span> <span m=''2421040''>the</span> <span m=''2421120''>probability</span>
  <span m=''2421660''>of</span> <span m=''2421730''>Ai</span> <span m=''2422130''>and</span>
  <span m=''2422440''>Aj</span> <span m=''2423670''>equaled</span> <span m=''2424040''>the</span>
  <span m=''2424120''>probability</span> <span m=''2424680''>of</span> <span m=''2424740''>Ai</span>
  <span m=''2425080''>times</span> <span m=''2425490''>the</span> <span m=''2425560''>probably</span>
  <span m=''2425940''>of</span> <span m=''2426030''>Aj.</span> <span m=''2426460''>For</span>
  <span m=''2426675''>any</span> <span m=''2426890''>pair,</span> <span m=''2427360''>it</span>
  <span m=''2427430''>was</span> <span m=''2427570''>true.</span> <span m=''2429130''>But</span>
  <span m=''2429310''>it</span> <span m=''2429420''>doesn''t</span> <span m=''2429730''>imply</span>
  <span m=''2430140''>mutual</span> <span m=''2430530''>independence.</span> <span
  m=''2432130''>So</span> <span m=''2432330''>pairwise</span> <span m=''2434270''>does</span>
  <span m=''2434420''>not</span> <span m=''2434830''>imply</span> <span m=''2435720''>mutual.</span>
  <span m=''2438870''>Mutual</span> <span m=''2439340''>would</span> <span m=''2439560''>imply</span>
  <span m=''2439890''>pairwise</span> <span m=''2440570''>because</span> <span m=''2441090''>it''s</span>
  <span m=''2441240''>true</span> <span m=''2441430''>for</span> <span m=''2441620''>every</span>
  <span m=''2441840''>subset</span> <span m=''2443090''>of</span> <span m=''2443230''>events.</span>
  </p><p><span m=''2446610''>All</span> <span m=''2446800''>right.</span> <span m=''2447050''>So</span>
  <span m=''2447150''>let''s</span> <span m=''2447360''>go</span> <span m=''2447470''>back</span>
  <span m=''2447890''>for</span> <span m=''2448210''>OJ</span> <span m=''2450230''>and</span>
  <span m=''2450430''>see</span> <span m=''2450860''>what</span> <span m=''2451210''>would</span>
  <span m=''2451620''>have</span> <span m=''2452030''>happened.</span> <span m=''2453670''>What</span>
  <span m=''2453890''>can</span> <span m=''2454020''>you</span> <span m=''2454160''>say</span>
  <span m=''2454460''>about</span> <span m=''2454680''>the</span> <span m=''2454770''>probability</span>
  <span m=''2455450''>of</span> <span m=''2455530''>a</span> <span m=''2455600''>blood</span>
  <span m=''2455990''>match</span> <span m=''2456390''>for</span> <span m=''2456530''>a</span>
  <span m=''2456600''>random</span> <span m=''2456950''>person</span> <span m=''2458510''>if</span>
  <span m=''2458680''>you</span> <span m=''2459000''>only</span> <span m=''2459420''>knew</span>
  <span m=''2459870''>that</span> <span m=''2460110''>these</span> <span m=''2460420''>factors</span>
  <span m=''2460920''>were</span> <span m=''2461120''>pairwise</span> <span m=''2461950''>independent?</span>
  <span m=''2464910''>Say</span> <span m=''2465340''>you</span> <span m=''2465500''>only</span>
  <span m=''2465850''>knew</span> <span m=''2466040''>that.</span> <span m=''2466530''>You</span>
  <span m=''2466640''>didn''t</span> <span m=''2466860''>know</span> <span m=''2467030''>they</span>
  <span m=''2467100''>were</span> <span m=''2467170''>mutually</span> <span m=''2467580''>independent,</span>
  <span m=''2468140''>but</span> <span m=''2468150''>you</span> <span m=''2468250''>knew</span>
  <span m=''2468540''>they</span> <span m=''2468690''>were</span> <span m=''2468850''>pairwise</span>
  <span m=''2469480''>independent</span> <span m=''2469735''>in</span> <span m=''2469990''>the</span>
  <span m=''2470060''>population.</span> <span m=''2475210''>What''s</span> <span
  m=''2475390''>the</span> <span m=''2475480''>best</span> <span m=''2475780''>you</span>
  <span m=''2475860''>can</span> <span m=''2476030''>say</span> <span m=''2476360''>about</span>
  <span m=''2476490''>the</span> <span m=''2476620''>probability</span> <span m=''2477000''>a</span>
  <span m=''2477130''>random</span> <span m=''2477500''>person</span> <span m=''2477860''>matches</span>
  <span m=''2478260''>that</span> <span m=''2478450''>blood</span> <span m=''2478650''>profile,</span>
  <span m=''2480550''>an</span> <span m=''2480670''>upper</span> <span m=''2480850''>bound</span>
  <span m=''2481130''>on</span> <span m=''2481200''>the</span> <span m=''2481270''>probability?</span>
  <span m=''2483560''>Yeah.</span> </p><p><span m=''2483815''>AUDIENCE:</span> <span
  m=''2484070''>1</span> <span m=''2484423''>in</span> <span m=''2484599''>50.</span>
  </p><p><span m=''2484776''>TOM LEIGHTON:</span> <span m=''2485130''>1</span> <span
  m=''2485615''>in</span> <span m=''2485857''>50.</span> <span m=''2486100''>Yeah.</span>
  <span m=''2487050''>So</span> <span m=''2487210''>what</span> <span m=''2487370''>you</span>
  <span m=''2487470''>can</span> <span m=''2487590''>say</span> <span m=''2487900''>is</span>
  <span m=''2488050''>1</span> <span m=''2488450''>in</span> <span m=''2488650''>50,</span>
  <span m=''2488850''>but</span> <span m=''2489080''>nothing</span> <span m=''2489480''>better.</span>
  <span m=''2490810''>So</span> <span m=''2490950''>let''s</span> <span m=''2491160''>see</span>
  <span m=''2491330''>why</span> <span m=''2491655''>1</span> <span m=''2491980''>in</span>
  <span m=''2492090''>50</span> <span m=''2492470''>works.</span> <span m=''2498490''>So</span>
  <span m=''2499390''>let''s</span> <span m=''2499800''>let</span> <span m=''2500410''>M1</span>
  <span m=''2501000''>be</span> <span m=''2501150''>the</span> <span m=''2501280''>event</span>
  <span m=''2501640''>you</span> <span m=''2501740''>match</span> <span m=''2502130''>here,</span>
  <span m=''2503370''>M2</span> <span m=''2503830''>be</span> <span m=''2503980''>the</span>
  <span m=''2504100''>event</span> <span m=''2504390''>you</span> <span m=''2504470''>match</span>
  <span m=''2504770''>their,</span> <span m=''2504980''>and</span> <span m=''2505160''>M3</span>
  <span m=''2505490''>be</span> <span m=''2505620''>the</span> <span m=''2505740''>event</span>
  <span m=''2506020''>you</span> <span m=''2506100''>match</span> <span m=''2506410''>that.</span>
  <span m=''2508300''>The</span> <span m=''2508390''>probability</span> <span m=''2508950''>you</span>
  <span m=''2509040''>match</span> <span m=''2509390''>all</span> <span m=''2509580''>three</span>
  <span m=''2514770''>is</span> <span m=''2515000''>upper</span> <span m=''2515250''>bounded</span>
  <span m=''2515650''>by</span> <span m=''2515750''>the</span> <span m=''2515860''>probability</span>
  <span m=''2516490''>you</span> <span m=''2516600''>match</span> <span m=''2516930''>the</span>
  <span m=''2517030''>first</span> <span m=''2517340''>two</span> <span m=''2520470''>because</span>
  <span m=''2522490''>matching</span> <span m=''2522900''>all</span> <span m=''2523100''>three</span>
  <span m=''2523360''>is</span> <span m=''2523510''>a</span> <span m=''2523810''>subset</span>
  <span m=''2524650''>of</span> <span m=''2524820''>this.</span> </p><p><span m=''2528220''>Pairwise</span>
  <span m=''2528850''>independence</span> <span m=''2529490''>means</span> <span m=''2530470''>that</span>
  <span m=''2530640''>this</span> <span m=''2530850''>is</span> <span m=''2530960''>true.</span>
  <span m=''2531390''>This</span> <span m=''2531610''>equals</span> <span m=''2532740''>the</span>
  <span m=''2532790''>probability</span> <span m=''2533270''>of</span> <span m=''2533360''>matching</span>
  <span m=''2533690''>the</span> <span m=''2533780''>first</span> <span m=''2534210''>times</span>
  <span m=''2534275''>the</span> <span m=''2534340''>probability</span> <span m=''2534710''>of</span>
  <span m=''2535050''>matching</span> <span m=''2535085''>the</span> <span m=''2535120''>second.</span>
  <span m=''2536760''>The</span> <span m=''2537170''>probability</span> <span m=''2537360''>of</span>
  <span m=''2537550''>matching</span> <span m=''2537850''>the</span> <span m=''2537930''>first</span>
  <span m=''2538260''>is</span> <span m=''2538350''>1/10,</span> <span m=''2539670''>probably</span>
  <span m=''2540030''>of</span> <span m=''2540210''>matching</span> <span m=''2540390''>the</span>
  <span m=''2540470''>second</span> <span m=''2540850''>is</span> <span m=''2540980''>1/5,</span>
  <span m=''2542690''>so</span> <span m=''2542840''>this</span> <span m=''2543050''>is</span>
  <span m=''2543160''>1/50.</span> <span m=''2546700''>And</span> <span m=''2547150''>you</span>
  <span m=''2547290''>picked</span> <span m=''2548260''>the</span> <span m=''2548360''>best</span>
  <span m=''2548690''>two.</span> <span m=''2549880''>You</span> <span m=''2550100''>could</span>
  <span m=''2550290''>have</span> <span m=''2550410''>picked</span> <span m=''2550830''>these</span>
  <span m=''2551120''>two</span> <span m=''2552430''>and</span> <span m=''2552610''>said</span>
  <span m=''2552820''>it</span> <span m=''2552880''>was</span> <span m=''2553240''>at</span>
  <span m=''2553350''>most</span> <span m=''2553670''>1/20</span> <span m=''2554810''>or</span>
  <span m=''2555190''>those</span> <span m=''2555540''>two</span> <span m=''2555690''>and</span>
  <span m=''2555940''>said</span> <span m=''2555966''>it''s</span> <span m=''2555993''>at</span>
  <span m=''2556020''>most</span> <span m=''2556380''>1/40.</span> <span m=''2558070''>But</span>
  <span m=''2558410''>you</span> <span m=''2558580''>were</span> <span m=''2559280''>clever</span>
  <span m=''2559540''>and</span> <span m=''2559800''>said,</span> <span m=''2559990''>OK,</span>
  <span m=''2560270''>I''m</span> <span m=''2560380''>going</span> <span m=''2560480''>to</span>
  <span m=''2560550''>take</span> <span m=''2560800''>these</span> <span m=''2561060''>two</span>
  <span m=''2561760''>and</span> <span m=''2561880''>use</span> <span m=''2562070''>that</span>
  <span m=''2562260''>as</span> <span m=''2562340''>my</span> <span m=''2562470''>upper</span>
  <span m=''2562630''>bound,</span> <span m=''2563030''>which</span> <span m=''2563090''>is</span>
  <span m=''2563170''>1/50.</span> </p><p><span m=''2564590''>And</span> <span m=''2564760''>it</span>
  <span m=''2564880''>might</span> <span m=''2565230''>well</span> <span m=''2565510''>be</span>
  <span m=''2567200''>that</span> <span m=''2567970''>1</span> <span m=''2568365''>in</span>
  <span m=''2568562''>50</span> <span m=''2568760''>people</span> <span m=''2569500''>match</span>
  <span m=''2569910''>all</span> <span m=''2570170''>three.</span> <span m=''2571450''>That</span>
  <span m=''2571630''>can</span> <span m=''2571750''>well</span> <span m=''2571950''>be.</span>
  <span m=''2574010''>Because</span> <span m=''2574410''>maybe</span> <span m=''2575250''>whenever</span>
  <span m=''2575750''>you''re</span> <span m=''2575950''>O</span> <span m=''2576070''>positive,</span>
  <span m=''2576660''>you</span> <span m=''2576750''>have</span> <span m=''2577000''>marker</span>
  <span m=''2577380''>XYZ.</span> <span m=''2577910''>That''s</span> <span m=''2578140''>possible,</span>
  <span m=''2579230''>potentially,</span> <span m=''2580220''>unless</span> <span
  m=''2580920''>we</span> <span m=''2581060''>find</span> <span m=''2581340''>out</span>
  <span m=''2581450''>otherwise.</span> </p><p><span m=''2585830''>What</span> <span
  m=''2586170''>if</span> <span m=''2586290''>I</span> <span m=''2586380''>tell</span>
  <span m=''2586650''>you</span> <span m=''2586960''>can''t</span> <span m=''2587380''>assume</span>
  <span m=''2587720''>any</span> <span m=''2588020''>independence</span> <span m=''2588680''>at</span>
  <span m=''2588740''>all?</span> <span m=''2590180''>What</span> <span m=''2590420''>can</span>
  <span m=''2590530''>you</span> <span m=''2590630''>say</span> <span m=''2590870''>about</span>
  <span m=''2591070''>the</span> <span m=''2591160''>probability</span> <span m=''2591710''>of</span>
  <span m=''2591790''>a</span> <span m=''2591860''>blood</span> <span m=''2592140''>match</span>
  <span m=''2592440''>here</span> <span m=''2592890''>for</span> <span m=''2593020''>a</span>
  <span m=''2593090''>random</span> <span m=''2593380''>person?</span> <span m=''2594650''>Yeah.</span>
  </p><p><span m=''2594900''>AUDIENCE:</span> <span m=''2595400''>1/10.</span> </p><p><span
  m=''2595900''>TOM LEIGHTON: What</span> <span m=''2596020''>is</span> <span m=''2596150''>it?</span>
  </p><p><span m=''2596290''>AUDIENCE:</span> <span m=''2596780''>1/10.</span> </p><p><span
  m=''2597270''>TOM LEIGHTON: 1/10.</span> <span m=''2599500''>Because</span> <span
  m=''2599990''>if</span> <span m=''2600220''>they</span> <span m=''2600340''>match</span>
  <span m=''2600460''>all</span> <span m=''2600720''>three,</span> <span m=''2600975''>they</span>
  <span m=''2601230''>match</span> <span m=''2601500''>this</span> <span m=''2602110''>and</span>
  <span m=''2602210''>that</span> <span m=''2602350''>probability</span> <span m=''2603510''>is</span>
  <span m=''2603650''>1/10,</span> <span m=''2604140''>so</span> <span m=''2604220''>it''s</span>
  <span m=''2604300''>at</span> <span m=''2604380''>most</span> <span m=''2604700''>1/10.</span>
  <span m=''2606510''>And</span> <span m=''2606710''>it</span> <span m=''2606790''>could</span>
  <span m=''2607070''>be</span> <span m=''2607280''>that</span> <span m=''2607380''>everybody</span>
  <span m=''2607760''>who''s</span> <span m=''2607970''>O</span> <span m=''2608570''>is</span>
  <span m=''2608830''>O</span> <span m=''2609210''>positive</span> <span m=''2610120''>and</span>
  <span m=''2610260''>has</span> <span m=''2610570''>XYZ.</span> <span m=''2611810''>So</span>
  <span m=''2611990''>unless</span> <span m=''2612240''>you</span> <span m=''2612350''>have</span>
  <span m=''2612610''>more</span> <span m=''2613580''>information,</span> <span m=''2614770''>that''s</span>
  <span m=''2614980''>the</span> <span m=''2615070''>best</span> <span m=''2615390''>you</span>
  <span m=''2615480''>can</span> <span m=''2615640''>say.</span> <span m=''2615870''>It</span>
  <span m=''2615990''>might</span> <span m=''2616180''>well</span> <span m=''2616360''>be</span>
  <span m=''2616540''>that''s</span> <span m=''2618230''>the</span> <span m=''2618340''>answer.</span>
  <span m=''2621720''>Any</span> <span m=''2621860''>questions</span> <span m=''2623850''>about</span>
  <span m=''2624140''>that?</span> </p><p><span m=''2626120''>So</span> <span m=''2626260''>the</span>
  <span m=''2626390''>assumptions</span> <span m=''2626960''>really</span> <span m=''2627260''>matter.</span>
  <span m=''2627600''>The</span> <span m=''2627690''>more</span> <span m=''2628120''>independence</span>
  <span m=''2628950''>you</span> <span m=''2629070''>assume,</span> <span m=''2630200''>the</span>
  <span m=''2630300''>better</span> <span m=''2630620''>bounds</span> <span m=''2631120''>and</span>
  <span m=''2631200''>the</span> <span m=''2631260''>probability</span> <span m=''2631790''>you</span>
  <span m=''2631910''>get</span> <span m=''2632470''>of</span> <span m=''2632730''>a</span>
  <span m=''2632920''>match.</span> <span m=''2637106''>It''s</span> <span m=''2637580''>a</span>
  <span m=''2637630''>little</span> <span m=''2637830''>bit</span> <span m=''2637930''>unrelated</span>
  <span m=''2638390''>to</span> <span m=''2638460''>this,</span> <span m=''2638660''>but</span>
  <span m=''2638740''>there</span> <span m=''2638850''>was</span> <span m=''2638940''>another</span>
  <span m=''2639530''>mathematics</span> <span m=''2640170''>dispute</span> <span
  m=''2640990''>at</span> <span m=''2641140''>the</span> <span m=''2641370''>OJ</span>
  <span m=''2641600''>trial.</span> <span m=''2643380''>It</span> <span m=''2643530''>turned</span>
  <span m=''2643850''>out</span> <span m=''2644030''>the</span> <span m=''2644110''>that</span>
  <span m=''2644450''>OJ</span> <span m=''2644620''>had</span> <span m=''2644790''>been</span>
  <span m=''2645170''>beating</span> <span m=''2645580''>up</span> <span m=''2645750''>Nicole</span>
  <span m=''2646450''>on</span> <span m=''2646630''>a</span> <span m=''2646690''>fairly</span>
  <span m=''2647010''>regular</span> <span m=''2647350''>basis</span> <span m=''2647750''>and</span>
  <span m=''2647820''>there</span> <span m=''2647895''>were</span> <span m=''2647970''>police</span>
  <span m=''2648320''>records</span> <span m=''2648710''>because</span> <span m=''2648880''>after</span>
  <span m=''2649120''>he''d</span> <span m=''2649250''>beat</span> <span m=''2649480''>her</span>
  <span m=''2649610''>up,</span> <span m=''2649910''>she''d</span> <span m=''2650020''>go</span>
  <span m=''2650270''>in</span> <span m=''2650430''>and</span> <span m=''2651340''>complain</span>
  <span m=''2651730''>to</span> <span m=''2651770''>the</span> <span m=''2651870''>police.</span>
  </p><p><span m=''2653250''>And</span> <span m=''2653470''>the</span> <span m=''2653540''>prosecution</span>
  <span m=''2654490''>wanted</span> <span m=''2654980''>this</span> <span m=''2655190''>evidence</span>
  <span m=''2655860''>admitted</span> <span m=''2656340''>at</span> <span m=''2656430''>the</span>
  <span m=''2656520''>trial</span> <span m=''2658410''>because</span> <span m=''2659420''>if</span>
  <span m=''2659580''>the</span> <span m=''2659660''>guy</span> <span m=''2659805''>is</span>
  <span m=''2659950''>a</span> <span m=''2660030''>wife</span> <span m=''2660420''>beater,</span>
  <span m=''2662410''>it</span> <span m=''2662520''>makes</span> <span m=''2662700''>you</span>
  <span m=''2662800''>think</span> <span m=''2663080''>that</span> <span m=''2663160''>maybe</span>
  <span m=''2663590''>he</span> <span m=''2663750''>killed</span> <span m=''2664050''>her.</span>
  <span m=''2665030''>And</span> <span m=''2665580''>the</span> <span m=''2665700''>defense</span>
  <span m=''2666180''>lawyers</span> <span m=''2666690''>argued</span> <span m=''2667070''>against</span>
  <span m=''2667690''>admitting</span> <span m=''2668220''>that</span> <span m=''2668410''>evidence</span>
  <span m=''2668810''>because</span> <span m=''2669090''>it</span> <span m=''2669150''>wasn''t</span>
  <span m=''2669550''>tied</span> <span m=''2670090''>to</span> <span m=''2670980''>the</span>
  <span m=''2671120''>actual</span> <span m=''2671490''>murder</span> <span m=''2671900''>scene</span>
  <span m=''2672180''>in</span> <span m=''2672270''>any</span> <span m=''2672440''>way</span>
  <span m=''2673070''>and</span> <span m=''2673270''>they</span> <span m=''2673410''>argued</span>
  <span m=''2673760''>it</span> <span m=''2673810''>would</span> <span m=''2673980''>be</span>
  <span m=''2674110''>prejudicial</span> <span m=''2674790''>to</span> <span m=''2674860''>the</span>
  <span m=''2674980''>jury</span> <span m=''2675900''>because,</span> <span m=''2676440''>of</span>
  <span m=''2676530''>course,</span> <span m=''2676940''>if</span> <span m=''2677050''>the</span>
  <span m=''2677140''>jury</span> <span m=''2677500''>hears</span> <span m=''2677780''>that</span>
  <span m=''2677870''>OJ</span> <span m=''2678160''>was</span> <span m=''2678340''>beating</span>
  <span m=''2678660''>her,</span> <span m=''2679380''>they</span> <span m=''2679480''>might</span>
  <span m=''2680030''>be</span> <span m=''2680140''>more</span> <span m=''2680300''>likely</span>
  <span m=''2680570''>to</span> <span m=''2680670''>include</span> <span m=''2681000''>to</span>
  <span m=''2681170''>convict</span> <span m=''2681410''>him</span> <span m=''2681650''>for</span>
  <span m=''2681760''>murdering</span> <span m=''2682200''>her.</span> </p><p><span
  m=''2683690''>Now,</span> <span m=''2684850''>they</span> <span m=''2684960''>got</span>
  <span m=''2685140''>the</span> <span m=''2685210''>math</span> <span m=''2685490''>council</span>
  <span m=''2685890''>again</span> <span m=''2686620''>to</span> <span m=''2686750''>argue</span>
  <span m=''2687180''>that</span> <span m=''2688180''>the</span> <span m=''2688330''>reason</span>
  <span m=''2688680''>you</span> <span m=''2688780''>shouldn''t</span> <span m=''2689250''>admit</span>
  <span m=''2689600''>this</span> <span m=''2690420''>is</span> <span m=''2690630''>because</span>
  <span m=''2692600''>the</span> <span m=''2692860''>probability</span> <span m=''2693860''>that</span>
  <span m=''2694020''>you</span> <span m=''2694160''>kill</span> <span m=''2694470''>your</span>
  <span m=''2694630''>wife,</span> <span m=''2698120''>that''s</span> <span m=''2698400''>K,</span>
  <span m=''2700030''>given</span> <span m=''2700390''>that</span> <span m=''2700440''>you</span>
  <span m=''2700750''>batter</span> <span m=''2701210''>your</span> <span m=''2701360''>wife,</span>
  <span m=''2702350''>that''s</span> <span m=''2702640''>B,</span> <span m=''2703830''>is</span>
  <span m=''2704060''>1</span> <span m=''2704350''>in</span> <span m=''2704480''>2,000.</span>
  <span m=''2707980''>I</span> <span m=''2708090''>would</span> <span m=''2708195''>have</span>
  <span m=''2708300''>guessed</span> <span m=''2708520''>it</span> <span m=''2708610''>was</span>
  <span m=''2708750''>higher,</span> <span m=''2709080''>but</span> <span m=''2710170''>the</span>
  <span m=''2710410''>evidence</span> <span m=''2710800''>did</span> <span m=''2710890''>show</span>
  <span m=''2711180''>that.</span> <span m=''2711680''>And</span> <span m=''2712180''>so</span>
  <span m=''2712400''>they</span> <span m=''2712520''>said,</span> <span m=''2712870''>look,</span>
  <span m=''2713070''>there''s</span> <span m=''2713140''>only</span> <span m=''2713440''>a</span>
  <span m=''2713510''>1</span> <span m=''2713810''>in</span> <span m=''2713950''>2,000</span>
  <span m=''2714680''>chance</span> <span m=''2715250''>that</span> <span m=''2715350''>this</span>
  <span m=''2715590''>evidence</span> <span m=''2716080''>of</span> <span m=''2716410''>wife</span>
  <span m=''2716750''>beating</span> <span m=''2717580''>is</span> <span m=''2717750''>relevant</span>
  <span m=''2719640''>and</span> <span m=''2719920''>therefore,</span> <span m=''2721070''>it</span>
  <span m=''2721200''>should</span> <span m=''2721350''>not</span> <span m=''2721560''>be</span>
  <span m=''2721660''>admitted</span> <span m=''2722080''>because</span> <span m=''2723030''>there''s</span>
  <span m=''2723190''>a</span> <span m=''2723260''>pretty</span> <span m=''2723460''>decent</span>
  <span m=''2723870''>chance</span> <span m=''2724180''>if</span> <span m=''2724250''>the</span>
  <span m=''2724340''>jury</span> <span m=''2724660''>hears</span> <span m=''2724940''>this,</span>
  <span m=''2725170''>they''re</span> <span m=''2725280''>going</span> <span m=''2725390''>to</span>
  <span m=''2725450''>convict</span> <span m=''2725830''>him.</span> </p><p><span
  m=''2727340''>That''s</span> <span m=''2727435''>a</span> <span m=''2727530''>pretty</span>
  <span m=''2727760''>good</span> <span m=''2727900''>argument.</span> <span m=''2729030''>And</span>
  <span m=''2729100''>usually</span> <span m=''2729380''>that</span> <span m=''2729540''>kind</span>
  <span m=''2729690''>of</span> <span m=''2729770''>thing,</span> <span m=''2729940''>you</span>
  <span m=''2730060''>exclude</span> <span m=''2730460''>it.</span> <span m=''2730660''>Yeah.</span>
  </p><p><span m=''2731090''>AUDIENCE: Where</span> <span m=''2731545''>did</span>
  <span m=''2732000''>that</span> <span m=''2732113''>number</span> <span m=''2732227''>come</span>
  <span m=''2732341''>from?</span> </p><p><span m=''2732455''>TOM LEIGHTON:</span>
  <span m=''2732910''>They</span> <span m=''2733140''>got</span> <span m=''2733400''>some</span>
  <span m=''2733630''>study</span> <span m=''2734110''>and</span> <span m=''2734250''>some</span>
  <span m=''2734430''>experts</span> <span m=''2734880''>to</span> <span m=''2734970''>come</span>
  <span m=''2735170''>in</span> <span m=''2735270''>and</span> <span m=''2735400''>say</span>
  <span m=''2735690''>that</span> <span m=''2737770''>for</span> <span m=''2737940''>every</span>
  <span m=''2738100''>2,000</span> <span m=''2738680''>wife</span> <span m=''2738940''>beaters,</span>
  <span m=''2739210''>only</span> <span m=''2739380''>one</span> <span m=''2739610''>of</span>
  <span m=''2739690''>them</span> <span m=''2739770''>actually</span> <span m=''2740070''>kills</span>
  <span m=''2740310''>his</span> <span m=''2740420''>wife.</span> <span m=''2744340''>Now,</span>
  <span m=''2745590''>what</span> <span m=''2745740''>do</span> <span m=''2746000''>you</span>
  <span m=''2746290''>suppose</span> <span m=''2746335''>the</span> <span m=''2746380''>prosecution</span>
  <span m=''2747190''>argued</span> <span m=''2747500''>back?</span> <span m=''2748290''>They</span>
  <span m=''2748410''>actually</span> <span m=''2748760''>argued</span> <span m=''2749050''>back</span>
  <span m=''2749270''>very</span> <span m=''2749470''>effectively,</span> <span m=''2749970''>because</span>
  <span m=''2750080''>that''s</span> <span m=''2750750''>a</span> <span m=''2750860''>tough</span>
  <span m=''2751120''>argument</span> <span m=''2751470''>to</span> <span m=''2751530''>get</span>
  <span m=''2751690''>by.</span> <span m=''2753080''>Yeah.</span> </p><p><span m=''2753530''>AUDIENCE:
  What''s</span> <span m=''2753998''>the</span> <span m=''2754466''>probability</span>
  <span m=''2754700''>that</span> <span m=''2754934''>you</span> <span m=''2755402''>kill</span>
  <span m=''2755870''>your</span> <span m=''2755987''>wife</span> <span m=''2756105''>in</span>
  <span m=''2756222''>the</span> <span m=''2756340''>first</span> <span m=''2756680''>place,</span>
  <span m=''2757380''>that</span> <span m=''2757700''>could</span> <span m=''2758077''>be</span>
  <span m=''2758831''>100</span> <span m=''2759210''>times</span> <span m=''2759560''>larger</span>
  <span m=''2759875''>than</span> <span m=''2760190''>usual.</span> </p><p><span m=''2760545''>TOM
  LEIGHTON:</span> <span m=''2760900''>Well,</span> <span m=''2761040''>that''s</span>
  <span m=''2761270''>a</span> <span m=''2761300''>good</span> <span m=''2761530''>point.</span>
  <span m=''2762900''>So</span> <span m=''2763130''>maybe</span> <span m=''2763530''>the</span>
  <span m=''2763650''>probability</span> <span m=''2764240''>of</span> <span m=''2764340''>killing</span>
  <span m=''2764670''>your</span> <span m=''2764790''>wife</span> <span m=''2765210''>not</span>
  <span m=''2765490''>knowing</span> <span m=''2765840''>B,</span> <span m=''2767688''>I</span>
  <span m=''2768150''>hope</span> <span m=''2768370''>is</span> <span m=''2768510''>pretty</span>
  <span m=''2768720''>small,</span> <span m=''2770870''>probably</span> <span m=''2771370''>that''s</span>
  <span m=''2771680''>very</span> <span m=''2772100''>small,</span> <span m=''2772470''>but</span>
  <span m=''2772760''>I</span> <span m=''2773060''>don''t</span> <span m=''2773210''>know.</span>
  <span m=''2775810''>But</span> <span m=''2775950''>in</span> <span m=''2776010''>any</span>
  <span m=''2776210''>case,</span> <span m=''2776530''>this</span> <span m=''2776700''>thing</span>
  <span m=''2776880''>you''re</span> <span m=''2776990''>going</span> <span m=''2777280''>from,</span>
  <span m=''2777450''>say</span> <span m=''2777630''>it''s</span> <span m=''2777770''>1</span>
  <span m=''2777890''>in</span> <span m=''2778010''>1</span> <span m=''2778130''>million</span>
  <span m=''2778760''>to</span> <span m=''2779200''>1</span> <span m=''2779370''>in</span>
  <span m=''2779470''>2,000,</span> <span m=''2779855''>1</span> <span m=''2780240''>in</span>
  <span m=''2780340''>2,000</span> <span m=''2780650''>is</span> <span m=''2780960''>still</span>
  <span m=''2781220''>too</span> <span m=''2781390''>small</span> <span m=''2782420''>to</span>
  <span m=''2782500''>be</span> <span m=''2782600''>used</span> <span m=''2782805''>as</span>
  <span m=''2783010''>evidence</span> <span m=''2783560''>that</span> <span m=''2783770''>OJ</span>
  <span m=''2784200''>did</span> <span m=''2784642''>it.</span> </p><p><span m=''2785084''>AUDIENCE:</span>
  <span m=''2785526''>Frequency</span> <span m=''2785968''>he</span> <span m=''2786410''>did</span>
  <span m=''2786852''>it.</span> </p><p><span m=''2787294''>TOM LEIGHTON:</span> <span
  m=''2787740''>Frequency,</span> <span m=''2788055''>they</span> <span m=''2788370''>didn''t</span>
  <span m=''2788680''>get</span> <span m=''2788800''>into</span> <span m=''2789010''>that</span>
  <span m=''2789220''>because</span> <span m=''2789450''>I</span> <span m=''2789573''>guess</span>
  <span m=''2789696''>he''d</span> <span m=''2789820''>done</span> <span m=''2790100''>it</span>
  <span m=''2790130''>a</span> <span m=''2790160''>bunch,</span> <span m=''2790570''>but</span>
  <span m=''2791210''>that''s</span> <span m=''2791430''>a</span> <span m=''2791460''>good</span>
  <span m=''2791620''>point.</span> <span m=''2791840''>It</span> <span m=''2791910''>could</span>
  <span m=''2792090''>be</span> <span m=''2792290''>there''s</span> <span m=''2792490''>multiple</span>
  <span m=''2792960''>beatings</span> <span m=''2793390''>is</span> <span m=''2793560''>higher.</span>
  <span m=''2794720''>Maybe</span> <span m=''2794940''>that''s</span> <span m=''2795120''>1</span>
  <span m=''2795310''>in</span> <span m=''2795400''>200</span> <span m=''2795900''>then.</span>
  <span m=''2797500''>In</span> <span m=''2797590''>fact,</span> <span m=''2797770''>that</span>
  <span m=''2797930''>may</span> <span m=''2798045''>be</span> <span m=''2798160''>the</span>
  <span m=''2798280''>case</span> <span m=''2798570''>because</span> <span m=''2798890''>I</span>
  <span m=''2798960''>think</span> <span m=''2799160''>there''s</span> <span m=''2799440''>probably</span>
  <span m=''2799820''>they</span> <span m=''2799930''>say</span> <span m=''2800130''>because</span>
  <span m=''2800330''>if</span> <span m=''2800460''>you</span> <span m=''2800540''>do</span>
  <span m=''2800700''>it</span> <span m=''2800770''>once,</span> <span m=''2800980''>you</span>
  <span m=''2801100''>do</span> <span m=''2801240''>it</span> <span m=''2801300''>multiple</span>
  <span m=''2801590''>times.</span> <span m=''2802870''>So</span> <span m=''2802980''>there''s</span>
  <span m=''2803100''>not</span> <span m=''2803340''>much</span> <span m=''2803540''>more</span>
  <span m=''2803740''>to</span> <span m=''2803810''>be</span> <span m=''2803880''>gaining</span>
  <span m=''2804150''>there.</span> </p><p><span m=''2804940''>There''s</span> <span
  m=''2805080''>a</span> <span m=''2805170''>critical</span> <span m=''2805890''>piece</span>
  <span m=''2806150''>of</span> <span m=''2806200''>information</span> <span m=''2806760''>we''ve</span>
  <span m=''2806950''>left</span> <span m=''2807320''>out</span> <span m=''2807480''>of</span>
  <span m=''2807580''>our</span> <span m=''2807700''>conditional</span> <span m=''2808140''>probabilities</span>
  <span m=''2808790''>here.</span> <span m=''2810276''>In</span> <span m=''2810690''>fact,</span>
  <span m=''2810850''>the</span> <span m=''2811010''>most</span> <span m=''2811160''>glaring</span>
  <span m=''2811580''>piece</span> <span m=''2812150''>of</span> <span m=''2812240''>all</span>
  <span m=''2812940''>of</span> <span m=''2813110''>evidence.</span> <span m=''2814500''>What''s</span>
  <span m=''2814600''>missing</span> <span m=''2814980''>here?</span> <span m=''2815130''>What</span>
  <span m=''2815310''>haven''t</span> <span m=''2815560''>we</span> <span m=''2815700''>factored</span>
  <span m=''2815990''>in?</span> <span m=''2816465''>Yeah.</span> </p><p><span m=''2816940''>AUDIENCE:</span>
  <span m=''2817415''>The</span> <span m=''2817890''>probability</span> <span m=''2818127''>of</span>
  <span m=''2818365''>B.</span> </p><p><span m=''2818840''>TOM LEIGHTON: The</span>
  <span m=''2819380''>probability</span> <span m=''2820180''>of</span> <span m=''2820520''>B,</span>
  <span m=''2820930''>that''s</span> <span m=''2821150''>the</span> <span m=''2821250''>battering.</span>
  <span m=''2823490''>Battering,</span> <span m=''2824120''>I</span> <span m=''2824230''>don''t</span>
  <span m=''2824360''>know</span> <span m=''2824460''>what</span> <span m=''2824580''>it</span>
  <span m=''2824680''>is,</span> <span m=''2824970''>probably</span> <span m=''2825200''>a</span>
  <span m=''2825280''>large</span> <span m=''2825660''>number.</span> <span m=''2827550''>Defense</span>
  <span m=''2827890''>would</span> <span m=''2828000''>argue</span> <span m=''2828310''>it''s</span>
  <span m=''2828580''>large,</span> <span m=''2829000''>I</span> <span m=''2829050''>guess,</span>
  <span m=''2829450''>but</span> <span m=''2829860''>it</span> <span m=''2830100''>shouldn''t</span>
  <span m=''2830260''>matter</span> <span m=''2831560''>that</span> <span m=''2831810''>much.</span>
  </p><p><span m=''2833664''>AUDIENCE:</span> <span m=''2834142''>The</span> <span
  m=''2834620''>probability</span> <span m=''2835098''>that</span> <span m=''2835576''>he</span>
  <span m=''2835815''>actually</span> <span m=''2836054''>beat</span> <span m=''2836532''>her,</span>
  <span m=''2837010''>given</span> <span m=''2837488''>that</span> <span m=''2837966''>she</span>
  <span m=''2838444''>threatened</span> <span m=''2838922''>him?</span> </p><p><span
  m=''2839400''>TOM LEIGHTON:</span> <span m=''2839890''>Well,</span> <span m=''2839990''>there''s</span>
  <span m=''2840040''>that,</span> <span m=''2840130''>but</span> <span m=''2840760''>they</span>
  <span m=''2840850''>have</span> <span m=''2840960''>police--</span> <span m=''2841660''>well,</span>
  <span m=''2841850''>that''s</span> <span m=''2842060''>true.</span> <span m=''2842160''>They</span>
  <span m=''2842280''>didn''t</span> <span m=''2842470''>see</span> <span m=''2842710''>him</span>
  <span m=''2842820''>doing</span> <span m=''2843190''>it,</span> <span m=''2843300''>but</span>
  <span m=''2843380''>let''s</span> <span m=''2843640''>say</span> <span m=''2843740''>that</span>
  <span m=''2843840''>they</span> <span m=''2844150''>had</span> <span m=''2844370''>good</span>
  <span m=''2844560''>evidence</span> <span m=''2844930''>that</span> <span m=''2845040''>he</span>
  <span m=''2845200''>did</span> <span m=''2845400''>it</span> <span m=''2845820''>and</span>
  <span m=''2847020''>defense</span> <span m=''2847470''>wasn''t</span> <span m=''2847770''>arguing</span>
  <span m=''2847910''>that</span> <span m=''2848050''>he</span> <span m=''2848210''>didn''t</span>
  <span m=''2848410''>really</span> <span m=''2848660''>beat</span> <span m=''2849000''>her.</span>
  <span m=''2850750''>The</span> <span m=''2850900''>key</span> <span m=''2851195''>thing</span>
  <span m=''2851490''>we''re</span> <span m=''2851600''>missing</span> <span m=''2851950''>here</span>
  <span m=''2853120''>is</span> <span m=''2853410''>Nicole</span> <span m=''2853690''>wound</span>
  <span m=''2853960''>up</span> <span m=''2854110''>dead.</span> <span m=''2855770''>She</span>
  <span m=''2856000''>was</span> <span m=''2856160''>dead.</span> <span m=''2857780''>And</span>
  <span m=''2857930''>there''s</span> <span m=''2858080''>another</span> <span m=''2858380''>stat</span>
  <span m=''2858760''>here</span> <span m=''2859010''>that</span> <span m=''2859260''>the</span>
  <span m=''2859470''>prosecution</span> <span m=''2860310''>argued.</span> </p><p><span
  m=''2872040''>So</span> <span m=''2872200''>they</span> <span m=''2872390''>argued</span>
  <span m=''2872680''>this</span> <span m=''2872900''>fact.</span> <span m=''2873730''>The</span>
  <span m=''2874230''>probability</span> <span m=''2875070''>the</span> <span m=''2875180''>husband</span>
  <span m=''2875610''>kills</span> <span m=''2875900''>his</span> <span m=''2876020''>wife,</span>
  <span m=''2876570''>given</span> <span m=''2876850''>that</span> <span m=''2877370''>he</span>
  <span m=''2877760''>batters</span> <span m=''2878230''>her</span> <span m=''2878610''>and</span>
  <span m=''2879390''>she</span> <span m=''2879590''>wound</span> <span m=''2879890''>up</span>
  <span m=''2880050''>dead,</span> <span m=''2880980''>that</span> <span m=''2881210''>somebody</span>
  <span m=''2881600''>murder</span> <span m=''2881965''>her</span> <span m=''2883040''>is</span>
  <span m=''2883240''>bigger</span> <span m=''2883550''>than</span> <span m=''2883700''>1/2.</span>
  <span m=''2885100''>So</span> <span m=''2885270''>here</span> <span m=''2885540''>M</span>
  <span m=''2885790''>is</span> <span m=''2885900''>somebody</span> <span m=''2886340''>murdered</span>
  <span m=''2886670''>the</span> <span m=''2886770''>wife.</span> <span m=''2888950''>Here,</span>
  <span m=''2889610''>the</span> <span m=''2889740''>husband</span> <span m=''2890090''>beats</span>
  <span m=''2890560''>her.</span> <span m=''2891030''>Now,</span> <span m=''2891530''>the</span>
  <span m=''2892250''>conditional</span> <span m=''2892570''>probability</span> <span
  m=''2892840''>that</span> <span m=''2892975''>he</span> <span m=''2893110''>killed</span>
  <span m=''2893345''>her</span> <span m=''2893580''>is</span> <span m=''2893710''>bigger</span>
  <span m=''2893940''>than</span> <span m=''2894070''>1/2</span> <span m=''2894710''>and</span>
  <span m=''2894880''>that''s</span> <span m=''2895080''>a</span> <span m=''2895140''>whopper.</span>
  <span m=''2896540''>Now,</span> <span m=''2896790''>it''s</span> <span m=''2896950''>very</span>
  <span m=''2897220''>relevant.</span> </p><p><span m=''2898760''>The</span> <span
  m=''2898830''>probability</span> <span m=''2899065''>he</span> <span m=''2899300''>killed</span>
  <span m=''2899500''>her</span> <span m=''2899700''>just</span> <span m=''2899920''>given</span>
  <span m=''2900120''>that</span> <span m=''2900190''>he</span> <span m=''2900455''>beat</span>
  <span m=''2900543''>her</span> <span m=''2900631''>is</span> <span m=''2900720''>only</span>
  <span m=''2900890''>1</span> <span m=''2901100''>in</span> <span m=''2901210''>2,000,</span>
  <span m=''2902290''>but</span> <span m=''2902470''>if</span> <span m=''2902550''>you</span>
  <span m=''2902650''>add</span> <span m=''2902960''>the</span> <span m=''2903040''>fact,</span>
  <span m=''2903590''>which</span> <span m=''2903810''>is</span> <span m=''2904120''>very</span>
  <span m=''2904350''>relevant</span> <span m=''2904680''>in</span> <span m=''2904740''>this</span>
  <span m=''2904920''>case,</span> <span m=''2905230''>that</span> <span m=''2905290''>the</span>
  <span m=''2905380''>wife</span> <span m=''2905630''>was</span> <span m=''2906000''>murdered,</span>
  <span m=''2907730''>this</span> <span m=''2907950''>is</span> <span m=''2908060''>now</span>
  <span m=''2908870''>very</span> <span m=''2909130''>compelling.</span> <span m=''2910290''>Now,</span>
  <span m=''2910330''>in</span> <span m=''2910430''>fact,</span> <span m=''2910700''>they</span>
  <span m=''2910780''>should</span> <span m=''2910970''>have</span> <span m=''2911160''>really</span>
  <span m=''2911490''>compare</span> <span m=''2911960''>this</span> <span m=''2913160''>to</span>
  <span m=''2914650''>probability</span> <span m=''2916250''>he</span> <span m=''2916350''>kills</span>
  <span m=''2916850''>her</span> <span m=''2917520''>given</span> <span m=''2917790''>that</span>
  <span m=''2918030''>she''s</span> <span m=''2918300''>dead.</span> <span m=''2919840''>And</span>
  <span m=''2920020''>so</span> <span m=''2920120''>that</span> <span m=''2920340''>would</span>
  <span m=''2920720''>determine</span> <span m=''2921110''>now</span> <span m=''2921220''>the</span>
  <span m=''2921330''>relevance</span> <span m=''2921750''>of</span> <span m=''2923070''>the</span>
  <span m=''2923170''>battering,</span> <span m=''2923430''>the</span> <span m=''2924370''>wife</span>
  <span m=''2924630''>beating.</span> <span m=''2925490''>That''s</span> <span m=''2925690''>what</span>
  <span m=''2925810''>they</span> <span m=''2925890''>should</span> <span m=''2926220''>have</span>
  <span m=''2926360''>done,</span> <span m=''2926610''>but</span> <span m=''2926750''>they</span>
  <span m=''2927145''>didn''t.</span> <span m=''2927342''>They</span> <span m=''2927540''>got</span>
  <span m=''2927780''>this</span> <span m=''2927990''>far</span> <span m=''2928480''>and</span>
  <span m=''2928690''>they</span> <span m=''2928810''>had</span> <span m=''2929000''>that</span>
  <span m=''2929220''>and</span> <span m=''2929270''>the</span> <span m=''2929320''>judge</span>
  <span m=''2929590''>said,</span> <span m=''2929845''>I''m</span> <span m=''2930100''>letting</span>
  <span m=''2930270''>it</span> <span m=''2930610''>in.</span> <span m=''2931610''>So</span>
  <span m=''2931770''>it</span> <span m=''2931940''>came</span> <span m=''2932180''>in</span>
  <span m=''2932390''>at</span> <span m=''2932490''>that</span> <span m=''2932670''>point.</span>
  </p><p><span m=''2933450''>But</span> <span m=''2933560''>this</span> <span m=''2933700''>would</span>
  <span m=''2933780''>be</span> <span m=''2933860''>the</span> <span m=''2933970''>right</span>
  <span m=''2934250''>comparison,</span> <span m=''2934780''>I</span> <span m=''2934850''>think.</span>
  <span m=''2935600''>Because</span> <span m=''2935870''>you</span> <span m=''2936000''>look</span>
  <span m=''2936190''>at</span> <span m=''2936250''>the</span> <span m=''2936310''>probability</span>
  <span m=''2936880''>that</span> <span m=''2937010''>you</span> <span m=''2937410''>killed</span>
  <span m=''2937860''>her</span> <span m=''2938980''>given</span> <span m=''2939240''>that</span>
  <span m=''2939330''>she''s</span> <span m=''2939520''>dead,</span> <span m=''2940650''>but</span>
  <span m=''2940780''>now</span> <span m=''2940940''>the</span> <span m=''2941040''>additional</span>
  <span m=''2941360''>information,</span> <span m=''2941790''>the</span> <span m=''2941860''>wife</span>
  <span m=''2942120''>battering,</span> <span m=''2942420''>how</span> <span m=''2942600''>does</span>
  <span m=''2942700''>that</span> <span m=''2942850''>change</span> <span m=''2943200''>the</span>
  <span m=''2943280''>probability?</span> <span m=''2944310''>And</span> <span m=''2944430''>it</span>
  <span m=''2944500''>probably</span> <span m=''2944750''>changes</span> <span m=''2945100''>it</span>
  <span m=''2945310''>materially.</span> <span m=''2948480''>So</span> <span m=''2948590''>it''s</span>
  <span m=''2948690''>all</span> <span m=''2948800''>a</span> <span m=''2948910''>little</span>
  <span m=''2949110''>gory,</span> <span m=''2949970''>but</span> <span m=''2950180''>it''s</span>
  <span m=''2950450''>interesting</span> <span m=''2951150''>to</span> <span m=''2951250''>see</span>
  <span m=''2951420''>how</span> <span m=''2951530''>mathematics</span> <span m=''2952990''>played</span>
  <span m=''2953210''>out</span> <span m=''2953780''>in</span> <span m=''2953850''>this</span>
  <span m=''2953990''>kind</span> <span m=''2954130''>of</span> <span m=''2954210''>environment.</span>
  <span m=''2954790''>Yeah.</span> </p><p><span m=''2955190''>AUDIENCE:</span> <span
  m=''2955643''>Are</span> <span m=''2955733''>we</span> <span m=''2955824''>supposed</span>
  <span m=''2955914''>to</span> <span m=''2956005''>assume</span> <span m=''2956096''>that</span>
  <span m=''2956549''>he</span> <span m=''2957002''>did</span> <span m=''2957455''>kill</span>
  <span m=''2957908''>his</span> <span m=''2958361''>wife?</span> </p><p><span m=''2958814''>TOM
  LEIGHTON:</span> <span m=''2959270''>Yes,</span> <span m=''2959700''>and</span>
  <span m=''2959770''>they</span> <span m=''2959840''>assumed</span> <span m=''2960300''>that,</span>
  <span m=''2960700''>but</span> <span m=''2961100''>when</span> <span m=''2961420''>you</span>
  <span m=''2961520''>decide</span> <span m=''2962130''>whether</span> <span m=''2962330''>or</span>
  <span m=''2962360''>not</span> <span m=''2962540''>to</span> <span m=''2962740''>admit</span>
  <span m=''2962920''>evidence,</span> <span m=''2964170''>if</span> <span m=''2964600''>it''s</span>
  <span m=''2965030''>prejudicial,</span> <span m=''2966570''>you''ve</span> <span
  m=''2966580''>got</span> <span m=''2966690''>to</span> <span m=''2966740''>have</span>
  <span m=''2966840''>a</span> <span m=''2966950''>really</span> <span m=''2967310''>good</span>
  <span m=''2967480''>grounds</span> <span m=''2967850''>to</span> <span m=''2967930''>get</span>
  <span m=''2968100''>it</span> <span m=''2968190''>in.</span> <span m=''2968410''>Like</span>
  <span m=''2968620''>if</span> <span m=''2968780''>the</span> <span m=''2968940''>evidence</span>
  <span m=''2969340''>is</span> <span m=''2969440''>going</span> <span m=''2969550''>to</span>
  <span m=''2969590''>make</span> <span m=''2969830''>the</span> <span m=''2969900''>jury</span>
  <span m=''2970230''>think</span> <span m=''2970450''>he</span> <span m=''2970570''>did</span>
  <span m=''2970790''>it,</span> <span m=''2971710''>then</span> <span m=''2971850''>you</span>
  <span m=''2971970''>really</span> <span m=''2972320''>got</span> <span m=''2972395''>to</span>
  <span m=''2972470''>argue</span> <span m=''2972820''>the</span> <span m=''2972970''>evidence</span>
  <span m=''2973330''>is</span> <span m=''2973450''>relevant</span> <span m=''2974340''>somehow.</span>
  <span m=''2975480''>There''s</span> <span m=''2975830''>material</span> <span m=''2976380''>information</span>
  <span m=''2977560''>and</span> <span m=''2977720''>that''s</span> <span m=''2977890''>what</span>
  <span m=''2977970''>the</span> <span m=''2978050''>fight</span> <span m=''2978310''>was</span>
  <span m=''2978440''>about.</span> <span m=''2978690''>A</span> <span m=''2978750''>1</span>
  <span m=''2978980''>in</span> <span m=''2979070''>2,000</span> <span m=''2979640''>relevance</span>
  <span m=''2980120''>isn''t</span> <span m=''2980410''>going</span> <span m=''2980510''>to</span>
  <span m=''2980620''>cut</span> <span m=''2980915''>it.</span> <span m=''2981740''>1</span>
  <span m=''2982900''>in</span> <span m=''2983030''>2,</span> <span m=''2983930''>that''s</span>
  <span m=''2984180''>probably</span> <span m=''2984430''>pretty</span> <span m=''2984620''>relevant.</span>
  <span m=''2985720''>And</span> <span m=''2985840''>that</span> <span m=''2986050''>will</span>
  <span m=''2986230''>be</span> <span m=''2986400''>the</span> <span m=''2986480''>grounds</span>
  <span m=''2986870''>on</span> <span m=''2986910''>which</span> <span m=''2987110''>the</span>
  <span m=''2987210''>judge</span> <span m=''2987500''>makes</span> <span m=''2987760''>his</span>
  <span m=''2987870''>decision.</span> <span m=''2989460''>But</span> <span m=''2989590''>yeah,</span>
  <span m=''2989760''>you</span> <span m=''2989900''>assume</span> <span m=''2990180''>he</span>
  <span m=''2990310''>didn''t</span> <span m=''2990440''>do</span> <span m=''2990690''>it.</span>
  </p><p><span m=''2996256''>All</span> <span m=''2996640''>right.</span> <span m=''2996860''>Back</span>
  <span m=''2997020''>to</span> <span m=''2997180''>independence.</span> <span m=''2997830''>So</span>
  <span m=''2998440''>the</span> <span m=''2998560''>last</span> <span m=''2998870''>example</span>
  <span m=''2999310''>today</span> <span m=''3000250''>is</span> <span m=''3000700''>derived</span>
  <span m=''3001100''>from</span> <span m=''3001230''>a</span> <span m=''3001280''>famous</span>
  <span m=''3001660''>paradox</span> <span m=''3003410''>and</span> <span m=''3003530''>has</span>
  <span m=''3003690''>several</span> <span m=''3004180''>actually</span> <span m=''3004420''>important</span>
  <span m=''3004860''>applications</span> <span m=''3005470''>in</span> <span m=''3005520''>computer</span>
  <span m=''3005880''>science.</span> <span m=''3006880''>And</span> <span m=''3007060''>this</span>
  <span m=''3007260''>problem</span> <span m=''3007530''>is</span> <span m=''3007650''>known</span>
  <span m=''3007840''>as</span> <span m=''3007950''>the</span> <span m=''3008050''>birthday</span>
  <span m=''3008850''>problem</span> <span m=''3009370''>or</span> <span m=''3009450''>the</span>
  <span m=''3009560''>birthday</span> <span m=''3009960''>paradox.</span> <span m=''3013170''>It''s</span>
  <span m=''3013540''>a</span> <span m=''3013640''>paradox</span> <span m=''3014180''>because</span>
  <span m=''3014590''>it</span> <span m=''3014750''>sort</span> <span m=''3014790''>of</span>
  <span m=''3014830''>has</span> <span m=''3015030''>a</span> <span m=''3015090''>surprising</span>
  <span m=''3015700''>answer.</span> <span m=''3020220''>Probably</span> <span m=''3020520''>a</span>
  <span m=''3020590''>lot</span> <span m=''3020870''>of</span> <span m=''3020940''>you</span>
  <span m=''3021130''>have</span> <span m=''3021230''>seen</span> <span m=''3021440''>this</span>
  <span m=''3021590''>before</span> <span m=''3021980''>in</span> <span m=''3022050''>some</span>
  <span m=''3022350''>form</span> <span m=''3022592''>or</span> <span m=''3022834''>another.</span>
  </p><p><span m=''3037860''>In</span> <span m=''3037970''>the</span> <span m=''3038050''>birthday</span>
  <span m=''3038390''>problem,</span> <span m=''3038900''>there</span> <span m=''3039110''>are</span>
  <span m=''3039530''>N</span> <span m=''3039990''>birthdays</span> <span m=''3045180''>and</span>
  <span m=''3045880''>typically</span> <span m=''3046310''>we''re</span> <span m=''3046420''>going</span>
  <span m=''3046600''>to</span> <span m=''3046640''>look</span> <span m=''3046680''>at</span>
  <span m=''3046720''>the</span> <span m=''3046760''>case</span> <span m=''3047090''>where</span>
  <span m=''3048780''>N</span> <span m=''3049040''>is</span> <span m=''3049210''>365,</span>
  <span m=''3050470''>the</span> <span m=''3050970''>days</span> <span m=''3051280''>of</span>
  <span m=''3051380''>the</span> <span m=''3052220''>year,</span> <span m=''3053290''>and</span>
  <span m=''3053480''>there</span> <span m=''3053620''>is</span> <span m=''3053760''>M</span>
  <span m=''3054020''>people.</span> <span m=''3059330''>And</span> <span m=''3059540''>for</span>
  <span m=''3059650''>example,</span> <span m=''3061250''>know</span> <span m=''3061330''>maybe</span>
  <span m=''3061520''>there''s</span> <span m=''3061650''>100</span> <span m=''3061990''>people</span>
  <span m=''3062280''>here.</span> <span m=''3067070''>And</span> <span m=''3067260''>what</span>
  <span m=''3067350''>we</span> <span m=''3067460''>want</span> <span m=''3067680''>to</span>
  <span m=''3067730''>know</span> <span m=''3069640''>is,</span> <span m=''3069990''>what</span>
  <span m=''3070140''>is</span> <span m=''3070240''>the</span> <span m=''3070340''>probability</span>
  <span m=''3075480''>that</span> <span m=''3075810''>two</span> <span m=''3076000''>or</span>
  <span m=''3076040''>more</span> <span m=''3076270''>people</span> <span m=''3080960''>have</span>
  <span m=''3081270''>the</span> <span m=''3081370''>same</span> <span m=''3081490''>birthday.</span>
  </p><p><span m=''3092760''>For</span> <span m=''3092880''>example,</span> <span
  m=''3093380''>how</span> <span m=''3093430''>many</span> <span m=''3093640''>people</span>
  <span m=''3093980''>think</span> <span m=''3094260''>there''s</span> <span m=''3094450''>at</span>
  <span m=''3094570''>least</span> <span m=''3094870''>a</span> <span m=''3094930''>50%</span>
  <span m=''3095690''>chance</span> <span m=''3096200''>that</span> <span m=''3096610''>a</span>
  <span m=''3096710''>pair</span> <span m=''3097100''>of</span> <span m=''3097180''>you</span>
  <span m=''3097450''>in</span> <span m=''3097530''>the</span> <span m=''3097680''>audience</span>
  <span m=''3098080''>here</span> <span m=''3098360''>have</span> <span m=''3098650''>the</span>
  <span m=''3098720''>same</span> <span m=''3098990''>birthday?</span> <span m=''3101460''>That''s</span>
  <span m=''3102090''>good.</span> <span m=''3102870''>How</span> <span m=''3102980''>many</span>
  <span m=''3103180''>people</span> <span m=''3103510''>think</span> <span m=''3103950''>there''s</span>
  <span m=''3104180''>a</span> <span m=''3104240''>better</span> <span m=''3104980''>than</span>
  <span m=''3105280''>90%</span> <span m=''3106110''>chance?</span> <span m=''3108030''>A</span>
  <span m=''3108300''>few</span> <span m=''3108345''>of</span> <span m=''3108390''>you.</span>
  <span m=''3109382''>All</span> <span m=''3109760''>right.</span> <span m=''3109930''>How</span>
  <span m=''3110070''>many</span> <span m=''3110260''>people</span> <span m=''3110550''>think</span>
  <span m=''3110720''>there''s</span> <span m=''3110860''>a</span> <span m=''3110920''>better</span>
  <span m=''3111270''>than</span> <span m=''3111420''>a</span> <span m=''3111620''>99%</span>
  <span m=''3112810''>chance</span> <span m=''3113410''>that</span> <span m=''3113780''>there''s</span>
  <span m=''3113930''>a</span> <span m=''3113990''>pair</span> <span m=''3114300''>of</span>
  <span m=''3114350''>matching</span> <span m=''3114680''>birthdays?</span> <span
  m=''3115700''>A</span> <span m=''3115780''>couple</span> <span m=''3116110''>left.</span>
  </p><p><span m=''3116950''>How</span> <span m=''3117120''>many</span> <span m=''3117330''>think</span>
  <span m=''3117520''>it''s</span> <span m=''3117680''>better</span> <span m=''3117890''>than</span>
  <span m=''3118030''>a</span> <span m=''3118100''>99.9%</span> <span m=''3120060''>chance?</span>
  <span m=''3121060''>We''ve</span> <span m=''3121310''>got</span> <span m=''3121560''>one,</span>
  <span m=''3122050''>two.</span> <span m=''3122440''>You</span> <span m=''3122570''>guys</span>
  <span m=''3122770''>are</span> <span m=''3122800''>going</span> <span m=''3122830''>to</span>
  <span m=''3122860''>be</span> <span m=''3122950''>stubborn.</span> <span m=''3123390''>Another</span>
  <span m=''3123630''>one.</span> <span m=''3123990''>All</span> <span m=''3124330''>right.</span>
  <span m=''3124500''>How</span> <span m=''3124630''>many</span> <span m=''3124780''>people</span>
  <span m=''3125060''>think</span> <span m=''3125360''>it''s</span> <span m=''3125600''>more</span>
  <span m=''3125830''>than</span> <span m=''3126010''>99.999%</span> <span m=''3129580''>chance?</span>
  <span m=''3131770''>Actually</span> <span m=''3132120''>it''s</span> <span m=''3132430''>six</span>
  <span m=''3132885''>9''s.</span> <span m=''3133340''>It''s</span> <span m=''3133900''>incredible.</span>
  <span m=''3135440''>It</span> <span m=''3135560''>is</span> <span m=''3135700''>a</span>
  <span m=''3135750''>virtual</span> <span m=''3136190''>certainty.</span> </p><p><span
  m=''3138120''>So</span> <span m=''3138760''>let''s</span> <span m=''3139050''>see.</span>
  <span m=''3139200''>In</span> <span m=''3139290''>fact,</span> <span m=''3139880''>the</span>
  <span m=''3139970''>chance</span> <span m=''3140390''>that</span> <span m=''3140520''>you''re</span>
  <span m=''3140710''>all</span> <span m=''3140920''>different</span> <span m=''3142440''>is</span>
  <span m=''3142640''>about</span> <span m=''3142930''>1</span> <span m=''3143170''>in</span>
  <span m=''3143280''>3</span> <span m=''3143610''>million</span> <span m=''3144970''>chance</span>
  <span m=''3145380''>that</span> <span m=''3145495''>you''re</span> <span m=''3145610''>all</span>
  <span m=''3145820''>different.</span> <span m=''3147290''>And</span> <span m=''3147420''>we''re</span>
  <span m=''3147550''>going</span> <span m=''3147650''>to</span> <span m=''3148020''>see</span>
  <span m=''3148270''>why</span> <span m=''3148490''>that''s</span> <span m=''3148990''>true</span>
  <span m=''3149300''>here.</span> <span m=''3150810''>But</span> <span m=''3151070''>to</span>
  <span m=''3151170''>do</span> <span m=''3151420''>that,</span> <span m=''3151890''>we''re</span>
  <span m=''3152030''>going</span> <span m=''3152120''>to</span> <span m=''3152190''>need</span>
  <span m=''3152460''>to</span> <span m=''3152540''>make</span> <span m=''3153410''>two</span>
  <span m=''3153910''>important</span> <span m=''3154440''>assumptions.</span> <span
  m=''3156720''>Any</span> <span m=''3156940''>ideas</span> <span m=''3157440''>about</span>
  <span m=''3157870''>what</span> <span m=''3158020''>assumptions</span> <span m=''3158490''>you''re</span>
  <span m=''3158550''>going</span> <span m=''3158650''>to</span> <span m=''3158690''>need?</span>
  <span m=''3159980''>Yeah.</span> </p><p><span m=''3160350''>AUDIENCE: Birthdays</span>
  <span m=''3160805''>are</span> <span m=''3161260''>uniformly</span> <span m=''3161715''>distributed.</span>
  </p><p><span m=''3162170''>TOM LEIGHTON: Birthdays</span> <span m=''3162630''>are</span>
  <span m=''3162670''>uniformly</span> <span m=''3163260''>distributed.</span> <span
  m=''3163585''>Any</span> <span m=''3163910''>other</span> <span m=''3164346''>ideas?</span>
  <span m=''3164782''>Yes.</span> </p><p><span m=''3165218''>AUDIENCE: He</span> <span
  m=''3165654''>stole</span> <span m=''3166090''>my</span> <span m=''3166310''>answer.</span>
  </p><p><span m=''3166530''>TOM LEIGHTON: Oh,</span> <span m=''3166810''>he</span>
  <span m=''3166896''>stole</span> <span m=''3166983''>yours.</span> <span m=''3167870''>What</span>
  <span m=''3168195''>else</span> <span m=''3168260''>are</span> <span m=''3168325''>you</span>
  <span m=''3168390''>going</span> <span m=''3168455''>to</span> <span m=''3168520''>need</span>
  <span m=''3168650''>to</span> <span m=''3168780''>assume?</span> <span m=''3170724''>Yeah.</span>
  </p><p><span m=''3171700''>AUDIENCE:</span> <span m=''3172190''>All</span> <span
  m=''3172360''>birthdays</span> <span m=''3172960''>are</span> <span m=''3173780''>independent</span>
  <span m=''3174190''>of</span> <span m=''3174280''>each</span> <span m=''3174410''>other.</span>
  </p><p><span m=''3174720''>TOM LEIGHTON: Yeah.</span> <span m=''3175110''>Mutually</span>
  <span m=''3175650''>independent.</span> <span m=''3176410''>We''re</span> <span
  m=''3176530''>going</span> <span m=''3176630''>to</span> <span m=''3176680''>need</span>
  <span m=''3176820''>that</span> <span m=''3177070''>as</span> <span m=''3177190''>well.</span>
  <span m=''3178380''>Now,</span> <span m=''3178880''>in</span> <span m=''3179000''>actuality,</span>
  <span m=''3179640''>neither</span> <span m=''3180580''>is</span> <span m=''3180760''>true</span>
  <span m=''3181680''>in</span> <span m=''3181830''>reality.</span> <span m=''3183020''>It''s</span>
  <span m=''3183220''>well</span> <span m=''3183550''>known</span> <span m=''3183900''>that</span>
  <span m=''3183980''>birthdays</span> <span m=''3184610''>tend</span> <span m=''3184870''>to</span>
  <span m=''3184960''>follow</span> <span m=''3185520''>seasonal</span> <span m=''3186250''>patterns</span>
  <span m=''3187320''>and</span> <span m=''3187550''>they''re</span> <span m=''3187700''>related</span>
  <span m=''3188260''>to</span> <span m=''3188360''>major</span> <span m=''3188780''>events.</span>
  </p><p><span m=''3190070''>Now,</span> <span m=''3190670''>do</span> <span m=''3190880''>you</span>
  <span m=''3191090''>all</span> <span m=''3191210''>remember</span> <span m=''3191610''>the</span>
  <span m=''3191730''>big</span> <span m=''3192240''>blackout</span> <span m=''3192750''>that</span>
  <span m=''3192820''>hit</span> <span m=''3192980''>the</span> <span m=''3193060''>Northeast</span>
  <span m=''3193590''>several</span> <span m=''3193940''>years</span> <span m=''3194160''>ago?</span>
  <span m=''3194830''>Do</span> <span m=''3195190''>you</span> <span m=''3195550''>remember</span>
  <span m=''3195790''>that?</span> <span m=''3196710''>Well,</span> <span m=''3196900''>it</span>
  <span m=''3197000''>turns</span> <span m=''3197310''>out,</span> <span m=''3197650''>this</span>
  <span m=''3197860''>is</span> <span m=''3198120''>a</span> <span m=''3198230''>true</span>
  <span m=''3198470''>fact,</span> <span m=''3198660''>there</span> <span m=''3198850''>were</span>
  <span m=''3198960''>a</span> <span m=''3199010''>lot</span> <span m=''3199190''>of</span>
  <span m=''3199280''>babies</span> <span m=''3199700''>born</span> <span m=''3200000''>nine</span>
  <span m=''3200230''>months</span> <span m=''3200480''>later.</span> <span m=''3201850''>In</span>
  <span m=''3202140''>fact,</span> <span m=''3202580''>they</span> <span m=''3202690''>had</span>
  <span m=''3202850''>a</span> <span m=''3202960''>name.</span> <span m=''3203020''>They''re</span>
  <span m=''3203140''>called</span> <span m=''3203320''>blackout</span> <span m=''3203810''>babies.</span>
  <span m=''3204730''>If</span> <span m=''3204880''>you</span> <span m=''3205000''>were</span>
  <span m=''3205080''>born</span> <span m=''3205570''>in</span> <span m=''3206020''>that</span>
  <span m=''3206240''>period</span> <span m=''3206520''>in</span> <span m=''3206600''>the</span>
  <span m=''3206670''>Northeast</span> <span m=''3207700''>and</span> <span m=''3207810''>there''s</span>
  <span m=''3207950''>all</span> <span m=''3208140''>these</span> <span m=''3208350''>news</span>
  <span m=''3208720''>stories</span> <span m=''3209190''>about</span> <span m=''3209550''>the</span>
  <span m=''3209640''>life</span> <span m=''3209930''>of</span> <span m=''3210030''>the</span>
  <span m=''3210100''>blackout</span> <span m=''3210560''>babies.</span> </p><p><span
  m=''3211770''>And</span> <span m=''3211920''>the</span> <span m=''3212000''>same</span>
  <span m=''3212240''>thing</span> <span m=''3212400''>happens</span> <span m=''3212810''>after</span>
  <span m=''3213060''>cold</span> <span m=''3213430''>snaps</span> <span m=''3213840''>in</span>
  <span m=''3213890''>the</span> <span m=''3213980''>winter</span> <span m=''3214370''>and</span>
  <span m=''3214760''>you</span> <span m=''3214840''>get</span> <span m=''3214960''>a</span>
  <span m=''3215000''>blizzard</span> <span m=''3215400''>or</span> <span m=''3215440''>this</span>
  <span m=''3215590''>kind</span> <span m=''3215740''>of</span> <span m=''3215820''>a</span>
  <span m=''3215880''>thing.</span> <span m=''3216860''>Nine</span> <span m=''3217100''>months</span>
  <span m=''3217340''>later,</span> <span m=''3218160''>you</span> <span m=''3218260''>get</span>
  <span m=''3218450''>babies.</span> <span m=''3219150''>In</span> <span m=''3219250''>fact,</span>
  <span m=''3220620''>I</span> <span m=''3220800''>had</span> <span m=''3220930''>a</span>
  <span m=''3220990''>personal</span> <span m=''3221370''>experience</span> <span
  m=''3221950''>with</span> <span m=''3222090''>this.</span> <span m=''3224040''>Well,</span>
  <span m=''3226740''>my</span> <span m=''3226880''>son</span> <span m=''3227280''>was</span>
  <span m=''3227470''>born</span> <span m=''3228330''>on</span> <span m=''3228460''>October</span>
  <span m=''3229230''>18,</span> <span m=''3229990''>1996.</span> <span m=''3231090''>And</span>
  <span m=''3231280''>on</span> <span m=''3231440''>the</span> <span m=''3231540''>day</span>
  <span m=''3231880''>he</span> <span m=''3232010''>was</span> <span m=''3232180''>born,</span>
  <span m=''3232470''>we''re</span> <span m=''3232560''>going</span> <span m=''3232780''>to</span>
  <span m=''3232820''>the</span> <span m=''3232920''>hospital</span> <span m=''3234100''>and</span>
  <span m=''3234420''>it</span> <span m=''3234540''>was</span> <span m=''3234740''>a</span>
  <span m=''3234810''>zoo.</span> </p><p><span m=''3235720''>The</span> <span m=''3235820''>maternity</span>
  <span m=''3236260''>ward</span> <span m=''3236620''>was</span> <span m=''3236770''>totally</span>
  <span m=''3237260''>full.</span> <span m=''3238190''>We</span> <span m=''3238500''>had</span>
  <span m=''3238720''>to</span> <span m=''3238780''>go</span> <span m=''3239120''>at</span>
  <span m=''3239210''>some</span> <span m=''3239370''>other</span> <span m=''3239530''>wing</span>
  <span m=''3239720''>of</span> <span m=''3239780''>the</span> <span m=''3239840''>hospital.</span>
  <span m=''3241050''>And</span> <span m=''3242230''>babies</span> <span m=''3242630''>were</span>
  <span m=''3242740''>popping</span> <span m=''3243140''>out</span> <span m=''3243290''>all</span>
  <span m=''3243470''>over</span> <span m=''3243590''>the</span> <span m=''3243690''>place.</span>
  <span m=''3245300''>And</span> <span m=''3245480''>I</span> <span m=''3245550''>asked,</span>
  <span m=''3245810''>what</span> <span m=''3246140''>is</span> <span m=''3246330''>going</span>
  <span m=''3246620''>on?</span> <span m=''3247040''>Why</span> <span m=''3247570''>don''t</span>
  <span m=''3247730''>you</span> <span m=''3247800''>have</span> <span m=''3247890''>enough</span>
  <span m=''3248070''>room</span> <span m=''3248920''>for</span> <span m=''3249120''>all</span>
  <span m=''3249330''>the</span> <span m=''3249390''>mothers</span> <span m=''3249750''>here?</span>
  </p><p><span m=''3250540''>And</span> <span m=''3250650''>they</span> <span m=''3250740''>said,</span>
  <span m=''3250950''>oh,</span> <span m=''3251120''>it''s</span> <span m=''3251230''>all</span>
  <span m=''3251380''>the</span> <span m=''3251460''>blizzard</span> <span m=''3251830''>babies.</span>
  <span m=''3252520''>And</span> <span m=''3252790''>I</span> <span m=''3252930''>go,</span>
  <span m=''3253050''>what?</span> <span m=''3253790''>And</span> <span m=''3253930''>they</span>
  <span m=''3253990''>go,</span> <span m=''3254190''>well,</span> <span m=''3254390''>remember</span>
  <span m=''3254650''>the</span> <span m=''3254750''>blizzard</span> <span m=''3255100''>of</span>
  <span m=''3255170''>''96?</span> <span m=''3256100''>It''s</span> <span m=''3256440''>like,</span>
  <span m=''3256630''>oh</span> <span m=''3257113''>yeah.</span> <span m=''3258562''>I</span>
  <span m=''3259045''>remember.</span> <span m=''3259528''>Yeah.</span> <span m=''3260980''>It</span>
  <span m=''3261455''>was</span> <span m=''3261930''>nine</span> <span m=''3262230''>months</span>
  <span m=''3262520''>prior</span> <span m=''3263080''>is</span> <span m=''3263220''>the</span>
  <span m=''3263310''>big</span> <span m=''3263500''>blizzard</span> <span m=''3263930''>and</span>
  <span m=''3264050''>so</span> <span m=''3264210''>it''s</span> <span m=''3264330''>all</span>
  <span m=''3264560''>the</span> <span m=''3264650''>blizzard</span> <span m=''3265070''>babies</span>
  <span m=''3265370''>coming.</span> </p><p><span m=''3268000''>So</span> <span m=''3269260''>they''re</span>
  <span m=''3269410''>not</span> <span m=''3269740''>uniform.</span> <span m=''3270310''>They''re</span>
  <span m=''3270450''>all</span> <span m=''3270780''>different</span> <span m=''3271050''>probabilities</span>
  <span m=''3271690''>here,</span> <span m=''3271830''>but</span> <span m=''3271980''>we''re</span>
  <span m=''3272170''>going</span> <span m=''3272260''>to</span> <span m=''3272350''>assume</span>
  <span m=''3273180''>they''re</span> <span m=''3273340''>equally</span> <span m=''3273650''>likely.</span>
  </p><p><span m=''3276570''>Now,</span> <span m=''3278120''>independence</span> <span
  m=''3278860''>is</span> <span m=''3279020''>also</span> <span m=''3279510''>not</span>
  <span m=''3279790''>true,</span> <span m=''3280660''>in</span> <span m=''3280830''>general.</span>
  <span m=''3281920''>What''s</span> <span m=''3282300''>one</span> <span m=''3282620''>way</span>
  <span m=''3283270''>that</span> <span m=''3283390''>birthdays</span> <span m=''3283820''>might</span>
  <span m=''3284210''>not</span> <span m=''3284510''>be</span> <span m=''3284770''>independent?</span>
  <span m=''3287210''>What</span> <span m=''3287380''>is</span> <span m=''3287520''>it?</span>
  </p><p><span m=''3287935''>AUDIENCE: Twins.</span> </p><p><span m=''3288350''>TOM
  LEIGHTON: Twins.</span> <span m=''3289540''>So</span> <span m=''3289655''>if</span>
  <span m=''3289770''>they''re</span> <span m=''3289920''>twins,</span> <span m=''3290300''>they</span>
  <span m=''3290615''>have</span> <span m=''3290930''>the</span> <span m=''3291020''>same</span>
  <span m=''3291260''>birthday.</span> <span m=''3292530''>Now,</span> <span m=''3292640''>there''s</span>
  <span m=''3292840''>other</span> <span m=''3293050''>ways.</span> <span m=''3293500''>In</span>
  <span m=''3293610''>fact,</span> <span m=''3294570''>my</span> <span m=''3295190''>only</span>
  <span m=''3295510''>sibling,</span> <span m=''3295900''>my</span> <span m=''3296030''>brother,</span>
  <span m=''3296990''>has</span> <span m=''3297260''>the</span> <span m=''3297370''>same</span>
  <span m=''3297770''>birthday</span> <span m=''3298150''>I</span> <span m=''3298300''>do,</span>
  <span m=''3299130''>but</span> <span m=''3299260''>I''m</span> <span m=''3299430''>two</span>
  <span m=''3299690''>years</span> <span m=''3300060''>older,</span> <span m=''3300880''>so</span>
  <span m=''3301030''>we</span> <span m=''3301160''>weren''t</span> <span m=''3301600''>twins.</span>
  <span m=''3302680''>Now,</span> <span m=''3302790''>you</span> <span m=''3302910''>say,</span>
  <span m=''3303700''>what</span> <span m=''3303890''>are</span> <span m=''3303920''>the</span>
  <span m=''3304100''>odds</span> <span m=''3304370''>of</span> <span m=''3304430''>that?</span>
  <span m=''3305780''>Well,</span> <span m=''3306050''>1</span> <span m=''3306300''>in</span>
  <span m=''3306440''>365,</span> <span m=''3308010''>you</span> <span m=''3308140''>think.</span>
  </p><p><span m=''3310200''>Well,</span> <span m=''3310420''>one</span> <span m=''3310890''>day</span>
  <span m=''3311090''>I''m</span> <span m=''3311210''>in</span> <span m=''3311300''>middle</span>
  <span m=''3311550''>school,</span> <span m=''3311800''>about</span> <span m=''3311970''>the</span>
  <span m=''3312120''>age</span> <span m=''3312290''>you</span> <span m=''3312350''>start</span>
  <span m=''3312620''>thinking</span> <span m=''3312840''>about</span> <span m=''3313070''>these</span>
  <span m=''3313290''>things,</span> <span m=''3314040''>and</span> <span m=''3314200''>you</span>
  <span m=''3314250''>get</span> <span m=''3314390''>the</span> <span m=''3314500''>idea</span>
  <span m=''3314780''>to</span> <span m=''3314870''>count</span> <span m=''3315170''>back</span>
  <span m=''3315440''>nine</span> <span m=''3315720''>months</span> <span m=''3316060''>from</span>
  <span m=''3316460''>your</span> <span m=''3316660''>birthday.</span> <span m=''3317160''>Probably</span>
  <span m=''3317600''>some</span> <span m=''3317657''>of</span> <span m=''3317715''>you</span>
  <span m=''3317772''>have</span> <span m=''3317830''>done</span> <span m=''3318040''>that.</span>
  <span m=''3318940''>And</span> <span m=''3320130''>I</span> <span m=''3320180''>did</span>
  <span m=''3320420''>that</span> <span m=''3320610''>and</span> <span m=''3320870''>that''s</span>
  <span m=''3321310''>my</span> <span m=''3321400''>dad''s</span> <span m=''3321830''>birthday.</span>
  <span m=''3324490''>I</span> <span m=''3324560''>was</span> <span m=''3324750''>like,</span>
  <span m=''3325480''>oh.</span> <span m=''3328520''>May</span> <span m=''3329230''>is</span>
  <span m=''3329400''>not</span> <span m=''3329750''>1</span> <span m=''3329990''>in</span>
  <span m=''3330140''>365.</span> <span m=''3332100''>It''s</span> <span m=''3332270''>like,</span>
  <span m=''3333310''>Happy</span> <span m=''3333640''>Birthday.</span> <span m=''3335810''>I</span>
  <span m=''3336140''>don''t</span> <span m=''3336270''>know.</span> </p><p><span
  m=''3336860''>Anyway,</span> <span m=''3337170''>I</span> <span m=''3337310''>almost</span>
  <span m=''3337510''>needed</span> <span m=''3337750''>to</span> <span m=''3337800''>go</span>
  <span m=''3337960''>into</span> <span m=''3338090''>therapy</span> <span m=''3338600''>after</span>
  <span m=''3338850''>that,</span> <span m=''3339160''>you</span> <span m=''3339250''>know.</span>
  <span m=''3340800''>So</span> <span m=''3341710''>now</span> <span m=''3341880''>you</span>
  <span m=''3342160''>all</span> <span m=''3342193''>got</span> <span m=''3342226''>to</span>
  <span m=''3342260''>count</span> <span m=''3342560''>back</span> <span m=''3342800''>nine</span>
  <span m=''3343090''>months</span> <span m=''3343370''>from</span> <span m=''3343440''>your</span>
  <span m=''3343530''>birthday.</span> <span m=''3345810''>Anybody</span> <span m=''3346040''>whose</span>
  <span m=''3346270''>birthday</span> <span m=''3346690''>is</span> <span m=''3346745''>on</span>
  <span m=''3346800''>September</span> <span m=''3347310''>30</span> <span m=''3347820''>or</span>
  <span m=''3348080''>October</span> <span m=''3348310''>1,</span> <span m=''3349100''>nine</span>
  <span m=''3349370''>months</span> <span m=''3349610''>back</span> <span m=''3349870''>is</span>
  <span m=''3349990''>New</span> <span m=''3350090''>Year''s</span> <span m=''3350340''>Eve.</span>
  <span m=''3351360''>That''s</span> <span m=''3351540''>dangerous.</span> <span m=''3353100''>So</span>
  <span m=''3353620''>in</span> <span m=''3353730''>reality,</span> <span m=''3355060''>birthdays</span>
  <span m=''3355510''>are</span> <span m=''3355610''>not</span> <span m=''3356180''>independent</span>
  <span m=''3357100''>and</span> <span m=''3357320''>they</span> <span m=''3357440''>are</span>
  <span m=''3357530''>not</span> <span m=''3358230''>randomly</span> <span m=''3358820''>distributed,</span>
  <span m=''3359610''>but</span> <span m=''3359800''>we''re</span> <span m=''3359950''>going</span>
  <span m=''3360050''>to</span> <span m=''3360110''>assume</span> <span m=''3360630''>that</span>
  <span m=''3360970''>because</span> <span m=''3362040''>we''re</span> <span m=''3362280''>going</span>
  <span m=''3362370''>to</span> <span m=''3362410''>use</span> <span m=''3362760''>this</span>
  <span m=''3362890''>same</span> <span m=''3363360''>analysis</span> <span m=''3364190''>for</span>
  <span m=''3364340''>computer</span> <span m=''3364700''>science</span> <span m=''3365090''>problems</span>
  <span m=''3365510''>where</span> <span m=''3365650''>things</span> <span m=''3365930''>are,</span>
  <span m=''3366550''>hopefully,</span> <span m=''3367020''>more</span> <span m=''3367760''>independent</span>
  <span m=''3368410''>and</span> <span m=''3368560''>random.</span> </p><p><span m=''3369990''>Now,</span>
  <span m=''3370120''>we''re</span> <span m=''3370260''>going</span> <span m=''3370370''>to</span>
  <span m=''3370430''>do</span> <span m=''3370590''>an</span> <span m=''3370660''>experiment</span>
  <span m=''3371330''>to</span> <span m=''3371430''>see</span> <span m=''3371660''>how</span>
  <span m=''3371870''>many</span> <span m=''3372190''>people</span> <span m=''3372590''>it</span>
  <span m=''3372710''>takes</span> <span m=''3373060''>us</span> <span m=''3373970''>to</span>
  <span m=''3374100''>get</span> <span m=''3374620''>a</span> <span m=''3374710''>pair</span>
  <span m=''3374930''>of</span> <span m=''3374970''>matching</span> <span m=''3375290''>birthdays.</span>
  <span m=''3375710''>So</span> <span m=''3375860''>I''m</span> <span m=''3375920''>going</span>
  <span m=''3376030''>to</span> <span m=''3376210''>run</span> <span m=''3376440''>through</span>
  <span m=''3376610''>people</span> <span m=''3377050''>in</span> <span m=''3377440''>order</span>
  <span m=''3377770''>in</span> <span m=''3377835''>the</span> <span m=''3377900''>rows</span>
  <span m=''3378220''>here,</span> <span m=''3379000''>get</span> <span m=''3379170''>your</span>
  <span m=''3379290''>birthday</span> <span m=''3379510''>and</span> <span m=''3379730''>we''re</span>
  <span m=''3379900''>going</span> <span m=''3379990''>to</span> <span m=''3380030''>record</span>
  <span m=''3380440''>and</span> <span m=''3380500''>we''re</span> <span m=''3380595''>going</span>
  <span m=''3380690''>to</span> <span m=''3380760''>see</span> <span m=''3380900''>how</span>
  <span m=''3381140''>far</span> <span m=''3381380''>we</span> <span m=''3381490''>go</span>
  <span m=''3382260''>until</span> <span m=''3382380''>there''s</span> <span m=''3382680''>a</span>
  <span m=''3382740''>match</span> <span m=''3383320''>in</span> <span m=''3383440''>that</span>
  <span m=''3383640''>group.</span> <span m=''3384880''>So</span> <span m=''3384970''>I</span>
  <span m=''3385020''>will</span> <span m=''3385190''>write</span> <span m=''3385360''>up</span>
  <span m=''3385440''>the</span> <span m=''3385540''>months</span> <span m=''3385910''>here.</span>
  <span m=''3411230''>And</span> <span m=''3411480''>we''ll</span> <span m=''3411590''>start</span>
  <span m=''3411900''>with</span> <span m=''3411990''>my</span> <span m=''3412290''>birthday</span>
  <span m=''3412870''>is</span> <span m=''3413020''>October</span> <span m=''3413820''>28.</span>
  </p><p><span m=''3415950''>So</span> <span m=''3416080''>let''s</span> <span m=''3416310''>go</span>
  <span m=''3416580''>right</span> <span m=''3416740''>across.</span> <span m=''3417180''>What</span>
  <span m=''3417340''>yours?</span> </p><p><span m=''3417830''>AUDIENCE:</span> <span
  m=''3418260''>April</span> <span m=''3418690''>1.</span> </p><p><span m=''3419120''>TOM
  LEIGHTON: April</span> <span m=''3419860''>1.</span> <span m=''3426610''>OK.</span>
  <span m=''3427260''>We</span> <span m=''3427460''>won''t</span> <span m=''3428200''>embarrass</span>
  <span m=''3428590''>you</span> <span m=''3428670''>here.</span> <span m=''3428810''>OK,</span>
  <span m=''3429000''>who''s</span> <span m=''3429240''>next?</span> <span m=''3430930''>What''s</span>
  <span m=''3431110''>your</span> <span m=''3431270''>birthday?</span> </p><p><span
  m=''3432283''>AUDIENCE:</span> <span m=''3432746''>I''m</span> <span m=''3433209''>sorry.</span>
  <span m=''3433672''>September</span> <span m=''3434135''>2.</span> </p><p><span
  m=''3434600''>TOM LEIGHTON: September</span> <span m=''3435260''>2.</span> <span
  m=''3435910''>All</span> <span m=''3436313''>right.</span> <span m=''3438020''>Yours.</span>
  </p><p><span m=''3438975''>AUDIENCE:</span> <span m=''3439290''>June</span> <span
  m=''3439340''>1.</span> </p><p><span m=''3439615''>TOM LEIGHTON:</span> <span m=''3439890''>June</span>
  <span m=''3440670''>1.</span> <span m=''3442440''>OK.</span> <span m=''3442880''>We''ll</span>
  <span m=''3443170''>come</span> <span m=''3443360''>back.</span> </p><p><span m=''3443610''>AUDIENCE:</span>
  <span m=''3443750''>April</span> <span m=''3444030''>8.</span> </p><p><span m=''3444310''>TOM
  LEIGHTON: What</span> <span m=''3444440''>is</span> <span m=''3444540''>it?</span>
  </p><p><span m=''3444940''>AUDIENCE: April</span> <span m=''3445410''>8.</span>
  </p><p><span m=''3445880''>TOM LEIGHTON: April</span> <span m=''3446440''>8.</span>
  <span m=''3447481''>All</span> <span m=''3447972''>right.</span> </p><p><span m=''3448954''>AUDIENCE:</span>
  <span m=''3449445''>November</span> <span m=''3449936''>20.</span> </p><p><span
  m=''3450427''>TOM LEIGHTON:</span> <span m=''3450920''>November</span> <span m=''3451510''>20.</span>
  </p><p><span m=''3452992''>AUDIENCE:</span> <span m=''3453443''>June</span> <span
  m=''3453894''>12.</span> </p><p><span m=''3454796''>TOM LEIGHTON:</span> <span m=''3455250''>June</span>
  <span m=''3456260''>12.</span> </p><p><span m=''3457736''>AUDIENCE:</span> <span
  m=''3458212''>December</span> <span m=''3458688''>29.</span> </p><p><span m=''3459640''>TOM
  LEIGHTON:</span> <span m=''3460120''>December</span> <span m=''3460450''>29.</span>
  </p><p><span m=''3461952''>AUDIENCE:</span> <span m=''3462394''>[INAUDIBLE].</span>
  </p><p><span m=''3464162''>TOM LEIGHTON:</span> <span m=''3464610''>What</span>
  <span m=''3464750''>is</span> <span m=''3464850''>it?</span> </p><p><span m=''3465260''>AUDIENCE:
  June</span> <span m=''3465600''>14.</span> </p><p><span m=''3465940''>TOM LEIGHTON:</span>
  <span m=''3466280''>June</span> <span m=''3466880''>14.</span> <span m=''3467480''>Ooh,</span>
  <span m=''3467655''>I</span> <span m=''3467830''>almost</span> <span m=''3468240''>got</span>
  <span m=''3468450''>one</span> <span m=''3468590''>there.</span> <span m=''3468820''>That</span>
  <span m=''3468910''>one''s</span> <span m=''3469070''>close.</span> <span m=''3470045''>All</span>
  <span m=''3470450''>right.</span> <span m=''3471260''>What''s</span> <span m=''3471410''>yours?</span>
  </p><p><span m=''3471770''>AUDIENCE:</span> <span m=''3472266''>March</span> <span
  m=''3472762''>6.</span> </p><p><span m=''3473260''>TOM LEIGHTON: March</span> <span
  m=''3473650''>6.</span> </p><p><span m=''3475000''>AUDIENCE:</span> <span m=''3475450''>May</span>
  <span m=''3475897''>2.</span> </p><p><span m=''3476344''>TOM LEIGHTON:</span> <span
  m=''3476791''>May</span> <span m=''3477240''>2.</span> </p><p><span m=''3478650''>AUDIENCE:</span>
  <span m=''3479120''>17th</span> <span m=''3479590''>of</span> <span m=''3480060''>November.</span>
  </p><p><span m=''3480530''>TOM LEIGHTON:</span> <span m=''3481000''>November</span>
  <span m=''3481290''>17.</span> <span m=''3481580''>Close</span> <span m=''3481950''>again.</span>
  </p><p><span m=''3482530''>AUDIENCE:</span> <span m=''3482963''>August</span> <span
  m=''3483396''>4.</span> </p><p><span m=''3484695''>TOM LEIGHTON:</span> <span m=''3485130''>August</span>
  <span m=''3485840''>4.</span> </p><p><span m=''3487028''>AUDIENCE:</span> <span
  m=''3487516''>July</span> <span m=''3488004''>25.</span> </p><p><span m=''3488980''>TOM
  LEIGHTON:</span> <span m=''3489470''>July</span> <span m=''3489910''>25.</span>
  <span m=''3490785''>I</span> <span m=''3491230''>don''t</span> <span m=''3491675''>think</span>
  <span m=''3492120''>we''ll</span> <span m=''3492320''>get</span> <span m=''3492460''>to</span>
  <span m=''3492540''>100</span> <span m=''3492920''>here,</span> <span m=''3493280''>hopefully.</span>
  <span m=''3494170''>Yeah,</span> <span m=''3494660''>what''s</span> <span m=''3494940''>yours?</span>
  </p><p><span m=''3495220''>AUDIENCE:</span> <span m=''3495635''>October</span> <span
  m=''3495842''>30.</span> </p><p><span m=''3496050''>TOM LEIGHTON: What</span> <span
  m=''3496210''>is</span> <span m=''3496300''>it?</span> </p><p><span m=''3496795''>AUDIENCE:
  October</span> <span m=''3497290''>30.</span> </p><p><span m=''3497710''>TOM LEIGHTON:
  October</span> <span m=''3498110''>30.</span> <span m=''3498510''>Got</span> <span
  m=''3498680''>close.</span> </p><p><span m=''3500716''>AUDIENCE:</span> <span m=''3501148''>July</span>
  <span m=''3501580''>6.</span> </p><p><span m=''3502012''>TOM LEIGHTON:</span> <span
  m=''3502450''>July</span> <span m=''3502890''>6.</span> <span m=''3503320''>All</span>
  <span m=''3503600''>right.</span> </p><p><span m=''3504726''>AUDIENCE:</span> <span
  m=''3505222''>February</span> <span m=''3505718''>25.</span> </p><p><span m=''3506214''>TOM
  LEIGHTON:</span> <span m=''3506710''>February</span> <span m=''3507080''>25.</span>
  </p><p><span m=''3510580''>AUDIENCE:</span> <span m=''3510992''>May</span> <span
  m=''3511404''>21.</span> </p><p><span m=''3512228''>TOM LEIGHTON:</span> <span m=''3512640''>May</span>
  <span m=''3512930''>what?</span> <span m=''3513930''>21st</span> <span m=''3514410''>of</span>
  <span m=''3514890''>May.</span> </p><p><span m=''3517630''>AUDIENCE:</span> <span
  m=''3517960''>May</span> <span m=''3518433''>30.</span> </p><p><span m=''3518906''>TOM
  LEIGHTON:</span> <span m=''3519380''>May</span> <span m=''3519900''>30.</span> <span
  m=''3521820''>You</span> <span m=''3522150''>guys</span> <span m=''3523110''>fooled</span>
  <span m=''3523370''>me.</span> <span m=''3523630''>What</span> <span m=''3523880''>have</span>
  <span m=''3524060''>you</span> <span m=''3524360''>got?</span> </p><p><span m=''3524660''>AUDIENCE:</span>
  <span m=''3525045''>January</span> <span m=''3525430''>12.</span> </p><p><span m=''3525815''>TOM
  LEIGHTON:</span> <span m=''3526200''>January</span> <span m=''3526870''>12.</span>
  <span m=''3527890''>All</span> <span m=''3527930''>right.</span> </p><p><span m=''3528852''>AUDIENCE:</span>
  <span m=''3529313''>July</span> <span m=''3529774''>14.</span> </p><p><span m=''3530696''>TOM
  LEIGHTON:</span> <span m=''3531160''>July</span> <span m=''3531910''>14.</span>
  <span m=''3535090''>OK.</span> </p><p><span m=''3535455''>AUDIENCE:</span> <span
  m=''3535820''>April</span> <span m=''3536265''>30.</span> </p><p><span m=''3537155''>TOM
  LEIGHTON:</span> <span m=''3537600''>April</span> <span m=''3538290''>30.</span>
  </p><p><span m=''3540303''>AUDIENCE:</span> <span m=''3540744''>March</span> <span
  m=''3541185''>13.</span> </p><p><span m=''3542067''>TOM LEIGHTON:</span> <span m=''3542510''>March</span>
  <span m=''3542960''>13.</span> <span m=''3545360''>All</span> <span m=''3545850''>right.</span>
  <span m=''3546000''>Did</span> <span m=''3546230''>I</span> <span m=''3546270''>get--</span>
  </p><p><span m=''3546610''>AUDIENCE: October</span> <span m=''3547090''>7.</span>
  </p><p><span m=''3547705''>TOM LEIGHTON:</span> <span m=''3548120''>October</span>
  <span m=''3548610''>7.</span> </p><p><span m=''3550044''>AUDIENCE:</span> <span
  m=''3550516''>October</span> <span m=''3550988''>8.</span> </p><p><span m=''3551460''>TOM
  LEIGHTON:</span> <span m=''3551932''>Ah,</span> <span m=''3552410''>you</span> <span
  m=''3552690''>guys.</span> <span m=''3556376''>OK.</span> <span m=''3557750''>Did</span>
  <span m=''3557820''>I</span> <span m=''3557880''>get</span> <span m=''3558060''>you?</span>
  </p><p><span m=''3558470''>AUDIENCE:</span> <span m=''3558893''>September</span>
  <span m=''3559316''>15.</span> </p><p><span m=''3559740''>TOM LEIGHTON: September</span>
  <span m=''3560460''>15.</span> </p><p><span m=''3562581''>AUDIENCE:</span> <span
  m=''3563048''>November</span> <span m=''3563515''>9.</span> </p><p><span m=''3564916''>TOM
  LEIGHTON:</span> <span m=''3565390''>November</span> <span m=''3565620''>9.</span>
  <span m=''3566464''>All</span> <span m=''3566886''>right.</span> </p><p><span m=''3567308''>AUDIENCE:
  July</span> <span m=''3567519''>15.</span> </p><p><span m=''3567730''>TOM LEIGHTON:
  July</span> <span m=''3569880''>15.</span> <span m=''3572190''>Close.</span> </p><p><span
  m=''3573306''>AUDIENCE:</span> <span m=''3573742''>September</span> <span m=''3574178''>3.</span>
  </p><p><span m=''3574614''>TOM LEIGHTON:</span> <span m=''3575050''>September</span>
  <span m=''3575650''>3.</span> <span m=''3576280''>You</span> <span m=''3576756''>guys</span>
  <span m=''3577232''>are</span> <span m=''3577710''>killing</span> <span m=''3577770''>me</span>
  <span m=''3578170''>here.</span> </p><p><span m=''3578680''>AUDIENCE:</span> <span
  m=''3579172''>February</span> <span m=''3579664''>6.</span> </p><p><span m=''3580156''>TOM
  LEIGHTON:</span> <span m=''3580650''>February</span> <span m=''3581310''>6.</span>
  </p><p><span m=''3581970''>AUDIENCE:</span> <span m=''3582434''>October</span> <span
  m=''3582898''>26.</span> </p><p><span m=''3584754''>TOM LEIGHTON:</span> <span m=''3585220''>OK.</span>
  </p><p><span m=''3586514''>AUDIENCE:</span> <span m=''3586978''>November</span>
  <span m=''3587442''>2.</span> </p><p><span m=''3588834''>TOM LEIGHTON:</span> <span
  m=''3589300''>November</span> <span m=''3589990''>2.</span> </p><p><span m=''3591163''>AUDIENCE:</span>
  <span m=''3591656''>January</span> <span m=''3592149''>23.</span> </p><p><span m=''3594121''>TOM
  LEIGHTON:</span> <span m=''3594620''>January</span> <span m=''3594885''>23.</span>
  </p><p><span m=''3596578''>AUDIENCE:</span> <span m=''3597054''>September</span>
  <span m=''3597530''>27.</span> </p><p><span m=''3599434''>TOM LEIGHTON:</span> <span
  m=''3599910''>You</span> <span m=''3600030''>guys</span> <span m=''3600240''>are</span>
  <span m=''3600280''>going</span> <span m=''3600360''>to</span> <span m=''3600420''>set</span>
  <span m=''3600650''>a</span> <span m=''3600700''>record</span> <span m=''3601060''>for</span>
  <span m=''3601160''>sure</span> <span m=''3601510''>here.</span> <span m=''3602230''>This</span>
  <span m=''3602560''>isn''t</span> <span m=''3602700''>the</span> <span m=''3603110''>way</span>
  <span m=''3603156''>it''s</span> <span m=''3603203''>supposed</span> <span m=''3603250''>to</span>
  <span m=''3603340''>go.</span> </p><p><span m=''3603890''>AUDIENCE:</span> <span
  m=''3604175''>December</span> <span m=''3604460''>30.</span> </p><p><span m=''3605292''>TOM
  LEIGHTON:</span> <span m=''3605710''>December</span> <span m=''3606260''>30.</span>
  </p><p><span m=''3609290''>AUDIENCE:</span> <span m=''3609790''>December</span>
  <span m=''3610235''>28.</span> </p><p><span m=''3610680''>TOM LEIGHTON:</span> <span
  m=''3611139''>Ah,</span> <span m=''3611598''>come</span> <span m=''3612057''>on,</span>
  <span m=''3612516''>guys.</span> <span m=''3615730''>What</span> <span m=''3615880''>is</span>
  <span m=''3616120''>the</span> <span m=''3616430''>probability</span> <span m=''3616690''>of</span>
  <span m=''3616950''>going</span> <span m=''3617210''>this</span> <span m=''3617370''>long</span>
  <span m=''3617660''>here?</span> <span m=''3618410''>Yeah.</span> </p><p><span m=''3619122''>AUDIENCE:</span>
  <span m=''3619554''>September</span> <span m=''3619986''>22.</span> </p><p><span
  m=''3620420''>TOM LEIGHTON: September</span> <span m=''3620910''>22.</span> </p><p><span
  m=''3623130''>AUDIENCE:</span> <span m=''3623597''>July</span> <span m=''3624064''>30.</span>
  </p><p><span m=''3626399''>TOM LEIGHTON:</span> <span m=''3626870''>July</span>
  <span m=''3627155''>30.</span> </p><p><span m=''3629396''>AUDIENCE:</span> <span
  m=''3629885''>The</span> <span m=''3630374''>24th</span> <span m=''3630863''>of</span>
  <span m=''3631352''>August.</span> </p><p><span m=''3632330''>TOM LEIGHTON:</span>
  <span m=''3632820''>24th</span> <span m=''3633200''>August.</span> <span m=''3633740''>I''m</span>
  <span m=''3633840''>going</span> <span m=''3633910''>to</span> <span m=''3633980''>have</span>
  <span m=''3634050''>to</span> <span m=''3634120''>ask</span> <span m=''3634310''>the</span>
  <span m=''3634410''>same</span> <span m=''3634670''>person</span> <span m=''3634980''>to</span>
  <span m=''3635050''>tell</span> <span m=''3635210''>me</span> <span m=''3635340''>twice</span>
  <span m=''3635710''>here</span> <span m=''3635850''>to</span> <span m=''3635900''>get</span>
  <span m=''3636030''>a</span> <span m=''3636080''>match.</span> <span m=''3637110''>We</span>
  <span m=''3637280''>got</span> <span m=''3637420''>over</span> <span m=''3637540''>there</span>
  <span m=''3637730''>now?</span> </p><p><span m=''3638150''>AUDIENCE:</span> <span
  m=''3638586''>April</span> <span m=''3639022''>6.</span> </p><p><span m=''3639460''>TOM
  LEIGHTON: April</span> <span m=''3640300''>6.</span> </p><p><span m=''3642141''>AUDIENCE:</span>
  <span m=''3642592''>October</span> <span m=''3643043''>16.</span> </p><p><span m=''3644396''>TOM
  LEIGHTON:</span> <span m=''3644850''>October</span> <span m=''3645110''>16.</span>
  </p><p><span m=''3645588''>AUDIENCE:</span> <span m=''3646066''>Did</span> <span
  m=''3646544''>ask</span> <span m=''3647022''>how</span> <span m=''3647261''>many--</span>
  </p><p><span m=''3647500''>AUDIENCE: September</span> <span m=''3647976''>3.</span>
  </p><p><span m=''3648452''>TOM LEIGHTON: September</span> <span m=''3648928''>3.</span>
  <span m=''3650460''>All</span> <span m=''3650510''>right.</span> <span m=''3652545''>Very</span>
  <span m=''3653455''>good.</span> <span m=''3655275''>All</span> <span m=''3655730''>right.</span>
  <span m=''3656190''>Let''s</span> <span m=''3656495''>count</span> <span m=''3656800''>and</span>
  <span m=''3656920''>see</span> <span m=''3657290''>how</span> <span m=''3657610''>many</span>
  <span m=''3658670''>we</span> <span m=''3658860''>got</span> <span m=''3659150''>here.</span>
  <span m=''3660230''>1,</span> <span m=''3660677''>2,</span> <span m=''3660826''>3,</span>
  <span m=''3660975''>4,</span> <span m=''3661124''>5,</span> <span m=''3661571''>6,</span>
  <span m=''3662018''>7,</span> <span m=''3662465''>8.</span> <span m=''3662912''>9,</span>
  <span m=''3663359''>10,</span> <span m=''3663806''>11,</span> <span m=''3664260''>12,</span>
  <span m=''3664730''>13,</span> <span m=''3665200''>14,</span> <span m=''3665670''>15,</span>
  <span m=''3666140''>16,</span> <span m=''3667080''>17,</span> <span m=''3667550''>18,</span>
  <span m=''3668020''>19,</span> <span m=''3668490''>20</span> <span m=''3668960''>21,</span>
  <span m=''3669440''>22,</span> <span m=''3669892''>23,</span> <span m=''3671760''>24,</span>
  <span m=''3672060''>25,</span> <span m=''3672560''>26,</span> <span m=''3673060''>27,</span>
  <span m=''3674060''>28,</span> <span m=''3674560''>29,</span> <span m=''3675560''>30,</span>
  <span m=''3676060''>31,</span> <span m=''3676560''>32,</span> <span m=''3677060''>33,</span>
  <span m=''3677560''>34,</span> <span m=''3678060''>35,</span> <span m=''3678560''>36,</span>
  <span m=''3679060''>37,</span> <span m=''3679560''>38,</span> <span m=''3680060''>39,</span>
  <span m=''3681060''>40,</span> <span m=''3681560''>41,</span> <span m=''3681800''>42.</span>
  <span m=''3682630''>That</span> <span m=''3682890''>is</span> <span m=''3683070''>a</span>
  <span m=''3683160''>record.</span> <span m=''3684360''>So</span> <span m=''3684580''>it</span>
  <span m=''3684870''>took</span> <span m=''3684980''>42</span> <span m=''3685730''>people</span>
  <span m=''3687230''>to</span> <span m=''3687500''>get</span> <span m=''3687890''>a</span>
  <span m=''3687990''>match.</span> </p><p><span m=''3689230''>Now</span> <span m=''3689400''>it</span>
  <span m=''3689520''>turns</span> <span m=''3689880''>out</span> <span m=''3690180''>that</span>
  <span m=''3690260''>for</span> <span m=''3690530''>N</span> <span m=''3690740''>equals</span>
  <span m=''3691050''>365,</span> <span m=''3692750''>the</span> <span m=''3692860''>magic</span>
  <span m=''3693270''>number</span> <span m=''3693550''>for</span> <span m=''3693750''>N</span>
  <span m=''3694030''>is</span> <span m=''3694160''>23,</span> <span m=''3695090''>that</span>
  <span m=''3695520''>by</span> <span m=''3695660''>23</span> <span m=''3696420''>people,</span>
  <span m=''3696840''>we</span> <span m=''3696950''>got</span> <span m=''3697110''>a</span>
  <span m=''3697160''>50-50</span> <span m=''3697900''>chance.</span> <span m=''3699180''>In</span>
  <span m=''3699280''>fact,</span> <span m=''3699370''>the</span> <span m=''3699450''>probability</span>
  <span m=''3699940''>of</span> <span m=''3700020''>a</span> <span m=''3700070''>match</span>
  <span m=''3701080''>on</span> <span m=''3701270''>23</span> <span m=''3701800''>people</span>
  <span m=''3702180''>is</span> <span m=''3702320''>0.506.</span> <span m=''3704260''>It''s</span>
  <span m=''3704580''>a</span> <span m=''3704660''>little</span> <span m=''3704860''>bit</span>
  <span m=''3705000''>better</span> <span m=''3705180''>than</span> <span m=''3705340''>50-50</span>
  <span m=''3705930''>chance</span> <span m=''3706400''>at</span> <span m=''3706640''>23.</span>
  <span m=''3707990''>Now,</span> <span m=''3708090''>maybe</span> <span m=''3708200''>we</span>
  <span m=''3708290''>should</span> <span m=''3708470''>figure</span> <span m=''3708720''>out.</span>
  <span m=''3708870''>It''s</span> <span m=''3708912''>too</span> <span m=''3708955''>late</span>
  <span m=''3708997''>for</span> <span m=''3709040''>homework</span> <span m=''3709460''>to</span>
  <span m=''3709650''>figure</span> <span m=''3709900''>out</span> <span m=''3709980''>what</span>
  <span m=''3710110''>the</span> <span m=''3710200''>chances</span> <span m=''3710620''>are</span>
  <span m=''3710735''>of</span> <span m=''3710850''>going</span> <span m=''3711190''>this</span>
  <span m=''3711500''>long</span> <span m=''3712600''>without</span> <span m=''3712890''>a</span>
  <span m=''3712930''>match.</span> <span m=''3713340''>That</span> <span m=''3713760''>maybe</span>
  <span m=''3714000''>worth</span> <span m=''3714270''>figuring</span> <span m=''3714670''>that</span>
  <span m=''3714820''>out.</span> </p><p><span m=''3715910''>Now,</span> <span m=''3717390''>it</span>
  <span m=''3717480''>may</span> <span m=''3717690''>seem</span> <span m=''3717890''>surprising</span>
  <span m=''3718430''>at</span> <span m=''3718530''>first</span> <span m=''3718830''>that</span>
  <span m=''3718940''>23</span> <span m=''3719490''>people</span> <span m=''3719890''>is</span>
  <span m=''3719980''>enough</span> <span m=''3720500''>to</span> <span m=''3720640''>have</span>
  <span m=''3720820''>a</span> <span m=''3720900''>50/50</span> <span m=''3721530''>chance</span>
  <span m=''3722730''>because</span> <span m=''3722900''>the</span> <span m=''3722990''>chance</span>
  <span m=''3723350''>of</span> <span m=''3723430''>any</span> <span m=''3723650''>pair</span>
  <span m=''3724040''>matching</span> <span m=''3724470''>is</span> <span m=''3724580''>1</span>
  <span m=''3724790''>in</span> <span m=''3724880''>365,</span> <span m=''3726000''>by</span>
  <span m=''3726160''>our</span> <span m=''3726290''>assumption.</span> <span m=''3727770''>And</span>
  <span m=''3727920''>that''s</span> <span m=''3728150''>small,</span> <span m=''3729230''>but</span>
  <span m=''3729840''>there''s</span> <span m=''3730020''>lots</span> <span m=''3730260''>of</span>
  <span m=''3730350''>pairs</span> <span m=''3730670''>of</span> <span m=''3730760''>people</span>
  <span m=''3732330''>and</span> <span m=''3732570''>every</span> <span m=''3732800''>pair</span>
  <span m=''3733210''>of</span> <span m=''3733270''>people</span> <span m=''3733630''>have</span>
  <span m=''3733870''>a</span> <span m=''3733960''>chance</span> <span m=''3734630''>to</span>
  <span m=''3735100''>match</span> <span m=''3735950''>and</span> <span m=''3736080''>that''s</span>
  <span m=''3736300''>why</span> <span m=''3736760''>23</span> <span m=''3737860''>turns</span>
  <span m=''3738170''>out</span> <span m=''3738310''>to</span> <span m=''3738360''>be</span>
  <span m=''3738450''>enough</span> <span m=''3738640''>to</span> <span m=''3738740''>get</span>
  <span m=''3738910''>to</span> <span m=''3738970''>50-50.</span> </p><p><span m=''3740420''>Now,</span>
  <span m=''3740580''>we''re</span> <span m=''3740710''>going</span> <span m=''3740810''>to</span>
  <span m=''3740860''>do</span> <span m=''3741000''>the</span> <span m=''3741160''>analysis</span>
  <span m=''3742020''>for</span> <span m=''3742170''>general</span> <span m=''3742670''>M</span>
  <span m=''3743140''>and</span> <span m=''3743640''>N</span> <span m=''3743790''>to</span>
  <span m=''3743940''>the</span> <span m=''3744030''>figure</span> <span m=''3744330''>out</span>
  <span m=''3744470''>the</span> <span m=''3744550''>probability</span> <span m=''3745370''>of</span>
  <span m=''3745480''>a</span> <span m=''3745550''>match</span> <span m=''3746490''>if</span>
  <span m=''3746680''>there''s</span> <span m=''3747850''>M</span> <span m=''3748160''>people</span>
  <span m=''3748820''>and</span> <span m=''3749050''>N</span> <span m=''3749580''>birthdays.</span>
  <span m=''3751230''>There''s</span> <span m=''3751500''>lots</span> <span m=''3751870''>of</span>
  <span m=''3751960''>ways</span> <span m=''3752250''>to</span> <span m=''3752360''>do</span>
  <span m=''3752590''>it.</span> <span m=''3756140''>The</span> <span m=''3757260''>easiest</span>
  <span m=''3758140''>is</span> <span m=''3758300''>to</span> <span m=''3758400''>sort</span>
  <span m=''3758660''>of</span> <span m=''3759690''>well,</span> <span m=''3759900''>we''ll</span>
  <span m=''3759980''>draw</span> <span m=''3760350''>the</span> <span m=''3760470''>sample</span>
  <span m=''3760870''>space.</span> <span m=''3761220''>It</span> <span m=''3761290''>will</span>
  <span m=''3761360''>be</span> <span m=''3761480''>too</span> <span m=''3761630''>big</span>
  <span m=''3762100''>to</span> <span m=''3762400''>draw</span> <span m=''3762620''>the</span>
  <span m=''3762710''>whole</span> <span m=''3762950''>thing,</span> <span m=''3763110''>but</span>
  <span m=''3763200''>we</span> <span m=''3763300''>can</span> <span m=''3763430''>sort</span>
  <span m=''3763590''>of</span> <span m=''3763670''>model</span> <span m=''3764020''>the</span>
  <span m=''3764130''>sample</span> <span m=''3764510''>space</span> <span m=''3766120''>and</span>
  <span m=''3766270''>then</span> <span m=''3766510''>look</span> <span m=''3766700''>at</span>
  <span m=''3766760''>the</span> <span m=''3766840''>sample</span> <span m=''3767050''>points.</span>
  </p><p><span m=''3781580''>So</span> <span m=''3782620''>you''ve</span> <span m=''3782790''>got</span>
  <span m=''3783060''>the</span> <span m=''3783330''>first</span> <span m=''3783660''>person</span>
  <span m=''3785680''>and</span> <span m=''3786030''>there''s</span> <span m=''3786910''>N</span>
  <span m=''3787190''>birthdays</span> <span m=''3788400''>here,</span> <span m=''3788710''>so</span>
  <span m=''3788950''>it</span> <span m=''3789010''>could</span> <span m=''3789120''>be</span>
  <span m=''3789220''>anywhere</span> <span m=''3789430''>from</span> <span m=''3789560''>January</span>
  <span m=''3790060''>1</span> <span m=''3791250''>out</span> <span m=''3791600''>to</span>
  <span m=''3791960''>December</span> <span m=''3792320''>31</span> <span m=''3794630''>and</span>
  <span m=''3794730''>in</span> <span m=''3794820''>general</span> <span m=''3795320''>this</span>
  <span m=''3795450''>will</span> <span m=''3795580''>be</span> <span m=''3795810''>N.</span>
  <span m=''3798170''>And</span> <span m=''3798280''>then</span> <span m=''3798410''>you</span>
  <span m=''3798480''>have</span> <span m=''3798680''>the</span> <span m=''3798770''>second</span>
  <span m=''3799150''>person</span> <span m=''3807045''>and</span> <span m=''3807540''>they</span>
  <span m=''3808035''>have</span> <span m=''3808282''>N</span> <span m=''3808530''>possibilities</span>
  <span m=''3809280''>for</span> <span m=''3809390''>their</span> <span m=''3810450''>birthday.</span>
  <span m=''3811510''>And</span> <span m=''3812360''>you</span> <span m=''3812520''>take</span>
  <span m=''3812760''>the</span> <span m=''3812840''>tree</span> <span m=''3813210''>down</span>
  <span m=''3813520''>M</span> <span m=''3813820''>levels</span> <span m=''3817560''>to</span>
  <span m=''3817640''>the</span> <span m=''3817710''>very</span> <span m=''3817940''>last</span>
  <span m=''3818310''>person</span> <span m=''3818660''>here.</span> </p><p><span
  m=''3825920''>So</span> <span m=''3826840''>each</span> <span m=''3827110''>node</span>
  <span m=''3827390''>has</span> <span m=''3827590''>degree</span> <span m=''3827910''>N</span>
  <span m=''3828360''>and</span> <span m=''3828530''>there''s</span> <span m=''3828820''>M</span>
  <span m=''3829020''>levels</span> <span m=''3829370''>on</span> <span m=''3829460''>this</span>
  <span m=''3829570''>tree.</span> <span m=''3830530''>So</span> <span m=''3830690''>the</span>
  <span m=''3830790''>sample</span> <span m=''3831210''>space</span> <span m=''3834710''>is</span>
  <span m=''3834940''>the</span> <span m=''3835040''>set</span> <span m=''3835510''>of</span>
  <span m=''3836720''>all</span> <span m=''3837870''>n-tuples</span> <span m=''3839280''>b1,</span>
  <span m=''3840700''>b2,</span> <span m=''3842233''>to</span> <span m=''3842674''>bm,</span>
  <span m=''3843560''>these</span> <span m=''3843810''>are</span> <span m=''3843950''>the</span>
  <span m=''3844620''>birthdays</span> <span m=''3846530''>where</span> <span m=''3848370''>every</span>
  <span m=''3848670''>value</span> <span m=''3849160''>of</span> <span m=''3849250''>bi</span>
  <span m=''3850880''>is</span> <span m=''3851040''>between</span> <span m=''3851636''>1</span>
  <span m=''3852092''>and</span> <span m=''3852548''>N.</span> <span m=''3855420''>So</span>
  <span m=''3855860''>a</span> <span m=''3855920''>sample</span> <span m=''3856330''>point</span>
  <span m=''3856670''>is</span> <span m=''3856780''>all</span> <span m=''3856930''>the</span>
  <span m=''3857010''>birthdays</span> <span m=''3857270''>of</span> <span m=''3857530''>the</span>
  <span m=''3857995''>M</span> <span m=''3858460''>people.</span> </p><p><span m=''3862180''>How</span>
  <span m=''3862370''>many</span> <span m=''3862580''>sample</span> <span m=''3862960''>points</span>
  <span m=''3863260''>are</span> <span m=''3863390''>there</span> <span m=''3863610''>here?</span>
  <span m=''3868460''>Remember</span> <span m=''3869720''>how</span> <span m=''3869830''>to</span>
  <span m=''3869920''>count</span> <span m=''3870200''>these</span> <span m=''3870420''>things?</span>
  <span m=''3872610''>Number</span> <span m=''3872840''>of</span> <span m=''3872920''>leaves</span>
  <span m=''3873290''>on</span> <span m=''3873420''>an</span> <span m=''3873580''>N-ary</span>
  <span m=''3873980''>tree</span> <span m=''3874330''>of</span> <span m=''3874450''>depth</span>
  <span m=''3874740''>M</span> <span m=''3875640''>or</span> <span m=''3875840''>you</span>
  <span m=''3875930''>can</span> <span m=''3876060''>think</span> <span m=''3876230''>of</span>
  <span m=''3876300''>it</span> <span m=''3876400''>this</span> <span m=''3876590''>way.</span>
  <span m=''3876780''>I''ve</span> <span m=''3876910''>got</span> <span m=''3878840''>N</span>
  <span m=''3879090''>choices</span> <span m=''3879580''>for</span> <span m=''3879725''>each</span>
  <span m=''3879870''>bi</span> <span m=''3880140''>and</span> <span m=''3880620''>there''s</span>
  <span m=''3880980''>M</span> <span m=''3881330''>of</span> <span m=''3881480''>them.</span>
  </p><p><span m=''3881950''>AUDIENCE:</span> <span m=''3882347''>[INAUDIBLE].</span>
  </p><p><span m=''3883141''>TOM LEIGHTON:</span> <span m=''3883540''>So</span> <span
  m=''3883700''>what''s</span> <span m=''3883900''>the</span> <span m=''3883990''>number</span>
  <span m=''3884290''>of</span> <span m=''3884400''>sample</span> <span m=''3884725''>points?</span>
  </p><p><span m=''3885050''>AUDIENCE:</span> <span m=''3885542''>N</span> <span m=''3886034''>to</span>
  <span m=''3886280''>the</span> <span m=''3886526''>M.</span> </p><p><span m=''3887020''>TOM
  LEIGHTON:</span> <span m=''3887435''>N</span> <span m=''3887850''>to</span> <span
  m=''3887960''>the</span> <span m=''3888330''>M.</span> <span m=''3891900''>Because</span>
  <span m=''3892660''>N</span> <span m=''3892960''>choices</span> <span m=''3893410''>here,</span>
  <span m=''3894720''>N</span> <span m=''3895000''>choices</span> <span m=''3895410''>here,</span>
  <span m=''3896780''>N</span> <span m=''3897020''>choices</span> <span m=''3897420''>there,</span>
  <span m=''3897660''>so</span> <span m=''3897740''>you</span> <span m=''3897820''>have</span>
  <span m=''3897900''>N</span> <span m=''3898150''>times</span> <span m=''3898420''>N</span>
  <span m=''3898640''>times</span> <span m=''3898920''>N</span> <span m=''3899360''>M</span>
  <span m=''3899800''>times.</span> <span m=''3902220''>And</span> <span m=''3903280''>what''s</span>
  <span m=''3903590''>the</span> <span m=''3903690''>probability</span> <span m=''3904420''>of</span>
  <span m=''3904500''>each</span> <span m=''3904760''>outcome?</span> <span m=''3907160''>For</span>
  <span m=''3907300''>a</span> <span m=''3907360''>set</span> <span m=''3907590''>of</span>
  <span m=''3907670''>possible</span> <span m=''3908080''>birthdays,</span> <span
  m=''3908910''>what''s</span> <span m=''3909200''>its</span> <span m=''3909320''>probability?</span>
  <span m=''3913460''>What''s</span> <span m=''3913700''>the</span> <span m=''3913780''>probability</span>
  <span m=''3914870''>of</span> <span m=''3915960''>b1,</span> <span m=''3917180''>b2,</span>
  <span m=''3918920''>bM?</span> </p><p><span m=''3927460''>So</span> <span m=''3927560''>the</span>
  <span m=''3927630''>probability</span> <span m=''3928180''>of</span> <span m=''3928250''>a</span>
  <span m=''3928300''>sample</span> <span m=''3928650''>point.</span> <span m=''3928950''>What''s</span>
  <span m=''3929120''>the</span> <span m=''3929180''>probability</span> <span m=''3929630''>that</span>
  <span m=''3929790''>the</span> <span m=''3929870''>first</span> <span m=''3930160''>person</span>
  <span m=''3930450''>has</span> <span m=''3930570''>birthday</span> <span m=''3930880''>b1,</span>
  <span m=''3931420''>the</span> <span m=''3931510''>second</span> <span m=''3931860''>has</span>
  <span m=''3931990''>b2,</span> <span m=''3932610''>and</span> <span m=''3932820''>the</span>
  <span m=''3932940''>N-th</span> <span m=''3933423''>has</span> <span m=''3933906''>bM?</span>
  <span m=''3936810''>Remember</span> <span m=''3936970''>that?</span> <span m=''3937618''>Yeah.</span>
  </p><p><span m=''3938046''>AUDIENCE:</span> <span m=''3938474''>1</span> <span m=''3938902''>over</span>
  <span m=''3938987''>N</span> <span m=''3939073''>to</span> <span m=''3939158''>the</span>
  <span m=''3939244''>M.</span> </p><p><span m=''3939330''>TOM LEIGHTON:</span> <span
  m=''3939760''>1</span> <span m=''3939980''>over</span> <span m=''3940170''>N</span>
  <span m=''3940470''>to</span> <span m=''3940553''>the</span> <span m=''3940636''>M</span>
  <span m=''3940720''>because</span> <span m=''3941030''>each</span> <span m=''3941410''>edge</span>
  <span m=''3942410''>is</span> <span m=''3942810''>probability</span> <span m=''3943035''>of</span>
  <span m=''3943260''>1</span> <span m=''3943510''>over</span> <span m=''3943760''>N</span>
  <span m=''3945700''>and</span> <span m=''3946080''>the</span> <span m=''3946180''>paths</span>
  <span m=''3946420''>are</span> <span m=''3946503''>length</span> <span m=''3946586''>M,</span>
  <span m=''3946670''>so</span> <span m=''3946780''>you''ve</span> <span m=''3946840''>got</span>
  <span m=''3947010''>1</span> <span m=''3947240''>over</span> <span m=''3947450''>N</span>
  <span m=''3947750''>to</span> <span m=''3947840''>the</span> <span m=''3947980''>M-th</span>
  <span m=''3948240''>power.</span> <span m=''3952770''>Probability</span> <span m=''3953025''>of</span>
  <span m=''3953280''>the</span> <span m=''3953370''>first</span> <span m=''3953680''>birthday</span>
  <span m=''3954050''>matching</span> <span m=''3954540''>is</span> <span m=''3954670''>1</span>
  <span m=''3954910''>in</span> <span m=''3955010''>N</span> <span m=''3955500''>times</span>
  <span m=''3955790''>1</span> <span m=''3956010''>in</span> <span m=''3956100''>N</span>
  <span m=''3957140''>times</span> <span m=''3957410''>1</span> <span m=''3957670''>in</span>
  <span m=''3957930''>N.</span> <span m=''3959840''>And</span> <span m=''3960020''>this</span>
  <span m=''3960080''>actually</span> <span m=''3960760''>makes</span> <span m=''3961060''>sense</span>
  <span m=''3961420''>because</span> <span m=''3963110''>I''ve</span> <span m=''3963240''>got</span>
  <span m=''3963490''>N</span> <span m=''3963720''>to</span> <span m=''3963770''>the</span>
  <span m=''3963930''>M</span> <span m=''3964070''>sample</span> <span m=''3964470''>points,</span>
  <span m=''3964890''>each</span> <span m=''3965150''>a</span> <span m=''3965220''>probability</span>
  <span m=''3965850''>1</span> <span m=''3966150''>over</span> <span m=''3966540''>N</span>
  <span m=''3966720''>to</span> <span m=''3966800''>the</span> <span m=''3966970''>M.</span>
  <span m=''3968000''>So</span> <span m=''3968140''>they</span> <span m=''3968300''>all</span>
  <span m=''3968500''>add</span> <span m=''3968610''>up</span> <span m=''3968720''>to</span>
  <span m=''3968820''>1,</span> <span m=''3970490''>which</span> <span m=''3970710''>is</span>
  <span m=''3970820''>good.</span> </p><p><span m=''3971920''>What</span> <span m=''3972170''>kind</span>
  <span m=''3972370''>of</span> <span m=''3972440''>sample</span> <span m=''3972810''>space</span>
  <span m=''3973140''>is</span> <span m=''3973260''>this</span> <span m=''3973550''>where</span>
  <span m=''3973650''>this</span> <span m=''3973820''>happens</span> <span m=''3974190''>where</span>
  <span m=''3974340''>all</span> <span m=''3974460''>the</span> <span m=''3974530''>probabilities</span>
  <span m=''3975040''>are</span> <span m=''3975070''>the</span> <span m=''3975160''>same?</span>
  </p><p><span m=''3975530''>AUDIENCE:</span> <span m=''3975916''>Uniform.</span>
  </p><p><span m=''3976302''>TOM LEIGHTON:</span> <span m=''3976690''>Uniform.</span>
  <span m=''3977580''>Makes</span> <span m=''3977780''>it</span> <span m=''3977870''>very</span>
  <span m=''3978210''>easy</span> <span m=''3978315''>to</span> <span m=''3978420''>work</span>
  <span m=''3978810''>with.</span> <span m=''3979080''>All</span> <span m=''3979130''>we</span>
  <span m=''3979180''>got</span> <span m=''3979230''>to</span> <span m=''3979310''>do</span>
  <span m=''3979470''>now</span> <span m=''3979770''>is</span> <span m=''3979880''>just</span>
  <span m=''3980470''>count</span> <span m=''3981240''>the</span> <span m=''3981330''>number</span>
  <span m=''3981550''>of</span> <span m=''3981610''>sample</span> <span m=''3981980''>points</span>
  <span m=''3982830''>where</span> <span m=''3982940''>there''s</span> <span m=''3983110''>a</span>
  <span m=''3983160''>matching</span> <span m=''3983520''>birthday</span> <span m=''3985350''>and</span>
  <span m=''3985480''>then</span> <span m=''3985590''>we</span> <span m=''3985690''>multiply</span>
  <span m=''3986170''>by</span> <span m=''3986770''>that</span> <span m=''3986960''>one</span>
  <span m=''3987130''>probability</span> <span m=''3987560''>1</span> <span m=''3987770''>over</span>
  <span m=''3987950''>N</span> <span m=''3988100''>to</span> <span m=''3988180''>the</span>
  <span m=''3988320''>M.</span> </p><p><span m=''3990830''>Now,</span> <span m=''3991450''>it</span>
  <span m=''3991640''>turns</span> <span m=''3991990''>out</span> <span m=''3992280''>that</span>
  <span m=''3992640''>rather</span> <span m=''3992990''>than</span> <span m=''3993340''>counting</span>
  <span m=''3993780''>the</span> <span m=''3993870''>number</span> <span m=''3994360''>of</span>
  <span m=''3994440''>sample</span> <span m=''3994840''>points</span> <span m=''3995240''>where</span>
  <span m=''3995340''>there''s</span> <span m=''3995500''>a</span> <span m=''3995550''>matching</span>
  <span m=''3996000''>birthday,</span> <span m=''3997180''>it''s</span> <span m=''3997420''>easier</span>
  <span m=''3998300''>to</span> <span m=''3998490''>count</span> <span m=''3998920''>the</span>
  <span m=''3999040''>number</span> <span m=''3999310''>of</span> <span m=''3999380''>sample</span>
  <span m=''3999740''>points</span> <span m=''4000080''>for</span> <span m=''4000190''>all</span>
  <span m=''4000500''>the</span> <span m=''4000580''>birthdays</span> <span m=''4001290''>are</span>
  <span m=''4001430''>different.</span> <span m=''4003095''>And</span> <span m=''4003490''>this</span>
  <span m=''4003730''>is</span> <span m=''4003820''>often</span> <span m=''4004190''>the</span>
  <span m=''4004280''>case</span> <span m=''4004580''>when</span> <span m=''4004660''>you''re</span>
  <span m=''4004750''>doing</span> <span m=''4004940''>a</span> <span m=''4005195''>counting</span>
  <span m=''4005450''>problem,</span> <span m=''4007470''>it''s</span> <span m=''4008100''>easier</span>
  <span m=''4008460''>to</span> <span m=''4008560''>count</span> <span m=''4008900''>the</span>
  <span m=''4009040''>opposite</span> <span m=''4009740''>of</span> <span m=''4009940''>what</span>
  <span m=''4010220''>you''re</span> <span m=''4010400''>after.</span> <span m=''4012100''>That</span>
  <span m=''4012300''>can</span> <span m=''4012450''>be</span> <span m=''4012640''>the</span>
  <span m=''4012760''>case</span> <span m=''4013150''>and</span> <span m=''4013280''>it</span>
  <span m=''4013340''>is</span> <span m=''4013530''>the</span> <span m=''4013610''>case</span>
  <span m=''4013900''>here.</span> <span m=''4014420''>So</span> <span m=''4014720''>we''re</span>
  <span m=''4014760''>going</span> <span m=''4015010''>to</span> <span m=''4015260''>do</span>
  <span m=''4015760''>that.</span> </p><p><span m=''4019680''>So</span> <span m=''4022130''>let''s</span>
  <span m=''4022480''>count</span> <span m=''4023240''>how</span> <span m=''4023540''>many</span>
  <span m=''4023780''>sample</span> <span m=''4024230''>points</span> <span m=''4025240''>are</span>
  <span m=''4025480''>all</span> <span m=''4026600''>different</span> <span m=''4027340''>birthdays,</span>
  <span m=''4028590''>so</span> <span m=''4028830''>no</span> <span m=''4029540''>pair</span>
  <span m=''4029890''>of</span> <span m=''4029980''>bi''s</span> <span m=''4030410''>is</span>
  <span m=''4030640''>the</span> <span m=''4030740''>same.</span> <span m=''4032130''>Let''s</span>
  <span m=''4032390''>do</span> <span m=''4032520''>that.</span> <span m=''4033180''>How</span>
  <span m=''4033360''>many</span> <span m=''4033590''>choices</span> <span m=''4034130''>are</span>
  <span m=''4034280''>there</span> <span m=''4034490''>for</span> <span m=''4034630''>b1?</span>
  <span m=''4035724''>365</span> <span m=''4038410''>or</span> <span m=''4038860''>N.</span>
  <span m=''4039540''>Let''s</span> <span m=''4039700''>do</span> <span m=''4039760''>this</span>
  <span m=''4039820''>in</span> <span m=''4039890''>terms</span> <span m=''4040100''>of</span>
  <span m=''4040190''>N</span> <span m=''4040480''>because</span> <span m=''4040515''>we''re</span>
  <span m=''4040550''>going</span> <span m=''4040640''>to</span> <span m=''4040680''>use</span>
  <span m=''4040930''>this</span> <span m=''4041110''>for</span> <span m=''4041200''>general</span>
  <span m=''4041530''>N.</span> </p><p><span m=''4042400''>How</span> <span m=''4042560''>many</span>
  <span m=''4042730''>choices</span> <span m=''4043140''>for</span> <span m=''4043270''>b2?</span>
  <span m=''4045470''>N</span> <span m=''4045720''>minus</span> <span m=''4046120''>1.</span>
  <span m=''4046360''>Given</span> <span m=''4046550''>you</span> <span m=''4046820''>are</span>
  <span m=''4046880''>the</span> <span m=''4046990''>first</span> <span m=''4047280''>one,</span>
  <span m=''4047340''>you</span> <span m=''4047460''>can''t</span> <span m=''4047750''>match</span>
  <span m=''4048050''>it.</span> <span m=''4048950''>And</span> <span m=''4049060''>then</span>
  <span m=''4049220''>N</span> <span m=''4049390''>minus</span> <span m=''4049750''>2</span>
  <span m=''4052540''>all</span> <span m=''4052643''>the</span> <span m=''4052746''>way</span>
  <span m=''4052850''>over</span> <span m=''4052960''>to</span> <span m=''4053020''>the</span>
  <span m=''4053080''>last</span> <span m=''4053470''>one</span> <span m=''4053570''>is</span>
  <span m=''4053690''>N</span> <span m=''4053870''>minus</span> <span m=''4054230''>M</span>
  <span m=''4055260''>plus</span> <span m=''4055510''>1.</span> <span m=''4057360''>And</span>
  <span m=''4057690''>this</span> <span m=''4057890''>is</span> <span m=''4057990''>a</span>
  <span m=''4058050''>formula</span> <span m=''4058380''>you</span> <span m=''4058545''>should</span>
  <span m=''4058710''>all</span> <span m=''4059660''>remember.</span> <span m=''4061050''>That''s</span>
  <span m=''4061230''>just</span> <span m=''4061660''>N</span> <span m=''4061880''>factorial</span>
  <span m=''4062560''>over</span> <span m=''4062790''>N</span> <span m=''4063010''>minus</span>
  <span m=''4063400''>M</span> <span m=''4064620''>factorial.</span> <span m=''4066430''>You</span>
  <span m=''4066590''>did</span> <span m=''4066790''>this</span> <span m=''4066940''>sort</span>
  <span m=''4067100''>of</span> <span m=''4067170''>stuff</span> <span m=''4068030''>a</span>
  <span m=''4068090''>couple</span> <span m=''4068350''>weeks</span> <span m=''4068580''>ago</span>
  <span m=''4068740''>with</span> <span m=''4068870''>counting</span> <span m=''4069300''>sets</span>
  <span m=''4069810''>and</span> <span m=''4069960''>probability</span> <span m=''4070490''>is</span>
  <span m=''4070620''>really--</span> <span m=''4071410''>a</span> <span m=''4071460''>lot</span>
  <span m=''4071640''>of</span> <span m=''4071710''>it''s</span> <span m=''4071850''>about</span>
  <span m=''4072120''>counting.</span> </p><p><span m=''4074250''>So</span> <span
  m=''4074460''>now</span> <span m=''4074690''>we</span> <span m=''4074800''>can</span>
  <span m=''4074930''>compute</span> <span m=''4075550''>the</span> <span m=''4075660''>probability</span>
  <span m=''4076280''>that</span> <span m=''4076450''>all</span> <span m=''4076820''>the</span>
  <span m=''4076900''>birthdays</span> <span m=''4077450''>are</span> <span m=''4077500''>different.</span>
  <span m=''4084630''>It''s</span> <span m=''4084880''>just</span> <span m=''4085230''>adding</span>
  <span m=''4085610''>up</span> <span m=''4087090''>all</span> <span m=''4087320''>the</span>
  <span m=''4087410''>sample</span> <span m=''4087750''>points</span> <span m=''4087990''>of</span>
  <span m=''4088230''>which</span> <span m=''4088450''>there''s</span> <span m=''4088660''>n</span>
  <span m=''4088840''>factorial</span> <span m=''4089580''>over</span> <span m=''4090620''>N</span>
  <span m=''4090820''>minus</span> <span m=''4091240''>M</span> <span m=''4091410''>factorial</span>
  <span m=''4092870''>and</span> <span m=''4093500''>multiply</span> <span m=''4094080''>by</span>
  <span m=''4094210''>the</span> <span m=''4094320''>probability</span> <span m=''4094840''>of</span>
  <span m=''4094920''>each</span> <span m=''4095100''>one,</span> <span m=''4096310''>which</span>
  <span m=''4096529''>is</span> <span m=''4096630''>1</span> <span m=''4096870''>over</span>
  <span m=''4097090''>N</span> <span m=''4097290''>to</span> <span m=''4097350''>the</span>
  <span m=''4097529''>M.</span> <span m=''4102069''>All</span> <span m=''4102170''>right.</span>
  <span m=''4102430''>So</span> <span m=''4102740''>we''ve</span> <span m=''4102990''>actually</span>
  <span m=''4103260''>now</span> <span m=''4103490''>answered</span> <span m=''4104170''>the</span>
  <span m=''4104250''>question.</span> <span m=''4104630''>This</span> <span m=''4104800''>is</span>
  <span m=''4104880''>the</span> <span m=''4104979''>probability</span> <span m=''4106359''>that</span>
  <span m=''4106450''>all</span> <span m=''4106700''>the</span> <span m=''4106790''>birthdays</span>
  <span m=''4107229''>are</span> <span m=''4107290''>different.</span> </p><p><span
  m=''4108670''>The</span> <span m=''4108770''>only</span> <span m=''4108939''>problem</span>
  <span m=''4109300''>is,</span> <span m=''4109560''>it''s</span> <span m=''4109720''>not</span>
  <span m=''4109939''>so</span> <span m=''4110149''>clear</span> <span m=''4112560''>what</span>
  <span m=''4112819''>the</span> <span m=''4112960''>answer</span> <span m=''4113359''>is</span>
  <span m=''4113580''>to</span> <span m=''4113760''>actually</span> <span m=''4114069''>compute</span>
  <span m=''4114479''>this</span> <span m=''4114720''>or</span> <span m=''4114790''>how</span>
  <span m=''4115270''>fast</span> <span m=''4115689''>it</span> <span m=''4115760''>grows.</span>
  <span m=''4117250''>So</span> <span m=''4117410''>if</span> <span m=''4117500''>I</span>
  <span m=''4117550''>wanted</span> <span m=''4117880''>to</span> <span m=''4117950''>get</span>
  <span m=''4118170''>a</span> <span m=''4119310''>closed</span> <span m=''4119760''>form</span>
  <span m=''4120109''>for</span> <span m=''4120210''>this</span> <span m=''4120410''>without</span>
  <span m=''4120640''>the</span> <span m=''4120720''>factorials,</span> <span m=''4122170''>what</span>
  <span m=''4122319''>do</span> <span m=''4122420''>I</span> <span m=''4122510''>do?</span>
  <span m=''4122979''>What</span> <span m=''4123109''>do</span> <span m=''4123189''>I</span>
  <span m=''4123270''>use?</span> <span m=''4125200''>Stirling''s</span> <span m=''4125790''>formula.</span>
  </p><p><span m=''4128310''>So</span> <span m=''4128720''>let''s</span> <span m=''4128859''>remember</span>
  <span m=''4129100''>that.</span> <span m=''4137630''>It</span> <span m=''4137770''>says</span>
  <span m=''4138090''>that</span> <span m=''4138200''>N</span> <span m=''4138370''>factorial</span>
  <span m=''4140200''>is</span> <span m=''4140680''>asymptotically</span> <span m=''4141510''>equal</span>
  <span m=''4141870''>to</span> <span m=''4142240''>square</span> <span m=''4142609''>root</span>
  <span m=''4142819''>2</span> <span m=''4143010''>pi</span> <span m=''4143340''>N</span>
  <span m=''4144990''>times</span> <span m=''4146010''>N</span> <span m=''4146229''>over</span>
  <span m=''4146520''>e</span> <span m=''4147779''>to</span> <span m=''4147850''>the</span>
  <span m=''4148000''>N.</span> <span m=''4149830''>And</span> <span m=''4150240''>that</span>
  <span m=''4150460''>is</span> <span m=''4150670''>accurate</span> <span m=''4151660''>within</span>
  <span m=''4152000''>0.1%</span> <span m=''4153680''>when</span> <span m=''4154229''>N</span>
  <span m=''4154430''>is</span> <span m=''4154550''>at</span> <span m=''4154630''>least</span>
  <span m=''4154850''>100.</span> <span m=''4155529''>So</span> <span m=''4155899''>not</span>
  <span m=''4155960''>only</span> <span m=''4156330''>is</span> <span m=''4156520''>it</span>
  <span m=''4156779''>asymptotically</span> <span m=''4157510''>equal,</span> <span
  m=''4158240''>it''s</span> <span m=''4158550''>right</span> <span m=''4158960''>on</span>
  <span m=''4159149''>track</span> <span m=''4160200''>for</span> <span m=''4160300''>a</span>
  <span m=''4160370''>reasonable</span> <span m=''4160680''>size</span> <span m=''4161162''>N.</span>
  </p><p><span m=''4165020''>Now,</span> <span m=''4165600''>I</span> <span m=''4165740''>won''t</span>
  <span m=''4166140''>drag</span> <span m=''4166500''>you</span> <span m=''4166590''>through</span>
  <span m=''4166810''>all</span> <span m=''4167109''>the</span> <span m=''4167200''>calculations.</span>
  <span m=''4167899''>I</span> <span m=''4168229''>used</span> <span m=''4168430''>to</span>
  <span m=''4168500''>actually</span> <span m=''4168790''>try</span> <span m=''4169859''>plugging</span>
  <span m=''4170240''>that</span> <span m=''4170470''>formula</span> <span m=''4170850''>in</span>
  <span m=''4171115''>for</span> <span m=''4171380''>here</span> <span m=''4171630''>and</span>
  <span m=''4171689''>here</span> <span m=''4172380''>and</span> <span m=''4172490''>then</span>
  <span m=''4172680''>going</span> <span m=''4173050''>through</span> <span m=''4173250''>all</span>
  <span m=''4173510''>the</span> <span m=''4173609''>calculations,</span> <span m=''4174410''>but</span>
  <span m=''4174430''>we</span> <span m=''4174529''>won''t</span> <span m=''4174890''>do</span>
  <span m=''4175029''>it</span> <span m=''4175080''>in</span> <span m=''4175160''>class.</span>
  <span m=''4175440''>It''s</span> <span m=''4175720''>in</span> <span m=''4175790''>the</span>
  <span m=''4175899''>text.</span> <span m=''4177300''>But</span> <span m=''4177350''>I</span>
  <span m=''4177399''>will</span> <span m=''4177560''>tell</span> <span m=''4177729''>you</span>
  <span m=''4177859''>where</span> <span m=''4177970''>that</span> <span m=''4178180''>winds</span>
  <span m=''4178510''>up.</span> <span m=''4180620''>It''s</span> <span m=''4180790''>not</span>
  <span m=''4180930''>hard,</span> <span m=''4181210''>you''ve</span> <span m=''4181290''>just</span>
  <span m=''4181420''>got</span> <span m=''4181540''>to</span> <span m=''4181660''>do</span>
  <span m=''4181930''>the</span> <span m=''4182200''>calculation.</span> </p><p><span
  m=''4188160''>So</span> <span m=''4188330''>this</span> <span m=''4188580''>is</span>
  <span m=''4188790''>means</span> <span m=''4188815''>the</span> <span m=''4188840''>probability</span>
  <span m=''4189359''>that</span> <span m=''4190670''>all</span> <span m=''4190950''>birthdays</span>
  <span m=''4191380''>are</span> <span m=''4191430''>different</span> <span m=''4198350''>turns</span>
  <span m=''4198710''>out</span> <span m=''4198990''>to</span> <span m=''4199080''>be</span>
  <span m=''4200030''>asymptotically</span> <span m=''4201000''>equal</span> <span
  m=''4201350''>to</span> <span m=''4202820''>e</span> <span m=''4204830''>to</span>
  <span m=''4205180''>the</span> <span m=''4205880''>N</span> <span m=''4206130''>minus</span>
  <span m=''4206530''>M</span> <span m=''4207080''>plus</span> <span m=''4208510''>1/2</span>
  <span m=''4211100''>times</span> <span m=''4211700''>the</span> <span m=''4211810''>natural</span>
  <span m=''4212280''>log</span> <span m=''4214030''>of</span> <span m=''4214360''>N</span>
  <span m=''4215000''>over</span> <span m=''4215340''>N</span> <span m=''4215530''>minus</span>
  <span m=''4215910''>M</span> <span m=''4218300''>minus</span> <span m=''4219130''>M.</span>
  <span m=''4220890''>And</span> <span m=''4221060''>that''s</span> <span m=''4221340''>accurate</span>
  <span m=''4221565''>to</span> <span m=''4221790''>within</span> <span m=''4222050''>0.2%,</span>
  <span m=''4223670''>if</span> <span m=''4223870''>N</span> <span m=''4224036''>and</span>
  <span m=''4224203''>N</span> <span m=''4224370''>minus</span> <span m=''4224700''>M</span>
  <span m=''4224840''>are</span> <span m=''4224900''>large,</span> <span m=''4225270''>larger</span>
  <span m=''4225510''>than</span> <span m=''4225590''>100.</span> <span m=''4225950''>So</span>
  <span m=''4226360''>in</span> <span m=''4226450''>fact,</span> <span m=''4226880''>it''s</span>
  <span m=''4227310''>almost</span> <span m=''4228020''>equal.</span> </p><p><span
  m=''4229830''>And</span> <span m=''4229950''>now</span> <span m=''4230090''>you</span>
  <span m=''4230230''>could</span> <span m=''4230400''>plug</span> <span m=''4230880''>in</span>
  <span m=''4232220''>N</span> <span m=''4232440''>equals</span> <span m=''4232780''>365</span>
  <span m=''4233840''>and</span> <span m=''4233960''>M</span> <span m=''4234150''>equals</span>
  <span m=''4234390''>100.</span> <span m=''4236650''>So</span> <span m=''4236820''>if</span>
  <span m=''4236890''>you</span> <span m=''4236990''>do</span> <span m=''4237170''>that,</span>
  <span m=''4240490''>in</span> <span m=''4240690''>fact,</span> <span m=''4240930''>if</span>
  <span m=''4241010''>somebody</span> <span m=''4241090''>has</span> <span m=''4241280''>a</span>
  <span m=''4241340''>calculator,</span> <span m=''4241950''>we</span> <span m=''4242030''>should</span>
  <span m=''4242200''>plug</span> <span m=''4242525''>in,</span> <span m=''4242850''>what</span>
  <span m=''4243280''>do</span> <span m=''4243430''>we</span> <span m=''4243560''>have,</span>
  <span m=''4245600''>42.</span> <span m=''4245950''>You</span> <span m=''4246125''>should</span>
  <span m=''4246300''>plug</span> <span m=''4246480''>in</span> <span m=''4246570''>M</span>
  <span m=''4246660''>equals</span> <span m=''4247260''>42</span> <span m=''4247740''>and</span>
  <span m=''4247850''>see</span> <span m=''4248020''>what</span> <span m=''4248180''>the</span>
  <span m=''4248280''>probability</span> <span m=''4248770''>is.</span> <span m=''4250300''>But</span>
  <span m=''4250420''>if</span> <span m=''4250510''>M</span> <span m=''4250690''>is</span>
  <span m=''4250790''>100,</span> <span m=''4251990''>the</span> <span m=''4252090''>chance</span>
  <span m=''4252680''>that</span> <span m=''4253770''>we''re</span> <span m=''4253980''>all</span>
  <span m=''4254230''>different,</span> <span m=''4256330''>this</span> <span m=''4256600''>equals</span>
  <span m=''4257220''>3.07</span> <span m=''4259320''>dot,</span> <span m=''4259470''>dot,</span>
  <span m=''4259640''>dot</span> <span m=''4260530''>times</span> <span m=''4260900''>10</span>
  <span m=''4261680''>to</span> <span m=''4262190''>the</span> <span m=''4262290''>minus</span>
  <span m=''4262700''>7.</span> <span m=''4265150''>And</span> <span m=''4265270''>we</span>
  <span m=''4265360''>should</span> <span m=''4265550''>check</span> <span m=''4265900''>for</span>
  <span m=''4266040''>M</span> <span m=''4266250''>equals</span> <span m=''4266540''>42.</span>
  <span m=''4267720''>My</span> <span m=''4267840''>guess</span> <span m=''4268080''>is</span>
  <span m=''4268170''>it''s</span> <span m=''4268380''>pretty</span> <span m=''4268770''>small,</span>
  <span m=''4269510''>but</span> <span m=''4269630''>I</span> <span m=''4269950''>don''t</span>
  <span m=''4270015''>know.</span> <span m=''4270080''>We''ll</span> <span m=''4270145''>have</span>
  <span m=''4270210''>to</span> <span m=''4270320''>check</span> <span m=''4270580''>that.</span>
  </p><p><span m=''4271351''>AUDIENCE:</span> <span m=''4271822''>0.0859.</span> </p><p><span
  m=''4274648''>TOM LEIGHTON:</span> <span m=''4275120''>Great.</span> <span m=''4275540''>So</span>
  <span m=''4276670''>a</span> <span m=''4276750''>9%</span> <span m=''4277520''>chance</span>
  <span m=''4278460''>of</span> <span m=''4279390''>having</span> <span m=''4279630''>42</span>
  <span m=''4280100''>people</span> <span m=''4280365''>all</span> <span m=''4280630''>miss</span>
  <span m=''4281020''>is</span> <span m=''4281055''>a</span> <span m=''4281090''>9%</span>
  <span m=''4281660''>chance.</span> <span m=''4282190''>So</span> <span m=''4282240''>we</span>
  <span m=''4282340''>were</span> <span m=''4282470''>little</span> <span m=''4283070''>unlucky.</span>
  <span m=''4283480''>That</span> <span m=''4283650''>won''t</span> <span m=''4283830''>happen</span>
  <span m=''4284170''>very</span> <span m=''4284610''>often.</span> <span m=''4285770''>But</span>
  <span m=''4285990''>when</span> <span m=''4286080''>you</span> <span m=''4286160''>go</span>
  <span m=''4286340''>from</span> <span m=''4286470''>42</span> <span m=''4286920''>to</span>
  <span m=''4287020''>100,</span> <span m=''4287430''>it</span> <span m=''4287490''>gets</span>
  <span m=''4287700''>really</span> <span m=''4288280''>small.</span> <span m=''4289720''>1</span>
  <span m=''4290070''>in</span> <span m=''4290545''>3</span> <span m=''4290663''>million</span>
  <span m=''4290782''>or</span> <span m=''4290901''>so.</span> <span m=''4293870''>Now,</span>
  <span m=''4294630''>if</span> <span m=''4294840''>N</span> <span m=''4295160''>is</span>
  <span m=''4295480''>365</span> <span m=''4296360''>and</span> <span m=''4296710''>M</span>
  <span m=''4296770''>is</span> <span m=''4296830''>23,</span> <span m=''4299160''>the</span>
  <span m=''4299270''>probability</span> <span m=''4299840''>comes</span> <span m=''4300110''>out</span>
  <span m=''4300310''>to</span> <span m=''4300390''>be</span> <span m=''4300540''>about</span>
  <span m=''4300970''>0.49,</span> <span m=''4303330''>so</span> <span m=''4303510''>about</span>
  <span m=''4303830''>50-50,</span> <span m=''4304190''>they''re</span> <span m=''4305142''>all</span>
  <span m=''4305618''>different.</span> </p><p><span m=''4310810''>Now.</span> <span
  m=''4311040''>For</span> <span m=''4311220''>general</span> <span m=''4311730''>M</span>
  <span m=''4311896''>and</span> <span m=''4312063''>N,</span> <span m=''4312230''>we''d</span>
  <span m=''4312390''>like</span> <span m=''4312610''>to</span> <span m=''4312730''>know</span>
  <span m=''4314210''>when</span> <span m=''4314620''>do</span> <span m=''4314690''>you</span>
  <span m=''4314810''>get</span> <span m=''4314960''>to</span> <span m=''4315020''>the</span>
  <span m=''4315140''>50-50</span> <span m=''4315760''>point?</span> <span m=''4316640''>We''d</span>
  <span m=''4316730''>like</span> <span m=''4316850''>to</span> <span m=''4316940''>derive</span>
  <span m=''4317400''>an</span> <span m=''4317450''>equation</span> <span m=''4318190''>for</span>
  <span m=''4318430''>M</span> <span m=''4318880''>in</span> <span m=''4319050''>terms</span>
  <span m=''4319430''>of</span> <span m=''4319520''>N</span> <span m=''4320550''>where</span>
  <span m=''4320640''>the</span> <span m=''4320760''>probability</span> <span m=''4321370''>of</span>
  <span m=''4321420''>being</span> <span m=''4321580''>all</span> <span m=''4321770''>different</span>
  <span m=''4322120''>is</span> <span m=''4322240''>about</span> <span m=''4322530''>1/2.</span>
  <span m=''4324590''>All</span> <span m=''4324680''>right.</span> <span m=''4324850''>So</span>
  <span m=''4324940''>let''s</span> <span m=''4325120''>do</span> <span m=''4325240''>that.</span>
  <span m=''4336270''>So</span> <span m=''4339460''>as</span> <span m=''4339590''>long</span>
  <span m=''4339810''>as</span> <span m=''4339900''>we</span> <span m=''4340160''>assume--</span>
  <span m=''4340780''>and</span> <span m=''4340880''>this</span> <span m=''4341040''>will</span>
  <span m=''4341280''>turn</span> <span m=''4341385''>out</span> <span m=''4341490''>to</span>
  <span m=''4341600''>be</span> <span m=''4341670''>true--</span> <span m=''4342500''>that</span>
  <span m=''4342640''>M</span> <span m=''4342890''>is</span> <span m=''4342950''>a</span>
  <span m=''4343010''>little</span> <span m=''4343400''>o</span> <span m=''4343600''>of</span>
  <span m=''4343750''>N</span> <span m=''4343910''>to</span> <span m=''4343960''>the</span>
  <span m=''4344060''>2/3</span> <span m=''4344830''>and</span> <span m=''4344960''>remember</span>
  <span m=''4345250''>little</span> <span m=''4345500''>o</span> <span m=''4345740''>means</span>
  <span m=''4345990''>it</span> <span m=''4346070''>grows</span> <span m=''4346360''>slower</span>
  <span m=''4347070''>than</span> <span m=''4347420''>N</span> <span m=''4347630''>to</span>
  <span m=''4347690''>the</span> <span m=''4347780''>2/3.</span> <span m=''4350190''>Then</span>
  <span m=''4350250''>we</span> <span m=''4350350''>can</span> <span m=''4350490''>simplify</span>
  <span m=''4351070''>that</span> <span m=''4351250''>expression</span> <span m=''4352230''>in</span>
  <span m=''4352390''>asymptotic</span> <span m=''4353030''>notation.</span> </p><p><span
  m=''4355240''>And</span> <span m=''4355390''>when</span> <span m=''4355520''>you</span>
  <span m=''4355620''>do</span> <span m=''4355900''>it,</span> <span m=''4358570''>I</span>
  <span m=''4358700''>won''t</span> <span m=''4358990''>drag</span> <span m=''4359240''>it</span>
  <span m=''4359310''>through</span> <span m=''4359490''>on</span> <span m=''4359600''>the</span>
  <span m=''4359670''>board.</span> <span m=''4360405''>It''s</span> <span m=''4360670''>also</span>
  <span m=''4360970''>in</span> <span m=''4361055''>the</span> <span m=''4361140''>text,</span>
  <span m=''4362510''>it</span> <span m=''4362870''>turns</span> <span m=''4363220''>out</span>
  <span m=''4363400''>to</span> <span m=''4363460''>be</span> <span m=''4363610''>much</span>
  <span m=''4363860''>simpler.</span> <span m=''4365030''>It''s</span> <span m=''4365200''>just</span>
  <span m=''4365460''>e</span> <span m=''4365700''>to</span> <span m=''4365760''>the</span>
  <span m=''4365860''>minus</span> <span m=''4366450''>M</span> <span m=''4366650''>squared</span>
  <span m=''4367730''>over</span> <span m=''4367950''>2N.</span> <span m=''4369900''>So</span>
  <span m=''4370030''>I</span> <span m=''4370110''>take</span> <span m=''4370390''>that</span>
  <span m=''4370590''>thing</span> <span m=''4370770''>up</span> <span m=''4370910''>there</span>
  <span m=''4371130''>and</span> <span m=''4371230''>I</span> <span m=''4371820''>assume</span>
  <span m=''4372300''>that</span> <span m=''4372500''>M</span> <span m=''4372820''>is</span>
  <span m=''4373790''>growing</span> <span m=''4374500''>less</span> <span m=''4374810''>fast</span>
  <span m=''4375200''>than</span> <span m=''4375300''>the</span> <span m=''4375390''>2/3</span>
  <span m=''4375810''>power</span> <span m=''4376140''>of</span> <span m=''4376220''>N</span>
  <span m=''4377400''>and</span> <span m=''4377540''>that</span> <span m=''4377700''>whole</span>
  <span m=''4377990''>upper</span> <span m=''4378260''>expression</span> <span m=''4378770''>reduces</span>
  <span m=''4379250''>down</span> <span m=''4379500''>to</span> <span m=''4379590''>M</span>
  <span m=''4379790''>squared</span> <span m=''4380100''>over</span> <span m=''4380260''>2N.</span>
  <span m=''4381110''>Everything</span> <span m=''4381420''>else</span> <span m=''4381860''>goes</span>
  <span m=''4382120''>to</span> <span m=''4382210''>0</span> <span m=''4382970''>in</span>
  <span m=''4383080''>the</span> <span m=''4383160''>exponent.</span> <span m=''4384310''>Doesn''t</span>
  <span m=''4384590''>matter.</span> </p><p><span m=''4386260''>Now,</span> <span
  m=''4386960''>if</span> <span m=''4387110''>I</span> <span m=''4387180''>set</span>
  <span m=''4387530''>this</span> <span m=''4387740''>to</span> <span m=''4387840''>be</span>
  <span m=''4388070''>1/2,</span> <span m=''4391670''>I</span> <span m=''4391810''>can</span>
  <span m=''4391970''>solve</span> <span m=''4392490''>this</span> <span m=''4392760''>to</span>
  <span m=''4392850''>find</span> <span m=''4393130''>out</span> <span m=''4393310''>what</span>
  <span m=''4393530''>M</span> <span m=''4393785''>has</span> <span m=''4394040''>to</span>
  <span m=''4394130''>be</span> <span m=''4394800''>to</span> <span m=''4394920''>make</span>
  <span m=''4395110''>that</span> <span m=''4395290''>be</span> <span m=''4395430''>1/2.</span>
  <span m=''4397740''>All</span> <span m=''4397870''>right.</span> <span m=''4398110''>So</span>
  <span m=''4398210''>this</span> <span m=''4398310''>will</span> <span m=''4398470''>be</span>
  <span m=''4398580''>true</span> <span m=''4400230''>if</span> <span m=''4400390''>and</span>
  <span m=''4400470''>only</span> <span m=''4400810''>if</span> <span m=''4401080''>minus</span>
  <span m=''4401640''>M</span> <span m=''4401830''>squared</span> <span m=''4402840''>over</span>
  <span m=''4403080''>2N</span> <span m=''4404710''>is</span> <span m=''4404870''>equal</span>
  <span m=''4405170''>to</span> <span m=''4405265''>the</span> <span m=''4405360''>natural</span>
  <span m=''4405800''>log</span> <span m=''4406140''>of</span> <span m=''4406220''>1/2.</span>
  <span m=''4409610''>And</span> <span m=''4409900''>that''s</span> <span m=''4410200''>true.</span>
  <span m=''4411040''>Take</span> <span m=''4411220''>the</span> <span m=''4411290''>minus</span>
  <span m=''4411670''>sign,</span> <span m=''4412250''>put</span> <span m=''4412345''>it</span>
  <span m=''4412440''>inside</span> <span m=''4412700''>to</span> <span m=''4412960''>make</span>
  <span m=''4413045''>a</span> <span m=''4413130''>log</span> <span m=''4413490''>of</span>
  <span m=''4413590''>2,</span> <span m=''4414820''>multiply</span> <span m=''4415240''>by</span>
  <span m=''4415410''>2N.</span> <span m=''4416580''>That''s</span> <span m=''4416850''>true</span>
  <span m=''4417100''>if</span> <span m=''4417200''>M</span> <span m=''4417250''>squared</span>
  <span m=''4417720''>equals</span> <span m=''4418310''>2N</span> <span m=''4420510''>natural</span>
  <span m=''4420920''>log</span> <span m=''4421180''>of</span> <span m=''4421290''>2.</span>
  </p><p><span m=''4423590''>And</span> <span m=''4423780''>now</span> <span m=''4424010''>I</span>
  <span m=''4424075''>can</span> <span m=''4424140''>solve</span> <span m=''4424520''>for</span>
  <span m=''4424650''>M</span> <span m=''4424880''>really</span> <span m=''4425200''>easily.</span>
  <span m=''4426800''>That''s</span> <span m=''4427100''>true</span> <span m=''4428570''>if</span>
  <span m=''4428770''>and</span> <span m=''4428850''>only</span> <span m=''4429150''>if</span>
  <span m=''4430350''>M</span> <span m=''4431660''>equals</span> <span m=''4433090''>the</span>
  <span m=''4433280''>square</span> <span m=''4433790''>root</span> <span m=''4434410''>of</span>
  <span m=''4434550''>2</span> <span m=''4435210''>natural</span> <span m=''4435610''>log</span>
  <span m=''4435810''>of</span> <span m=''4435900''>2N,</span> <span m=''4438090''>which</span>
  <span m=''4438360''>is</span> <span m=''4438530''>about</span> <span m=''4439420''>1.177</span>
  <span m=''4441172''>square</span> <span m=''4441610''>root</span> <span m=''4442083''>of</span>
  <span m=''4442556''>N.</span> <span m=''4445870''>So</span> <span m=''4446060''>for</span>
  <span m=''4446200''>general</span> <span m=''4446790''>N,</span> <span m=''4448560''>you</span>
  <span m=''4448700''>get</span> <span m=''4448910''>a</span> <span m=''4448960''>50%</span>
  <span m=''4449720''>probability</span> <span m=''4451200''>of</span> <span m=''4451370''>having</span>
  <span m=''4451680''>a</span> <span m=''4451730''>matching</span> <span m=''4452250''>birthday</span>
  <span m=''4453710''>when</span> <span m=''4454020''>M</span> <span m=''4454440''>is</span>
  <span m=''4454620''>in</span> <span m=''4454720''>this</span> <span m=''4454920''>range,</span>
  <span m=''4457780''>pretty</span> <span m=''4458030''>close</span> <span m=''4458330''>to</span>
  <span m=''4458450''>1.2</span> <span m=''4459270''>square</span> <span m=''4459570''>root</span>
  <span m=''4459650''>of</span> <span m=''4459740''>N.</span> </p><p><span m=''4461920''>Now,</span>
  <span m=''4462360''>this</span> <span m=''4462660''>square</span> <span m=''4463080''>root</span>
  <span m=''4463290''>N</span> <span m=''4463670''>phenomenon,</span> <span m=''4464440''>this</span>
  <span m=''4464660''>thing</span> <span m=''4464850''>here,</span> <span m=''4465490''>that''s</span>
  <span m=''4465740''>what''s</span> <span m=''4465940''>known</span> <span m=''4466130''>as</span>
  <span m=''4466230''>the</span> <span m=''4466310''>birthday</span> <span m=''4466650''>principle.</span>
  <span m=''4469630''>It</span> <span m=''4469770''>says</span> <span m=''4470100''>if</span>
  <span m=''4470240''>you''ve</span> <span m=''4470350''>got</span> <span m=''4471490''>roughly</span>
  <span m=''4471900''>square</span> <span m=''4472260''>root</span> <span m=''4472360''>of</span>
  <span m=''4472460''>N</span> <span m=''4472670''>randomly</span> <span m=''4473250''>allocated</span>
  <span m=''4473800''>items</span> <span m=''4474890''>into</span> <span m=''4475390''>N</span>
  <span m=''4476070''>boxes</span> <span m=''4476810''>or</span> <span m=''4476930''>bins</span>
  <span m=''4477680''>or</span> <span m=''4477830''>birthdays,</span> <span m=''4479580''>there''s</span>
  <span m=''4479780''>a</span> <span m=''4479860''>decent</span> <span m=''4480280''>chance</span>
  <span m=''4480930''>two</span> <span m=''4481170''>of</span> <span m=''4481410''>the</span>
  <span m=''4481600''>items</span> <span m=''4481940''>will</span> <span m=''4482060''>go</span>
  <span m=''4482260''>into</span> <span m=''4482380''>the</span> <span m=''4482490''>same</span>
  <span m=''4482820''>bin</span> <span m=''4484340''>if</span> <span m=''4484460''>the</span>
  <span m=''4484610''>randomly</span> <span m=''4485230''>allocated.</span> <span
  m=''4487120''>In</span> <span m=''4487370''>this</span> <span m=''4487570''>case,</span>
  <span m=''4487770''>the</span> <span m=''4487850''>bins</span> <span m=''4488240''>are</span>
  <span m=''4488280''>the</span> <span m=''4488380''>possible</span> <span m=''4488860''>days</span>
  <span m=''4489130''>of</span> <span m=''4489200''>the</span> <span m=''4489310''>year</span>
  <span m=''4489670''>that</span> <span m=''4489900''>we</span> <span m=''4490440''>put</span>
  <span m=''4490630''>each</span> <span m=''4490790''>person</span> <span m=''4491090''>into</span>
  <span m=''4491320''>for</span> <span m=''4491440''>their</span> <span m=''4491560''>birthday.</span>
  <span m=''4493150''>Any</span> <span m=''4493310''>questions</span> <span m=''4494555''>about</span>
  <span m=''4495040''>that?</span> <span m=''4498920''>Yeah.</span> </p><p><span m=''4499360''>AUDIENCE:</span>
  <span m=''4499852''>M</span> <span m=''4500098''>and</span> <span m=''4500344''>N</span>
  <span m=''4500508''>are</span> <span m=''4500672''>like</span> <span m=''4500836''>numbers</span>
  <span m=''4501328''>like</span> <span m=''4501820''>they''re</span> <span m=''4501943''>defined</span>
  <span m=''4502066''>up</span> <span m=''4502189''>there</span> <span m=''4502312''>or</span>
  <span m=''4502804''>does</span> <span m=''4503050''>it</span> <span m=''4503296''>mean</span>
  <span m=''4503460''>to</span> <span m=''4503624''>say</span> <span m=''4503788''>M</span>
  <span m=''4504280''>equals</span> <span m=''4504772''>[INAUDIBLE]?</span> </p><p><span
  m=''4505756''>TOM LEIGHTON:</span> <span m=''4506260''>Yeah.</span> <span m=''4506980''>So</span>
  <span m=''4507850''>here</span> <span m=''4508160''>I</span> <span m=''4508240''>looked</span>
  <span m=''4508353''>at</span> <span m=''4508466''>a</span> <span m=''4508580''>special</span>
  <span m=''4509070''>case</span> <span m=''4509490''>where</span> <span m=''4509600''>N</span>
  <span m=''4509815''>was</span> <span m=''4510030''>365,</span> <span m=''4510370''>M</span>
  <span m=''4510710''>was</span> <span m=''4511203''>100,</span> <span m=''4512190''>but</span>
  <span m=''4512320''>we</span> <span m=''4512440''>can</span> <span m=''4512580''>imagine</span>
  <span m=''4513160''>them</span> <span m=''4513360''>as</span> <span m=''4513530''>arbitrary</span>
  <span m=''4514290''>numbers</span> <span m=''4515420''>that</span> <span m=''4515550''>could</span>
  <span m=''4515700''>be</span> <span m=''4515790''>getting</span> <span m=''4516030''>large.</span>
  <span m=''4517350''>And</span> <span m=''4517640''>so</span> <span m=''4517780''>over</span>
  <span m=''4518030''>here</span> <span m=''4518300''>and</span> <span m=''4518380''>I</span>
  <span m=''4518470''>say</span> <span m=''4519550''>M</span> <span m=''4519920''>is</span>
  <span m=''4520460''>little</span> <span m=''4520660''>o</span> <span m=''4520890''>of</span>
  <span m=''4520953''>N</span> <span m=''4521016''>to</span> <span m=''4521080''>the</span>
  <span m=''4521240''>2/3,</span> <span m=''4522480''>I</span> <span m=''4522690''>mean,</span>
  <span m=''4523996''>well,</span> <span m=''4524342''>M</span> <span m=''4524516''>equals</span>
  <span m=''4524690''>square</span> <span m=''4524970''>root</span> <span m=''4525090''>of</span>
  <span m=''4525180''>N</span> <span m=''4525390''>would</span> <span m=''4525520''>qualify.</span>
  <span m=''4526250''>Square</span> <span m=''4526620''>root</span> <span m=''4526720''>of</span>
  <span m=''4526830''>N</span> <span m=''4527060''>is</span> <span m=''4527350''>little</span>
  <span m=''4527590''>o</span> <span m=''4527665''>of</span> <span m=''4527740''>N</span>
  <span m=''4527820''>to</span> <span m=''4527900''>the</span> <span m=''4528050''>2/3.</span>
  <span m=''4529950''>So</span> <span m=''4530100''>as</span> <span m=''4530210''>long</span>
  <span m=''4530590''>as</span> <span m=''4531310''>M</span> <span m=''4531540''>is</span>
  <span m=''4531650''>not</span> <span m=''4531830''>growing</span> <span m=''4532080''>too</span>
  <span m=''4532250''>fast,</span> <span m=''4533320''>I</span> <span m=''4533410''>can</span>
  <span m=''4533570''>simplify</span> <span m=''4534260''>that</span> <span m=''4534450''>expression</span>
  <span m=''4534760''>up</span> <span m=''4535070''>there,</span> <span m=''4536270''>which</span>
  <span m=''4536420''>is</span> <span m=''4536490''>what</span> <span m=''4536650''>I</span>
  <span m=''4536720''>did.</span> </p><p><span m=''4536950''>And</span> <span m=''4537030''>then</span>
  <span m=''4537130''>we</span> <span m=''4537220''>go</span> <span m=''4537360''>back</span>
  <span m=''4537650''>and</span> <span m=''4537740''>we</span> <span m=''4537860''>find,</span>
  <span m=''4538860''>in</span> <span m=''4539290''>fact,</span> <span m=''4540890''>the</span>
  <span m=''4541090''>square</span> <span m=''4541320''>root</span> <span m=''4541450''>of</span>
  <span m=''4541700''>N</span> <span m=''4541920''>the</span> <span m=''4542000''>right</span>
  <span m=''4542180''>answer</span> <span m=''4542980''>and</span> <span m=''4543120''>that</span>
  <span m=''4543300''>is</span> <span m=''4543510''>little</span> <span m=''4543810''>o</span>
  <span m=''4543864''>of</span> <span m=''4543972''>N</span> <span m=''4544026''>to</span>
  <span m=''4544080''>the</span> <span m=''4544160''>2/3.</span> <span m=''4545650''>And</span>
  <span m=''4545770''>I</span> <span m=''4545820''>have</span> <span m=''4546010''>to</span>
  <span m=''4546070''>use</span> <span m=''4546250''>a</span> <span m=''4546290''>different</span>
  <span m=''4546840''>argument</span> <span m=''4548400''>if</span> <span m=''4548790''>I</span>
  <span m=''4548890''>assumed</span> <span m=''4549260''>M</span> <span m=''4549430''>was</span>
  <span m=''4549590''>bigger,</span> <span m=''4550380''>which</span> <span m=''4550570''>I</span>
  <span m=''4550620''>didn''t</span> <span m=''4551030''>do.</span> <span m=''4551750''>I</span>
  <span m=''4551850''>didn''t</span> <span m=''4551970''>drag</span> <span m=''4552230''>it</span>
  <span m=''4552340''>for</span> <span m=''4552450''>that.</span> <span m=''4553140''>But</span>
  <span m=''4553270''>I</span> <span m=''4553290''>would</span> <span m=''4553460''>have</span>
  <span m=''4553550''>to</span> <span m=''4553630''>go</span> <span m=''4553710''>check</span>
  <span m=''4553950''>that</span> <span m=''4554110''>case.</span> </p><p><span m=''4556340''>So</span>
  <span m=''4556470''>we</span> <span m=''4556550''>can</span> <span m=''4556690''>think</span>
  <span m=''4556840''>of</span> <span m=''4556920''>general</span> <span m=''4557320''>is</span>
  <span m=''4557470''>M</span> <span m=''4557670''>and</span> <span m=''4557750''>N</span>
  <span m=''4557900''>as</span> <span m=''4558030''>being</span> <span m=''4558320''>arbitrary</span>
  <span m=''4558800''>variables</span> <span m=''4559730''>and</span> <span m=''4559940''>potentially</span>
  <span m=''4560370''>growing.</span> <span m=''4560730''>M</span> <span m=''4560920''>can</span>
  <span m=''4561020''>be</span> <span m=''4561120''>a</span> <span m=''4561170''>function</span>
  <span m=''4561560''>of</span> <span m=''4561650''>N.</span> <span m=''4562680''>And</span>
  <span m=''4562850''>in</span> <span m=''4562930''>fact,</span> <span m=''4563710''>when</span>
  <span m=''4563940''>M</span> <span m=''4564230''>is</span> <span m=''4564340''>the</span>
  <span m=''4564450''>square</span> <span m=''4564740''>root</span> <span m=''4564940''>function</span>
  <span m=''4565290''>of</span> <span m=''4565380''>N,</span> <span m=''4565990''>then</span>
  <span m=''4566170''>we</span> <span m=''4566260''>got</span> <span m=''4566390''>a</span>
  <span m=''4566440''>50%</span> <span m=''4566960''>chance</span> <span m=''4567370''>of</span>
  <span m=''4567500''>a</span> <span m=''4567550''>match.</span> </p><p><span m=''4571080''>Now,</span>
  <span m=''4573750''>the</span> <span m=''4573830''>birthday</span> <span m=''4574150''>principle</span>
  <span m=''4574560''>comes</span> <span m=''4574830''>up</span> <span m=''4575170''>all</span>
  <span m=''4575420''>over</span> <span m=''4575550''>the</span> <span m=''4575660''>place</span>
  <span m=''4575970''>in</span> <span m=''4576050''>computer</span> <span m=''4576370''>science</span>
  <span m=''4578700''>and</span> <span m=''4578980''>it''s</span> <span m=''4579540''>worth</span>
  <span m=''4579950''>remembering.</span> <span m=''4583140''>For</span> <span m=''4583230''>example,</span>
  <span m=''4585090''>the</span> <span m=''4585190''>generic</span> <span m=''4585610''>form</span>
  <span m=''4585960''>for</span> <span m=''4586050''>this</span> <span m=''4586310''>is</span>
  <span m=''4586390''>when</span> <span m=''4586540''>you</span> <span m=''4586620''>have</span>
  <span m=''4586850''>a</span> <span m=''4586900''>hash</span> <span m=''4587290''>function.</span>
  <span m=''4590510''>Let''s</span> <span m=''4590620''>say</span> <span m=''4590790''>I</span>
  <span m=''4590900''>have</span> <span m=''4591390''>a</span> <span m=''4591510''>hash</span>
  <span m=''4591940''>function,</span> <span m=''4593190''>h,</span> <span m=''4594040''>from</span>
  <span m=''4594190''>a</span> <span m=''4594260''>large</span> <span m=''4594690''>set</span>
  <span m=''4594880''>of</span> <span m=''4595000''>items</span> <span m=''4595490''>into</span>
  <span m=''4595750''>a</span> <span m=''4595800''>small</span> <span m=''4596280''>set</span>
  <span m=''4596510''>of</span> <span m=''4596630''>items.</span> <span m=''4599280''>For</span>
  <span m=''4599420''>example,</span> <span m=''4599890''>say</span> <span m=''4600180''>I''m</span>
  <span m=''4600280''>computing</span> <span m=''4600870''>digital</span> <span m=''4601230''>signatures.</span>
  <span m=''4603200''>This</span> <span m=''4603380''>is</span> <span m=''4603480''>the</span>
  <span m=''4603570''>space</span> <span m=''4603940''>of</span> <span m=''4604040''>all</span>
  <span m=''4604240''>messages,</span> <span m=''4605640''>this</span> <span m=''4605840''>is</span>
  <span m=''4605940''>the</span> <span m=''4606030''>space</span> <span m=''4606390''>of</span>
  <span m=''4606480''>all</span> <span m=''4606770''>1,000-bit</span> <span m=''4607620''>digital</span>
  <span m=''4607940''>signatures,</span> <span m=''4609030''>and</span> <span m=''4609190''>h</span>
  <span m=''4609440''>is</span> <span m=''4609560''>a</span> <span m=''4609640''>digital</span>
  <span m=''4609990''>signature</span> <span m=''4610480''>outcome.</span> </p><p><span
  m=''4611750''>Say</span> <span m=''4612010''>I''m</span> <span m=''4612130''>doing</span>
  <span m=''4612360''>memory</span> <span m=''4612770''>allocations.</span> <span
  m=''4613720''>So</span> <span m=''4613990''>all</span> <span m=''4614190''>the</span>
  <span m=''4614280''>things</span> <span m=''4614530''>I</span> <span m=''4614560''>might</span>
  <span m=''4614750''>be</span> <span m=''4614840''>sticking</span> <span m=''4615220''>into</span>
  <span m=''4616110''>a</span> <span m=''4616210''>register,</span> <span m=''4617190''>here''s</span>
  <span m=''4617430''>all</span> <span m=''4617550''>the</span> <span m=''4617640''>places</span>
  <span m=''4618000''>it</span> <span m=''4618030''>could</span> <span m=''4618190''>go.</span>
  <span m=''4618640''>Here''s</span> <span m=''4618870''>all</span> <span m=''4619050''>the</span>
  <span m=''4619330''>registers.</span> <span m=''4620360''>Error</span> <span m=''4620690''>checking.</span>
  <span m=''4621760''>This</span> <span m=''4621930''>is</span> <span m=''4622020''>all</span>
  <span m=''4622400''>the</span> <span m=''4622510''>garbled</span> <span m=''4622890''>messages</span>
  <span m=''4623350''>in</span> <span m=''4623400''>the</span> <span m=''4623480''>world.</span>
  <span m=''4624490''>This</span> <span m=''4624580''>is</span> <span m=''4624670''>the</span>
  <span m=''4624760''>set</span> <span m=''4624970''>of</span> <span m=''4625030''>messages</span>
  <span m=''4625720''>that</span> <span m=''4625820''>make</span> <span m=''4625860''>sense,</span>
  <span m=''4627360''>all</span> <span m=''4627600''>handled</span> <span m=''4628000''>by</span>
  <span m=''4628830''>functions,</span> <span m=''4629630''>random</span> <span m=''4629940''>kind</span>
  <span m=''4630110''>of</span> <span m=''4630190''>functions</span> <span m=''4630610''>often.</span>
  </p><p><span m=''4632770''>Now,</span> <span m=''4633640''>what</span> <span m=''4633810''>you</span>
  <span m=''4633940''>worry</span> <span m=''4634320''>about</span> <span m=''4634620''>when</span>
  <span m=''4634730''>you''re</span> <span m=''4634840''>hashing</span> <span m=''4635420''>is</span>
  <span m=''4635560''>collisions.</span> <span m=''4637830''>Let</span> <span m=''4638330''>me</span>
  <span m=''4638520''>define</span> <span m=''4638970''>that.</span> <span m=''4640240''>We</span>
  <span m=''4640460''>say</span> <span m=''4640650''>that</span> <span m=''4640850''>x</span>
  <span m=''4641160''>collides</span> <span m=''4644850''>with</span> <span m=''4645080''>y</span>
  <span m=''4647680''>if</span> <span m=''4648290''>the</span> <span m=''4648370''>hash</span>
  <span m=''4648790''>of</span> <span m=''4648900''>x</span> <span m=''4649840''>equals</span>
  <span m=''4650300''>the</span> <span m=''4650390''>hash</span> <span m=''4650790''>of</span>
  <span m=''4650920''>y,</span> <span m=''4652030''>but</span> <span m=''4652640''>x</span>
  <span m=''4652880''>and</span> <span m=''4652950''>y</span> <span m=''4653130''>are</span>
  <span m=''4653230''>different.</span> <span m=''4656650''>For</span> <span m=''4656660''>example,</span>
  <span m=''4657180''>say</span> <span m=''4657420''>you''re</span> <span m=''4657550''>looking</span>
  <span m=''4657810''>at</span> <span m=''4657880''>digital</span> <span m=''4658210''>signatures.</span>
  <span m=''4659930''>You</span> <span m=''4660110''>would</span> <span m=''4660310''>not</span>
  <span m=''4660670''>want</span> <span m=''4660900''>the</span> <span m=''4660990''>signature</span>
  <span m=''4661620''>for</span> <span m=''4662780''>a</span> <span m=''4663000''>$100</span>
  <span m=''4663600''>check</span> <span m=''4663905''>to</span> <span m=''4664210''>your</span>
  <span m=''4664320''>mom</span> <span m=''4665620''>to</span> <span m=''4665770''>match</span>
  <span m=''4666140''>your</span> <span m=''4666280''>signature</span> <span m=''4667220''>for</span>
  <span m=''4667420''>$100,000</span> <span m=''4668360''>check</span> <span m=''4669692''>to</span>
  <span m=''4670130''>Boris.</span> <span m=''4672960''>Because</span> <span m=''4673130''>that</span>
  <span m=''4673260''>would</span> <span m=''4673360''>be</span> <span m=''4673450''>bad</span>
  <span m=''4673770''>because</span> <span m=''4674030''>then</span> <span m=''4674180''>Boris</span>
  <span m=''4674550''>could</span> <span m=''4674650''>come</span> <span m=''4674880''>in</span>
  <span m=''4675810''>and</span> <span m=''4675980''>take</span> <span m=''4676260''>that</span>
  <span m=''4676630''>check</span> <span m=''4676930''>to</span> <span m=''4677000''>your</span>
  <span m=''4677120''>mom</span> <span m=''4677370''>for</span> <span m=''4677680''>$100,</span>
  <span m=''4678590''>converted</span> <span m=''4678855''>to</span> <span m=''4679120''>a</span>
  <span m=''4679210''>$100,000</span> <span m=''4679930''>check</span> <span m=''4680260''>to</span>
  <span m=''4680360''>him</span> <span m=''4681960''>and</span> <span m=''4682160''>the</span>
  <span m=''4682220''>signature</span> <span m=''4682485''>is</span> <span m=''4682750''>authentic</span>
  <span m=''4683730''>if</span> <span m=''4683890''>there''s</span> <span m=''4684370''>a</span>
  <span m=''4684420''>collision</span> <span m=''4684850''>in</span> <span m=''4684890''>the</span>
  <span m=''4684930''>signatures.</span> </p><p><span m=''4686040''>So</span> <span
  m=''4686180''>very</span> <span m=''4686620''>important</span> <span m=''4687150''>when</span>
  <span m=''4687250''>you''re</span> <span m=''4687320''>doing</span> <span m=''4687520''>hash</span>
  <span m=''4687810''>functions</span> <span m=''4688200''>and</span> <span m=''4688590''>in</span>
  <span m=''4688720''>many</span> <span m=''4688940''>applications,</span> <span m=''4689570''>you</span>
  <span m=''4689680''>don''t</span> <span m=''4689980''>want</span> <span m=''4690180''>collisions</span>
  <span m=''4691850''>because</span> <span m=''4692130''>all</span> <span m=''4692310''>the</span>
  <span m=''4692373''>whole</span> <span m=''4692436''>thing</span> <span m=''4692500''>start</span>
  <span m=''4692930''>breaking.</span> <span m=''4694160''>Memory</span> <span m=''4694490''>allocation.</span>
  <span m=''4695020''>You</span> <span m=''4695080''>don''t</span> <span m=''4695140''>want</span>
  <span m=''4695270''>to</span> <span m=''4695310''>assign</span> <span m=''4695620''>two</span>
  <span m=''4695790''>things</span> <span m=''4696080''>in</span> <span m=''4696110''>the</span>
  <span m=''4696200''>same</span> <span m=''4696450''>place.</span> <span m=''4697770''>Error</span>
  <span m=''4698080''>correction.</span> <span m=''4698880''>There''s</span> <span
  m=''4699030''>only</span> <span m=''4699190''>one</span> <span m=''4699460''>answer</span>
  <span m=''4699770''>you</span> <span m=''4699870''>want</span> <span m=''4700020''>to</span>
  <span m=''4700060''>get</span> <span m=''4700200''>out</span> <span m=''4700430''>at</span>
  <span m=''4700505''>the</span> <span m=''4700580''>end.</span> </p><p><span m=''4703100''>Now,</span>
  <span m=''4703680''>from</span> <span m=''4703800''>the</span> <span m=''4703930''>pigeon</span>
  <span m=''4704260''>hole</span> <span m=''4704400''>principle,</span> <span m=''4704810''>you</span>
  <span m=''4704930''>know</span> <span m=''4705890''>if</span> <span m=''4706030''>this</span>
  <span m=''4706240''>set</span> <span m=''4706450''>is</span> <span m=''4706610''>bigger</span>
  <span m=''4706690''>than</span> <span m=''4706770''>that</span> <span m=''4707020''>set,</span>
  <span m=''4707900''>there</span> <span m=''4707955''>is</span> <span m=''4708010''>going</span>
  <span m=''4708130''>to</span> <span m=''4708190''>be</span> <span m=''4708330''>a</span>
  <span m=''4708360''>collision.</span> <span m=''4708900''>That''s</span> <span m=''4709180''>what</span>
  <span m=''4709380''>the</span> <span m=''4709470''>pigeon</span> <span m=''4709760''>hole</span>
  <span m=''4709890''>principle</span> <span m=''4710280''>says.</span> <span m=''4710720''>Two</span>
  <span m=''4710900''>guys</span> <span m=''4711180''>will</span> <span m=''4711260''>get</span>
  <span m=''4711450''>mapped</span> <span m=''4711660''>to</span> <span m=''4711720''>the</span>
  <span m=''4711800''>same</span> <span m=''4712050''>thing.</span> <span m=''4713490''>However,</span>
  <span m=''4714010''>often</span> <span m=''4714410''>in</span> <span m=''4714490''>practice</span>
  <span m=''4715010''>what</span> <span m=''4715100''>we</span> <span m=''4715240''>care</span>
  <span m=''4715590''>about</span> <span m=''4716430''>is</span> <span m=''4716620''>a</span>
  <span m=''4716690''>subset</span> <span m=''4718010''>L</span> <span m=''4718270''>prime</span>
  <span m=''4719810''>of</span> <span m=''4720230''>L</span> <span m=''4720530''>that''s</span>
  <span m=''4720710''>pretty</span> <span m=''4720930''>small</span> <span m=''4722160''>because</span>
  <span m=''4722370''>the</span> <span m=''4722450''>set</span> <span m=''4722650''>of</span>
  <span m=''4722720''>messages</span> <span m=''4723190''>we</span> <span m=''4723330''>really</span>
  <span m=''4723660''>assign</span> <span m=''4724080''>is</span> <span m=''4724200''>pretty</span>
  <span m=''4724420''>small</span> <span m=''4725200''>compared</span> <span m=''4725550''>to</span>
  <span m=''4725675''>all</span> <span m=''4725800''>1,000-bit</span> <span m=''4726370''>signatures</span>
  <span m=''4726765''>that</span> <span m=''4727160''>are</span> <span m=''4727410''>possible.</span>
  </p><p><span m=''4728370''>And</span> <span m=''4728560''>what</span> <span m=''4728710''>you''d</span>
  <span m=''4728890''>like</span> <span m=''4729670''>is</span> <span m=''4729890''>that</span>
  <span m=''4730020''>for</span> <span m=''4730110''>this</span> <span m=''4730330''>smaller</span>
  <span m=''4730810''>set</span> <span m=''4731010''>of</span> <span m=''4731100''>messages,</span>
  <span m=''4731580''>you</span> <span m=''4731690''>might</span> <span m=''4731950''>want</span>
  <span m=''4732110''>to</span> <span m=''4732180''>assign,</span> <span m=''4732820''>they</span>
  <span m=''4733220''>all</span> <span m=''4733430''>get</span> <span m=''4733610''>mapped</span>
  <span m=''4734400''>one</span> <span m=''4734710''>to</span> <span m=''4734810''>one.</span>
  <span m=''4736210''>And</span> <span m=''4736350''>the</span> <span m=''4736440''>birthday</span>
  <span m=''4736800''>principle</span> <span m=''4737910''>says</span> <span m=''4738620''>life</span>
  <span m=''4738880''>is</span> <span m=''4739000''>not</span> <span m=''4739210''>so</span>
  <span m=''4739350''>nice.</span> <span m=''4741560''>So</span> <span m=''4741700''>let</span>
  <span m=''4741770''>me</span> <span m=''4741840''>write</span> <span m=''4742060''>that</span>
  <span m=''4742260''>down</span> <span m=''4742710''>then</span> <span m=''4742960''>we''ll</span>
  <span m=''4743437''>be</span> <span m=''4743914''>done.</span> <span m=''4750592''>All</span>
  <span m=''4751069''>right.</span> <span m=''4751560''>So</span> <span m=''4751680''>the</span>
  <span m=''4751770''>birthday</span> <span m=''4752170''>principle</span> <span m=''4763140''>says</span>
  <span m=''4763590''>that</span> <span m=''4765200''>if</span> <span m=''4765650''>S</span>
  <span m=''4765960''>is</span> <span m=''4766080''>at</span> <span m=''4766170''>least</span>
  <span m=''4766440''>100,</span> <span m=''4769870''>L</span> <span m=''4770110''>prime</span>
  <span m=''4770500''>is</span> <span m=''4770600''>a</span> <span m=''4770670''>subset</span>
  <span m=''4771100''>of</span> <span m=''4771230''>L</span> <span m=''4772451''>that</span>
  <span m=''4772860''>is</span> <span m=''4773310''>at</span> <span m=''4773420''>least</span>
  <span m=''4774270''>the</span> <span m=''4774370''>square</span> <span m=''4774650''>root</span>
  <span m=''4774840''>of</span> <span m=''4774960''>S.</span> </p><p><span m=''4776590''>So</span>
  <span m=''4776710''>the</span> <span m=''4776800''>cardinality</span> <span m=''4777135''>of</span>
  <span m=''4777470''>the</span> <span m=''4777600''>things</span> <span m=''4777820''>you</span>
  <span m=''4777940''>want</span> <span m=''4778250''>to</span> <span m=''4778770''>hash</span>
  <span m=''4779740''>is</span> <span m=''4779880''>bigger</span> <span m=''4780100''>than</span>
  <span m=''4780280''>1.2</span> <span m=''4781180''>square</span> <span m=''4781570''>root</span>
  <span m=''4781920''>the</span> <span m=''4782020''>cardinality</span> <span m=''4782770''>of</span>
  <span m=''4783100''>S.</span> <span m=''4785800''>And</span> <span m=''4787390''>if</span>
  <span m=''4787650''>the</span> <span m=''4787750''>values</span> <span m=''4793145''>of</span>
  <span m=''4793640''>the</span> <span m=''4793780''>function</span> <span m=''4794510''>h</span>
  <span m=''4795460''>on</span> <span m=''4795630''>L</span> <span m=''4795800''>prime</span>
  <span m=''4797290''>are</span> <span m=''4797490''>randomly</span> <span m=''4798090''>chosen,</span>
  <span m=''4801350''>uniform,</span> <span m=''4807280''>and</span> <span m=''4807570''>mutually</span>
  <span m=''4808010''>independent,</span> <span m=''4814260''>then</span> <span m=''4814500''>there''s</span>
  <span m=''4814670''>at</span> <span m=''4814750''>least</span> <span m=''4815050''>a</span>
  <span m=''4815100''>50%</span> <span m=''4815820''>chance,</span> <span m=''4816500''>so</span>
  <span m=''4816630''>with</span> <span m=''4816790''>probability</span> <span m=''4819000''>at</span>
  <span m=''4819090''>least</span> <span m=''4819360''>1/2,</span> <span m=''4822720''>there''s</span>
  <span m=''4822920''>a</span> <span m=''4822970''>collision.</span> <span m=''4824310''>There</span>
  <span m=''4824450''>exists</span> <span m=''4824850''>an</span> <span m=''4824980''>x</span>
  <span m=''4825250''>and</span> <span m=''4825335''>a</span> <span m=''4825420''>y</span>
  <span m=''4826350''>such</span> <span m=''4826710''>that</span> <span m=''4827590''>x</span>
  <span m=''4827880''>does</span> <span m=''4828070''>not</span> <span m=''4828310''>equal</span>
  <span m=''4828610''>y--</span> <span m=''4829340''>and</span> <span m=''4829430''>these</span>
  <span m=''4829590''>are</span> <span m=''4829660''>in</span> <span m=''4829695''>L</span>
  <span m=''4829730''>prime--</span> <span m=''4831650''>but</span> <span m=''4832870''>h</span>
  <span m=''4833160''>of</span> <span m=''4833280''>x</span> <span m=''4834480''>equals</span>
  <span m=''4834960''>h</span> <span m=''4835190''>of</span> <span m=''4835590''>y.</span>
  </p><p><span m=''4837840''>All</span> <span m=''4837970''>right.</span> <span m=''4838120''>The</span>
  <span m=''4838200''>proof</span> <span m=''4838480''>is</span> <span m=''4838860''>not</span>
  <span m=''4839140''>hard,</span> <span m=''4839440''>it''s</span> <span m=''4839560''>just</span>
  <span m=''4839800''>we</span> <span m=''4839940''>more</span> <span m=''4840150''>or</span>
  <span m=''4840170''>less</span> <span m=''4840450''>did</span> <span m=''4840640''>it.</span>
  <span m=''4841910''>You</span> <span m=''4842010''>just</span> <span m=''4842210''>plug</span>
  <span m=''4842500''>in</span> <span m=''4843100''>the</span> <span m=''4843200''>cardinality</span>
  <span m=''4843730''>of</span> <span m=''4843765''>L</span> <span m=''4843800''>prime</span>
  <span m=''4844340''>for</span> <span m=''4844480''>M</span> <span m=''4844880''>and</span>
  <span m=''4845120''>the</span> <span m=''4845260''>cardinality</span> <span m=''4845830''>of</span>
  <span m=''4845900''>S</span> <span m=''4846300''>for</span> <span m=''4846530''>N.</span>
  <span m=''4847620''>And</span> <span m=''4847810''>it''s</span> <span m=''4847930''>bad</span>
  <span m=''4848230''>news</span> <span m=''4848680''>because</span> <span m=''4849010''>it</span>
  <span m=''4849120''>means</span> <span m=''4849880''>it</span> <span m=''4850000''>doesn''t</span>
  <span m=''4850320''>take</span> <span m=''4850600''>very</span> <span m=''4850890''>many</span>
  <span m=''4851130''>messages,</span> <span m=''4852450''>just</span> <span m=''4852670''>square</span>
  <span m=''4853230''>root</span> <span m=''4853940''>the</span> <span m=''4854030''>number</span>
  <span m=''4854290''>of</span> <span m=''4854370''>signatures</span> <span m=''4855560''>to</span>
  <span m=''4855670''>get</span> <span m=''4855840''>a</span> <span m=''4855900''>collision.</span>
  <span m=''4857940''>You''d</span> <span m=''4858310''>hope</span> <span m=''4858700''>you</span>
  <span m=''4858800''>could</span> <span m=''4858980''>get</span> <span m=''4859980''>that</span>
  <span m=''4860350''>you</span> <span m=''4860490''>could</span> <span m=''4860640''>have</span>
  <span m=''4860840''>L</span> <span m=''4861030''>prime</span> <span m=''4861310''>be</span>
  <span m=''4861450''>as</span> <span m=''4861590''>big</span> <span m=''4861810''>as</span>
  <span m=''4861930''>S</span> <span m=''4862330''>and</span> <span m=''4862730''>that</span>
  <span m=''4862780''>somehow</span> <span m=''4862830''>they''d</span> <span m=''4862880''>all</span>
  <span m=''4863200''>go</span> <span m=''4863350''>one</span> <span m=''4863590''>to</span>
  <span m=''4863700''>one,</span> <span m=''4864710''>that</span> <span m=''4864850''>everybody</span>
  <span m=''4865210''>in</span> <span m=''4865270''>this</span> <span m=''4865440''>room</span>
  <span m=''4865660''>would</span> <span m=''4865760''>have</span> <span m=''4865930''>a</span>
  <span m=''4865980''>different</span> <span m=''4866260''>birthday.</span> <span
  m=''4866970''>That</span> <span m=''4867120''>is</span> <span m=''4867260''>not</span>
  <span m=''4867520''>how</span> <span m=''4867730''>it</span> <span m=''4867800''>works</span>
  <span m=''4868570''>if</span> <span m=''4868720''>things</span> <span m=''4868960''>are</span>
  <span m=''4869040''>random,</span> <span m=''4869380''>which</span> <span m=''4869560''>is</span>
  <span m=''4869660''>the</span> <span m=''4869740''>case</span> <span m=''4870010''>you</span>
  <span m=''4870100''>usually</span> <span m=''4870480''>like</span> <span m=''4870680''>to</span>
  <span m=''4870770''>have.</span> </p><p><span m=''4871750''>Now,</span> <span m=''4871860''>this</span>
  <span m=''4872050''>technique</span> <span m=''4872650''>is</span> <span m=''4872760''>used</span>
  <span m=''4873170''>to</span> <span m=''4873240''>crack</span> <span m=''4873950''>cryptographic</span>
  <span m=''4874600''>protocols</span> <span m=''4876000''>and</span> <span m=''4876130''>it''s</span>
  <span m=''4876260''>called</span> <span m=''4876530''>the</span> <span m=''4876590''>birthday</span>
  <span m=''4877050''>attack</span> <span m=''4877990''>based</span> <span m=''4878290''>on</span>
  <span m=''4878330''>the</span> <span m=''4878410''>birthday</span> <span m=''4878720''>principle.</span>
  <span m=''4879740''>So</span> <span m=''4879850''>what</span> <span m=''4879960''>you</span>
  <span m=''4880040''>do</span> <span m=''4880320''>is,</span> <span m=''4880400''>you</span>
  <span m=''4880480''>get</span> <span m=''4880610''>a</span> <span m=''4880650''>bunch</span>
  <span m=''4880890''>of</span> <span m=''4880960''>messages</span> <span m=''4881970''>that</span>
  <span m=''4882090''>are</span> <span m=''4882170''>encrypted</span> <span m=''4883480''>and</span>
  <span m=''4883940''>pretty</span> <span m=''4884190''>soon</span> <span m=''4885070''>you</span>
  <span m=''4885190''>find</span> <span m=''4885640''>two</span> <span m=''4885950''>that</span>
  <span m=''4886260''>get</span> <span m=''4887000''>maybe</span> <span m=''4887240''>encrypted</span>
  <span m=''4887600''>the</span> <span m=''4887670''>same</span> <span m=''4887950''>way.</span>
  <span m=''4888350''>And</span> <span m=''4888460''>once</span> <span m=''4888660''>you</span>
  <span m=''4888760''>have</span> <span m=''4889080''>that,</span> <span m=''4889790''>now</span>
  <span m=''4889930''>you</span> <span m=''4889965''>can</span> <span m=''4890000''>go</span>
  <span m=''4890260''>back</span> <span m=''4890700''>and</span> <span m=''4890950''>crack</span>
  <span m=''4891540''>the</span> <span m=''4891610''>crypto</span> <span m=''4891950''>system.</span>
  <span m=''4893640''>For</span> <span m=''4893720''>example,</span> <span m=''4894110''>you</span>
  <span m=''4894340''>break</span> <span m=''4894580''>schemes</span> <span m=''4894870''>like</span>
  <span m=''4895060''>RSA</span> <span m=''4896210''>with</span> <span m=''4896350''>a</span>
  <span m=''4896390''>birthday</span> <span m=''4896790''>attack</span> <span m=''4897680''>if</span>
  <span m=''4898610''>this</span> <span m=''4898780''>space</span> <span m=''4899250''>is</span>
  <span m=''4899370''>not</span> <span m=''4899600''>big</span> <span m=''4899770''>enough</span>
  <span m=''4900390''>and</span> <span m=''4900470''>that''s</span> <span m=''4900630''>one</span>
  <span m=''4900780''>reason</span> <span m=''4901070''>why</span> <span m=''4901570''>now</span>
  <span m=''4901770''>RSA,</span> <span m=''4903040''>the</span> <span m=''4903150''>keys</span>
  <span m=''4904110''>have</span> <span m=''4904310''>thousands</span> <span m=''4904760''>of</span>
  <span m=''4904850''>digits</span> <span m=''4906310''>because</span> <span m=''4906500''>otherwise</span>
  <span m=''4906850''>you</span> <span m=''4906940''>can</span> <span m=''4907040''>use</span>
  <span m=''4907190''>attacks</span> <span m=''4907580''>like</span> <span m=''4907740''>this</span>
  <span m=''4908720''>and</span> <span m=''4910020''>crack</span> <span m=''4910330''>them</span>
  <span m=''4910630''>more</span> <span m=''4910850''>easily.</span> </p><p><span
  m=''4912450''>Any</span> <span m=''4912600''>questions</span> <span m=''4913040''>about</span>
  <span m=''4913280''>that?</span> <span m=''4915760''>OK.</span> <span m=''4916110''>Very</span>
  <span m=''4916380''>good.</span> <span m=''4916580''>We''re</span> <span m=''4916750''>done</span>
  <span m=''4917030''>for</span> <span m=''4917160''>today.</span> </p>'
type: course
uid: 8e18030450f67e1dd860281e4c93b825

---
None