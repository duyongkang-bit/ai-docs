# OpenCode锛氬紑婧怉I缂栫▼鍔╂墜鐨勫叏鏂伴€夋嫨

杩欎袱骞存垜璇曡繃浜嗗悇绉岮I缂栫▼宸ュ叿锛屾渶缁堟垜閫夋嫨浜哋penCode銆傛垜鏈変笁涓繀椤讳娇鐢∣penCode鐨勭悊鐢憋細

1. 100%寮€婧愶紝涓嶇粦瀹氫换浣旳I鎻愪緵鍟?
2. 瀹夎绠€鍗曪紝澶氱骞冲彴鏀寔
3. 鍐呯疆鏅鸿兘浠ｇ悊锛屽姛鑳藉己澶?

OpenCode鐨勬渶澶т紭鍔垮氨鏄畬鍏ㄥ紑婧愶紝涓嶇粦瀹氫换浣旳I鎻愪緵鍟嗐€備綘鍙互鑷敱閫夋嫨Claude銆丱penAI銆丟oogle鎴栨湰鍦版ā鍨嬶紝闅忕潃妯″瀷鎶€鏈殑鍙戝睍锛岃繖绉嶇伒娲绘€у皢涓轰綘鑺傜渷鎴愭湰骞舵彁渚涙洿浼樼殑浣撻獙銆?

鍚屾椂OpenCode鐢眓eovim鐢ㄦ埛鍜宼erminal.shop鐨勫垱寤鸿€呮墦閫狅紝涓撴敞浜庣粓绔晫闈㈢殑鏋佽嚧浣撻獙锛屽悓鏃舵彁渚涘鎴风-鏈嶅姟鍣ㄦ灦鏋勶紝鏀寔杩滅▼鎿嶄綔绛夐珮绾у姛鑳姐€?

## 蹇€熷畨瑁呮寚鍗?

OpenCode鎻愪緵澶氱瀹夎鏂瑰紡锛屾弧瓒充笉鍚屽钩鍙扮敤鎴风殑闇€姹傦細

**YOLO瀹夎娉?*锛氬彧闇€涓€琛屽懡浠?`curl -fsSL https://opencode.ai/install | bash`锛屽嵆鍙畬鎴愬畨瑁呫€?

**鍖呯鐞嗗櫒瀹夎**锛?
- npm/bun/pnpm/yarn锛歚npm i -g opencode-ai@latest`
- Windows锛歚scoop install opencode` 鎴?`choco install opencode`
- macOS鍜孡inux锛氭帹鑽愪娇鐢?`brew install anomalyco/tap/opencode`
- Arch Linux锛歚sudo pacman -S opencode` 鎴?`paru -S opencode-bin`
- 鍏朵粬绯荤粺锛歚mise use -g opencode` 鎴?`nix run nixpkgs#opencode`

**妗岄潰搴旂敤**锛歄penCode杩樻彁渚汢eta鐗堟闈㈠簲鐢紝鏀寔macOS銆乄indows鍜孡inux骞冲彴锛屽彲閫氳繃releases椤甸潰鎴杘pencode.ai/download涓嬭浇銆?

## 鍐呯疆鏅鸿兘浠ｇ悊

OpenCode鍖呭惈涓や釜鍐呯疆浠ｇ悊锛屽彲閫氳繃Tab閿垏鎹細

**build浠ｇ悊**锛氶粯璁や唬鐞嗭紝鎷ユ湁瀹屾暣鐨勫紑鍙戞潈闄愶紝閫傚悎鏃ュ父寮€鍙戝伐浣溿€?

**plan浠ｇ悊**锛氬彧璇讳唬鐞嗭紝榛樿鎷掔粷鏂囦欢缂栬緫锛岃繍琛宐ash鍛戒护鍓嶄細璇锋眰鏉冮檺锛岄潪甯搁€傚悎鎺㈢储闄岀敓浠ｇ爜搴撴垨瑙勫垝浠ｇ爜鍙樻洿銆?

姝ゅ锛孫penCode杩樺唴缃簡涓€涓€氱敤瀛愪唬鐞嗭紝鐢ㄤ簬澶嶆潅鎼滅储鍜屽姝ラ浠诲姟锛屽彲閫氳繃鍦ㄦ秷鎭腑浣跨敤@general璋冪敤銆?

## 鑷畾涔夊畨瑁呯洰褰?

OpenCode瀹夎鑴氭湰浼氭寜鐓т互涓嬩紭鍏堢骇閫夋嫨瀹夎璺緞锛?
1. $OPENCODE_INSTALL_DIR - 鑷畾涔夊畨瑁呯洰褰?
2. $XDG_BIN_DIR - 绗﹀悎XDG鍩虹鐩綍瑙勮寖鐨勮矾寰?
3. $HOME/bin - 鏍囧噯鐢ㄦ埛浜岃繘鍒剁洰褰曪紙濡傛灉瀛樺湪鎴栧彲鍒涘缓锛?
4. $HOME/.opencode/bin - 榛樿鍥為€€璺緞

渚嬪锛屼綘鍙互閫氳繃 `OPENCODE_INSTALL_DIR=/usr/local/bin curl -fsSL https://opencode.ai/install | bash` 鏉ヨ嚜瀹氫箟瀹夎鐩綍銆?

## 鍔犲叆绀惧尯

濡傛灉浣犲OpenCode鎰熷叴瓒ｏ紝娆㈣繋鍔犲叆鎴戜滑鐨勭ぞ鍖篋iscord鎴栧叧娉╔.com锛屼笌鍏朵粬寮€鍙戣€呬氦娴佷娇鐢ㄥ績寰楀拰鎶€宸с€?

OpenCode锛屼负寮€鍙戣€呮墦閫犵殑寮€婧怉I缂栫▼鍔╂墜锛岃浣犵殑缂栫爜鏁堢巼鎻愬崌鍒版柊楂樺害锛