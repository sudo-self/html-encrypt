<script>document.write(unescape('%3Chtml%3E%0A%3Chead%3E%0A%20%20%20%20%3Cmeta%20charset%3D%22UTF-8%22%20/%3E%0A%20%20%20%20%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%2C%20initial-scale%3D1.0%22%20/%3E%0A%20%20%20%20%3Cmeta%20name%3D%22title%22%20content%3D%22HTML%20Encrypt%22%20/%3E%0A%20%20%20%20%3Cmeta%20name%3D%22description%22%20content%3D%22HTML%20Encrypt%20tool%20obfuscates%20text%20using%20basic%20encoding%20methods%20to%20make%20content%20less%20readable%20while%20maintaining%20its%20original%20format%20for%20web%20use.%22%20/%3E%0A%20%20%20%20%3Cmeta%20name%3D%22keywords%22%20content%3D%22HTML%20encryption%2C%20HTML%20decryption%22%20/%3E%0A%20%20%20%20%3Cmeta%20name%3D%22author%22%20content%3D%22JesseJesse%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22og%3Atype%22%20content%3D%22website%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22og%3Aurl%22%20content%3D%22https%3A//html.jessejesse.xyz%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22og%3Atitle%22%20content%3D%22HTML%20Encrypt%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22og%3Adescription%22%20content%3D%22HTML%20Encrypt%20tool%20obfuscates%20text%20using%20basic%20encoding%20methods%20to%20make%20content%20less%20readable%20while%20maintaining%20its%20original%20format%20for%20web%20use.%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22og%3Aimage%22%20content%3D%22https%3A//html.jessejesse.xyz/og.png%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22twitter%3Acard%22%20content%3D%22summary_large_image%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22twitter%3Aurl%22%20content%3D%22https%3A//html.jessejesse.xyz%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22twitter%3Atitle%22%20content%3D%22HTML%20Encrypt%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22twitter%3Adescription%22%20content%3D%22HTML%20Encrypt%20tool%20obfuscates%20text%20using%20basic%20encoding%20methods%20to%20make%20content%20less%20readable%20while%20maintaining%20its%20original%20format%20for%20web%20use.%22%20/%3E%0A%20%20%20%20%3Cmeta%20property%3D%22twitter%3Aimage%22%20content%3D%22https%3A//html.jessejesse.xyz/og.png%22%20/%3E%0A%20%20%20%20%3Clink%20rel%3D%22icon%22%20href%3D%22/favicon.ico%22%20sizes%3D%22any%22%20/%3E%0A%20%20%20%20%3Clink%20rel%3D%22apple-touch-icon%22%20href%3D%22/apple-touch-icon.png%22%20/%3E%0A%20%20%20%20%3Clink%20rel%3D%22stylesheet%22%20href%3D%22https%3A//cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css%22%20/%3E%0A%20%20%20%20%3Clink%20rel%3D%22manifest%22%20href%3D%22/manifest.json%22%20/%3E%0A%20%20%20%20%3Ctitle%3EHTML%20Encrypt%3C/title%3E%0A%3C/head%3E%0A%20%20%20%20%3Cstyle%3E%0A%20%20%20%20%20%20*%20%7B%0A%20%20%20%20%20%20%20%20box-sizing%3A%20border-box%3B%0A%20%20%20%20%20%20%20%20margin%3A%200%3B%0A%20%20%20%20%20%20%20%20padding%3A%200%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20body%20%7B%0A%20%20%20%20%20%20%20%20font-family%3A%20%22Segoe%20UI%22%2C%20Tahoma%2C%20Geneva%2C%20Verdana%2C%20sans-serif%3B%0A%20%20%20%20%20%20%20%20background-color%3A%20%231e1e2e%3B%0A%20%20%20%20%20%20%20%20color%3A%20%23cdd6f4%3B%0A%20%20%20%20%20%20%20%20padding%3A%2020px%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20h1%20%7B%0A%20%20%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20%20%20color%3A%20%2374c7ec%3B%0A%20%20%20%20%20%20%20%20font-size%3A%202rem%3B%0A%20%20%20%20%20%20%20%20margin-bottom%3A%2020px%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20.container%20%7B%0A%20%20%20%20%20%20%20%20max-width%3A%20900px%3B%0A%20%20%20%20%20%20%20%20margin%3A%200%20auto%3B%0A%20%20%20%20%20%20%20%20background-color%3A%20%23292738%3B%0A%20%20%20%20%20%20%20%20padding%3A%2020px%3B%0A%20%20%20%20%20%20%20%20border-radius%3A%2012px%3B%0A%20%20%20%20%20%20%20%20box-shadow%3A%200%205px%2015px%20rgba%280%2C%200%2C%200%2C%200.3%29%3B%0A%20%20%20%20%20%20%20%20display%3A%20flex%3B%0A%20%20%20%20%20%20%20%20gap%3A%2020px%3B%0A%20%20%20%20%20%20%20%20justify-content%3A%20center%3B%0A%20%20%20%20%20%20%20%20flex-wrap%3A%20wrap%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20.textarea-container%20%7B%0A%20%20%20%20%20%20%20%20flex%3A%201%3B%0A%20%20%20%20%20%20%20%20display%3A%20flex%3B%0A%20%20%20%20%20%20%20%20flex-direction%3A%20column%3B%0A%20%20%20%20%20%20%20%20justify-content%3A%20center%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20textarea%20%7B%0A%20%20%20%20%20%20%20%20width%3A%20100%25%3B%0A%20%20%20%20%20%20%20%20padding%3A%2012px%3B%0A%20%20%20%20%20%20%20%20font-family%3A%20%22Courier%20New%22%2C%20Courier%2C%20monospace%3B%0A%20%20%20%20%20%20%20%20font-size%3A%201rem%3B%0A%20%20%20%20%20%20%20%20color%3A%20%23cdd6f4%3B%0A%20%20%20%20%20%20%20%20background-color%3A%20%2345475a%3B%0A%20%20%20%20%20%20%20%20border%3A%201px%20solid%20%2389b4fa%3B%0A%20%20%20%20%20%20%20%20border-radius%3A%208px%3B%0A%20%20%20%20%20%20%20%20resize%3A%20vertical%3B%0A%20%20%20%20%20%20%20%20flex-grow%3A%201%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20.buttons%20%7B%0A%20%20%20%20%20%20%20%20display%3A%20flex%3B%0A%20%20%20%20%20%20%20%20flex-wrap%3A%20wrap%3B%0A%20%20%20%20%20%20%20%20gap%3A%2010px%3B%0A%20%20%20%20%20%20%20%20justify-content%3A%20center%3B%0A%20%20%20%20%20%20%20%20align-items%3A%20stretch%3B%0A%20%20%20%20%20%20%20%20margin-top%3A%2020px%3B%0A%20%20%20%20%20%20%20%20flex-basis%3A%20100%25%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20.buttons%20input%20%7B%0A%20%20%20%20%20%20%20%20padding%3A%2010px%2015px%3B%0A%20%20%20%20%20%20%20%20font-size%3A%201rem%3B%0A%20%20%20%20%20%20%20%20background-color%3A%20%2389b4fa%3B%0A%20%20%20%20%20%20%20%20color%3A%20%231e1e2e%3B%0A%20%20%20%20%20%20%20%20border%3A%20none%3B%0A%20%20%20%20%20%20%20%20border-radius%3A%208px%3B%0A%20%20%20%20%20%20%20%20cursor%3A%20pointer%3B%0A%20%20%20%20%20%20%20%20transition%3A%20background-color%200.3s%20ease%3B%0A%20%20%20%20%20%20%20%20flex%3A%201%201%2030%25%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20.buttons%20input%3Ahover%20%7B%0A%20%20%20%20%20%20%20%20background-color%3A%20%2374c7ec%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20.file-size%20%7B%0A%20%20%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20%20%20color%3A%20%2374c7ec%3B%0A%20%20%20%20%20%20%20%20font-size%3A%200.9rem%3B%0A%20%20%20%20%20%20%20%20margin-top%3A%2010px%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20footer%20%7B%0A%20%20%20%20%20%20%20%20margin-top%3A%201.5rem%3B%0A%20%20%20%20%20%20%20%20font-size%3A%200.875rem%3B%0A%20%20%20%20%20%20%20%20color%3A%20%2374c7ec%3B%0A%20%20%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20footer%20a%20%7B%0A%20%20%20%20%20%20%20%20color%3A%20inherit%3B%0A%20%20%20%20%20%20%20%20text-decoration%3A%20none%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20footer%20a%3Ahover%20%7B%0A%20%20%20%20%20%20%20%20text-decoration%3A%20underline%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%23toast%20%7B%0A%20%20%20%20%20%20%20%20visibility%3A%20hidden%3B%0A%20%20%20%20%20%20%20%20min-width%3A%20250px%3B%0A%20%20%20%20%20%20%20%20margin-left%3A%20-125px%3B%0A%20%20%20%20%20%20%20%20background-color%3A%20%23000%3B%0A%20%20%20%20%20%20%20%20color%3A%20%2374c7ec%3B%0A%20%20%20%20%20%20%20%20text-align%3A%20center%3B%0A%20%20%20%20%20%20%20%20border-radius%3A%208px%3B%0A%20%20%20%20%20%20%20%20padding%3A%2016px%3B%0A%20%20%20%20%20%20%20%20position%3A%20fixed%3B%0A%20%20%20%20%20%20%20%20z-index%3A%201%3B%0A%20%20%20%20%20%20%20%20left%3A%2050%25%3B%0A%20%20%20%20%20%20%20%20bottom%3A%2030px%3B%0A%20%20%20%20%20%20%20%20font-size%3A%2017px%3B%0A%20%20%20%20%20%20%20%20transition%3A%0A%20%20%20%20%20%20%20%20%20%20visibility%200s%2C%0A%20%20%20%20%20%20%20%20%20%20opacity%200.5s%20ease%3B%0A%20%20%20%20%20%20%20%20opacity%3A%200%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%23toast.show%20%7B%0A%20%20%20%20%20%20%20%20visibility%3A%20visible%3B%0A%20%20%20%20%20%20%20%20opacity%3A%201%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20@media%20%28max-width%3A%20768px%29%20%7B%0A%20%20%20%20%20%20%20%20.container%20%7B%0A%20%20%20%20%20%20%20%20%20%20flex-direction%3A%20column%3B%0A%20%20%20%20%20%20%20%20%20%20gap%3A%2015px%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20.buttons%20%7B%0A%20%20%20%20%20%20%20%20%20%20flex-basis%3A%20auto%3B%0A%20%20%20%20%20%20%20%20%20%20margin-top%3A%200%3B%0A%20%20%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20%20%20textarea%20%7B%0A%20%20%20%20%20%20%20%20%20%20height%3A%20150px%3B%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%3C/style%3E%0A%20%20%20%20%3Cscript%3E%0A%20%20%20%20%20%20function%20EncryptBasic%28%29%20%7B%0A%20%20%20%20%20%20%20%20var%20NewCode%20%3D%20escape%28document.getElementById%28%22InputArea%22%29.value%29%3B%0A%20%20%20%20%20%20%20%20NewCode%20%3D%0A%20%20%20%20%20%20%20%20%20%20%22%3Cscript%3Edocument.write%28unescape%28%27%22%20+%20NewCode%20+%20%22%27%29%29%3C%5C/script%3E%22%3B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22OutputArea%22%29.value%20%3D%20NewCode%3B%0A%20%20%20%20%20%20%20%20showToast%28%22Basic%20encryption%20applied%21%22%29%3B%0A%20%20%20%20%20%20%20%20FileSizes%28%29%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20EncryptAll%28%29%20%7B%0A%20%20%20%20%20%20%20%20var%20NewCode%20%3D%20%22%22%3B%0A%20%20%20%20%20%20%20%20var%20OldCode%20%3D%20document.getElementById%28%22InputArea%22%29.value%3B%0A%20%20%20%20%20%20%20%20for%20%28var%20i%20%3D%200%3B%20i%20%3C%20OldCode.length%3B%20i++%29%20%7B%0A%20%20%20%20%20%20%20%20%20%20NewCode%20+%3D%20Hex%28OldCode.charCodeAt%28i%29%29%3B%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20NewCode%20%3D%0A%20%20%20%20%20%20%20%20%20%20%22%3Cscript%3Edocument.write%28unescape%28%27%22%20+%20NewCode%20+%20%22%27%29%29%3C%5C/script%3E%22%3B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22OutputArea%22%29.value%20%3D%20NewCode%3B%0A%20%20%20%20%20%20%20%20showToast%28%22Expert%20encryption%20applied%21%22%29%3B%0A%20%20%20%20%20%20%20%20FileSizes%28%29%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20Decrypt%28%29%20%7B%0A%20%20%20%20%20%20%20%20var%20NewCode%20%3D%20unescape%28document.getElementById%28%22InputArea%22%29.value%29%3B%0A%20%20%20%20%20%20%20%20NewCode%20%3D%20NewCode.replace%28%22%22%2C%20%22%22%29.replace%28%22%27%29%29%3C%5C/script%3E%22%2C%20%22%22%29%3B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22OutputArea%22%29.value%20%3D%20NewCode%3B%0A%20%20%20%20%20%20%20%20showToast%28%22Decrypted%21%22%29%3B%0A%20%20%20%20%20%20%20%20FileSizes%28%29%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20Hex%28dec%29%20%7B%0A%20%20%20%20%20%20%20%20var%20hexbase%20%3D%20%220123456789ABCDEF%22%3B%0A%20%20%20%20%20%20%20%20var%20hx_hi%20%3D%20Math.floor%28dec%20/%2016%29%3B%0A%20%20%20%20%20%20%20%20var%20hx_lo%20%3D%20dec%20%25%2016%3B%0A%20%20%20%20%20%20%20%20return%20%22%25%22%20+%20hexbase%5Bhx_hi%5D%20+%20hexbase%5Bhx_lo%5D%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20FileSizes%28%29%20%7B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22topSize%22%29.innerText%20%3D%0A%20%20%20%20%20%20%20%20%20%20document.getElementById%28%22InputArea%22%29.value.length%3B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22bottomSize%22%29.innerText%20%3D%0A%20%20%20%20%20%20%20%20%20%20document.getElementById%28%22OutputArea%22%29.value.length%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20pasteInput%28%29%20%7B%0A%20%20%20%20%20%20%20%20navigator.clipboard%0A%20%20%20%20%20%20%20%20%20%20.readText%28%29%0A%20%20%20%20%20%20%20%20%20%20.then%28%28text%29%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20document.getElementById%28%22InputArea%22%29.value%20%3D%20text%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20showToast%28%22Pasted%20from%20clipboard%22%29%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20FileSizes%28%29%3B%0A%20%20%20%20%20%20%20%20%20%20%7D%29%0A%20%20%20%20%20%20%20%20%20%20.catch%28%28err%29%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20console.error%28%22Failed%20to%20read%20clipboard%20contents%3A%20%22%2C%20err%29%3B%0A%20%20%20%20%20%20%20%20%20%20%7D%29%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20copyOutput%28%29%20%7B%0A%20%20%20%20%20%20%20%20var%20outputText%20%3D%20document.getElementById%28%22OutputArea%22%29.value%3B%0A%20%20%20%20%20%20%20%20navigator.clipboard%0A%20%20%20%20%20%20%20%20%20%20.writeText%28outputText%29%0A%20%20%20%20%20%20%20%20%20%20.then%28%28%29%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20showToast%28%22Copied%20to%20clipboard%21%22%29%3B%0A%20%20%20%20%20%20%20%20%20%20%7D%29%0A%20%20%20%20%20%20%20%20%20%20.catch%28%28err%29%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20console.error%28%22Failed%20to%20copy%20text%3A%20%22%2C%20err%29%3B%0A%20%20%20%20%20%20%20%20%20%20%7D%29%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20clearFields%28%29%20%7B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22InputArea%22%29.value%20%3D%20%22%22%3B%0A%20%20%20%20%20%20%20%20document.getElementById%28%22OutputArea%22%29.value%20%3D%20%22%22%3B%0A%20%20%20%20%20%20%20%20FileSizes%28%29%3B%0A%20%20%20%20%20%20%20%20showToast%28%22cleared%21%22%29%3B%0A%20%20%20%20%20%20%7D%0A%0A%20%20%20%20%20%20function%20showToast%28message%29%20%7B%0A%20%20%20%20%20%20%20%20var%20toast%20%3D%20document.getElementById%28%22toast%22%29%3B%0A%20%20%20%20%20%20%20%20toast.textContent%20%3D%20message%3B%0A%20%20%20%20%20%20%20%20toast.classList.add%28%22show%22%29%3B%0A%20%20%20%20%20%20%20%20setTimeout%28%28%29%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20toast.classList.remove%28%22show%22%29%3B%0A%20%20%20%20%20%20%20%20%7D%2C%203000%29%3B%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%3C/script%3E%0A%20%20%3Cbody%3E%0A%20%20%20%20%3Cdiv%20class%3D%22container%22%3E%0A%20%20%20%20%20%20%3Cdiv%20class%3D%22textarea-container%22%3E%0A%20%20%20%20%20%20%20%20%3Ch1%3EHTML%20Encrypt%3C/h1%3E%0A%20%20%20%20%20%20%20%20%3Ctextarea%0A%20%20%20%20%20%20%20%20%20%20id%3D%22InputArea%22%0A%20%20%20%20%20%20%20%20%20%20rows%3D%2210%22%0A%20%20%20%20%20%20%20%20%20%20placeholder%3D%22%26lt%3Bh1%26gt%3BWelcome%20to%20HTML%20Encrypt%26lt%3B/h1%26gt%3B%22%0A%20%20%20%20%20%20%20%20%3E%3C/textarea%3E%0A%20%20%20%20%20%20%20%20%3Cp%20class%3D%22file-size%22%20style%3D%22color%3A%20%2374c7ec%22%3E%0A%20%20%20%20%20%20%20%20%20%20%3Cspan%20id%3D%22topSize%22%3E0%3C/span%3E%26nbsp%3Bbytes%0A%20%20%20%20%20%20%20%20%3C/p%3E%0A%20%20%20%20%20%20%3C/div%3E%0A%0A%20%20%20%20%20%20%3Cdiv%20class%3D%22buttons%22%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22button%22%20value%3D%22Paste%22%20onclick%3D%22pasteInput%28%29%22%20/%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22button%22%20value%3D%22Encrypt%22%20onclick%3D%22EncryptBasic%28%29%22%20/%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22button%22%20value%3D%22Expert%22%20onclick%3D%22EncryptAll%28%29%22%20/%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22button%22%20value%3D%22Decrypt%22%20onclick%3D%22Decrypt%28%29%22%20/%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22button%22%20value%3D%22Copy%22%20onclick%3D%22copyOutput%28%29%22%20/%3E%0A%20%20%20%20%20%20%20%20%3Cinput%20type%3D%22button%22%20value%3D%22Clear%22%20onclick%3D%22clearFields%28%29%22%20/%3E%0A%20%20%20%20%20%20%3C/div%3E%0A%0A%20%20%20%20%20%20%3Cdiv%20class%3D%22textarea-container%22%3E%0A%20%20%20%20%20%20%20%20%3Ctextarea%0A%20%20%20%20%20%20%20%20%20%20id%3D%22OutputArea%22%0A%20%20%20%20%20%20%20%20%20%20rows%3D%2210%22%0A%20%20%20%20%20%20%20%20%20%20placeholder%3D%22%26lt%3Bscript%26gt%3BWelcome%2520to%2520HTML%2520Encrypt%26lt%3B/script%26gt%3B%22%0A%20%20%20%20%20%20%20%20%3E%3C/textarea%3E%0A%20%20%20%20%20%20%20%20%3Cp%20class%3D%22file-size%22%20style%3D%22color%3A%20%2374c7ec%22%3E%0A%20%20%20%20%20%20%20%20%20%20%3Cspan%20id%3D%22bottomSize%22%3E0%3C/span%3E%26nbsp%3Bbytes%0A%20%20%20%20%20%20%20%20%3C/p%3E%0A%20%20%20%20%20%20%3C/div%3E%0A%20%20%20%20%3C/div%3E%0A%0A%20%20%20%20%3Cdiv%20id%3D%22toast%22%3E%3C/div%3E%0A%20%20%20%20%3Cfooter%20class%3D%22footer%22%3E%0A%20%20%20%20%20%20%3Ca%20href%3D%22https%3A//x.com/ilostmyipad%22%20target%3D%22_blank%22%3E%0A%20%20%20%20%20%20%20%20%3Ci%20class%3D%22fab%20fa-twitter%22%20aria-hidden%3D%22true%22%3E%3C/i%3E%0A%20%20%20%20%20%20%3C/a%3E%0A%20%20%20%20%20%20%26nbsp%3B%26nbsp%3B%0A%20%20%20%20%20%20%3Ca%20href%3D%22https%3A//github.com/sudo-self%22%20target%3D%22_blank%22%3E%0A%20%20%20%20%20%20%20%20%3Ci%20class%3D%22fab%20fa-github%22%20aria-hidden%3D%22true%22%3E%3C/i%3E%0A%20%20%20%20%20%20%3C/a%3E%0A%20%20%20%20%20%20%26nbsp%3B%26nbsp%3B%0A%20%20%20%20%20%20%3Ca%0A%20%20%20%20%20%20%20%20href%3D%22/cdn-cgi/l/email-protection%23621607010a22080711110708071111074c010d0f%22%0A%20%20%20%20%20%20%3E%0A%20%20%20%20%20%20%20%20%3Ci%20class%3D%22fas%20fa-envelope%22%20aria-hidden%3D%22true%22%3E%3C/i%3E%0A%20%20%20%20%20%20%3C/a%3E%0A%20%20%20%20%20%20%26nbsp%3B%26nbsp%3B%0A%20%20%20%20%20%20%3Ca%20href%3D%22https%3A//www.linkedin.com/in/jrsdevelopments/%22%20target%3D%22_blank%22%3E%0A%20%20%20%20%20%20%20%20%3Ci%20class%3D%22fab%20fa-linkedin%22%20aria-hidden%3D%22true%22%3E%3C/i%3E%0A%20%20%20%20%20%20%3C/a%3E%0A%20%20%20%20%20%20%26nbsp%3B%26nbsp%3B%0A%20%20%20%20%20%20%3Ca%0A%20%20%20%20%20%20%20%20href%3D%22https%3A//play.google.com/store/apps/dev%3Fid%3D5617955831297880975%22%0A%20%20%20%20%20%20%20%20target%3D%22_blank%22%0A%20%20%20%20%20%20%3E%0A%20%20%20%20%20%20%20%20%3Ci%20class%3D%22fab%20fa-google-play%22%20aria-hidden%3D%22true%22%3E%3C/i%3E%0A%20%20%20%20%20%20%3C/a%3E%0A%20%20%20%20%3C/footer%3E%0A%20%20%3C/body%3E%0A%0A%3C/html%3E'))</script>
