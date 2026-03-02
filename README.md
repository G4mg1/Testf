local Arg = {}

function Arg.Notice(Title, Content, duration, icon)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title,
		Text = Content,
		Icon = icon,
		Duration = duration
	})
end

return Arg
