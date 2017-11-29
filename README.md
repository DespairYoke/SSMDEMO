                                     Springboot第一次使用
    
public class RestfulApiWebDemo {

    @RequestMapping("/")
    String home(){
        return "Hello World!";
    }

    public static void main(String[] args) {
        SpringApplication.run(RestfulApiWebDemo.class,args);
    }
}
通过SpringApplication启动内部tomcat服务器， @RequestMapping("/")确定访问路径
