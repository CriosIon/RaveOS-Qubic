# RaveOS-Qubic
GPU mining RaveOS
![image](https://github.com/CriosIon/RaveOS-Qubic/assets/63637120/7eb65013-1ac8-4a33-83b1-e967124a2985)
Version 1.9.6

Added functionality to resubmit unconfirmed solutions after a client restart
Removed HugePages settings from RaveOS
Resolved path-related issue in raveos package
Additional stability improvements
Important: since qubic algo change, running miner on raveos requires 535+ nvidia drivers, use this command in shell to upgrade raveos:
upgrade 8926-2226

RaveOs full Qubic Miner Integration
No need for custom package additions anymore. Qubminer 1.9.6 sfully integrated into Rave OS. This smooth integration elevates the Qubic mining experience, providing a streamlined and user-centric solution.


💫 Back my efforts and help foster its development. 💫

If you value my work and wish to support its continued progress, I would greatly appreciate any tips you can provide. Every contribution, regardless of the amount, has a significant impact and inspires me to keep developing and enhancing my capabilities. Your support is invaluable and helps ensure I can maintain a high level of service.

To support me, use Qubic: FZCNOURXYEPULCFPOZOVLAJMIEZBPIJSVZWXMAMSTAKMZJFBQJHQMJABKBUB

Support received : 420,472 Qubic - Thank you for your future support!



I'm grateful to have you along for the ride!

❗ Mandatory Installation Instructions (14/05/2024)
Drivers 535+: run this command to upgrade RaveOs upgrade 8926-2226
Use recommended OC before mining
Only NVIDIA GPU compatible

⚙️ Settings
it's miner GPU only, check out settings below for seamless setup

Recommended Rave OS GPU overclocks : 

Medium

3000 series nvidia-smi -lmc 7000 && nvidia-smi -lgc 1500

4000 series nvidia-smi -lmc 7000 && nvidia-smi -lgc 2400

High

3000 series nvidia-smi -lmc 7000 && nvidia-smi -lgc 1700

4000 series nvidia-smi -lmc 7000 && nvidia-smi -lgc 2900

Please use "Tunning Settings" from workers's dashboard to set global or specific OC like this:
![image](https://github.com/CriosIon/RaveOS-Qubic/assets/63637120/6634eb31-dd13-4b8e-9888-fcd3a9f4844b)

Additional Command Line Arguments (options):
Setting	Description
"accessToken":	This is you personal JWT Token which you can obtain from the Control Panel at qubic.li
"payoutId":	This is the ID you want to get token payout for your found solutions. (https://app.qubic.li/main/mining/pool)
![image](https://github.com/CriosIon/RaveOS-Qubic/assets/63637120/0a9770dc-a6e1-4113-98b7-0b22acca7370)


🛩️ Rave OS Settings
I/ Add Wallet: Select Qubic
![image](https://github.com/CriosIon/RaveOS-Qubic/assets/63637120/41fbd6ae-e006-474d-953d-d8205437fbb4)

GPU Only Mining
"accessToken":"YOUROWNTOKEN"
![image](https://github.com/CriosIon/RaveOS-Qubic/assets/63637120/f725e2d3-1637-4e79-826d-30983fe487b4)

applay


