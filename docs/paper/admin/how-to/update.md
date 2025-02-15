---
slug: /update
title: Updating Paper
description: 如何更新 Paper 服务器到最新版本。
---

# 更新 Paper 服务器

本指南将介绍如何更新您的 Paper 服务器到最新版本。保持服务器更新到最新版本非常重要，可以获得最新的功能、性能优化和安全修复。

## 更新步骤

更新 Paper 服务器非常简单，只需几个步骤即可完成：

1.  **备份服务器文件。**  在更新服务器之前，务必备份您的服务器文件，包括 `world` 文件夹、配置文件、插件文件夹等。以防止更新过程中出现意外情况导致数据丢失。您可以参考 [备份指南](/paper/updating#step-1-backup) 了解更多备份信息。
2.  **停止服务器。**  在更新服务器之前，必须先停止正在运行的 Paper 服务器。
3.  **下载最新 Paper JAR 文件。**  访问 [PaperMC 官网下载页面](https://papermc.io/downloads)，下载最新版本的 Paper 服务器 JAR 文件。请确保下载的版本与您当前的 Minecraft 版本对应。
4.  **替换旧的 Paper JAR 文件。**  将您下载的最新 Paper JAR 文件重命名为您服务器启动脚本中指定的名称 (通常为 `paper.jar`)，然后替换您服务器目录中旧的 Paper JAR 文件。
5.  **启动服务器。**  使用您的服务器启动脚本启动 Paper 服务器。Paper 服务器将使用新的 JAR 文件启动，并应用最新的更新。

**完成！** 您的 Paper 服务器已成功更新到最新版本。

## 注意事项

*   **定期更新。**  建议您定期检查 PaperMC 官网，关注 Paper 的更新动态，并及时更新您的服务器到最新版本。
*   **关注更新日志。**  在更新 Paper 服务器之前，建议您查看 Paper 的更新日志，了解新版本包含的更新内容、修复的 Bug 以及可能的兼容性变化。更新日志通常在 PaperMC 官网或 GitHub 仓库中发布。
*   **插件兼容性。**  更新 Paper 服务器版本后，部分插件可能需要更新才能与新版本 Paper 兼容。更新服务器后，请检查您的插件是否正常工作，如有异常，请及时更新插件或联系插件作者。
*   **配置文件更新。**  在极少数情况下，Paper 的配置文件格式可能会在新版本中发生变化。更新服务器后，如果遇到配置相关的问题，请参考 Paper 官方文档，检查配置文件格式是否需要更新。通常情况下，Paper 会自动处理配置文件迁移，您无需手动修改配置文件。
*   **测试更新。**  在生产环境更新服务器之前，建议您先在测试服务器上进行更新测试，确保更新过程顺利，服务器运行正常，插件兼容性良好。

## 自动化更新 (不推荐)

虽然理论上可以通过脚本或其他工具自动化更新 Paper 服务器，但 **强烈不建议** 这样做。自动化更新可能会带来以下风险：

*   **更新失败风险。**  自动化更新脚本可能在某些情况下更新失败，导致服务器无法启动或数据损坏。
*   **未测试更新风险。**  自动化更新可能会跳过测试环节，直接将未经验证的新版本应用到生产环境，可能引入未知问题。
*   **插件不兼容风险。**  自动化更新无法自动处理插件兼容性问题，更新后可能导致插件无法正常工作。

**为了保证服务器的稳定性和数据的安全性，请务必手动更新 Paper 服务器，并严格按照更新步骤进行操作。**

## 遇到问题？

如果您在更新 Paper 服务器过程中遇到任何问题，例如服务器启动失败、插件异常、世界数据错误等，请不要慌张。

*   **查看服务器日志。**  服务器日志文件 (通常位于 `logs/latest.log`) 包含了服务器运行过程中的各种信息，包括错误和警告信息。查看服务器日志可以帮助您定位问题原因。
*   **回滚到旧版本。**  如果您在更新后遇到严重问题，无法解决，可以回滚到更新前的旧版本 Paper 服务器。只需将您之前备份的旧版本 Paper JAR 文件替换回去即可。
*   **寻求社区帮助。**  如果自行排查问题困难，请随时在 [PaperMC Discord](https://discord.gg/papermc) 的 `#paper-help` 频道中寻求帮助。请详细描述您的问题，并提供服务器日志、Paper 版本、插件列表等信息，以便社区成员更好地帮助您。

---

**希望本指南能够帮助您顺利更新 Paper 服务器。祝您游戏愉快！**
