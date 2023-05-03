# testaja
@import url("https://fonts.googleapis.com/css?family=Montserrat");*{padding: 0;margin: 0;box-sizing: border-box;font-family: "Montserrat", sans-serif !important}body{height: 100%;background: #ffcf47;color: #333;letter-spacing: 0.15em}.slider{position: fixed;top: 0;left: 0;right: 0;bottom: 0}.wrapper{height: 100%;overflow: hidden;position: relative;z-index: 1}#items{width: 10000%;height: 100%;background: navajowhite;position: relative;top: 0}#items.shifting{transition: left 0.2s ease-out}#items div{width: 100vw;height: 100%;cursor: pointer;float: left;display: flex;flex-direction: column;justify-content: center;align-items: center;position: relative;background: #ffcf47}#items div img{width: 200px}#items div p{margin-top: 20px;font-size: 1.3em;font-weight: bold;text-align: center;padding: 0 50px}.slider.loaded #items div:nth-child(5n){background: #7adcef}.slider.loaded #items div:nth-child(5n + 1){background: #ffcf47}.slider.loaded #items div:nth-child(5n + 2){background: #a78df5}.slider.loaded #items div:nth-child(5n + 3){background: #7cef7a}.slider.loaded #items div:nth-child(5n + 4){background: #f97c68}.control{position: absolute;top: 50%;width: 40px;height: 40px;background: #fff;border-radius: 20px;margin-top: -20px;box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.3);z-index: 2}.prev:active,.next:active{transform: scale(0.8)}.open{position: fixed;z-index: 100;top: 0;left: 0;right: 0;bottom: 0;text-align: center}.open .left{position: fixed;top: 0;left: 0;bottom: 0;width: 50vw;background: #7adcef;border-right: 5px solid white}.open .right{position: fixed;top: 0;right: 0;bottom: 0;width: 50vw;background: #f97c68;border-left: 5px solid white}.open .content{display: inline-block;position: relative;height: 100%;display: flex;flex-direction: column;justify-content: center;align-items: center}.open .content .lock{height: 130px;width: 130px;border-radius: 65px;background: #333;position: relative;border: 9px solid white;-webkit-border-radius: 60px;-moz-border-radius: 65px;-ms-border-radius: 65px;-o-border-radius: 65px;-webkit-border-radius: 65px}.open .content .lock .top{margin: 10px auto 0;width: 50px;height: 45px;border-top-right-radius: 20px;border-top-left-radius: 20px;border: 9px solid #ffcf47}.open .content .lock .bottom{margin: -10px auto 0;height: 55px;width: 65px;background: white;border: 9px solid #ffcf47;border-radius: 15px;-webkit-border-radius: 15px;-moz-border-radius: 15px;-ms-border-radius: 15px;-o-border-radius: 15px}.open .text{font-weight: bold;position: relative;display: inline-block;margin: auto;bottom: 100px;background: white;box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.311);padding: 15px 20px;border-radius: 10px;-webkit-border-radius: 10px;-moz-border-radius: 10px;-ms-border-radius: 10px;-o-border-radius: 10px}.slide-open{width: 0;height: 80vh}@keyframes lock-pop{0%{scale: 1}50%,60%{scale: 1.2}100%{scale: 0}}.help{position: fixed;right: 20px;top: 20px;z-index: 10;display: flex;align-items: center;border-radius: 20px;-webkit-border-radius: 20px;-moz-border-radius: 20px;-ms-border-radius: 20px;-o-border-radius: 20px}.help .icon{height: 40px;width: 40px;border-radius: 20px;cursor: pointer}.help .icon .line{height: 100%;display: flex;flex-direction: column;justify-content: center;align-items: center;gap: 6px}.help .icon .line div{width: 30px;height: 5px;border-radius: 2px;background: white;-webkit-border-radius: 2px;-moz-border-radius: 2px;-ms-border-radius: 2px;-o-border-radius: 2px}.help .icon .close{height: 100%;display: flex;flex-direction: column;justify-content: center;align-items: center;display: none}.help .icon .close div{width: 35px;height: 5px;border-radius: 2px;background: white;-webkit-border-radius: 2px;-moz-border-radius: 2px;-ms-border-radius: 2px;-o-border-radius: 2px;transform: translateY(2.5px) rotate(-45deg);-webkit-transform: translateY(2.5px) rotate(-45deg);-moz-transform: translateY(2.5px) rotate(-45deg);-ms-transform: translateY(2.5px) rotate(-45deg);-o-transform: translateY(2.5px) rotate(-45deg)}.help .icon .close div:last-child{transform: translateY(-2.5px) rotate(45deg);-webkit-transform: translateY(-2.5px) rotate(45deg);-moz-transform: translateY(-2.5px) rotate(45deg);-ms-transform: translateY(-2.5px) rotate(45deg);-o-transform: translateY(-2.5px) rotate(45deg)}.help .desc{position: relative;background: white;font-weight: bold;font-size: 1.1em;border-radius: 20px;height: 40px;width: 200px;display: flex;overflow: hidden;align-items: center;justify-content: center;-webkit-border-radius: 20px;-moz-border-radius: 20px;-ms-border-radius: 20px;-o-border-radius: 20px;scale: 0}.help .desc a{text-decoration: none;color: #333}.bg{background: #f58d8d;position: relative;top: 0;bottom: 0;width: 100vw;position: fixed;z-index: -1}.content .card-pesan{text-align: start !important;position: relative;min-height: 70px;margin: 20px;padding: 15px 15px 30px 15px;background: rgb(255, 255, 255);border-radius: 10px;box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);font-size: 1.05em !important;-webkit-border-radius: 10px;-moz-border-radius: 10px;-ms-border-radius: 10px;-o-border-radius: 10px;letter-spacing: 0px !important}.content div.card-pesan span{font-size: 0.9em !important;font-weight: bold !important}.content .card-pesan h6{position: absolute;right: 10px;bottom: 5px;font-size: 0.8em !important}.swal2-popup{padding-bottom: 0;max-width: 400px;border-radius: 20px;overflow: hidden}.swal2-title{font-size: 1.2em;font-weight: 500;padding-top: 40px}.swal2-actions{margin: 0 !important;padding: 20px 0}.swal2-actions button,button:active,button:focus{border-radius: 10px !important;-webkit-border-radius: 10px !important;-moz-border-radius: 10px !important;-ms-border-radius: 10px !important;-o-border-radius: 10px !important}.swal2-loading{padding-bottom: 20px}textarea{resize: none}.
