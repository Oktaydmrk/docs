
### 检查您的自托管运行器是否已成功添加

After completing the steps to add a self-hosted runner, the runner and its status are now listed under {% ifversion fpt or ghec %}"Runners"{% elsif ghae or ghes %}"Self-hosted runners"{% endif %}.

必须激活自托管运行器应用程序，运行器才能接受作业。 当运行器应用程序连接到 {% data variables.product.product_name %} 并准备接收作业时，您将在机器的终端上看到以下消息。

{% data reusables.actions.self-hosted-runner-connected-output %}

更多信息请参阅“[自托管运行器监控和故障排除](/actions/hosting-your-own-runners/monitoring-and-troubleshooting-self-hosted-runners)”。
