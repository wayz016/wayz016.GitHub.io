# 工资计算器
一个按照时薪计算实时工资的H5网页  


如果不需要手动输入请求改这里 let dailySalary = prompt("请输入日薪：");  
                           let dailySalary = 100     /* 100的含义是时薪100元 */  
                           
                         
下边是可以修改的变量  
          document.getElementById("countdown").textContent = "不要加班赶紧跑！";                        /* 下班后提醒的内容 */  
          let earnedMoney = 0;                                                                         /* 初始的工资 */  
          let dailySalary = prompt("请输入日薪：");                                                     /* 时薪 */  
          const startOfWork = new Date(now.getFullYear(), now.getMonth(), now.getDate(), 9, 0, 0);     /* 上班时间 */  
          const endOfWork = new Date(now.getFullYear(), now.getMonth(), now.getDate(), 18, 0, 0);      /* 下班时间 */  
          
          
          目前存在的bug是早上上班前依旧会显示下班倒计时  
          
          
          由衷感谢chatgpt  
