极智工作室专用仓库《工作室专用》
我们的开发语言是lua，现有产品呆萌盒子，生存战争&盒子。

《第一条代码（语言lua）关于界面代码》注：本代码非本人所写，《出现任何问题概不负责》。
①小白菜QQ：2694199949所写
import "android.graphics.drawable.ColorDrawable" 
包名=this.getPackageManager().getPackageInfo(this.getPackageName(),((32552732/2/2-8183)/10000-6-231)/9)
版本=tostring(包名.versionName)
版本号=tonumber(包名.versionCode)
gt=
{
  LinearLayout,
  orientation="vertical",
  {
    CardView;
    layout_gravity='center';
    elevation='0dp';
    layout_width='94%w';
    CardBackgroundColor='#EEFFFFFF';
    layout_height='wrap';
    radius='10dp';
    layout_marginTop="25%h";
    {
      LinearLayout;
      orientation='horizontal';
      layout_width='94%w';
      layout_height='wrap';
      {
        TextView;
        layout_width='94%w';
        layout_height='fill';
        gravity='center';
        textColor='#FF000000';
        text='修改by.Jonathan\nQQ2858727468';
        textSize='8sp';
        layout_marginTop="5dp";
      };
    }; 
    {
      CardView;
      layout_marginTop='18dp';
      layout_gravity='top';
      CardElevation='-1';
      layout_width='fill';
      layout_height='0.8dp';
      radius='0dp';
      CardBackgroundColor='#16000000';
    };
    {
      LinearLayout;
      Orientation='vertical';
      layout_width='fill';
      layout_height='420dp';
      layout_marginTop='22dp';
      {
        TextView;
        layout_width='fill';
        layout_height='wrap';
        layout_marginLeft='10dp';
        layout_marginTop='10dp';
        Gravity='left';
        textColor='#7C000000';
        text='关于';
        textSize='18sp';
      };
      {
        ScrollView;
        layout_width='fill';
        layout_height='fill';
        VerticalScrollBarEnabled=false;
        {
          LinearLayout;
          Orientation='vertical';
          layout_width='fill';
          layout_height='fill';
          {
            CardView;
            layout_margin='2dp';
            layout_marginTop='3dp';
            layout_gravity='center';
            CardElevation='-1';
            layout_width='90%w';
            layout_height='90dp';
            radius='8dp';
            CardBackgroundColor='#FFFFFFFF';
            {
              LinearLayout;
              Orientation='horizontal';
              layout_width='fill';
              layout_height='fill';
              {
                CardView;
                layout_marginLeft='10dp';
                layout_gravity='center';
                CardElevation='5dp';
                layout_width='68dp';
                layout_height='68dp';
                radius='10dp';
                CardBackgroundColor='#FFFFFFFF';
                {
                  LinearLayout;
                  layout_width='fill';
                  layout_height='fill';
                  background='https://i.loli.net/2020/04/22/97b4cHi5FJA3Z2q.png';
                };
              };
              {
                TextView;
                layout_width='wrap';
                layout_height='wrap';
                Gravity='left';
                layout_margin='26dp';
                textColor='#FF000000';
                text="版本："..版本.."\n版本号："..版本号;
                textSize='12sp';
              };

              {
                CardView;
                layout_margin='0';
                layout_gravity='center';
                CardElevation='0';
                layout_width='wrap';
                layout_height='wrap';
                radius='6dp';
                CardBackgroundColor='#CDFF0000';
                id='gxl';
                {
                  TextView;
                  layout_margin='2dp';
                  layout_width='fill';
                  layout_height='fill';
                  Gravity='center';
                  textColor='#FFFFFFFF';
                  text='发现新版本';
                  textSize='12sp';
                };
              };
            };
          };
          {
            CardView;
            layout_margin='2dp';
            layout_marginTop='3dp';
            layout_gravity='center';
            CardElevation='-1';
            layout_width='90%w';
            layout_height='45dp';
            radius='8dp';
            CardBackgroundColor='#FFFFFFFF';
            id='gfwz';

            {
              ImageView;
              src='imgs/gfwz.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='left|center';
              layout_margin='8dp';
            };
            {
              TextView;
              layout_width='wrap';
              layout_height='fill';
              layout_marginLeft='45dp';
              Gravity='left|center';
              textColor='#FF000000';
              text='联系搬运工';
              textSize='18sp';
            };
            {
              ImageView;
              src='imgs/right.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='right|center';
              layout_margin='8dp';
            };
          };
          {
            CardView;
            layout_margin='2dp';
            layout_marginTop='3dp';
            layout_gravity='center';
            CardElevation='-1';
            layout_width='90%w';
            layout_height='45dp';
            radius='8dp';
            CardBackgroundColor='#FFFFFFFF';
            id='gnjs';

            {
              ImageView;
              src='imgs/gnjs.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='left|center';
              layout_margin='8dp';
            };
            {
              TextView;
              layout_width='wrap';
              layout_height='fill';
              layout_marginLeft='45dp';
              Gravity='left|center';
              textColor='#FF000000';
              text='功能介绍';
              textSize='18sp';
            };
            {
              ImageView;
              src='imgs/right.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='right|center';
              layout_margin='8dp';
            };
          };
          {
            CardView;
            layout_margin='2dp';
            layout_marginTop='3dp';
            layout_gravity='center';
            CardElevation='-1';
            layout_width='90%w';
            layout_height='45dp';
            radius='8dp';
            CardBackgroundColor='#FFFFFFFF';
            id='tbs';
            {
              ImageView;
              src='imgs/tbs.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='left|center';
              layout_margin='8dp';
            };
            {
              TextView;
              layout_width='wrap';
              layout_height='fill';
              layout_marginLeft='45dp';
              Gravity='left|center';
              textColor='#FF000000';
              text='TBS内核';
              textSize='18sp';
            };
            {
              ImageView;
              src='imgs/right.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='right|center';
              layout_margin='8dp';
            };
          };
          {
            TextView;
            layout_width='fill';
            layout_height='wrap';
            layout_marginLeft='10dp';
            layout_marginTop='10dp';
            Gravity='left';
            textColor='#7C000000';
            text='软件数据';
            textSize='18sp';
          };
          {
            CardView;
            layout_margin='2dp';
            layout_marginTop='3dp';
            layout_gravity='center';
            CardElevation='-1';
            layout_width='90%w';
            layout_height='45dp';
            radius='8dp';
            CardBackgroundColor='#FFFFFFFF';
            id='sjwjj';
            {
              ImageView;
              src='imgs/sjwjj.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='left|center';
              layout_margin='8dp';
            };
            {
              TextView;
              layout_width='wrap';
              layout_height='fill';
              layout_marginLeft='45dp';
              Gravity='left|center';
              textColor='#FF000000';
              text='数据文件夹';
              textSize='18sp';
            };
            {
              ImageView;
              src='imgs/right.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='right|center';
              layout_margin='8dp';
            };
          };
          {
            CardView;
            layout_margin='2dp';
            layout_marginTop='3dp';
            layout_gravity='center';
            CardElevation='-1';
            layout_width='90%w';
            layout_height='45dp';
            radius='8dp';
            CardBackgroundColor='#FFFFFFFF';
            id='qcsj';
            {
              ImageView;
              src='imgs/qcsj.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='left|center';
              layout_margin='8dp';
            };
            {
              TextView;
              layout_width='wrap';
              layout_height='fill';
              layout_marginLeft='45dp';
              Gravity='left|center';
              textColor='#FF000000';
              text='清除数据';
              textSize='18sp';
            };
            {
              ImageView;
              src='imgs/right.png';
              layout_width='25dp';
              layout_height='25dp';
              layout_gravity='right|center';
              layout_margin='8dp';
            };
          };
          {
            LinearLayout;
            Orientation='horizontal';
            layout_width='fill';
            layout_height='wrap';
            {
              TextView;
              layout_width='45%w';
              layout_height='wrap';
              layout_marginRight='10dp';
              layout_marginTop='24dp';
              layout_marginBottom='15dp';
              Gravity='right';
              textColor='#83000000';
              text='隐私问题';
              textSize='10sp';
              id='yswt';
            };
            {
              TextView;
              layout_width='45%w';
              layout_height='wrap';
              layout_marginLeft='10dp';
              layout_marginTop='24dp';
              layout_marginBottom='15dp';
              Gravity='left';
              textColor='#83000000';
              text='版权问题';
              textSize='10sp';
              id='bqwt';
            };
          };
        };
      };
    };
  };
};
dialog= AlertDialog.Builder(this)
.setCancelable(true)
xiaobaicai=dialog.show()
xiaobaicai.getWindow().setContentView(loadlayout(gt));
xiaobaicai.getWindow().setBackgroundDrawable(ColorDrawable(0x00000000));
gxl.setVisibility(View.INVISIBLE)
gfwz.onClick=function()
  联系QQ(2858727468)
end
gnjs.onClick=function()
  弹出消息("自己去琢磨琢磨，就会了")
end
tbs.onClick=function()
  pop=PopupMenu(activity,tbs)
  menu=pop.Menu
  menu.add("安装").onMenuItemClick=function(a)
    进入子页面("浏览器",{标题="腾讯TBS-安装页面",链接="http://debugx5.qq.com/"})
  end
  menu.add("调试").onMenuItemClick=function(a)
    进入子页面("浏览器",{标题="腾讯TBS-调试页面",链接="http://debugx5.qq.com/"})
  end
  pop.show()
end
sjwjj.onClick=function()
  require "import"
  import "android.app.*"
  import "android.os.*"
  import "android.widget.*"
  import "android.view.*"
  layout={
    LinearLayout;
    layout_height="fill";
    orientation="vertical";
    layout_width="fill";
    {
      LinearLayout;
      layout_width="fill";
      orientation="horizontal";
      {
        TextView;
        text="加载中...";
        layout_height="4%h";
        gravity="center|left";
        id="path";
        layout_width="94%w";
      };
      {
        ProgressBar;
        layout_height="4%h";
        id="jz";
        layout_width="6%w";
      };
    };
    {
      ListView;
      layout_height="fill";
      id="list";
      layout_width="fill";
    };
  };
  dl=LuaDialog(activity)
  .setTitle("选择文件")
  .setView(loadlayout(layout))
  dl.show()
  item={
    LinearLayout;
    layout_width="fill";
    orientation="vertical";
    {
      LinearLayout;
      layout_width="fill";
      layout_height="wrap";
      orientation="vertical";
      {
        LinearLayout;
        layout_width="fill";
        layout_height="wrap";

        orientation="horizontal";
        {
          ImageView;
          layout_width="6%h";
          layout_gravity="center";
          id="icon";
          ColorFilter="#FF444444";
          layout_marginLeft="4%w";
          layout_height="6%h";
        };
        {
          TextView;
          text="name";
          id="name";
          layout_height="wrap";
          textColor="#000000";

          layout_marginRight="5dp";
          layout_gravity="center";
        };
      };
      {
        LinearLayout;
        layout_width="fill";

        orientation="horizontal";
        layout_height="4%h";
        {
          TextView;
          layout_width="80%w";
          layout_gravity="left";
          id="xx";
          text="1969 96 97";
          layout_marginLeft="6%w";
        };
      };
    };
  }
  import "com.androlua.LuaUtil"
  function getMD5(path)
    return tostring(LuaUtil.getFileMD5(tostring(path)))
  end

  function GetFilelastTime(path)
    f = File(path); 
    cal = Calendar.getInstance();
    time = f.lastModified()
    cal.setTimeInMillis(time); 
    return cal.getTime().toLocaleString()
  end
  function GetFileSize(path)
    import "java.io.File"
    import "android.text.format.Formatter"
    size=File(tostring(path)).length()
    Sizes=Formatter.formatFileSize(activity, size)
    return Sizes
  end
  adp=LuaAdapter(activity,item)
  function show(f)
    jz.setVisibility(View.GONE)
    dir=f 
    if tostring(dir)~="/" then
      path.setText(tostring(dir).."/")
    else
      path.setText(tostring(dir).."")
    end
    adp.clear()
    ls=luajava.astable(f.listFiles() or String{}) 
    table.sort(ls,function(a,b)
      return (a.isDirectory()~=b.isDirectory() and a.isDirectory()) or ((a.isDirectory()==b.isDirectory()) and a.Name<b.Name)
    end) 
    adp.add{icon="icon/dir.png",name="../",xx=""}
    for n=1,#ls do
      if ls[n].isDirectory() then
        adp.add{icon="icon/dir.png",name=ls[n].Name,xx=GetFilelastTime(tostring(ls[n]))}
      end
    end
    for n=1,#ls do
      if ls[n].isDirectory() then
      else
        adp.add{icon="icon/file.png",name=ls[n].Name,xx=GetFilelastTime(tostring(ls[n])).."  "..GetFileSize(tostring(ls[n]))}
      end
    end
  end
  list.Adapter=adp

  import "java.io.File"
  function OpenFile(path)
    import "android.webkit.MimeTypeMap"
    import "android.content.Intent"
    import "android.net.Uri"
    import "java.io.File"
    FileName=tostring(File(path).Name)
    ExtensionName=FileName:match("%.(.+)")
    Mime=MimeTypeMap.getSingleton().getMimeTypeFromExtension(ExtensionName)
    if Mime then 
      intent = Intent(); 
      intent.addFlags(Intent.FLAG_ACTIVITY_NEW_TASK); 
      intent.setAction(Intent.ACTION_VIEW); 
      intent.setDataAndType(Uri.fromFile(File(path)), Mime); 
      activity.startActivity(intent);
    else
      Toastc("找不到可以用来打开此文件的程序")
    end
  end
  function 加载(path)
    jz.setVisibility(View.VISIBLE)
    path=path
    thread(function()
      require "import"
      import "java.io.File"
      Thread.sleep(100)
      call("show",File("/storage/emulated/0/板板块/夸喵/"))
    end)
  end
  加载("/storage/emulated/0/板板块/夸喵/")--改成你要加载的文件夹地址就行
  list.onItemClick=function(l,v,p,i)
    if v.Tag.name.Text=="../" then 
      show(dir.ParentFile or dir)
      print(ls[p])
    elseif ls[p].isDirectory() then 
      show(ls[p])
    elseif not ls[p].isDirectory() then
      文件选择结果 = tostring(ls[p])
      对话框()
      .设置标题("提示")
      .设置消息(文件选择结果)
      .设置积极按钮("确定",function()
        显示消息("点击了确定")
      end)
      .设置消极按钮("取消")
      .显示()
      dl.dismiss()
    end
  end
end
qcsj.onClick=function()
  执行Shell("rm -rf /sdcard/板板块/夸喵/")
  执行Shell("rm -rf /data/data/"..this.packageName.."/cache/")
  执行Shell("rm -rf /data/user/0/"..this.packageName.."/cache/")
  执行Shell("rm -rf /data/data/"..this.packageName.."/files/data/")
  执行Shell("rm -rf /data/user/0/"..this.packageName.."/files/data/")
  执行Shell("rm -rf /sdcard/Android/data/"..this.packageName.."/files/VideoCache/main/")
  执行Shell("rm -rf /storage/emulated/0/Android/data/"..this.packageName.."/files/VideoCache/main/")
  退出程序()
end
yswt.onClick=function()
  对话框()
  .设置标题("用户隐私问题")
  .设置消息("本软件无需任何登录信息，无需获取cookie，软件内加载网址均来自网络，请谨慎")
  .设置积极按钮("确定",function()
  end)
  .设置消极按钮("")
  .显示()
end
bqwt.onClick=function()
  对话框()
  .设置标题("关于版权问题")
  .设置消息("本软件所有资源均来自网络，如果触犯到您的合法权益，请尽快与我们取得联系")
  .设置积极按钮("确定",function()
  end)
  .设置消极按钮("")
  .显示()
end
Http.get("http://www.iyuji.cn/iyuji/s/M2QzbjdIa1ZlMWJSZDhrdkZPVk5IUT09/1563872115173597",nil,nil,nil,function(code,content)
  content=content:gsub("&lt;","<"):gsub("&gt;",">"):gsub("&nbsp;"," "):gsub("<br/>",""):gsub("amp;",""):gsub("</p>",""):gsub("<p>","\n");
  远端版本=content:match("《远端版本》(.-)《远端版本》")
  本地=版本
  if (远端版本)>本地 then
    gxl.setVisibility(View.VISIBLE)
  else
  end
end)
gxl.onClick=function()
  Http.get("http://www.iyuji.cn/iyuji/s/M2QzbjdIa1ZlMWJSZDhrdkZPVk5IUT09/1563872115173597",nil,nil,nil,function(code,content)
    content=content:gsub("&lt;","<"):gsub("&gt;",">"):gsub("&nbsp;"," "):gsub("<br/>",""):gsub("amp;",""):gsub("</p>",""):gsub("<p>","\n");
    更新内容=content:match("《更新内容》(.-)《更新内容》")
    下载地址=content:match("《下载地址》(.-)《下载地址》")
    远端版本=content:match("《远端版本》(.-)《远端版本》")
    软件名称=content:match("《软件名称》(.-)《软件名称》")
    本地=版本
    if (远端版本)>本地 then
      gt=
      {
        LinearLayout;
        orientation='vertical';
        layout_width='fill';
        layout_height='fill';
        background='#00000000';
        gravity='center';
        {
          CardView;
          layout_margin='0dp';
          elevation='2dp';
          layout_width='90%w';
          layout_height='wrap';
          radius='15dp';
          {
            LinearLayout;
            orientation='vertical';
            layout_width='fill';
            layout_height='wrap';
            background='#FFFFFFFF';
            {
              TextView;
              layout_width='fill';
              layout_height='50dp';
              gravity='center';
              textColor='#FFFFFFFF';
              text="发现新版本";
              textSize='20sp';
              id="title";
            };
            {
              ScrollView,
              layout_width='fill';
              layout_height='220dp';
              layout_marginTop='10dp';
              {
                LinearLayout;
                layout_margin='10dp';
                orientation='vertical';
                layout_width='fill';
                layout_height='fill';
                {
                  TextView;
                  textColor='#FF7D7D7D';
                  padding='15dp';
                  text=更新内容.."\n\n当前版本："..本地.."\n最新版本："..远端版本;
                  textSize='15sp';
                };
              };
            };
            {
              LinearLayout;
              orientation='vertical';
              layout_width='fill';
              layout_height='wrap';
              gravity='center';
              id="进度框";
              {
                ProgressBar;
                style="?android:attr/progressBarStyleHorizontal";
                layout_width='100%w';
                layout_height='5dp';
                secondaryProgress="100";
                id="进度";
              };
              {
                TextView;
                layout_width='fill';
                layout_height='35dp';
                gravity='center';
                textColor='#FF7D7D7D';
                text='已下载:';
                textSize='12sp';
                id="进度弹出消息";
              };
            };
            {
              TextView;
              layout_width='fill';
              layout_height='1dp';
              background='#FFDCDCDC';
            };
            {
              LinearLayout;
              orientation='horizontal';
              layout_width='fill';
              layout_height='50dp';
              gravity='center';
              {
                TextView;
                layout_weight='1';
                layout_width='40%w';
                layout_height='50dp';
                gravity='center';
                textColor='#FF7D7D7D';
                text='取消';
                textSize='15sp';
                onClick=function()
                  duihk.dismiss()
                end
              };
              {
                TextView;
                layout_width='1dp';
                layout_height='fill';
                background='#FFDCDCDC';
              };
              {
                TextView;
                layout_weight='1';
                layout_width='40%w';
                layout_height='50dp';
                gravity='center';
                textColor='#FF7D7D7D';
                text='立即更新';
                textSize='15sp';
                id="更新";
                onClick=function()
                  xiaz()
                end
              };
            };
          };
        };
      };
      duihk=Dialog(activity)
      duihk.setContentView(loadlayout(gt))
      duihk.getWindow().setBackgroundDrawableResource(android.R.color.transparent);
      duihk.getWindow().setGravity(Gravity.CENTER)
      duihk.setCanceledOnTouchOutside(true);
      duihk.getWindow().getAttributes().width =WindowManager.LayoutParams.MATCH_PARENT
      duihk.show()
      进度框.setVisibility(View.GONE)
      function ControlsGradient(id,左色,右色,圆角)
        import "android.graphics.drawable.GradientDrawable"
        drawable = GradientDrawable(GradientDrawable.Orientation.TR_BL,{左色,右色});
        drawable.setCornerRadii({圆角,圆角,圆角,圆角,圆角,圆角,圆角,圆角});
        id.setBackgroundDrawable(drawable)
      end
      ControlsGradient(title,0xFFE7E7E7,0xFF444444,0)
      function xiaz()
        if 更新.Text=="立即安装" then
          inapk(path)
        elseif 更新.Text=="下载中" then
          弹出消息("请等待下载完毕...")
        else
          local url=(下载地址)
          path="/sdcard/板板块/Download/"..软件名称..".apk"
          big(url,path)
          进度框.setVisibility(View.VISIBLE)
        end
      end

      function big(url,path)
        import "java.net.URL"
        realUrl = URL(url)
        con = realUrl.openConnection();
        con.setRequestProperty("accept","*/*");
        con.setRequestProperty("connection","Keep-Alive");
        con.setRequestProperty("Content-Type","application/x-www-form-urlencoded");
        lens=con.getContentLength()
        进度弹出消息.setText("已下载:0%")
        down(url,path)
      end
      import "android.content.*"
      import "android.net.*"
      function inapk(path)
        intent = Intent(Intent.ACTION_VIEW);
        intent.setDataAndType(Uri.parse("file:///"..path), "application/vnd.android.package-archive")
        intent.addFlags(Intent.FLAG_ACTIVITY_NEW_TASK);
        activity.startActivity(intent);
      end
      function down(url,path)
        local tt=Ticker()
        tt.start()
        Http.download(url,path,function(code,data,cookie,header)
          tt.stop()
          进度.incrementProgressBy(100)
          进度弹出消息.setText("下载已完成")
          更新.setText("立即安装")
          进度.incrementProgressBy(-100)
          进度框.setVisibility(View.GONE)
          inapk(path)
        end)
        function tt.onTick()
          local f=io.open(path,"r")
          if f~=nil then
            local len=f:read("a")
            local s=#len/lens
            local w=activity.Width*s
            进度.incrementProgressBy(tointeger(s*10))
            进度弹出消息.setText("已下载"..math.ceil(s*100).."%")
            更新.setText("下载中")
          end
        end
      end
    else
      弹出消息("已是最新版本")
    end
  end)
end



