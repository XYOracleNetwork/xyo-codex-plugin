# xyo-codex-plugin

OpenAI Codex marketplace mirror for [`XYOracleNetwork/xyo-skills`](https://github.com/XYOracleNetwork/xyo-skills) — XL1 / XYO development skills for AI coding assistants.

This repository is **auto-generated** from the source repo on each release. Do not open PRs against this repo; file issues and contribute at [xyo-skills](https://github.com/XYOracleNetwork/xyo-skills) instead.

## Install

You can install the XYO Skills plugin either through the Codex desktop UI or with the `codex` CLI.

### Via the UI

1. Open the Codex sidebar and click **Plugins**.

   ![Plugins entry in the Codex sidebar](docs/images/step-01-plugins-sidebar.png)

2. Make sure the **Plugins** tab is selected (not **Skills**).

   ![Plugins tab toggle](docs/images/step-02-plugins-tab.png)

3. On the **Make Codex work your way** page, open the **More** dropdown in the filter row.

   ![Marketplace page filter row with the More dropdown](docs/images/step-03-marketplace-page.png)

4. Click **+ Add more**.

   ![+ Add more entry in the More dropdown](docs/images/step-04-add-more.png)

5. Fill in the **Add marketplace** dialog:

   - **Source**: `https://github.com/XYOracleNetwork/xyo-codex-plugin`
   - **Git ref**: `main`
   - **Sparse paths**: `plugins/codex`

6. Click the **Add marketplace** button at the bottom of the dialog.

   ![Add marketplace dialog filled in](docs/images/step-05-add-marketplace-dialog.png)

7. Back on the marketplace page, open the **More** dropdown again.

8. Select **XYO Skills** from the dropdown to filter the page to that marketplace.

   ![XYO Skills selected in the More dropdown](docs/images/step-06-xyo-skills-filter.png)

9. Under **Developer Tools**, find the **XYO Skills** card and click the **+** button (hover shows *Install plugin*).

   ![XYO Skills card in Developer Tools](docs/images/step-07-developer-tools-card.png)

   ![Install plugin tooltip on the plus button](docs/images/step-08-install-plugin.png)

   After install, the plugin page opens and lists the bundled XL1 / XYO skills:

   ![Installed XYO Skills plugin with skill list](docs/images/step-09-installed.png)

Start a new Codex thread after installing so the skill list is refreshed.

### Via textual commands

```shell
codex plugin marketplace add XYOracleNetwork/xyo-codex-plugin --ref main
codex plugin add xyo-skills@xyo-skills
```

Start a new Codex thread after installing or updating so the skill list is refreshed.

## Other distributions

| Tool | Repo |
|---|---|
| Claude Code | [`XYOracleNetwork/xyo-claude-plugin`](https://github.com/XYOracleNetwork/xyo-claude-plugin) |
| Skills.sh | [`XYOracleNetwork/xyo-skills`](https://github.com/XYOracleNetwork/xyo-skills) |

## License

[LGPL-3.0-only](./LICENSE) — same as the source repo.
