# guidedSlotMachine
This is a guided slot machine, just change class name.

How to use :



      $("#goBtn").click(function() {
        $(".slot").toggleClass("play-pause");
        $(".slot").attr("id", "slotNight")
        // slotTwo 可以換成其他會開出其它結果
        // slotZero : 藍777
        // slotOne : 綠檸檬
        // slotTwo : 橘子
        // slotThree : 鈴鐺
        // slotFour : 葡萄
        // slotFive : BAR
        // slotSix : 西瓜
        // slotSeven : 鑽石
        // slotEight : 紅777
        // slotNight : 黃檸檬
      });

    
    
    
Demo : 
<a href="http://www.clara.url.tw/guidedSlotMachine/index.html" target="_blank">可控制開獎結果的拉霸機</a>
