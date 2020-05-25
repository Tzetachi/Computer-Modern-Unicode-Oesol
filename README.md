# Computer-Modern-Unicode-Oesol
Computer Modern Unicode Oesol (이하, CMUO)은 언어학자 외솔 최현배 선생이 고안한 풀어쓰기 한글 자모를 구현한 컴퓨터 글꼴입니다.

Computer Modern Unicode Oesol (henceforth, CMUO) is a computer font set for disassembled Hangul, invented by Choe Hyeon-bae (a.k.a. Oesol), a Korean linguist. (An English version of this document is in preperation.)

## 코드

CMUO가 포함하는 풀어쓰기 한글 자모는, 대문자와 소문자의 구분이 있고, 현행 ‹한글 맞춤법›에 없는 특수 자모들이 있다는 특성상, 부득이 Private Use Area에 배정하였으며, 각각의 코드는 다음과 같습니다:

- 대문자(ㄱ~ㅎ) — U+E000–U+E00D
- 대문자(ㅏ~ㅣ) — U+E00E–U+E017
- 대문자(딴이, 짧은 ㅗ, 짧은 ㅜ, 짧은 ㅡ, 짧은 ㅣ) — U+E018–U+E01C
- 소문자(ㄱ~ㅎ) — U+E01D–U+E02A
- 소문자(ㅏ~ㅣ) — U+E02B–U+E034
- 소문자(딴이, 짧은 ㅗ, 짧은 ㅜ, 짧은 ㅡ, 짧은 ㅣ) — U+E035–U+E039

“ㄸ”, “ㅒ” 등의 합자는 따로 글자를 만들거나 코드를 배당하지 않았으며, 자음 이응의 순서는 «글자의 혁명»의 원안에서는 히읗의 뒤이지만, 현행 ‹한글 맞춤법›에 맞춰 시옷의 뒤에 배치하였습니다.

## 특수 자모들에 대한 간단한 설명

- 딴이: “ㅏ”, “ㅓ”, “ㅗ”(, “ㅜ”) 등의 뒤에 붙어 “ㅐ”, “ㅔ”, “ㅚ”(, “ㅟ”)를 형성할 적에 쓰입니다. “ㅟ”는 «글자의 혁명»에서는 이중 모음으로 취급하여 딴이를 쓰지 않으나, 현행 ‹한글 맞춤법›을 따라 단모음으로 본다면, 딴이를 쓸 수도 있을 것입니다.
- 짧은 ㅗ: “ㅏ”, “ㅐ” 등의 앞에 붙어 /w/ 음소를 나타냅니다; “ㅘ”와 “ㅙ”의 “ㅗ”라고 생각하시면 됩니다.
- 짧은 ㅜ: “ㅓ”, “ㅔ”, “ㅣ” 등의 앞에 붙어 /w/(, /ɥ/) 음소를 나타냅니다; “ㅝ”, “ㅞ”, “ㅟ”의 “ㅜ”라고 생각하시면 됩니다.
- 짧은 ㅡ: “ㅣ”의 앞에 붙어 /ɰ/ 음소를 나타냅니다; “ㅢ”의 “ㅡ”라고 생각하시면 됩니다.
- 짧은 ㅣ: 운두의 /j/ 음소를 나타내며, 일반적인 표기에는 쓰이지 않고, 대신 “ㅑ”, “ㅒ”, “ㅕ”, “ㅖ”, “ㅛ”, “ㅠ” 등을 씁니다.

## 입력

이 글꼴로 입력하기 위해서는 [ZyntharSekki](https://github.com/ZyntharSekki) 님이 만드신 날개셋 입력기용 자판 배열인 [Oesol-key](https://github.com/ZyntharSekki/Oesol-key)나 N. d. H. 님의 LaTeX 패키지인 [oesolscript](https://bitbucket.org/novadh/oesolscript/src/master/)를 이용하실 수 있습니다.

## 그 밖의 사항들

이 글꼴은 Computer Modern Unicode를 기반으로 수정하여 만들어졌으며, Computer Modern Unicode와 동일하게 SIL Open Font License하에 배포됩니다. SIL Open Font License에 대한 더 자세한 정보는 [이곳](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL_web)에서 얻을 수 있습니다.

제작자 본인은 타이포그래피에 관한 전문 지식/기술을 갖추지 않았습니다. 이 때문에 글꼴이 다소간 조화롭지 못할 수 있다는 점을 유의하시기 바랍니다. 만약 개선하거나 수정하고 싶은 사항이 있다면, OFL License가 허용하는 한도 내에서, 자유로이 수정 및 재배포하실 수 있습니다.
